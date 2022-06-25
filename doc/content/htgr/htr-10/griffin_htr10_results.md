# HTR-10 Griffin Neutronics Results

*Contact: Javier Ortensi, Javier.Ortensi@inl.gov*

This section is a short summary of the results section of [!citep](HTR-10Benchmark) and looks at the various results carried out by Griffin for various HTR-10 calculations. The two main input files are the *htr-10-critical.i* and the *htr-10-full.i* which are documented in detail in the Griffin Neutronics Model Section.  


## Running an Input File

If the user has access to Griffin built upon a working Moose Framework the following command from the shell prompt will execute the input file. 

```language=bash

/projects/griffin/griffin-opt -i htr-10-critical.i

```

## *Initial Critical* Core Results 

The first set of results for this model deal with the *htr-10-critical.i* input file which is the initial criticality benchmark. Table 1 summarizes the results of Griffin using tensor diffusion coefficients (TDC) and super homogenization (SPH) compared against MCNP and Serpent using ENDFB-VI and Serpent using ENDFB-VII.r1. As can be seen in the table below, Griffin matches with the accepted Serpent solution very well. 

!table id=critical_eigven_values caption=Eigenvalues computed with different codes for the initial critical configuration. (MCNP results obtained from [!citep](IRPhEP))
| Code  | keff  | uncertainty rel. error (pcm)  |
| :- | :- | :- | :- |
| MCNP (ENDFB-VI)  | 1.01190 | +/- 21 | 
| Serpent (ENDFB-VI) | 1.01025 | +/- 5.1 |
| Serpent (ENDFB-VII.r1) | 1.00023 | +/- 2.3 |
| Griffin TDC-SPH-Diffusion | 1.00089 | 67.3 |

Additionally, the flux distribution in the critical core is plotted in below. The effect of the upper cavity is clearly visible as the flux is almost flat within this region. The thermal flux peaks in the bottom conus are also visible.

!media /htr10/flux_critical_core.png
   style=width:80%
   id=htr10_flux
   caption=Flux distribution in the critical core (axial centerline) [!citep](HTR-10Benchmark).

## *Full Core* Results

For the *Full Core* case, there are a multitude of different cross section and equivalence libraries that can be switched out in the *htr-10-full.i* in order to model the full htr-10 reactor at different temperatures and rod positions.  

One of the first problems to benchmark against

After the steady-state calculations, a Pressurized Loss of Forced Cooling (PLOFC) is performed using the following event sequence:

* 0-13s: A reduction in reactor inlet coolant mass flow rate from the nominal 192.7 kg/s to 0.0 kg/s over 13 seconds. The mass flow ramp is assumed linear; a reduction in reactor helium outlet pressure from the nominal 90 bar to 60 bar in 13 seconds.

* 13-16s: All control rods are fully inserted over 3 seconds to SCRAM the reactor.

* 16-180,000s: No change in input parameters (50hr).

!media /pbmr/PBMR400TransientFuel.png
      style=width:50%
      id=fuelTransient
      caption=Average fuel temperature over time during the PLOFC transient between various codes.

!media /pbmr/PBMR400TransientModerator.png
      style=width:50%
      id=moderatorTransient
      caption=Average moderator temperature over time during the PLOFC transient between various codes.

The results from this transient can be found in [fuelTransient] and [moderatorTransient]. Both moderator and fuel average temperature start to increase after the reactor shutdown since there is no more active flow cooling the reactor. The only mechanism for heat removal is the less efficient heat transfer through the outer reflector/barrel/RPC/cavity/RCCS. The temperatures reach their maximum around 100,000s (~28hr) and then start to decrease thanks to a reduction of the generated decay heat. As shown in the figure above, the fuel average temperature and the moderator average temperature results are in the range of the other participant solutions confirming that the Pronghorn/Griffin coupled model is consistent with legacy codes developed explicity for PBRs.
