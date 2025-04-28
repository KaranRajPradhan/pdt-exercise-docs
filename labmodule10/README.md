# Programming Digital Twins

## Lab Module 10 README.md

Be sure to implement all the requirements listed at [PDT-INF-10-001 - Lab Module 10](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/18).


### Description
This project is a part of the TELE7374-02: Building Digital Twins Spring 2025 Course instructed by Professor [Andy King](https://www.linkedin.com/in/aking/).

The Digital Twin App [Unity6](https://unity.com/releases/unity-6) with primary support of the [LabBenchStudios-PDT-Unity](https://github.com/programming-digital-twins/LabBenchStudios-PDT-Unity.git) package, that provides Digital Twin State Manager and MQTT connection handler prefabs, data sent from edge devices (in JSON format) can be easily mapped into predefined Digital Twin Definition Language. This project involves using these packages to provide a simulation environment for machines like Wind Turbines and HVACs. 


### Use Cases Covered:
- Predictive Maintenance: Using visualization in a spatial simulation that represents live data to realize maintenance needs.
- System Control: Ability to control actual machines either through pre-defined set of rules or through simulated user interaction(button presses).
- User Training: Live user and maintenance training can be given without the need to be present in the actual scene, in addition to the ability to record processess. 


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

#### Edge Devices Used:

- EDA1: Environment Sensor Data: Temperature, Pressure and Humidity + System Performance Data (Emulated through SenseHAT)
- EDA2: Environment Sensor Data: Temperature, Pressure and Humidity + System Performance Data (Simulated)
- EDA3: Wind Turbine Data (Simulated)
- EDA4: Wind Turbine Data (Simulated)
- EDA5: Custom Environment Sensor Data (Simulated)

#### Script Implementations:
- Animation Handler: C# scripts to look at incoming data and change colors of object based on pre-programmed thresholds.
- Command Handler: C# scripts to look at incoming data and send actuation commands to the corresponding edge device based on pre-programmed thresholds.


### References

This project largely uses the following:
- [Unity 6](https://unity.com/releases/unity-6)

#### Packages
- [LabBenchStudios-PDT-Unity](https://github.com/programming-digital-twins/LabBenchStudios-PDT-Unity.git)
- [PDT Client Framework Components](https://github.com/programming-digital-twins/pdt-cfw-components)

EOF.
