# Driver-Safety-Enhancement-Using-Eye-Blink-Detection-BAC-and-Proximity-Sensors


## Project Overview
This project focuses on preventing vehicle accidents caused by drowsy or drunk driving. By monitoring the driver’s eye-blinking rate and blood alcohol content (BAC), the system can detect signs of drowsiness or intoxication and alert the driver or passengers to take necessary action.

## Objectives
- To ensure the safety of vehicle occupants by detecting driver drowsiness and alcohol influence.
- To implement a cost-effective solution using readily available components.

## Components
- **Hardware**:
  - Raspberry Pi 4 Model B
  - Pi Camera
  - MQ3 Alcohol Sensor
  - Proximity Sensors
  - Buzzers
  - Jumper Cables
  - Micro-SD Card
  - 15.3 W Power Supply
- **Software**:
  - Python
  - OpenCV Library

## Methodology
1. **Design Schematic**: Create a detailed schematic for the connections.
2. **Connect Peripherals**: Assemble the hardware components as per the schematic.
3. **Programming**: Write the necessary code for the Raspberry Pi to process inputs from the sensors.
4. **Calibration**: Adjust the BAC sensor to Indian standards (30 mg of alcohol per 100 ml of blood).
5. **Testing**: Conduct live tests to ensure the system functions correctly and make adjustments if necessary.

## Software Implementation
- **Eye-Blink Detection**: 
  - Uses Pi Camera to capture video feed.
  - Applies haar cascades in OpenCV to detect eyes.
  - Triggers an alarm if signs of drowsiness are detected.
- **Alcohol Detection**:
  - MQ3 sensor measures BAC levels.
  - Triggers an alarm if BAC exceeds the safe limit.

## Flowchart

![Screenshot (45)](https://github.com/theliwash/Driver-Safety-Enhancement-Using-Eye-Blink-Detection-BAC-and-Proximity-Sensors/assets/163035610/8c651fa7-ce7d-478f-9fa6-ccba345339f4)

## Circuit Diagram


![Screenshot (44)](https://github.com/theliwash/Driver-Safety-Enhancement-Using-Eye-Blink-Detection-BAC-and-Proximity-Sensors/assets/163035610/507493ab-a411-4cba-ae16-f3e122392e36)

## Results and Analysis
- **Distance Factor**: Performance varies with the distance between the driver and the camera.
- **Effect of Ambient Light**: Ambient lighting conditions can affect the accuracy of detection.

## Conclusion
The project successfully demonstrates a method to enhance vehicle safety by detecting driver drowsiness and alcohol influence. The system's effectiveness is influenced by external factors like ambient light and distance but provides a significant step towards reducing vehicular accidents.

## Acknowledgements
- Special thanks to our project guide Dr. Bhargabjyoti Saikia and Head of the Department Mr. N.H. Singh for their guidance and support.
- Gratitude to our parents and friends for their inspiration and support.

