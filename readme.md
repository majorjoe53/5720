![Hemlock's Gray Matter - AdvantageKit Swerve Base](./docs/images/Github%20Header.png)

<p align="center">
  <a href="https://github.com/wpilibsuite/allwpilib/releases/tag/v2024.1.1-beta-4"><img src="https://img.shields.io/badge/WPILib-2024.1.1--beta--4-AC2B37" /></a>
  <a href="https://v6.docs.ctr-electronics.com/en/stable/"><img src="https://img.shields.io/badge/Phoenix6-24.0.0--beta--7-97D700"></a>
  <a href="https://docs.revrobotics.com/sparkmax/software-resources/spark-max-api-information"><img src="https://img.shields.io/badge/REVLib-2024.0.0-f05a28"></a>
</p>

<p align="center">This is a template repository for starting a new <a href="https://wpilib.org/">WPILib</a> robot project using <a href="https://github.com/Mechanical-Advantage/AdvantageKit">AdvantageKit</a>. It provides support for TalonFX and SparkMAX powered drivetrains, as well as April Tag field tracking with Limelight and full robot simulation with code replay.</p>

## Getting Started

Click on the "Use this template" button at the top of the repository (or the one directly below this)

[![Use this template](https://img.shields.io/badge/Use_this_template-238636?style=for-the-badge)](https://github.com/new?template_name=AdvantageKitSwerveTemplate&template_owner=Hemlock5712)

Clone the repository, then change the team number in the `.wpilib/wpilib_preferences.json` file.

> Note: You will need the 2024 beta version of WPILib VSCode and 2024_v2.0 beta roboRIO image installed to run this properly. You can download both from the [WPILib Releases Page](https://github.com/wpilibsuite/allwpilib/releases)

---

When deploying code to your robot, you'll need to change the value of `currentMode` to `Mode.REAL` in `Constants.java`

## Other values to adjust

### Drive.java
  * `MAX_LINEAR_SPEED` , `TRACK_WIDTH_X` , `TRACK_WIDTH_Y`

### GyroIOPigeon2.java
  * `pigeon`

### Module.java
  * `WHEEL_RADIUS`

### ModuleIOTalonFX.java or ModuleIOSparkMax.java
  * `DRIVE_GEAR_RATIO`, `TURN_GEAR_RATIO`, `IS_TURN_MOTOR_INVERTED`, along with all drive, turn, CANcoder, CANbus, and `absoluteEncoderOffsets` values



## Credits

This project is heavily based on example code from Team 6328 - Mechanical Advantage from their [AdvantageKit repository](https://github.com/Mechanical-Advantage/AdvantageKit)
