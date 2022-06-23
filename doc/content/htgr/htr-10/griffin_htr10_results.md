# HTR-10 Griffin Neutronics Results

This section looks at the various results carried out by Griffin for various HTR-10 calculations. The two main input files are the *htr-10-critical.i* and the *htr-10-full.i* which are documented in detail in the Griffin Neutronics Model Section.  


## Running an Input File

If the user has access to Griffin built upon a working Moose Framework the following command from the shell prompt will execute the input file. 

```language=bash

/projects/griffin/griffin-opt -i htr-10-critical.i

```

## *Initial Critical* Core Results 

!table id=fuel_salt_properties caption=Thermophysical properties of the fuel salt.
|   |   | Unit  | LiF-BeF$_4$-ZrF$_4$-UF$_4$  |
| :- | :- | :- | :- |
| Melting temperature | $T_{melt}$ | $K$ | $722.15$  |
| Density | $\rho$ | $kg/m^3$  | $2553.3-0.562\bullet T$ |
| Dynamic viscosity | $\mu$ | $Pa\bullet s$ | $8.4\times 10^{-5} exp(4340/T)$ |
| Thermal conductivity | $k$ | $W/(m\bullet K)$ | $1.0$ |
| Specific heat capacity | $c_p$ | $J/(kg\bullet K)$ | $2009.66$ |

!media /pbmr/PBMR400THResults.png
    style=width:70%
    id=THResults
    caption=Pressure drop, fluid temperature, and solid temperature results from the Pronghorn PBMR 400 model. Streamlines are shown in white to indicate helium flow.

The steady-state helium pressure, temperature, and velocity streamlines are shown in [THResults] along with the graphite temperature. The helium temperature increases once it enters into the pebble bed where power is generated. The spatial temperature distribution shows a temperature peak of ~1300K close to the bottom center of the core. The streamlines show how most of the helium flows directly into the bed, with just a small amount flowing into the top cavity. Helim originating from different radial positions in the core mixes in the outlet plenum to produce the average helium outlet temperature. In normal operation, most of the heat generated in the pebble bed is removed by the helium flow. However, the central reflector graphite has no active cooling (this is a benchmark simplification, in reality active cooling is provided): therefore, its temperature is at least 500K higher than the rest of the graphite in the core.

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
