🚗 Building a CAN-Based Automotive Dashboard using PIC18F4580
During my embedded systems training at Emertxe Information Technologies, I developed a project focused on designing a distributed automotive dashboard system using the CAN (Controller Area Network) protocol and Embedded C.
The objective was to simulate how multiple Electronic Control Units (ECUs) in a vehicle communicate efficiently to exchange real-time data and update dashboard information.
🔹 System Architecture
 To replicate real-world automotive communication, the system was structured into three independent ECUs connected via CAN:
• ECU1 – Acquires vehicle speed (ADC) and gear input (keypad), then transmits data
 • ECU2 – Measures engine RPM (ADC) and controls indicators (LEFT / RIGHT / HAZARD)
 • ECU3 – Functions as the dashboard, receiving CAN messages and updating the CLCD
This distributed design provided hands-on insight into how automotive ECUs interact reliably with minimal wiring.
🔹 Key Features Implemented
⚙️ Analog Data Acquisition
 Utilized the 10-bit ADC of PIC18F4580 to capture speed and RPM signals and convert them into meaningful values.
🎛 Control Inputs (Gear & Indicators)
 Implemented keypad-based input handling to simulate real vehicle controls.
📟 Dashboard Display System
 Real-time display of Speed, RPM, and Gear on CLCD
 Indicator status updates using LEDs
 Continuous system operation without blocking execution
🧠 Bare-Metal Firmware Development
 Developed without an RTOS using a modular driver-based approach for ADC, CAN, CLCD, and Matrix Keypad.
🛠 Technologies & Concepts Used
• Embedded C Programming
 • CAN Protocol Implementation
 • PIC18F4580 Microcontroller
 • Peripheral Interfacing
 • Real-Time Embedded System Design
💡 Key Takeaways
✔ Understanding of CAN-based ECU communication
 ✔ Practical experience with ADC configuration and scaling
 ✔ Improved skills in structured embedded firmware design
 ✔ Exposure to real-time distributed systems
🚀 This project strengthened my foundation in automotive embedded systems and real-time communication.
