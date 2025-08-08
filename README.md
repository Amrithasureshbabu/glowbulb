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
![Workflow](Add your workflow/architecture diagram here)
*Add caption explaining your workflow*

For Hardware:

# Schematic & Circuit
![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

# Build Photos
![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

### Project Demo
# Video]
https://github.com/Amrithasureshbabu/glowbulb/blob/main/Screen%20Recording%202025-08-09%20035648.mp4
# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- [Name 1]: [Specific contributions]
- [Name 2]: [Specific contributions]
- [Name 3]: [Specific contributions]

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)


