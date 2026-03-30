# 12Nm Direct Drive Sim Racing Wheel

This is my DIY direct drive force feedback steering wheel built around a 12Nm NEMA 34 closed-loop stepper motor. I wanted a strong, responsive wheel without spending a a lot of money on commercial options.

### Project Overview
The wheel uses a stepper motor controlled by OpenFFBoard firmware and a TMC4671 FOC driver. Being fully direct drive with no gearbox resulting a in a quiet, reliable, and simple system for simulator racing or anything else..

### Budget Breakdown
The critical electronics — 12Nm stepper motor + encoder, STM32F407 board, Elecrow TMC4671 driver kit, 60V DC power supply, Nylon filament, and a cooling fan — came out to a total of $362. The remaining cost covers hardware, wiring, and additional 3D printing filament.

### Build Details
- **Motor**: 12Nm NEMA 34 closed-loop stepper with 1000 PPR encoder  
- **Driver**: Elecrow OpenFFBoard TMC4671 FOC driver  
- **Controller**: OpenFFBoard STM32F407 stack
- **Power**: 60V 350W DC PSU  
- **Base**: Fully 3d printed in order to be cheap and customizable
- **Wheel**: 3D printed in PETG with electrical tape for grip  
- **Quick Release & Adapter**: Printed in Nylon CF for maximum strength under torque  

I used carbon fiber nylon for all structural parts (base, clamps, and quick release) because the motor has a lot of torque. The wheel rim is PETG because I cannot use fiber reinforced filaments because it can leave fibers in your skin.

### Current Status
Have all the parts selected and working on getting all the wiring done (using KiCAD which is completely new to me) and using CAD(Fusion 360 which is also new to me) to create the housing for the motor.

I'll continue updating this repo with my final configuration files, WheelCheck results, and any improvements I make.

### Repository Contents
- Full BOM.csv with prices and links  
- KiCad wiring schematic  
- 3D models (.STEP files)
- Instructions for assembly and 3d printing

Safety risks: 
-High Torque motor, it can break you wrist or bruise it bad, use common sense
-60V system, if there are any damaged wires or incorrectly wired, it can cause a fire or electrical shock

This is still a work in progress and I am figuring stuff out. Please let me know if I am doing anything wrong and can improve on or change.
