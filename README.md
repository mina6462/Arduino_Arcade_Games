🕹️ Arduino IDE Arcade Games

A collection of interactive arcade-style games built on Arduino, featuring real hardware components, live scoring displays, and 3D-printed enclosures.


Overview
This project brings classic arcade-game concepts to life using Arduino microcontrollers and physical electronics. Each game integrates sensors, LEDs, and LCD displays for real-time scoring and interactivity. Enclosures and mechanical components were 3D-printed and designed from scratch, and a stable power supply was engineered to support all components simultaneously.
The project was presented to 50+ students and faculty as a live technical demonstration.

Tech Stack
CategoryTools / ComponentsMicrocontrollerArduino UNOProgrammingC++, Arduino IDEDesign & SimulationTinkerCAD, Electrical SchematicsHardwareSensors, LEDs, LCD Displays, ButtonsFabrication3D Printing (PLA), Custom Enclosures

Games Included
🎯 Game 1 — [Your Game Name Here]

Brief description of gameplay and hardware used (e.g., "Reflex-based button game using LEDs and a timer displayed on LCD")

🎮 Game 2 — [Your Game Name Here]

Brief description of gameplay and hardware used

(Add or remove games as needed)

Hardware Components

Arduino UNO microcontroller
16x2 LCD display (live score output)
Various sensors (ultrasonic, IR, etc.)
LEDs and resistors
Push buttons
Regulated power supply circuit
3D-printed game enclosure (designed in TinkerCAD)


Project Structure
arduino-arcade-games/
├── game1/
│   ├── game1.ino              # Arduino sketch for Game 1
│   └── schematic_game1.png   # Wiring schematic
├── game2/
│   ├── game2.ino              # Arduino sketch for Game 2
│   └── schematic_game2.png   # Wiring schematic
├── cad/
│   └── enclosure.stl          # 3D model for printed enclosure
├── docs/
│   └── presentation.pdf       # Technical presentation slides
└── images/
    └── demo.jpg               # Photo of final build

Key Features

Live Scoring — LCD display updates in real time during gameplay
Sensor Integration — Multiple sensor types used for game input and interactivity
Power Supply Design — Engineered a stable power circuit to support all components without brownout
3D-Printed Enclosures — Custom-designed mechanical housing for a polished, durable final product
Technical Presentation — Demonstrated system design and functionality to a live audience of 50+ people


How to Run

Open the desired game folder (e.g., /game1)
Open game1.ino in Arduino IDE
Connect your Arduino UNO via USB
Select the correct Board and Port under Tools
Click Upload
Wire components according to schematic_game1.png
Power up and play!


Project Status
✅ Completed — October 2024 – December 2024

Media

📷 Photos of the physical build and demo coming soon


What I Learned

Writing clean, efficient C++ for resource-constrained microcontrollers
Integrating multiple hardware peripherals (sensors, displays, LEDs) on a single Arduino
Designing and 3D printing functional enclosures from scratch in TinkerCAD
Communicating a full hardware project clearly to a non-technical audience
