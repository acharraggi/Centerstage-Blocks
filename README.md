# Centerstage-Blocks
Repository of Blocks example programs from the Centerstage FTC season.

Note: work in progress, just a couple of programs uploaded so far.

BasicOmniOpMode - Blocks supplied sample program that drives a Mecanum-Drive or an X-Drive train robot.

blocks-AprilTag - basic April Tag program with Len Intrinsics set for Logitech C920 at resolution 1920x1080. Also has disabled blocks for webcam exposure/gain setting. Also shows writing messages to the Robot Contoller Log.

blocks-AprilTagEasy - Blocks supplied sample program that shows detected April Tags on the driver station via telemetry.

blocks-RobotAutoDriveTFODpixel - example program that combines the TFOD sample program and the BasicOmniOpMode sample program. It drives forward, the looks at each spike mark in turn and uses TFOD to check for the pixel. If found, the robot drives onto the spike mark and announces that if found the pixel.

blocks-RobotAutoDriveToAprilTagOmni - Based on the Java sample program RobotAutoDriveToAprilTagOmni, but this program is strictly autonomous.

blocks-TFOD - basic TFOD that detects the pixel, with webcam resolution set to 1920x1080.

blocks-TFODconcreteModel - TFOD on Cup, Crown, Tower model (based on videos taken on concrete).

blocks-TFODcustom - TFOD on Red/Blue Duplo team props. Make use of setMinResultConfidence.

blocksTFODcustomSpikeMark - custome TFOD that will report which spike mark has the Red or Blue Duplo Team Prop. Also demostrates using gamepad during initialization.

blocks-TFODeasy -  Blocks supplied sample program detects the pixel (if looking down on it).

blocks- TFODswitchable - Blocks supplied sample program detects the pixel, and can switch between webcams.

Studica-Teleop - Blocks program to drive the robot during the driver controlled period and activate various mechanisms.

These  programs make use of a demonstration robot uses mecanum wheels and four motors. It was built from the Studica robotics Kit: https://www.studica.com/studica-robotics/studica-robotics-ftc-starter-kit-2023-2024
![Model](https://raw.githubusercontent.com/acharraggi/Centerstage-Blocks/main/Images/PXL_20231028_205146758.jpg)

- It has two webcams, one points down for Pixel detection, one points forward for April Tag detection.
- It has a small arm that can attempt to place the yellow pixel on the backdrop. It's not able to pick up pixels.
- It has a small drone launcher on top, and a pair of arms that can be used to hang in end game.

![Model](https://raw.githubusercontent.com/acharraggi/Centerstage-Blocks/main/Images/PXL_20231028_205153028.jpg)