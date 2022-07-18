# Citing

If you make use of the Virtual Test Bed, please reference this paper as well as the relevant papers for the reactor models and the numerical codes.

```
@inproceedings{vtb2021,
               title = {The Virtual Test Bed Repository : A Library of Multiphysics Reference Reactor Models using NEAMS Tools},
               author = {A. Abou-Jaoude and D. Gaston and G. Giudicelli and B. Feng and C. Permann},
               year = {2021},
               booktitle = {Transactions of the American Nuclear Society},
               booksubtitle = {Winter Meeting}
              }
A. Abou-Jaoude, D. Gaston, G. Giudicelli, B. Feng and C. Permann, "The Virtual Test Bed Repository : A Library of Multiphysics Reference Reactor Models using NEAMS Tools", Transactions of the American Nuclear Society (2020)
```

## Reactor models

If you make use of models in the repository to build models for a published study, please reference
the following:

### Molten Salt Reactor style=font-size:125%

- Molten Salt Fast Reactor (Pronghorn-Griffin core model)

```
@article{aboujaoude2021,
         title = {A Workflow Leveraging MOOSE Transient Multiphysics Simulations to Evaluate the Impact of Thermophysical Property Uncertainties on Molten-Salt Reactors},
         author = {A. Abou-Jaoude and S. Harper and G. Giudicelli and P. Balestra and S. Schunert and N.Martin and A. Lindsay and M. Tano},
         journal = {Annals of Nuclear Energy},
         volume = {163},
         pages = {108546},
         doi = {https://doi.org/10.1016/j.anucene.2021.108546},
         url = {https://www.sciencedirect.com/science/article/pii/S0306454921004229},
         year = 2021
        }
A. Abou-Jaoude, S. Harper, G. Giudicelli, P. Balestra, S. Schunert, N.Martin, A. Lindsay and M. Tano, "A Workflow Leveraging MOOSE Transient Multiphysics Simulations to Evaluate the Impact of Thermophysical Property Uncertainties on Molten-Salt Reactors", Annals of Nuclear Energy 163, 108546, (2021)
```

- Molten Salt Fast Reactor (Nek5000 model)

```
@inproceedings{fang2021,
               title = {CFD Modeling of Molten Salt Fast Reactor Using Nek5000},
               author = {Jun Fang, Dillon R Shaver and Bo Feng},
               year = {2021},
               booktitle = {Transactions of the American Nuclear Society},
               booksubtitle = {Winter Meeting}
              }
Jun Fang, Dillon R Shaver and Bo Feng, "CFD Modeling of Molten Salt Fast Reactor Using Nek5000", Transactions of the American Nuclear Society (2021)
```

- Molten Salt Reactor Experiment (SAM model)

```
@techreport{Hu2021,
            title = {FY21 SAM Developments for MSR Modeling.},
            author = {Hu R. and Hu G. and Gorman M. and Fang J. and Mui T. and O’Grady D. and Fei T. and Salko R.},
            institution = {Argonne National Laboratory},
            number = {ANL/NSE-21/74},
            year = 2021
           }
Hu R., Hu G., Gorman M., Fang J., Mui T., O’Grady D., Fei T. and Salko R., "FY21 SAM Developments for MSR Modeling.", Argonne National Laboratory, ANL/NSE-21/74 (2021)
```

### Pebble bed fluoride-salt cooled high temperature reactor style=font-size:125%

- Core multiphysics analysis (Pronghorn-Griffin core model)

```
@article{giudicelli2021,
         title = {Coupled Multiphysics Multiscale Transient Simulations of The Mk1-Fhr Reactor Using Finite Volume Capabilities of The Moose Framework},
         author = {Guillaume Giudicelli and Alexander Lindsay and Paolo Balestra and Robert Carlsen and Javier Ortensi and Derek Gaston and Mark DeHart and Abdalla Abou-Jaoude and April J Novak},
         year = {2021},
         journal = {Proceedings of the International Conference of Mathematics and Computation for Nuclear Science and Engineering}
        }
Guillaume Giudicelli, Alexander Lindsay, Paolo Balestra, Robert Carlsen, Javier Ortensi, Derek Gaston, Mark DeHart, Abdalla Abou-Jaoude and April J Novak, "Coupled Multiphysics Multiscale Transient Simulations of The Mk1-Fhr Reactor Using Finite Volume Capabilities of The Moose Framework", Proceedings of the International Conference of Mathematics and Computation for Nuclear Science and Engineering, 2021
```

