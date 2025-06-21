![Screenshot (2)](https://github.com/user-attachments/assets/3448700e-ca19-4a08-b17c-a2b0cc76ec3d)XY Axis Sketching Robot - Project Documentation
Project Overview
This dissertation presents the design and development of an XY Axis Sketching Robot capable of drawing precise sketches on various surfaces including walls, glass, and paper. The system utilizes two degrees of freedom (X and Y axes) with a servo-controlled pen mechanism, controlled through Arduino UNO microcontroller and open-source software.

![image](https://github.com/user-attachments/assets/03f6060c-b3aa-4bbe-a280-469a6fa5d4d9)


Key Features
2-DOF robotic drawing system

Arduino UNO R3 microcontroller

Stepper motors for X-Y axis movement (NEMA 17)

MG90S servo motor for pen control

GT2 timing belt and pulley system

Open-source control software (Inkscape, Makelangelo)

3D-printed custom components

Working area: 430mm × 320mm

Portable and wall-mountable design

System Components
Mechanical Components
Frame Structure:

Custom 3D-printed mounting brackets
![image](https://github.com/user-attachments/assets/26fbcaee-5301-44ce-84a4-1f33c23f5e6d)
Pen holder assembly
![image](https://github.com/user-attachments/assets/f686089a-af77-468d-9690-5b58f2419dbd)
GT2 rubber belt transmission system
![image](https://github.com/user-attachments/assets/d7037a6f-c4d1-4178-8ace-a4313652bce0)
Aluminum pulleys (16 teeth)

Actuation System:
![image](https://github.com/user-attachments/assets/2fcf0dd7-5b72-4fd7-a177-40a0053c8b15)
2× NEMA 17 stepper motors
![image](https://github.com/user-attachments/assets/cebeb0c8-a3eb-437f-9c26-d700b119439c)
1× MG90S servo motor

Electronic Components
Control System:

Arduino UNO R3

L293D motor drive shield

Power System:

5V power supply

Design Implementation
The robotic system was designed using CATIA software with key considerations:

Motion System:

Cartesian coordinate movement

Belt-driven transmission for smooth operation

Precise pen control via servo mechanism

Software Integration:

Inkscape for SVG file conversion

Makelangelo software for G-code generation

Arduino IDE for microcontroller programming

Control System Architecture
Software Workflow
Image → SVG conversion (Inkscape)

SVG → G-code conversion (Makelangelo)

G-code interpretation (Arduino)

Motor control signals (L293D shield)

Key Algorithms
Stepper motor control for precise positioning

Servo PWM control for pen up/down movement

Path optimization for efficient drawing

Assembly Instructions
Mechanical Assembly:

Mount stepper motors on upper corners

Install GT2 pulleys and belt system

Attach pen holder with servo mechanism

Secure counterweights for belt tensioning

Electrical Connections:

Connect steppers and servo to motor shield

Interface Arduino with computer via USB

Ensure proper power supply connections

Performance Results
The system successfully demonstrated the ability to:

Accurately reproduce vector images

Maintain consistent line quality

Operate on vertical surfaces

Achieve positioning accuracy of ±0.5mm
![image](https://github.com/user-attachments/assets/4cba84d9-6d84-4858-9163-00fb327171f7)
Cost Analysis
![image](https://github.com/user-attachments/assets/c3e696de-a8e9-4e77-b295-43a88b39147e)
Total project cost: ₹5,207 (approx. $70 USD)

Major cost components:

Stepper motors: ₹1,526

Control electronics: ₹1,161

Mechanical components: ₹1,728

3D printing materials: ₹792

Future Enhancements
Advanced Control:

Bluetooth/IoT connectivity

Mobile app interface

Real-time status monitoring

Enhanced Capabilities:

Multi-color drawing system

Larger working area

Force feedback for surface adaptation

Applications:

Laser engraving attachment

CNC milling adaptation

Educational robotics platform

Repository Structure
text

/xy-sketching-robot
│── /documentation       # Project reports and documentation
│── /cad                 # CATIA design files
│── /firmware            # Arduino control code
│── /3d_models           # STL files for printing
│── /test_results        # Performance data and samples
│── README.md            # Project overview
└── LICENSE              # Usage terms
Getting Started

Assemble mechanical components according to CAD drawings

Upload provided Arduino sketch
![image](https://github.com/user-attachments/assets/08ec62e6-abd6-4b63-8046-e3aebdeb8225)
Install required software (Inkscape, Makelangelo)
![image](https://github.com/user-attachments/assets/d1624fee-73a4-4df0-8127-0ffb8f8c4e02)
makelangelo software
Calibrate machine dimensions in software

Load SVG image and initiate drawing process

Dependencies
Arduino IDE (v1.8+)

Inkscape (v1.0+)

Makelangelo software

Ultimaker Cura (for 3D printing)
![image](https://github.com/user-attachments/assets/32e51f76-34ac-46d0-b972-687f2701758c)
![image](https://github.com/user-attachments/assets/4e7f4a16-9a07-4277-bda9-80e47547f6a2)
![image](https://github.com/user-attachments/assets/4634219b-a58a-4cce-86ea-82247d93fc82)
![image](https://github.com/user-attachments/assets/40396b16-8f1e-4916-9dda-eba852eb5d76)
![image](https://github.com/user-attachments/assets/f6249690-6d4f-4bf8-956e-fccfb0a5a756)


