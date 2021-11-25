# atlas-swerve
Example code and logic for differential swerve drive

Planning to use falcon 500 motors.
docs on those motors can be found here: https://docs.ctre-phoenix.com/en/stable/index.html

Inspiration for this includes the following:
https://www.youtube.com/watch?v=32aPNl0YauY

Basic Design Principles:
- 2 Falcon 500 Motors used which control both turning and driving.
- 1 CTRE CANcoder used for obtaining where the wheel is when the robot is powered on.
- Bearings that mount to the axle which when supports an inline encoder mount with the wheel whilst still alowing the wheel to spin.
- Building on the above; possibly more bearings on this structure to go along the sides of the 2 gears for more support
