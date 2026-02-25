5V Regulated DC Power Supply Using 7805

Overview
This project demonstrates the design, construction, and testing of a 5V regulated DC power supply using a 7805 linear voltage regulator. The aim is to understand voltage regulation, thermal behaviour, load regulation, and stability.

Objectives
- Convert 9–12V DC input to a stable 5V output
- Study load regulation and voltage drift
- Analyse thermal performance
- Understand oscillation prevention using decoupling capacitors

Components Used
- 7805 voltage regulator
- 470µF electrolytic capacitor
- 0.33µF ceramic capacitor (input)
- 0.1µF ceramic capacitor (output)
- LED + 330Ω resistor
- Breadboard and jumper wires

Circuit Description
The circuit consists of an input filter capacitor, a 7805 linear regulator, and output decoupling to ensure stable voltage regulation and prevent oscillation.

Testing Performed
- No-load voltage measurement
- Load regulation testing
- Thermal observation
- Fault analysis (missing capacitor, overload)

Results
- Output voltage remained stable at ~5.0V under nominal load
- Thermal rise observed at higher currents
- Output instability occurred when decoupling capacitors were removed

Key Learnings
- Importance of decoupling capacitors
- Thermal limitations of linear regulators
- Difference between linear and switching regulation

Future Improvements
- Replace linear regulator with buck converter
- Add current protection
- Design PCB version

Author
Nicey Raphael  
Graduate Electronics Engineer


