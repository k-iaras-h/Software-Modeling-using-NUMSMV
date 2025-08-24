This project models a smart home system using NuSMV, focusing on authentication, temperature control, door/light management, and security alarms. The model ensures safe and correct behavior through formal verification using CTL logic.

Features

Face ID-based login flow

Mode selection: Temperature or Door/Light

Automatic and manual control paths

Heater/AC activation based on temperature

Lighting and alarm based on night mode

Mutual exclusion and access restriction checks

Verification Approach

Written in NuSMV using modular components

Properties verified with CTL formulas

Visualized with a Binary Decision Diagram (BDD) where only valid behavior follows a path of 1s

Future Enhancements

Time-based alarms

Custom temperature settings

Emergency unlock and day/night detection

Run the .smv file in NuSMV ( the moset common way to run is , use the commend prompt in order to run )
