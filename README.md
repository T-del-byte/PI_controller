# PI_controller
# Objective
PI controller for 2nd order plus time delay process
# Tools & Technologies
IC TL074
POTENTIOMETER
CAPACITOR
RESISTOR
BATTERY 
# Working Principle
A PI controller for a second-order plus time delay (SOPTD) process adjusts the control signal based on the **error** (P term) and its **accumulated past values** (I term) to eliminate steady-state error.
It compensates the SOPTD system's slow response and delay by tuning gains to improve stability, speed, and disturbance rejection.
# Constrction
Using op-amps(AD820), break the equation into building blocks – Integrators, Differentiators, Adders, Amplifiers.
- Gain stages and summing
- Integrators (low frequency)	100μF + resistor 
- Summing Inputs (Inputs are added before feeding into op-amps)
- Pulse Source (PULSE→ Step/pulse input)
- Run Simulation (Time-domain transient simulation)
# Output
A PI controller for a second-order plus time delay (SOPTD) process adjusts the control signal proportionally to the error and its integral to compensate for process lag and delay, aiming to improve steady-state accuracy and dynamic response.
# Application
Speed control in large motors, Chemical process control, Level control in tank, etc.
