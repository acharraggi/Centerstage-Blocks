# Centerstage-Blocks
Repository of Blocks example programs from the Centerstage FTC season. Click on the program names below to see the downloaded image of the program.

- [blocks-AprilTag](Images/blocks-AprilTag.png) - basic April Tag program with Len Intrinsics set for Logitech C920 at resolution 1920x1080. Also has disabled blocks for webcam exposure/gain setting. Also shows writing messages to the Robot Contoller Log.

- [blocks-RobotAutoDriveTFODpixel](Images/blocks-RobotAutoDriveTFODpixel.png) - example program that combines the TFOD sample program and the BasicOmniOpMode sample program. It drives forward, the looks at each spike mark in turn and uses TFOD to check for the pixel. If found, the robot drives onto the spike mark and announces that if found the pixel. See it in action here: https://youtu.be/n5UvLlFu5Lw

- [blocks-RobotAutoDriveToAprilTagOmni](Images/blocks-RobotAutoDriveToAprilTagOmni.png) - Example program that attempts to drives towards and position itself in front of an April Tag. Based on the Java sample program RobotAutoDriveToAprilTagOmni, but this program is strictly autonomous. See it in action here: https://youtu.be/E7zqoAymHww

- [blocks-blocksTFODcustomSpikeMark](Images/blocks-TFODcustomSpikeMark.png) - custom TFOD that will report which spike mark has the Red or Blue Duplo Team Prop. Also demostrates using gamepad during initialization, not used later in this program, but this is where you could adjust exposure if needed.

- [Studica-Teleop](Images/Studica-Teleop.png)
Studica-Teleop - Blocks program to drive the robot during the driver controlled period and activate various mechanisms.

These  programs make use of a demonstration robot uses mecanum wheels and four motors. It was built from the Studica robotics Kit: https://www.studica.com/studica-robotics/studica-robotics-ftc-starter-kit-2023-2024.

The config file has these names:
- Webcam 1
- Webcam 2
- Motor port 0 - NeveRest40Gearmotor - drive_leftFront
- Motor port 1 -NeveRest40Gearmotor - drive_leftBack
- Motor port 2 -NeveRest40Gearmotor - drive_rightFront
- Motor port 3 -NeveRest40Gearmotor - drive_rightBack
- Servo port 0 - Servo - plane
- Servo port 0 - Servo - hang
- Servo port 0 - Servo - pixel

![Model](https://raw.githubusercontent.com/acharraggi/Centerstage-Blocks/main/Images/PXL_20231028_205146758.jpg)

- It has two webcams, one points down for Pixel detection, one points forward for April Tag detection.
- It has a small arm that can attempt to place the yellow pixel on the backdrop. It's not able to pick up pixels.
- It has a small drone launcher on top, and a pair of arms that can be used to hang in end game.

![Model](https://raw.githubusercontent.com/acharraggi/Centerstage-Blocks/main/Images/PXL_20231028_205153028.jpg)