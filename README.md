D.O.M 27 Synth
My project is a fully DIY & anaglouge modular synth based on the eurorack system. It features 4 fundemental components of synthesis - a VCO, LFO, VCF & VCA. Because it is a modular synth & based on eurorack, this means that I can create more modules when I please to expand
the functionality of my synth. 

I made this my project is due to my passion for synth music and a want to learn to electronics. This was perfect as I could learn some basics of anaglouge electronics while also creating a useable, musical instrument. It was also perfect because modular synthesis is 
typically a very expensive hobby to get into.

## All 4 modules together 
![image](https://github.com/user-attachments/assets/85197b87-c91b-4e42-b6df-25c2b775514b)
## VCA pcb
![image](https://github.com/user-attachments/assets/37be5d73-dde8-478d-9ac8-0fa493a5fe8e)
## LFO pcb
![image](https://github.com/user-attachments/assets/07191062-0c23-4746-a653-a4278b05967b)
## VCO pcb
![image](https://github.com/user-attachments/assets/17143ab4-50b9-4f06-a48b-001e742754a7)
## VCF pcb
![image](https://github.com/user-attachments/assets/0b74a0ac-cdbf-4b2f-bb67-427607a43b9b)

# D.O.M 27 Synth Bill of Materials

| Footprint | Reference | Qty | Value | Source |
|-----------|-----------|-----|-------|--------|
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C1,C4 | 2 | 1n | DS-20 VCF |
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C5 | 1 | 470n | DS-20 VCF |
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C6 | 1 | 4.7n | DS-20 VCF |
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C8,C9,C10,C11 | 4 | 100n | DS-20 VCF |
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C2 | 1 | 2.2nF | DOMSynth |
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C3 | 1 | 1µF | DOMSynth |
| Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm | C1,C2 | 2 | 47n | Dom LFO |
| Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm | C1,C4 | 2 | C | Dom VCA |
| Capacitor_THT:CP_Radial_D6.3mm_P2.50mm | C7,C12 | 2 | 10u | DS-20 VCF |
| Capacitor_THT:CP_Radial_D5.0mm_P2.50mm | C2,C3 | 2 | C_Polarized | Dom VCA |
| LED_THT:LED_D5.0mm | D1,D3 | 2 | LED | DS-20 VCF |
| Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal | D2 | 1 | 1N4148 | DOMSynth |
| Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal | D1,D2,D3,D4 | 4 | 1N4148 | Dom LFO |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J7,J8,J9,J10 | 4 | AudioPlug3 | DS-20 VCF |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J1 | 1 | CV In | DOMSynth |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J2 | 1 | FM In | DOMSynth |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J3 | 1 | Saw Out | DOMSynth |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J4 | 1 | Pulse Out | DOMSynth |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J5 | 1 | PMW In | DOMSynth |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J1,J2,J7,J8 | 4 | AudioPlug3 | Dom LFO |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J1 | 1 | CV2 in | Dom VCA |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J2 | 1 | Audio 2 in | Dom VCA |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J3,J4,J5,J6,J9,J14 | 6 | AudioPlug3 | Dom VCA |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J7 | 1 | cv in | Dom VCA |
| Connector_Audio:Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles | J8 | 1 | audio in | Dom VCA |
| Connector_IDC:IDC-Header_2x08_P2.54mm_Vertical | J12 | 1 | Conn_02x08_Odd_Even | DS-20 VCF |
| Connector_IDC:IDC-Header_2x08_P2.54mm_Vertical | J6 | 1 | Conn_02x08_Top_Bottom | DOMSynth |
| Connector_IDC:IDC-Header_2x08_P2.54mm_Vertical | J6 | 1 | Conn_02x08_Top_Bottom | Dom LFO |
| Connector_IDC:IDC-Header_2x08_P2.54mm_Vertical | J11 | 1 | Conn_02x08_Odd_Even | Dom VCA |
| Package_TO_SOT_THT:TO-92_Inline | Q2,Q4 | 2 | BC557 | DS-20 VCF |
| Package_TO_SOT_THT:TO-92_Inline | Q1 | 1 | BC548 | DOMSynth |
| Package_TO_SOT_THT:TO-92_Inline | Q3 | 1 | BC558 | DOMSynth |
| Package_TO_SOT_THT:TO-92_Inline | Q1,Q2,Q3,Q4,Q5,Q6,Q7,Q8,Q9 | 9 | BC548 | Dom VCA |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R1,R2,R28,R29,R32,R36 | 6 | 10k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R19,R20,R23,R24,R37,R38 | 6 | 100k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R25,R35,R41 | 3 | 4.7k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R26,R27,R30,R31 | 4 | 220 | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R33 | 1 | 1k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R34 | 1 | 47k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R39 | 1 | 220k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R40 | 1 | 1.5k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R42 | 1 | 470k | DS-20 VCF |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R1,R2,R6,R8,R12,R14,R22 | 7 | 100k | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R3,R5,R7,R9 | 4 | 10k | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R4,R11 | 2 | 1M | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R10 | 1 | 1k5 | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R13,R17 | 2 | 68k | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R15 | 1 | 33k | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R16,R18 | 2 | 1k | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R21 | 1 | 14k | DOMSynth |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R1,R19 | 2 | 150k | Dom LFO |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R2,R20 | 2 | 2.2k | Dom LFO |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R3,R7,R8,R23,R27,R28 | 6 | 1k | Dom LFO |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R4,R24 | 2 | 100k | Dom LFO |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R5,R25 | 2 | 4.7k | Dom LFO |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R6,R26 | 2 | 10k | Dom LFO |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R1,R2,R14,R15,R17,R18,R19,R20,R34,R35,R47,R48,R66,R67,R68,R70 | 16 | 100k | Dom VCA |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R3,R21,R27 | 3 | 200k | Dom VCA |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R4,R5,R9,R22,R23,R24,R25,R37,R38,R42,R71 | 11 | 10k | Dom VCA |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R6,R13,R16,R28,R29,R36,R39,R46,R49,R50,R51,R52 | 12 | 1k | Dom VCA |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R7,R10,R11,R12,R30,R31,R32,R33,R40,R43,R44,R45 | 12 | 15k | Dom VCA |
| Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R8,R26,R41 | 3 | 33k | Dom VCA |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV7,RV8,RV9,RV10 | 4 | 100k | DS-20 VCF |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV11 | 1 | 10k | DS-20 VCF |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV1 | 1 | 250k | DOMSynth |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV2,RV3,RV5 | 3 | 100k | DOMSynth |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV4 | 1 | 1M | DOMSynth |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV1,RV7 | 2 | 100k | Dom LFO |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV2,RV8 | 2 | 500k | Dom LFO |
| Potentiometer_THT:Potentiometer_Alpha_RD901F-40-00D_Single_Vertical | RV1,RV4,RV7,RV13 | 4 | 100k | Dom VCA |
| Potentiometer_THT:Potentiometer_Bourns_3296P_Horizontal | RV2,RV5,RV8 | 3 | 10k | Dom VCA |
| Potentiometer_THT:Potentiometer_Bourns_3296P_Horizontal | RV3,RV6,RV9 | 3 | 5k | Dom VCA |
| MusicThingModular:BOURNS_3362P_TRIMMER | RV12 | 1 | 1k | DS-20 VCF |
| MusicThingModular:BOURNS_3362P_TRIMMER | RV6 | 1 | 1k | DOMSynth |
| Package_DIP:DIP-8_W7.62mm | U1,U2,U3,U4,U5,U6 | 6 | TL072 | DS-20 VCF |
| Package_TO_SOT_SMD:SOT-23-5 | U7,U8 | 2 | LM13700 | DS-20 VCF |
| Package_DIP:DIP-14_W7.62mm | U1,U4,U5,U6 | 4 | TL074 | DOMSynth |
| Package_DIP:DIP-14_W7.62mm | U3 | 1 | 74HC14 | DOMSynth |
| Package_DIP:DIP-14_W7.62mm | U1,U2,U3,U4 | 4 | TL074 | Dom LFO |
| Package_DIP:DIP-8_W7.62mm | U1,U2,U3,U5 | 4 | TL072 | Dom VCA |
