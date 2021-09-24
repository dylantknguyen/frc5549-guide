# Programming Resources

- [WPILib Docs (Official FRC Library & Docs)](https://docs.wpilib.org/en/latest/)
- [WPILib Java API](https://first.wpi.edu/wpilib/allwpilib/docs/release/java/index.html)
- [WPILib Java Examples](https://docs.wpilib.org/en/stable/docs/software/examples-tutorials/wpilib-examples.html)
- [Discussion Forum Focused on FRC](https://www.chiefdelphi.com/)

# Concepts to Learn (Ordered)

1. **Setting up Environment:** [Install WPILib and VS Code](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html). Note that we are using Java, not LabView or C++. If you wish to control to the robot from your laptop, install the [FRC Game Tools](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/frc-game-tools.html). Please note that this package includes a lot of software. It's only necessary on the white Gryphon Robotics laptop.
2. **Learn Java and Git**: Most online Java resources are quite lengthy. As there is quite little time to learn Java, I highly suggest that you ask your programming captain to teach you. You really only need the basics. Variables, files, classes, methods, constants, if statements, and for statements. As for Git, once again ask your programming captain. You can also read [my resources on Git](Git.md).
3. **Learn to Drive via Joysticks:** Follow [this WPILib guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-4/creating-benchtop-test-program-cpp-java.html). It will teach you how to setup a project and drive the robot with the joysticks (Property of Gryphon Robotics)
4. **Programming Functionality to Xbox Controller:** For this step, there is no WPILib guide. However, I suggest that you refer to the WPILib Java API docs on the [Xbox Controller class](https://first.wpi.edu/wpilib/allwpilib/docs/release/java/edu/wpi/first/wpilibj/XboxController.html). If you are using a TimedRobot project, remember that you can simply have code run _if_ a button is being pressed.
5. **Run Motor on Button Press:** Note that we use motor controllers from CTR Electronics. Therefore, we must use their library on top of WPILib. The instructions on how to add their library are [here](https://docs.ctre-phoenix.com/en/stable/ch05a_CppJava.html#frc-c-java-add-phoenix) and their instructions on setting up a single Talon SRX are [here](https://docs.ctre-phoenix.com/en/stable/ch05a_CppJava.html#frc-java-build-test-single-talon). If you want to tune our motors, see [here](https://docs.ctre-phoenix.com/en/stable/ch05_PrepWorkstation.html). Please note that most members will not need to install it as it is already installed on the white Gryphon Robotics laptop. [CTR Electronics Java API Documentation](https://www.ctr-electronics.com/downloads/api/java/html/index.html)
6. **Add More Functionality**: Try to have multiple controllers move together and at the same time. Refer to the documentation on [the SpeedControllerGroup class](https://first.wpi.edu/wpilib/allwpilib/docs/release/java/edu/wpi/first/wpilibj/SpeedControllerGroup.html). Combine this with if statements so that it can only will be run on a button press.
7. **Make a short autonomous:** Combine your knowledge used to create a short autonomous. I'd suggest you just move the robot forward for a set amount of time, turn the robot, then reverse the robot for a set amount of time.
8. **Learn Sensors:** Sensors are the first step to adding cool new functionality. This brings value to a value to the robot that mechanical and electrical cannot provide. An example of this is that we automatically moved a ball from our intake mechanism to our shooter mechanism if it wasn't full. I suggest you learn about limit switches, color sensors, and ultrasonics. Those are the important ones. If you have time, learn about hall effect sensors, which is a digital input. That was the key component in our lift mechanism during 2019. Some guides on these sensors can be seen [here](https://docs.wpilib.org/en/stable/docs/software/sensors/index.html)
9. **Advanced Control**: Now, here is where programming really shines. Encoders, NavX, PID, and the Limelight. These features differentiates between teams that make it to Worlds and teams that don't. Note how I do not mention the district championships because you can get to district championships without any of this control. If the team is worried about the robot breaking down during competition, give mechanical and electrical more time. Remember, this is a team game. As for resources, there are few resources. Most of the learning will need to be done through experimentation. However, here are the docs for [Encoders](https://docs.wpilib.org/en/stable/docs/software/sensors/encoders-software.html?highlight=Encoders), [PID](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/introduction/index.html), [NavX](https://pdocs.kauailabs.com/navx-mxp/examples/), and [Limelight](https://docs.limelightvision.io/en/latest/). In addition, feel free to reach out to Dylan (Alumni), if you need assistance.

Note: Please listen to your programming captain. This is my opinion on the order I think you should learn these concepts in. Your captain may have a different order of importants. Listen to them.

# Additional Resources

- [FRC 5549 (2020) - Java Command-based Rewrite](https://github.com/dylantknguyen/FRC5549-2020-Java)
- [FRC 5549 (2020) - Python](https://github.com/FRC5549Robotics/5549-2020)
- [FRC 5549 (2019) - Python](https://github.com/FRC5549Robotics/5549-2019)

# Contact

Feel free to contact me via the FRC 5549 Discord. My nickname there is Dylan. If you cannot reach me there, ask one of the captains if they have my contact information. If they do not, feel free to open an issue here and I will do my best to respond.
