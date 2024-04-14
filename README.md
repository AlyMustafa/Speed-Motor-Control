# Motor Control with Ultrasonic Sensor and LCD Monitoring

## Objective

Control motor speed based on the car's distance to obstacles using an ultrasonic sensor. The system includes an LCD screen for displaying distance data and uses PWM signals to adjust motor speed to prevent collisions.

## Hardware

- **Microcontroller**: Operating at 72MHz
- **PWM**: Frequency set to 20kHz
- **Ultrasonic Sensor**: For distance measurement
- **LCD Display**: For real-time monitoring
- **Motor and Driver**: For speed control

## Programming

- **Language**: C
- **IDE**: Keil uVision

## Custom Drivers

All drivers in this project have been written from scratch, including:

- **GPIO (General Purpose Input/Output)**: Manages sensor inputs and motor control outputs.
- **Timers**: Provides precise timing for controlling PWM signals and sensor operations.
- **PWM (Pulse Width Modulation)**: Generates signals to modulate motor speed based on distance data.
- **LCD**: Displays distance measurements and other relevant information.
- **Motor**: Controls motor speed and operation.

## Advantages

- Ensures safety and efficiency by dynamically adjusting motor speed.
- Provides real-time monitoring through the LCD display.
- Utilizes PWM for smooth and precise motor control.

## Future Improvements

- Potential integration of additional sensors for enhanced safety and functionality.
- Further optimization of motor control algorithms.
- Improved user interface and data visualization.

## Version Control

- Utilizes Git for version control and collaboration, ensuring smooth project management.
