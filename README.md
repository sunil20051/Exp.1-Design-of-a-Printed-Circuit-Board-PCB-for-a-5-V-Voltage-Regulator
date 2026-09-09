# Exp.1-Design-of-a-Printed-Circuit-Board-PCB-for-a-5-V-Voltage-Regulator
Aim

To design the schematic and PCB layout of a 5 V voltage regulator circuit using KiCad, perform electrical and design rule checks, and generate Gerber files for PCB fabrication

Apparatus Required

1.Computer with KiCad (Version 8.0 or later)
2.7805 Voltage Regulator (TO-220 Package)
3.DC Input Connector (7–12 V)
4.Output Connector
5.Capacitor – 0.33 µF (Input)
6.Capacitor – 0.1 µF (Output)
7.Capacitor – 10 µF Electrolytic (Optional)
8.LED
9.330 Ω Resistor
10.PCB design libraries available in KiCad

Circuit Diagram

<img width="960" height="504" alt="Screenshot 2026-08-03 133428" src="https://github.com/user-attachments/assets/e416aed9-4524-4c8a-a2d6-e980088389b5" />












Procedure

1.Open KiCad and create a new project.
2.Draw the schematic by placing the 7805 regulator, capacitors, resistor, LED, and connectors.
3.Assign proper net labels (VIN, +5V, GND).
4.Perform Electrical Rule Check (ERC) and rectify all errors, if any.
5.Assign suitable footprints to all schematic components.
6.Open the PCB Editor and import the netlist/schematic.
7.Arrange all components considering minimum track length and proper placement.
8.Define the board outline.
9.Route all PCB tracks using the required track width.
10.Create a copper fill (ground plane) connected to GND.

Output:


<img width="960" height="504" alt="Screenshot 2026-08-03 133814" src="https://github.com/user-attachments/assets/c9cbf0c0-3efc-45a9-bd1b-f30e267d2714" />


<img width="960" height="504" alt="Screenshot 2026-08-03 134418" src="https://github.com/user-attachments/assets/28f722c6-4bf8-4f94-85d4-2e02db2065ec" />















Result:

The PCB layout for the 5 V Voltage Regulator was successfully designed in KiCad. The schematic passed the Electrical Rule Check (ERC), the PCB passed the Design Rule Check (DRC) without errors, and the Gerber files required for PCB fabrication were successfully generated










11.Run the Design Rule Checker (DRC) and correct any reported violations.
12.Add reference designators, board title, and revision information.
Generate Gerber files and drill files for PCB fabrication.
