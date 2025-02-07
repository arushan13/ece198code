Designed and implemented a Crash Prevention System for older vehicles without built-in crash detection capabilities. The system utilized two STM32 Nucleo boards (STM32F401RE):

Sensor Module: The first STM32 board collected distance measurements from an ultrasonic sensor mounted externally on the vehicle. This module processed real-time data and transmitted it wirelessly to the alert system.

Alert Module: The second STM32 board, mounted on the windshield, received the transmitted data via UART. It provided the driver with immediate feedback through LEDs and a piezo buzzer, alerting them to potential collision risks.

The development involved leveraging UART communication for reliable data transfer, GPIO programming for interfacing hardware components, and Embedded C++ to create an efficient, real-time processing system. Using the STM32 Cube IDE, I optimized the system to work seamlessly with minimal hardware and budget constraints, showcasing ingenuity in resourceful problem-solving and embedded systems engineering.

This project demonstrates our ability to integrate software and hardware into functional, user-focused solutions, aligning with real-world applications in automotive safety.
