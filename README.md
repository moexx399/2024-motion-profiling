# Overview
- Base swerve built with YAGSL
    - lib: https://github.com/BroncBotz3481/YAGSL
    - example project: https://github.com/BroncBotz3481/YAGSL-Example
- Pathplanning software is PathPlanner: https://github.com/mjansen4857/pathplanner
- Simulation visulized with: https://github.com/Mechanical-Advantage/AdvantageScope
- Powerpoint link: https://1drv.ms/p/s!AutaRYnTDq2IgwDoHKtY8IMPlVqC?e=Yc5fE9


### Changes Made to base YAGSL example project
https://github.com/moexx399/2024-motion-profiling/blob/master/src/main/java/frc/robot/RobotContainer.java
- Create sendable chooser
    - https://github.com/mjansen4857/pathplanner/wiki/Java-Example:-Build-an-Auto#build-a-sendablechooser-with-all-autos-in-project
- Add all robot commands
    - https://github.com/mjansen4857/pathplanner/wiki/Java-Example:-Register-Named-Commands
- Add teleop buttons for on the fly path planning
    - Pathfind to pose: https://github.com/mjansen4857/pathplanner/wiki/Java-Example:-Automatic-Pathfinding#autobuilder
    - Pathfind then follow path: https://github.com/mjansen4857/pathplanner/wiki/Java-Example:-Automatic-Pathfinding#autobuilder-1

https://github.com/moexx399/2024-motion-profiling/blob/master/src/main/java/frc/robot/subsystems/swervedrive/SwerveSubsystem.java
- Add AutoBuilder.configureHolonomic to init function
    - https://github.com/mjansen4857/pathplanner/wiki/Java-Example:-Build-an-Auto#configuring-autobuilder

## WARNING!!! THIS PROJECT WAS MADE WITH 2024 BETA VENDOR LIBRARIES AND MODIFIED 2023 VENDOR LIBRARIES. MAKE SURE YOU USE ALL 2024 VENDOR LIBRARIES WITH WPI VS CODE. 