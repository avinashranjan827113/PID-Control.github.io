# PID_Controller
This project implements a water level control system using a PID (Proportional-Integral-Derivative) controller. The goal is to maintain the water level within a specified range by adjusting the inflow rate based on the feedback received from the water level sensor.
# Features
- **PID Controller**: The system uses a PID controller to maintain the water level at the desired setpoint.
- **Real-Time Monitoring**: The water level is monitored in real-time, and the inflow rate is adjusted accordingly.
- **Scalable Design**: The system can be easily adapted for different container sizes and flow rates.
# How It Works
The PID controller continuously calculates the error between the desired water level (setpoint) and the actual water level. Based on this error, the controller adjusts the inflow rate to minimize the error and maintain the water level at the setpoint.

The PID controller consists of three components:

- Proportional (P): Adjusts the inflow rate proportionally to the error.
- Integral (I): Eliminates steady-state error by integrating the error over time.
- Derivative (D): Predicts future errors based on the rate of change of the error.
