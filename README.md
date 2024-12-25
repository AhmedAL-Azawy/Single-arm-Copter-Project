# Single-arm Copter Project

## **Overview**
The Single-arm Copter Project is a robotic system designed to demonstrate precise angular control and efficient motion. This project integrates advanced hardware components and control algorithms to create a reliable and versatile system suitable for various applications, including automation and industrial tasks.

## **Project Goals**
- Achieve precise angular control of the robotic arm.
- Utilize feedback sensors to enhance system performance.
- Enable wireless control for real-time operation.
- Implement a robust PID controller to ensure smooth and stable motion.

## **System Specifications**
- **Arm Length**: 18 cm
- **Total Load**: 300 g
- **Control System**: Arduino Uno
- **Power Supply**: SMPS S-200-12 (12V, 16.5A)

## **Hardware Components**
1. **Brushless Motor**: EMAX 1400KV (XA2212) with a propeller (EPP 10X4.5 Inch) for efficient thrust generation.
2. **Power Supply**: SMPS S-200-12 (12V, 16.5A) to deliver stable power to the motor and control system.
3. **Sensors**:
   - Rotary Encoder Module: For precise angular feedback.
   - IR Sensor Encoder: To provide additional feedback for RPM calculations.
   - GY-521 MPU6050 Accelerometer and Gyroscope Module: For detecting orientation and angular velocity.
4. **HC-05 Bluetooth Module**: Enables wireless communication for controlling the desired angle of the arm.

## **Software Features**
- **Control Algorithm**: Implements a PID controller to ensure precise control of the arm’s angle.
- **Feedback Integration**: Utilizes real-time data from the rotary encoder, IR encoder, and MPU6050 module to optimize performance.
- **Wireless Control**: Allows the user to set target angles via Bluetooth using a mobile device or computer.
- **RPM Monitoring**: Calculates and displays RPM data using the IR sensor encoder.

## **Project Workflow**
1. **Initialization**:
   - Set up all components and ensure proper wiring.
   - Calibrate sensors and initialize the PID controller.

2. **Feedback Loop**:
   - Collect real-time data from the sensors.
   - Calculate the error between the target and current angles.
   - Use the PID controller to adjust the motor’s throttle to minimize the error.

3. **Wireless Control**:
   - Receive user commands via Bluetooth.
   - Update the target angle dynamically.

4. **Performance Monitoring**:
   - Display real-time RPM, angle, and control signals for debugging and optimization.

## **Applications**
- Automation tasks requiring precise motion.
- Industrial systems with high precision requirements.
- Demonstrations of control systems in educational settings.

## **Future Enhancements**
- Integrating additional sensors for more robust feedback.
- Improving the PID tuning process with adaptive algorithms.
- Exploring multi-axis control for more complex applications.
- Enhancing the wireless interface for better user interaction.

## **How to Run the Project**
1. Connect all components as per the circuit diagram (to be provided).
2. Upload the Arduino code to the Arduino Uno.
3. Power the system using the SMPS.
4. Use a Bluetooth-compatible device to send angle commands and observe the arm's motion.

## **Acknowledgments**
This project was made possible through the integration of engineering principles, creative problem-solving, and teamwork.

## **Contact**
For any inquiries or collaboration opportunities, please feel free to reach out via GitHub or LinkedIn.

