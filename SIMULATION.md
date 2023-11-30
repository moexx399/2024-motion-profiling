### How to Simulate Robot Code
1. ctl+shift+p in vs code
2. select "WPILib: SImulate Robot Code"
    - ![start sim](assets/start_sim.png "Start Simulation")
3. Select simulation options 
    - Select "Sim GUI" if you would like to use 
    - Select "Use Real DriverStation" if you would like to use the real driverstation and shuffleboard 
    - ![sim options](assets/sim_options.png "Simulation Options")
4. Connect your joysticks either in the DriverStation or the SIM GUI
    - In the sim GUI you need to drag the joystick from "System Joysticks" to the "Joystick" panel. This code uses Joystick 0.
    - ![connect joysticks](assets/sim_connect_joystick.png "Connect Joysticks")
    - In the FRC DriverStation you connect the joystick as usual

### Set Up AdvantageScope
1. Install SdvantageScope from their github https://github.com/Mechanical-Advantage/AdvantageScope
2. Open advantageScope
3. Open the dashboard included in this repo at ./AdvantageScope 11-19-2023.json
    - ![import layout](assets/advantagescope_import_layout.png "Import AdvantageScope Layout")
4. Connect AdvantageScope to your simulation
    - ![connect sim](assets/advantagescope_connect_sim.png "AdvantageScope Connect to Simulation")
5. If done correctly you should see your robot on the field 
    - ![advantagescop running](assets/advantagescope_running.png "AdvantageScope Running")
6. You can now use this to visulize your position on the field and visulize your individual swerve modules. 

### How to run Autonomus
1. Select you auto 
    - Select which auto you would like to run from the "Auto Chooser" this list will be populated from your Auto's section of PathPlanner

| ![Pathplanner autos](assets/pathplanner_autos.png "Pathplanner Autos") | 
|:--:| 
| *Pathplanner Autos* |

| ![auto chooser shuffleboard](assets/auto_chooser.png "Auto Chooser Shuffleboard") | 
|:--:| 
| *ShuffleBoard Auto Selector* |

| ![auto chooser sim](assets/sim_auto_selector.png "Auto Chooser Sim") | 
|:--:| 
| *Simulation Auto Selector* |

2. Once you have your auto selected you can enable the robot in autonomus and watch it follow the path!

### How to run Teleop
1. Enable the robot in Teleoperated
2. The driver joystick is controler 0
    - axis 0 (a/s on keyboard)= left/right
    - axis 1 (w/s on keyboard)= forward/backwards
    - axis 2 (r/e on keyboard)= rotation
    - button 1 (z on keyboard) = reset gyro
    - button 3 (c on keyboard)= Pathplann to feeder station and follow path
    - button 4 (v on keyboard)= pathplan to pose at scoring position
3. Make sure you hit button 3 and button 4 and watch your robot generate its paths on the fly to get to locations on the field!