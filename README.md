# Controller Drive

* Create a new WPILib project.
* Copy this README, and put it in a file named `README.md` in the root directory of the new project.

Check in with a mentor.

* Install the Third-Party Library for CTRE (Phoenix).
* Set up a program to drive the robot. Follow [this guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-4/creating-test-drivetrain-program-cpp-java.html). The motor controller we use is `WPI_VictorSPX` (not Talons!).
* Drive the robot around!

Check in with a mentor once you have this working (or if you're having issues!).

Then, check in after completing each of the following:
* Slow down the acceleration of the robot using a [slew rate limiter](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/filters/slew-rate-limiter.html).
* Display some joystick value on the [SmartDashboard](https://docs.wpilib.org/en/stable/docs/software/dashboards/shuffleboard/getting-started/shuffleboard-displaying-data.html) as a gauge. (Be sure to change the dashboard implementation to Shuffleboard in the driver station.)
```java
SmartDashboard.put...(key, value);
``` 
* Then, display it as a graph.
* Display the controller's A button state on the [SmartDashboard.](https://docs.wpilib.org/en/stable/docs/software/dashboards/shuffleboard/getting-started/shuffleboard-displaying-data.html)