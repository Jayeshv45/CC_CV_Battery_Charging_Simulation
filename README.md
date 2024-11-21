# CC_CV_Battery_Charging_Simulation
Simulink Project for Battery Charging Using Constant Current and Constant Voltage Methods

# CC & CV Battery Charging Simulation

## Project Description
This Simulink project demonstrates the use of Constant Current (CC) and Constant Voltage (CV) charging methods for a battery. The model includes:
- A controlled voltage source providing a constant voltage of 4.19V.
- A controlled current source providing a constant current of 27A.
- An SPDT switch with a threshold of 80% (0.8) to switch between CC and CV charging.
- A battery connected to the output of the SPDT switch.
- Monitoring of State of Charge (SOC), Current, and Voltage using a scope.

## Features
- Simulates battery charging using CC and CV methods.
- Uses an SPDT switch to transition between charging modes based on SOC.
- Monitors SOC, Current, and Voltage in real-time and displays results on a scope.

## Files Included
- `CC_CV_Battery_Charging_Simulation.slx`: The Simulink model file.
- `README.md`: Project description and details.
- Optional: Additional documentation in the `docs` folder.

## How to Use
1. Clone this repository to your local machine.
2. Open `CC_CV_Battery_Charging_Simulation.slx` in MATLAB Simulink.
3. Run the simulation and observe the SOC, Current, and Voltage outputs on the scope.

## Author
- Jayesh Verma
- [LinkedIn](https://www.linkedin.com/in/jayeshv45/)
