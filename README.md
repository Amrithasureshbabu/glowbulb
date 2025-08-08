<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


# [GLOW IN LIGHT BULB] 🎯


## Basic Details
### Team Name: [ZERO IMPACT]


### Team Members
- Team Lead: [ABHINAND T] - [JYOTHI ENGINEERING COLLEGE]
- Member 2: [AMRITHA SURESH BABU] - [JYOTHI ENGINEERING COLLEGE]
  

### Project Description
[A light bulb that glows when it detects light. Yes, it turns on when it’s already bright. Because why not?
]

### The Problem (that doesn't exist)
[Too many devices turn on in the dark. What about those lonely bulbs that crave daylight? We’re solving the tragic neglect of bulbs during sunny hours]

### The Solution (that nobody asked for)
[We built a system where a light bulb glows only when it senses ambient light. The brighter the environment, the brighter the bulb. It’s the ultimate attention-seeking appliance.
]

## Technical Details
### Technologies/Components Used
For Software:
- [HTML ,CSS]
- [Arduino IDE, GitHub]

For Hardware:
- Light-dependent resistor (LDR)
- Arduino Uno
- Breadboard
- Resistor
- Bulb

### Implementation
For Software:
int value=0;
void setup()
{
  Serial.begin(9600);
  pinMode(11, OUTPUT);
  pinMode(A0, INPUT);
}

void loop()
  
{
  
  value= analogRead(A0);
  
  if(value<10)
  {
    digitalWrite(11, LOW);
    Serial.println("Light OFF");
    Serial.println(value);
  }
  else
  {
     digitalWrite(11, HIGH);
    Serial.println("Light ON");
    Serial.println(value);
  }
}
# Installation
[commands]

# Run
[- Connect the circuit
- Upload code via Arduino IDE
- Place it in sunlight and watch it glow like it’s showing off


]

### Project Documentation
For Software:

# Screenshots (Add at least 3)


![Screenshot2](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20035341.png)
The image shows a light-sensitive circuit built using an Arduino Uno, a photoresistor (LDR), and a light bulb. Here's how each part contributes:
- Key Components
- Arduino Uno: Acts as the brain of the system, reading light levels and controlling the bulb.
- Photoresistor (LDR): Senses ambient light. Its resistance decreases as light increases.
- Resistors: Used to create a voltage divider with the LDR, allowing the Arduino to read varying light levels.
- Light Bulb: The star of the show—it glows when the LDR detects enough light.
- Breadboard & Jumper Wires: For easy prototyping and connections.
- USB Cable: Powers the Arduino and allows code upload.




# Diagrams
![Workflow](https://github.com/Amrithasureshbabu/glowbulb/blob/main/workflow.png)
Workflow Explanation
This flowchart illustrates the decision-making process for a light-reactive bulb system. The system begins by detecting ambient light and reading its intensity. It then compares the light level to a predefined threshold.
For Hardware:

# Schematic & Circuit
![Circuit](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20035341.png)
*Add caption explaining connections*
The image shows a light-sensitive circuit built using an Arduino Uno, a photoresistor (LDR), and a light bulb. Here's how each part contributes:
- Key Components
- Arduino Uno: Acts as the brain of the system, reading light levels and controlling the bulb.
- Photoresistor (LDR): Senses ambient light. Its resistance decreases as light increases.
- Resistors: Used to create a voltage divider with the LDR, allowing the Arduino to read varying light levels.
- Light Bulb: The star of the show—it glows when the LDR detects enough light.
- Breadboard & Jumper Wires: For easy prototyping and connections.
- USB Cable: Powers the Arduino and allows code upload.

![Schematic](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20041941.png)
- Voltage Divider for Light Sensing
- R3 and R2 form a voltage divider. The LDR (likely represented by R2) changes resistance based on light.
- The voltage at the junction of R3 and R2 is fed into A0, the analog input pin on the Arduino.
- Arduino Reads Light Level
- The Arduino continuously reads the analog voltage at A0.
- Based on the voltage, it determines the ambient light level.
- Bulb Activation via D9
- If the light level is above a certain threshold, the Arduino sends a HIGH signal to D9.
- D9 controls the inductor (L1), which could be a relay coil or directly driving a bulb.
- R1 limits current to protect the inductor and circuit.


# Build Photos
![Components](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20042955.png)
![Components](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20043025.png)
![Components](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20043043.png)
![Components](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20043112.png)
![Components](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20043141.png)
![Components](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20043216.png)




![Final](https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screenshot%202025-08-09%20035341.png)
*Explain the final build*
- Arduino Uno: The microcontroller that reads light levels and controls the bulb.
- LDR (Light Dependent Resistor): Senses the brightness of the environment.
- Relay Module: Acts as a switch to control the high-voltage bulb using Arduino’s low-voltage signal.
- LED Bulb (or any small light bulb): The output device that glows when triggered.
- Resistors: Used in the voltage divider circuit with the LDR.
- Breadboard & Jumper Wires: For prototyping and easy connections.
- Power Supply: USB for Arduino and external power for the bulb.


### Project Demo
# Video]
https://drive.google.com/file/d/1FC-5FpiQMrvffZpXH5_Hhz6xpGf5Zgyv/view?usp=drivesdk

# Additional Demos
additional link
[project link]:[https://amrithasureshbabu.github.io/glowbulb/]

## Team Contributions
- [Abhinand]: [- Circuit design, Arduino coding, concept ideation,Hardware setup]
- [Amritha]: [testing, documentation,GitHub commits, hosting, video editing]
   


---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)