- Pebble bed fluoride-salt cooled high temperature reactor reflector model

```
@inproceedings{novak2021,
               title = {Conjugate Heat Transfer Coupling of NekRS and MOOSE for Bypass Flow Modeling},
               author = {April J. Novak and Dillon Shaver and Bo Feng},
               year = {2021},
               booktitle = {Transactions of the American Nuclear Society},
               booksubtitle = {ANS Winter Meeting}
              }
April J. Novak, Dillon Shaver and Bo Feng, "Conjugate Heat Transfer Coupling of NekRS and MOOSE for Bypass Flow Modeling", Transactions of the American Nuclear Society (2021)
```

- Integrated Plant Analysis

```
@inproceedings{Ahmed2017,
               address = {Xi'an, China},
               author = {Ahmed K K and Scarlat R O and Hu R},
               booktitle = {17th International Topical Meeting on Nuclear Reactor Thermal Hydraulics
        	        (NURETH-17)},
               language = {English},
               publisher = {American Nuclear Society},
               title = {{Benchmark Simulation of Natural Circulation Cooling System
        	        with Salt Working Fluid Using SAM}},
               url = {https://www.osti.gov/biblio/1392061},
               year = {2017}
              }
Ahmed K. K., Scarlat R. O. and Hu R., "Benchmark Simulation of Natural Circulation Cooling System with Salt Working Fluid Using SAM", Transactions of the  American Nuclear Society (2017)
```


### Sodium Fast Reactor style=font-size:125%

- Sodium Fast Reactor assembly model

```
@article{MARTIN2022109066,
         title = {A multiphysics model of the versatile test reactor based on the MOOSE framework},
         journal = {Annals of Nuclear Energy},
         volume = {172},
         pages = {109066},
         year = {2022},
         issn = {0306-4549},
         doi = {https://doi.org/10.1016/j.anucene.2022.109066},
         url = {https://www.sciencedirect.com/science/article/pii/S0306454922001013},
         author = {Nicolas Martin and Ryan Stewart and Sam Bays}
        }
Nicolas Martin, Ryan Stewart and Sam Bays, "A multiphysics model of the versatile test reactor based on the MOOSE framework", Annals of Nuclear Energy, 172, 109066 (2022)
```

- Advanced Burner Test Reactor SAM model

```
@techreport{Hu2019,
            author = {Hu, G., Zhang, G., & Hu, R.},
            year = 2019,
            title = {{Reactivity Feedback Modeling in SAM.}},
            url = {https://doi.org/10.2172/1499041}
           }
Hu, G., Zhang, G., & Hu, R., "Reactivity Feedback Modeling in SAM", Argonne National Laboratory, ANL/NSE-19/1150747 (2019)
```

- Versatile Test Reactor

```
@article{vtr_martin,
  author = {{Martin, Nicholas} and {Stewart, Ryan} and {Bays, Sam}},
  title = {A Multiphysics Model of the Versatile Test Reactorbased on the MOOSE Framework},
  url = "https://doi.org/10.1016/j.anucene.2022.109066",
  journal = {Annals of Nuclear Energy},
  year = 2022,
  volume = 172,
}
```

### High Temperature Gas Cooled Reactor style=font-size:125%

- Modular High Temperature Gas Reactor

```
@techreport{Vegendla2019,
            author = {Vegendla Prasad and Hu Rui and Zou Ling},
            number = {ANL-19/35},
            mendeley-tags = {ANL-19/35},
            institution = {Argonne National Laboratory},
            title = {{Multi-Scale Modeling of Thermal-Fluid Phenomena Related to Loss of
              Forced Circulation Transient in HTGRs}},
            year = {2019}
           }
Vegendla Prasad, Hu Rui and Zou Ling, "Multi-Scale Modeling of Thermal-Fluid Phenomena Related to Loss of Forced Circulation Transient in HTGRs", Argonne National Laboratory, ANL-19/35 (2019)
```

- PBMR-400 numerical benchmark

```
@article{balestra2021,
         title = {PBMR-400 benchmark solution of exercise 1 and 2 using the moose based applications: MAMMOTH, Pronghorn},
         author = {Paolo Balestra and Sebastian Schunert and Robert W Carlsen and April J Novak and Mark D DeHart and Richard C Martineau},
         year = {2021},
         journal = {EPJ Web of Conferences},
         pages = {247}
       }
Paolo Balestra, Sebastian Schunert, Robert W Carlsen, April J Novak, Mark D DeHart and Richard C Martineau, "PBMR-400 benchmark solution of exercise 1 and 2 using the moose based applications: MAMMOTH, Pronghorn", 247 (2021)
```

