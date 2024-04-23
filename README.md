# AdaptiveCruiseControl_ForwardCollisionAvoidance

This repo contains the implementation of two ADAS Features (Adaptive Cruise Control and Forward Collision Avoidance) on an ARM Cortex-M3 microcontroller (STM32F103C8T6) using a Real-Time Operating System(RTOS). 

## Project Machine State Diagram 

![Project Machine State](https://github.com/SeifAhmed25/AdaptiveCruiseControl_ForwardCollisionAvoidance/assets/64741466/887afc53-483c-4365-9db8-eff880fa1495)

## Reqiurements 

This Project is mainly divided into 3 Levels 

### Level 1 
- Implementing the ADAS features (Adaptive cruise ontrol - Forward collision avoidance).
- Implementing the System using Real-Time Operating Systemt (FreeRTOS).
- Target: (STM32F103C8T6) microcontroller.    

### Level 2 
- Dividing the System Tasks among 2 Microcontrollers.
- The System will be communicating via CAN BUS.
- Targets: no of 2 (STM32F103C8T6) microcontrollers.  

### Level 3
- Implementing the FOTA (Firmware Over The Air) Software using ESP32 NodeMCU.
- Uploading new ADAS features and releases using FOTA. 
- Targets: no of 2 (STM32F103C8T6) microcontrollers + ESP32.
