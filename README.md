
# Mini Segway Project

### Overview
This project focuses on developing a mini Segway that uses microcontrollers, sensors, and motor drivers to achieve self-balancing functionality. The Segway is designed to be controlled through sensor feedback and remote control, ensuring stability even in the presence of disturbances or rotation.

## Configuration

The Segway is designed to automatically balance itself using input from a gyroscope and accelerometer. Below is an image of the Segway model used in this project:

<p align="center">
  <img src="https://github.com/tahafaghani/ML-App/blob/main/Exe-GUI.png" width="45%" alt="Segway Model"/>
</p>

### Features
- **Self-Balancing**: Maintains balance using gyroscope and accelerometer sensors (MPU6050).
- **Remote Control**: Controlled through a YK45 remote control.
- **Disturbance Recovery**: Automatically corrects balance when disturbed or rotated.
  
### Getting Started
Follow the steps below to set up and run the Mini Segway project:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/tahafaghani/Mini-Segway.git
   ```

2. **Wiring and Circuit Setup**: 
   - Refer to the **Design&simulation.pdf** and **final presentation.pdf** documents for detailed wiring instructions.
   
3. **Upload the Code**:
   - Open the `final-mini-segway.ino` file in the Arduino IDE or PlatformIO.
   - Connect your Arduino or compatible microcontroller and upload the code.

### Hardware Requirements
To build the Mini Segway, you will need the following components:
- **Microcontroller**: Arduino or any compatible board
- **IMU**: MPU6050 (Gyroscope and Accelerometer)
- **Motor Driver**: L298N or a similar motor driver
- **Motors**: DC motors
- **Power Supply**: 9V Battery (minimum 1A current)


  <p align="center">
  <img src="https://github.com/tahafaghani/Mini-Segway/blob/main/components.PNG" width="45%" alt="Segway Model"/>
</p>
Here’s a simplified circuit diagram for reference:

<p align="center">
  <img src="https://github.com/tahafaghani/Mini-Segway/blob/main/Circuit.PNG" width="45%" alt="Circuit Diagram"/>
</p>

### Code
The main code for controlling the Mini Segway is provided in the attached Arduino script, `final-mini-segway.ino`. This code handles reading sensor data, processing it to control the motors, and balancing the Segway.

### Contributions
Contributions are always welcome! If you'd like to improve the project or add new features:
1. Fork this repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request for review.

### Contact
If you have any questions or suggestions, feel free to reach out:

- **Taha Faghani** - [taha.faghani.daroopi@gmail.com](mailto:taha.faghani.daroopi@gmail.com)
- GitHub: [tahafaghani](https://github.com/tahafaghani)

