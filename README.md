# Automatic-PID

## Introduction

The FRC Automatic PID Tuning Library is a Java library designed to simplify and automate the process of tuning PID controllers for the FIRST Robotics Competition (FRC). It provides a convenient way to optimize your robot's PID controllers for various subsystems such as drivetrains, elevators, and more.

## Features

- Automated PID tuning for FRC robots.
- User-friendly and customizable tuning process.
- Gradle and Maven compatibility for easy integration.

## Getting Started

### Prerequisites

Before using this library, you'll need:

- A working FRC development environment with Java support.
- Gradle or Maven installed on your development machine.

### Installation

You can easily add the FRC Automatic PID Tuning Library to your FRC project as a dependency by including it in your `build.gradle` (for Gradle) or `pom.xml` (for Maven) file.

#### Maven
```xml
<dependencies>
    <!-- ... other dependencies ... -->
    <dependency>
        <groupId>com.example</groupId>
        <artifactId>frc-pid-tuning</artifactId>
        <version>1.0.0</version>
    </dependency>
</dependencies>
```

#### Gradle
```gradle
dependencies {
    // ... other dependencies ...
    implementation 'com.example:frc-pid-tuning:1.+'
}
```

### Usage

1. Define Automatic-PID as a dependency
2. Chose an accurate system model
3. Add model as input, along with other important system information
4. Collect the output values from characterization
5. Use output values (P,I,D) for your system's PID controller

## Documentation

For more details and advanced usage, please refer to the library's official github pages documentation.

## Contributing

We welcome contributions from the FRC community. If you encounter issues or have ideas for improvements, please feel free to open an issue or submit a pull request on our GitHub repository.

## License

This project is licensed under the WPILib License.

## Contact

For any questions or support, please contact our team.

---

Happy PID tuning for your FRC robot! We hope this tool  makes the process smoother and more efficient for your team.
