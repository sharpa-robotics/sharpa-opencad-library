# sharpa-opencad-library

 Sharpa Wave open hardware repository provides mechanical CAD resources for the project, structured by part category and assembly arrangement.The default flange is an ISO-9409-1-50-4-M6 interface, ensuring compatibility with most robotic arms such as Universal Robots(UR), Franka, and Flexiv, among others. Files are supplied in STEP format to ensure compatibility with major CAD platforms and to support manufacturing, integration, and engineering analysis.


## Table of Contents

- [Repository Structure](#repository-structure)



## Repository Structure



```text
│  README.md
│
└─wave_01
    ├─adapter
    │      Internal-Interface.pdf
    │      Internal-Interface.STEP
    │      Flange-Interface.pdf
    │      Flange-Interface.STEP
    │      Wrist-Interface.pdf
    │      Wrist-Interface.STEP
    │
    └─simplified-model
           wave01-R.step
           wave01-L.step           
```



### Directory Description


| Directory | Description |
|-----------|-------------|
| `adapter/` | Adapter flanges and interfaces for various application scenarios, facilitating installation and custom design |
| `simplified-model/` | Simplified full-hand models in various configurations, intended to support CAD-based custom design, simulation, and related applications |

