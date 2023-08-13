# kerolesgirges-Adabtive-Cruise-Control-system

This project involves the creation of an adaptive cruise control system using an ATmega32 microcontroller, Bluetooth module, LCD display, LDR sensor, three LEDs, DC motor, ultrasonic sensor, and an external EEPROM. The system is designed to automatically regulate a vehicle's speed to maintain a safe following distance from the car ahead. Additionally, it can communicate with a smartphone app through Bluetooth, enabling features such as cruise control activation/deactivation and other functionalities. The ultrasonic sensor is employed to detect obstacles and prevent collisions.

Hardware Components:
The project employs the following hardware components:
- ATmega32 Microcontroller: Serves as the primary control unit, collecting inputs from the LDR, Bluetooth module, and ultrasonic sensor, while managing outputs to the LCD, LEDs, and DC motor.
- Bluetooth Module: Facilitates wireless connectivity between the system and a smartphone app, allowing commands for cruise control activation, emergency brake, and more.
- LCD Display: Presents real-time distance information and system errors.
- LDR Sensor: Measures reflected light intensity from the preceding vehicle.
- Three LEDs: Indicate system status - green (safe movement), blue (emergency brake), and yellow (waiting state).
- DC Motor: Simulates vehicle speed, controlled by ATmega32's PWM signal.
- Ultrasonic Sensor: Detects obstacles in front of the vehicle by emitting ultrasonic waves and measuring their return time.
- External EEPROM: Stores distance, cruise status, and error information to retain settings during power disruptions.

Software Components:
Software components used in the project:
- Microchip IDE: Utilized to program the ATmega32 microcontroller using the C language.
- MIT App Inventor: Employs visual programming to develop an Android smartphone app that communicates with the Bluetooth module. The app sends commands for speed and distance adjustments and displays real-time feedback.

Usage Instructions:
To utilize this project, follow these steps:
1. Assemble and connect all hardware components.
2. Upload code to the ATmega32 using an appropriate programming tool.
3. Install the MIT App Inventor on an Android device.
4. Power on the system and smartphone app, then establish a Bluetooth connection.
5. Begin enjoying the benefits of the adaptive cruise control system.

An upcoming demo video will provide a visual presentation of the project's functionality.