- Assembly Cardinal model

```
@InProceedings{novak_2021b,
               title       = {{Coupled Monte Carlo Transport and Thermal-Hydraulics Modeling of a Prismatic Gas Reactor Fuel Assembly Using Cardinal}},
               author     = {A.J. Novak and D. Andrs and P. Shriwise and D. Shaver and P.K. Romano and E. Merzari and P. Keutelian},
               booktitle  = {{Proceedings of Physor}},
               year       = 2022
              }
A.J. Novak, D. Andrs, P. Shriwise, D. Shaver, P.K. Romano, E. Merzari and P. Keutelian, "Coupled Monte Carlo Transport and Thermal-Hydraulics Modeling of a Prismatic Gas Reactor Fuel Assembly Using Cardinal" (2022)
```

### Micro Reactor style=font-size:125%

- Heat Pipe Micro Reactor

```
@article{Stauff2021,
        title = {Preliminary Applications of NEAMS Codes for Multiphysics Modeling of a Heat Pipe Microreactor},
        author = {Nicolas E. Stauff and Kun Mo and Yan Cao and Justin W. Thomas and Yinbin Miao and Changho Lee and Christopher Matthews and Bo Feng},
        year = {2021},
        journal = {Proceedings of the American Nuclear Society Annual 2021 Meeting}
       }
Nicolas E. Stauff, Kun Mo, Yan Cao, Justin W. Thomas, Yinbin Miao, Changho Lee, Christopher Matthews and Bo Feng, "Preliminary Applications of NEAMS Codes for Multiphysics Modeling of a Heat Pipe Microreactor", Transactions of the American Nuclear Society, (2021)
```

## Software / codes

