# Traffic Light System Team
We are a team of developers and engineers working on a smart traffic light system using Arduino Yun and Grove Shield. Our project aims to simulate real-world traffic management with pedestrian crossing functionality.
## Project Overview
This project demonstrates a basic traffic light control system. It uses three LEDs (red, yellow, and green) to mimic the behavior of a real traffic light, and includes a push button to simulate a pedestrian crossing feature.

**Technologies:**
- Arduino Yun
- Grove Shield
- Arduino IDE
- LEDs (Red, Yellow, Green)
- Push Button
## Team Members
- **Ben** - Developer & Documentation
- **Dimitri** - Code Architect & Testing
## Key Features
- Simulates a real-world traffic light with LEDs.
- Push button to trigger pedestrian crossing and change light sequence.
- Adjustable light duration using code functions (delay()).
- Grove Shield for easy hardware connections.
## How to Use
1. Clone this repository:
https://github.com/BenGavin16/IOT.git
2. Open the Arduino IDE and connect the Arduino Yun via USB.
3. Upload the code to the board and connect the components (LEDs, Push Button).
4. Press the push button to simulate pedestrian crossing.
## Future Improvements
- Add real-time monitoring via Wi-Fi module.
- Implement advanced traffic light control algorithms based on traffic density.
- Enhance pedestrian button functionality.
## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests to improve the project.

## Updated Assignment 2 Changes
Challenges Faced:

WiFi Connectivity Issues:
Configuring the Arduino Yun to connect to WiFi was challenging and consumed significant time.
Compilation Errors:
Several errors were encountered while uploading code via Arduino IDE, mostly related to library usage and board settings.
Some errors were resolved through troubleshooting, but a few persisted, impacting testing.
Lessons Learned:

Hardware-software integration requires meticulous attention to library compatibility and board configurations.
IoT projects demand rigorous testing at every stage to identify and fix issues early.
Current Status:

The updated code includes logic for real-time traffic light status updates via Blynk.
Full functionality could not be verified due to unresolved upload and connectivity issues.
Future Steps:

Debug the WiFi connectivity problem on the Arduino Yun.
Test and finalize the updated code.
Consider alternative IoT platforms for better integration and reliability.