The references for various features of MOOSE may be found on this
[page](https://mooseframework.inl.gov/citing.html).
If you make use of the following NEAMS software, please reference the following:

Bison

```
@article{doi:10.1080/00295450.2020.1836940,
         author = {Richard L. Williamson and Jason D. Hales and Stephen R. Novascone and Giovanni Pastore and Kyle A. Gamble and Benjamin W. Spencer and Wen Jiang and Stephanie A. Pitts and Albert Casagranda and Daniel Schwen and Adam X. Zabriskie and Aysenur Toptan and Russell Gardner and Christoper Matthews and Wenfeng Liu and Hailong Chen},
         title = {BISON: A Flexible Code for Advanced Simulation of the Performance of Multiple Nuclear Fuel Forms},
         journal = {Nuclear Technology},
         volume = {207},
         number = {7},
         pages = {1-27},
         year  = {2021},
         publisher = {Taylor & Francis},
         doi = {10.1080/00295450.2020.1836940},
         URL = {https://doi.org/10.1080/00295450.2020.1836940},
        }
Richard L. Williamson, Jason D. Hales, Stephen R. Novascone, Giovanni Pastore, Kyle A. Gamble, Benjamin W. Spencer, Wen Jiang, Stephanie A. Pitts, Albert Casagranda, Daniel Schwen, Adam X. Zabriskie, Aysenur Toptan, Russell Gardner, Christoper Matthews, Wenfeng Liu and Hailong Chen, "BISON: A Flexible Code for Advanced Simulation of the Performance of Multiple Nuclear Fuel Forms", Nuclear Technology (2021)
```

Griffin

```
@techreport{Griffin2020,
            title = "Griffin User Manual",
            institution = "Idaho National Laboratory",
            author = {Mark DeHart and Fredrick N. Gleicher and Vincent Laboure and Javier Ortensi and Zachary Prince and Sebastian Schunert and Yaqi Wang},
            number = {INL/EXT-19-54247},
            year = 2020
           }
Mark DeHart, Fredrick N. Gleicher, Vincent Laboure, Javier Ortensi, Zachary Prince, Sebastian Schunert and Yaqi Wang, "Griffin User Manual", Idaho National Laboratory, INL/EXT-19-54247, 2020
```

Nek5000

```
@Misc{nek5000-web-page,
      Author = "Paul F. Fischer and James W. Lottes and Stefan G. Kerkemeier",
      Title  = "{nek5000 Open source spectral element {CFD} solver}",
      Note   = "http://nek5000.mcs.anl.gov",
      Year   = "2008"
     }
Paul F. Fischer, James W. Lottes and Stefan G. Kerkemeier, "Nek5000 Open source spectral element CFD solver", http://nek5000.mcs.anl.gov (2008)
```

NekRS

```
@misc{fischer2021nekrs,
      title={NekRS, a GPU-Accelerated Spectral Element Navier-Stokes Solver},
      author={Paul Fischer and Stefan Kerkemeier and Misun Min and Yu-Hsiang Lan and Malachi Phillips and Thilina Rathnayake and Elia Merzari and Ananias Tomboulides and Ali Karakus and Noel Chalmers and Tim Warburton},
      year={2021},
      eprint={2104.05829},
      archivePrefix={arXiv},
      primaryClass={cs.PF}
     }
Paul Fischer, Stefan Kerkemeier, Misun Min, Yu-Hsiang Lan, Malachi Phillips, Thilina Rathnayake, Elia Merzari, Ananias Tomboulides, Ali Karakus, Noel Chalmers and Tim Warburton, "NekRS, a GPU-Accelerated Spectral Element Navier-Stokes Solver" (2021)
```

Cardinal

```
@article{cardinal2021NT,
         title = {{Cardinal}: A Lower Length-Scale Multiphysics Simulator for Pebble-Bed Reactors},
         author = {E. Merzari and H. Yuan and M. Min and D. Shaver and R. Rahaman and P. Shriwise and P. Romano and A. Talamo and Y. Lan and D. Gaston and R. Martineau and P. Fischer and Y. Hassan},
         year = {2021},
         journal = {{Nuclear Technology}},
         DOI = {https://doi.org/10.1080/00295450.2020.1824471},
         url = {https://www.tandfonline.com/doi/full/10.1080/00295450.2020.1824471}
}
E. Merzari, H. Yuan, M. Min, D. Shaver, R. Rahaman, P. Shriwise, P. Romano, A. Talamo, Y. Lan, D. Gaston, R. Martineau, P. Fischer and Y. Hassan, "Cardinal : A Lower Length-Scale Multiphysics Simulator for Pebble-Bed Reactors", Nuclear Technology (2021)
```

Pronghorn

```
@article{pronghorn2020NT,
         title = {{Pronghorn}: A Multidimensional Coarse-Mesh Application for Advanced Reactor Thermal Hydraulics},
         author = {A.J. Novak and R.W. Carlsen and S. Schunert and P. Balestra and D. Reger and R.N. Slaybaugh and R.C. Martineau},
         year = {2021},
         journal = {{Nuclear Technology}},
         doi = {https://doi.org/10.1080/00295450.2020.1825307},
         url = {https://www.tandfonline.com/doi/full/10.1080/00295450.2020.1825307},
         keywords = {Pronghorn, pebble bed reactor, MOOSE}
        }
A.J. Novak, R.W. Carlsen, S. Schunert, P. Balestra, D. Reger, R.N. Slaybaugh and R.C. Martineau, "Pronghorn: A Multidimensional Coarse-Mesh Application for Advanced Reactor Thermal Hydraulics", Nuclear Technology (2021)
```

SAM

```
@techreport{SAM2017,
            title = "SAM Theory Manual",
            institution = {Argonne National Laboratory},
            author = {R. Hu},
            number = {ANL/NE-17/4},
            year = 2017
           }
R. Hu, "SAM Theory Manual", Argonne National Laboratory, ANL/NE-17/4 (2017)
```

Sockeye

```
@article{hansel2021sockeye,
         author = {Joshua E. Hansel and Ray A. Berry and David Andrs and Matthias S. Kunick and Richard C. Martineau},
         title = {Sockeye: A One-Dimensional, Two-Phase, Compressible Flow Heat Pipe Application},
         journal = {Nuclear Technology},
         volume = {207},
         number = {7},
         pages = {1096-1117},
         year  = {2021},
         publisher = {Taylor & Francis},
         doi = {10.1080/00295450.2020.1861879},
         URL = {https://doi.org/10.1080/00295450.2020.1861879},
         eprint = {https://doi.org/10.1080/00295450.2020.1861879}
}
Joshua E. Hansel, Ray A. Berry, David Andrs, Matthias S. Kunick and Richard C. Martineau, "Sockeye: A One-Dimensional, Two-Phase, Compressible Flow Heat Pipe Application", Nuclear Technology, 207-7, 1096-1117 (2021)
```
