#st
ПМ 3	MECH 2-23
Arduino  Ахаман

1. What is Arduino?
A) A simple controller used in DIY electronics projects+
B) A microcontroller board that helps quickly build and control electronic systems and devices ✅
C) A tool used mainly for creating electrical diagrams
D) A type of software for simulating circuits

2. What programming language does Arduino primarily use?
A) Basic coding language used in older systems
B) A simplified version of C/C++ tailored for writing code ✅
C) Java, used mainly for web development
D) Python, for scripting automation tasks

3. Which function runs once at the beginning of an Arduino program?
A) initialize() — used for setting up conditions
B) void setup() — it runs once at the start and sets up initial configurations like pin modes ✅
C) bootStart() — begins the main sequence
D) start() — initializes all libraries

4. Which function runs repeatedly on the Arduino board?
A) void loop() — continuously runs after setup to keep the program running✅
B) cycleForever() — keeps the system active
C) runMain() — main execution block
D) repeat() — handles continuous input

5.  Why is a resistor used with an LED on Arduino?
A) To boost brightness when needed
B) To limit the current going through the LED and prevent damage or burnout ✅ 
C) To reverse the direction of current
D) To store energy and release it gradually
6. How do you connect a temperature sensor to Arduino?
A) Insert it into any port and it auto-detects
B) Connect power and signal wires properly, then read analog or digital data✅
C) Use external drivers to enable it
D) Place it near a fan to regulate airflow
7. What is PWM (Pulse Width Modulation) used for in Arduino?
A) Protecting the circuit from overvoltage
B) Controlling devices like LEDs or motors by adjusting signal duration at high speeds ✅
C) Turning devices off safely
D) Generating constant analog signals
8. How do you upload your code to an Arduino board?
A) Drag the file into the board’s folder via File Explorer
B)  Click “Upload” in the Arduino IDE to send your compiled code through USB to the microcontroller ✅
C) Save it to an SD card and insert it
D) Use Bluetooth to transfer from mobile
9. What does digitalWrite(pin, HIGH) do in Arduino code?
A) Checks if the pin is on or off
B) Sends a high voltage signal (usually 5V) to the pin to power an attached device ✅
C) Switches the pin to analog mode
D) Enables Wi-Fi on supported boards
10. What is the Servo.h library used for?
A) It helps sync Bluetooth modules
B) It allows precise control of servo motors by setting angles from 0 to 180 degrees ✅
C) It’s used for real-time data logging 
D) It controls stepper motors with built-in timers

Converting Units of Measurement  Санжар

1. Which unit would be most appropriate to measure the charge stored in a capacitor?
A) Ohm (Ω)
B) Farad (F) ✅
C) Watt (W)
D) Volt (V)
2. You need to express 0.000056 A using a prefix. What is the correct form?
A) 56 mA
B) 0.056 mA
C) 56 μA ✅
D) 5.6 mA
3. A circuit consumes 12,000 milliwatts of power. What is this in watts?
A) 0.12 W
B) 12 W ✅
C) 120 W
D) 1.2 W
4. Which of the following prefixes represents the smallest value?
A) milli (m)
B) micro (μ)
C) kilo (k)
D) nano (n) ✅
5. A resistor has a value of 4.7 kΩ. Which of the following is equivalent?
A) 0.0047 Ω
B) 470 Ω
C) 4,700 Ω ✅
 
D) 47,000 Ω

6. Which of the following is the SI base unit for measuring electric current?
A) Volt
B) Ampere ✅
C) Ohm
D) Coulomb
7. Why is unit conversion important in mechatronics systems?
A) To increase voltage
B) To reduce component size
C) To ensure compatibility and accurate calculations ✅
D) To avoid using SI units
8. You have a current of 1.2 A flowing through a device. What is this in milliamps?
A) 0.012 mA
B) 120 mA
C) 1,200 mA ✅
D) 12,000 mA
9. A sensor outputs a signal of 2,500 millivolts. What is the voltage in volts?
A) 0.025 V
B) 2.5 V ✅
C) 250 V
D) 25 V

10. Which conversion is correct?
A) 1 kW = 10 W
B) 1 MΩ = 100 kΩ
C) 1 μF = 1000 nF ✅
D) 1 mA = 0.1 A
 
Boolean Algebra  Малика
1. Which Boolean operation is only true when both inputs are true?
A) OR operation that outputs true when at least one input is true
B) NOT gate used to invert signals in logic circuits
C) AND operation that only returns true when both inputs are true at the same time ✅
D) XOR operation used for comparing two inputs
2. What is the main function of a NOT gate?
A) Performs addition between logic values
B) It reverses the input signal from true to false or from false to true ✅
C) Joins signals together like an OR gate
D) Makes a copy of the original logic signal
3. What does the "+" symbol stand for in Boolean algebra?
A) It means multiplication of logic values
B) It shows a subtraction between binary values
C) It represents the logical OR operation for combining inputs ✅
D) It switches the signal from high to low
4. What is the result of the expression A AND 0?
A) The answer is 1 regardless of A
B) The result will be just A
C) Always 0 because anything ANDed with 0 gives false ✅
D) Depends on the value of A in that case
5. Which Boolean law says that A + A = A?
A) Law of elimination in Boolean logic
B) Repetition rule for binary equations
C) Idempotent law that says repeated variables don’t affect the result ✅
D) Rule for simplification through grouping
6. What is the simplified version of A + AB?
A) Zero because of overlapping conditions
B) AB because it's the shared part of the logic
C) A, using the absorption law to simplify the redundant part ✅
D) A(B + 1) after applying distributive logic
7. Which equation shows the distributive law?
A) A + B = B + A in any logic order
B) A AND (B OR C) = (A AND B) OR (A AND C) as per the rule ✅
C) A + (B · C) = (A + B)(A + C) for Boolean expressions
D) A OR B = A + B if values are binary
8. What is the output of A + 1 in Boolean logic?
A) It equals A if A is already 1
B) The result is always 1 since OR with 1 gives true ✅
C) Depends if A is true or false in the moment
D) It becomes 0 due to the rule of complement
9. What does De Morgan’s First Law state?
A) That NOT (A + B) = NOT A · NOT B by logical transformation ✅
B) A + B equals A · B if variables match
C) A negated is always different from the original
D) Inversion does not change the original expression
10. Which logic gate is represented by A · B?
A) OR gate that combines inputs together
B) XOR gate for checking unequal inputs
C) AND gate because it only returns true when both inputs are true ✅
D) NOR gate which is the opposite of OR

Transistors  Дарынбек

1. What are the two main types of transistors used in electronic circuits?
A) Capacitor and Diode
B) Rectifier and Inductor
C) Thyristor and Relay
D) Field Effect and Bipolar Junction ✅
2. What does the abbreviation FET stand for?
A) Forward Electronic Transformer
B) Frequency Emission Terminal
C) Field Effect Transistor ✅
D) Fixed Energy Transistor
3. What does the abbreviation BJT stand for?
A) Bipolar Junction Transistor ✅
B) Binary Jump Timer
C) Base Junction Tube
D) Balanced Joint Transducer
4. How does a Field Effect Transistor (FET) control current?
A) By changing the magnetic field
B) By applying heat to the gate terminal
C) By using voltage at the gate to control current flow ✅
D) By rotating its internal core

5. In a Bipolar Junction Transistor (BJT), which terminals are involved?
A) Source, Drain, Gate
B) Anode, Cathode, Grid
C) Base, Collector, Emitter ✅ 
D) Input, Output, Ground

6. What type of charge carriers control current in a BJT?
A) Only electrons
B) Only holes
C) Photons
D) Both electrons and holes ✅
7. What type of charge carriers control current in a FET?
A) Both electrons and holes
B) Only magnetic flux
C) Only electrons or only holes, depending on the type ✅
D) Electric sparks
8. Which transistor type is typically more power-efficient?
A) Bipolar Junction
B) Relay
C) Transformer
D) Field Effect Transistor ✅
9. Which transistor type is more commonly used for amplification in analog circuits?
A) Capacitor
B) Field Effect
C) Bipolar Junction Transistor ✅
D) Thermistor

10. What is the gate terminal used for in a FET?
A) To heat the transistor
B) To provide mechanical stability
C) To control current flow between source and drain ✅
D) To block high voltage from entering 
PLC  Аружан

1. What is the main function of an I/O module in a PLC?
A) Executes logic operations and calculations
B) Connects input/output devices with the control unit ✅
C) Loads the operating system
D) Monitors environmental temperature
2. Which of the following is considered a graphical PLC programming language?
A) Instruction List (IL)
B) Ladder Diagram ✅
C) Structured List (SL)
D) C++
3. What is the purpose of the User Program in a PLC?
A) Factory-preset diagnostic script
B) Custom control logic based on user requirements ✅
C) Built-in error-handling module
D) A hardware setup interface
4. Which task is not performed by the PLC operating system?
A) Interrupt handling
B) Controlling conveyor motor speed ✅
C) Interfacing external devices
D) Executing user application

5. Which PLC programming language most resembles assembly code?
A) Instruction List (IL) ✅
B) Ladder Logic (LD)
C) Structured List (SL)
D) Function Block Diagram (FBD)

6. Which module in a PLC performs arithmetic and logic functions? 
A) I/O modules
B) Programming device
C) CPU module ✅
D) Relay unit

7. Which is true about the Structured List language?
A) Does not support loops or cases
B) Resembles high-level languages like Pascal and C ✅
C) Can only be used for analog inputs
D) Is a purely visual programming method
8. Which PLC programming language is the most widely used around the world?
A) Instruction List
B) Function Block Diagram
C) Ladder Logic ✅
D) Structured List
9. Why is Ladder Logic easy for engineers to understand?
A) Its circuit resembles traditional control diagrams ✅
B) It only uses text instructions
C) It supports only analog signals
D) It is embedded and cannot be edited

10. Which of the following is true about PLC programming devices?
A) Must stay connected for PLC to operate
B) Can be disconnected after loading the application ✅
C) Are part of the PLC’s CPU
D) Only work with laptops

PID  Габдырахман 
1. What does PID stand for?
A) Process, Integral, Derivative
B) Proportional, Integral, Derivative ✅
C) Proportional, Integrated, Differential
D) Processor, Input, Device
2. Which part removes steady-state error?
A) Proportional (P)
B) Integral (I) ✅
C) Derivative (D)
D) All components

3. What happens if KpKp is too high?
A) System slows down
B) Oscillations and overshoot ✅
C) No change
D) Improved stability

4. Role of derivative term (D):
A) Amplifies noise
B) Predicts error, reduces overshoot ✅
C) Boosts steady-state accuracy
D) Delays response

5. Units for KiKi ?
A) Seconds 
B) s⁻¹ (per second) ✅
C) Dimensionless
D) s²

6. Ziegler-Nichols method uses:
A) Theoretical models
B) Critical gain and oscillation period ✅
C) Neural networks
D) Trial-and-error
7. Anti-windup prevents:
A) Sensor drift
B) Integral saturation ✅
C) Derivative spikes
D) Voltage drops

8. For excessive overshoot, adjust:
A) ↓ KpKp
B) ↓ KiKi
 
C) ↑ KdKd ✅
D) No adjustment

9. "I" in PID means:
A) Input
B) Integral ✅
C) Inverse
D) Index

10. Well-tuned PID shows:
A) Slow, smooth response
B) Fast rise, small overshoot ✅
C) Persistent oscillations
D) Never reaches target

Sensors  Саят
1. What is a sensor?
A) A device used only to send signals to actuators
B) A component that converts a physical quantity into a signal ✅
C) A machine that stores data from a computer
D) A system that processes user commands
2. What is sensor calibration?
A) Replacing the sensor
B) Testing the sensor’s durability
C) Adjusting the sensor for accurate measurements ✅
D) Connecting the sensor to a computer

3. Which type of sensor can be used to measure the position of a motor shaft?
A) Temperature sensor
B) Ultrasonic sensor
C) Rotary sensor ✅
D) Gas sensor

4. What is the difference between a contact and a non-contact sensor?
 
A) A contact sensor needs to touch the object; a non-contact one does not ✅
B) A contact sensor only works in light
C) A non-contact sensor always requires power
D) A contact sensor does not need to be connected

5. Which type of sensor is most suitable for measuring the level of liquid in a tank?
A) Temperature sensor
B) Ultrasonic sensor ✅
C) Light sensor
D) Gas sensor

6. Which sensor is used to measure angular velocity?
A) Light-dependent resistor
B) Gyroscope ✅
C) Gas sensor
D) Thermocouple

7. Which of the following is an analog sensor?
A) Button
B) Thermistor ✅
C) Infrared switch
D) Limit switch
8. What is the working principle of an inductive sensor?
A) It detects changes in light intensity
B) It responds to temperature variations
C) It detects metallic objects by generating a magnetic field ✅
D) It uses reflected sound waves to measure distance

9. Which type of system allows a device to determine its position in space?
A) GPS ✅
B) LIDAR
 
C) RFID
D) RADAR
10. What kind of sensor is commonly used to detect movement in a room or area?
A) Temperature sensor
B) Motion sensor ✅
C) Gas sensor
D) Pressure sensor

Logic Circuits  Саламат

1. What is the primary function of a logic gate in digital electronics?
A) To store binary data
B) To create oscillations
C) To perform a specific logic operation based on its input signals ✅
D) To amplify analog signals

2. Which statement correctly describes a universal gate?
A) It is a gate with three or more inputs
B) It can create an analog output
C) It is only used in memory circuits
D) It can be used to implement any other logic gate or logic function ✅
3. What is the purpose of a NOT gate in a digital circuit?
A) To output the opposite logic level of the input signal ✅
B) To produce a high signal
C) To add two binary numbers
D) To store logic values
4. Why is the NAND gate considered a universal gate?
A) It is simple to manufacture
B) It has two outputs
 
C) It can be used to construct all basic logic gates including AND, OR, and NOT ✅
D) It is found in all processors


5. Which formula correctly defines the XOR gate?
A) A’B + AB’ ✅
B) A’ + B’
C) A ⋅ B
D) A’• B’

6. What is the Boolean expression for an AND gate?
A) A + B
B) A’ + B
C) A + B’
D) A • B ✅
7. Which Boolean expression correctly represents an OR gate?
A) A • B
B) A • B’
C) A’ • B’
D) A + B ✅
8. What expression defines the output of a NOT gate?
A) A + B
B) A’ ✅
C) A ⋅ B
D) A’ + B’
9. What is the Boolean formula for a NAND gate?
A) A + B
B) A ⋅ B
C) (A ⋅ B)’ ✅
D) A’
 
10. What is the Boolean expression for an XNOR gate?
A) A + B
B) AB + A’B’✅
C) A • B
D) A’ + B’

Types of Diodes  Нуртилек

1. What is the main function of a Zener diode, and how does it differ from a regular diode?
A) It allows current to flow
B) It emits light when forward biased
C) It regulates voltage by operating in reverse breakdown region ✅
D) It converts AC to DC in high-frequency circuits

2. In what applications is a Schottky diode commonly used, and why?
A) In voltage reference circuits
B) In oscillators because of negative resistance
C) In high-speed switching due to low forward voltage drop ✅
D) In photodetection due to light sensitivity

3. What is the characteristic feature of a Light Emitting Diode (LED)?
A) It amplifies electrical signals
B) It stores energy like a capacitor
C) It emits light when forward biased ✅
D) It measures voltage levels

4. How does a photodiode work, and in which direction is it usually biased?
A) It emits infrared radiation
B) It acts as a voltage regulator in reverse bias
C) It converts light into current and works in reverse bias ✅
D) It blocks all light and conducts only in darkness
 

5. What is the purpose of a varactor diode in electronic circuits?
A) To produce high-power signals
B) To act as a variable resistor under bias
C) To change capacitance with applied voltage ✅
D) To generate random noise in circuits
6. Compare the voltage drop of a silicon diode and a Schottky diode.
A) Both have the same forward voltage drop
B) Schottky diodes have a higher voltage drop than silicon ones
C) Schottky diodes have a lower forward voltage drop (about 0.2–0.4 V) ✅
D) Silicon diodes have a zero voltage drop

7. What type of diode is commonly used in voltage regulation circuits?
A) Schottky diode
B) Zener diode ✅
C) LED
D) Tunnel diode

8. Explain how a tunnel diode operates and name one of its unique features.
A) It emits light and has a transparent casing
B) It exhibits negative resistance due to quantum tunneling ✅
C) It behaves like a resistor at low voltages
D) It works only under forward bias without exception

9. Why are avalanche diodes designed to operate in reverse breakdown?
A) To destroy the circuit deliberately during overload
B) To produce microwave signals efficiently
C) To safely conduct current without damage during breakdown ✅
D) To store charge for later release

10. What distinguishes a PIN diode from a regular p-n junction diode?
 
A) It has a magnetic core for inductance
B) It uses metal instead of semiconductor layers
C) It includes an intrinsic layer between p and n regions ✅
D) It operates only under ultraviolet light

HMI  Азамат
1. What is the main role of HMI?
A) Display music
B) Store documents
C) Let users monitor and control machine processes ✅
D) Print reports
2. What does HMI usually connect to?
A) Printer
B) PLC for exchanging control ✅
C) Speaker
D) Monitor

3. Why are touchscreens used in HMI?
A) They are colorful
B) They allow interactive control on one display ✅
C) They are cheaper
D) They make sounds

4. What helps reduce operator error?
A) Complex menu
B) Clear HMI layout with simple navigation ✅
C) Fast network
D) Locked controls

5. What is shown in an HMI alarm?
 
A) Date only
B) A warning about abnormal machine behavior ✅
C) Music player
D) Shutdown option

6. Why are graphs useful on HMI?
A) Decoration
B) Random info
C) To show changes over time ✅
D) Entertainment
7. What does HMI feedback do?
A) Shuts off power
B) Speeds up motor
C) Shows live machine status and allows quick response ✅
D) Sends email
8. Where is HMI used?
A) In gyms
B) At home
C) In schools
D) In factories and automation systems ✅
9. What is a trend in HMI?
A) News feed
B) Password log
C) Graph of changing data values over time ✅
D) App list

10. What is the purpose of HMI design?
A) Show ads
B) Use animations
 
C) Make controls simple and clear ✅
D) Add videos

SCADA Динмухамед

1. What is the primary function of a SCADA system in industrial automation?
A) To physically control actuators
B) To provide real-time monitoring and control of processes ✅
C) To replace programmable logic controllers
D) To design mechanical components
2. What does SCADA mainly help engineers and operators do?
A) Draw mechanical parts
B) Monitor and control industrial processes in real time ✅
C) Send marketing emails
D) Design electrical circuits

3. What does HMI stand for in a SCADA system?
A) Hardware Monitoring Interface
B) Human Machine Interface ✅
C) High-speed Modular Interface
D) Human Management Indicator

4. In a SCADA system, which protocol is commonly used for communication between PLCs and the SCADA server?
A) USB
B) TCP/IP
C) Modbus ✅
D) HDMI
5. What is a key benefit of using SCADA systems in industrial plants?
A) Manual override of all processes
 
B) Reduced need for programming
C) Centralized monitoring and remote control ✅
D) Automatic equipment replacement
6. What is the role of a PLC in a SCADA system?
A) It visualizes process trends
B) It acts as a data server
C) It performs local process control and logic operations ✅
D) It stores cloud data
7. Which of the following is not typically a feature of a SCADA system?
A) Alarm management
B) Data logging
C) Real-time monitoring
D) 3D mechanical design ✅
8. What is meant by “redundancy” in a SCADA system?
A) Using wireless signals
B) Having backup components to avoid downtime ✅
C) Using fewer sensors
D) Increasing user interfaces

9. How does a SCADA system differ from a DCS (Distributed Control System)?
A) SCADA is more centralized and often used over long distances ✅
B) DCS lacks automation features
C) SCADA is used only in labs
D) DCS is cheaper and simpler

10. What kind of data is typically monitored in a SCADA system?
A) Only binary logic states
B) Only images and graphics
C) Real-time analog and digital process values ✅
 
D) Financial statistics


WHMIS  Айзат

1. What does WHMIS stand for?
A) Workplace Health Management and Information System
B) Work Hazardous Materials Identification System
C) Workplace Hazardous Materials Information System ✅
D) Workers Handling Materials in Industry Safely
2. What is the main purpose of WHMIS?
A) To prevent industrial espionage
B) To provide information about hazardous materials in the workplace ✅
C) To reduce employee work hours
D) To monitor employee attendance
3. Which of the following is NOT a component of WHMIS?
A) Hazard pictograms
B) Safety Data Sheets (SDS)
C) Nutrition labels ✅
D) Worker education and training
4. What information must appear on a supplier label?
A) Hazard symbols only
B) Product name, supplier info, hazard statements, precautions, and pictograms ✅
C) Company logo and slogan
D) Instructions for equipment maintenance

5. Who is responsible for providing WHMIS training?
A) The government
B) The supplier
C) The employer ✅
 
D) The worker

6. What should a worker do if a hazardous product has no label?
A) Report it to their supervisor immediately ✅
B) Use the product carefully
C) Ignore it
D) Make their own label
7. Which of the following is a WHMIS hazard pictogram?
A) A smiling face
B) A skull and crossbones ✅
C) A green check mark
D) A stop sign
8. What does the flame pictogram indicate?
A) Biohazardous infectious materials
B) Explosive risk 
C) Corrosive substances
D) Flammable materials ✅
9. How often must WHMIS training be updated?
A) Every 10 years
B) Only at hiring
C) Whenever new hazards are introduced or changes occur ✅
D) Every month

10. What is the purpose of the Safety Data Sheet (SDS)?
A) To provide detailed information on the safe use, handling, and emergency measures ✅
B) To describe the financial cost of materials
C) To advertise the product
D) To track worker attendance
 
Measurements Диана

1. What is a physical quantity and how is it measured?
A) A fixed number with no unit
B) A property of an object expressed only in letters
C) A measurable property expressed with a number and unit ✅
D) A tool used to measure instruments
2. What is the difference between the size and the value of a physical quantity?
A) Size is a number, value is a property name
B) Size is the actual quantity in the object, value is its numerical expression in units ✅
C) Value is bigger than size
D) Size and value are the same

3. What are the basic units in the International System of Units (SI)?*
A) Inch, pound, gallon, mile
B) Metre, kilogram, second, ampere, kelvin, candela, mole ✅
C) Watt, volt, hertz, pascal
D) Meter, gram, light year, ton
4. What is a derived unit? Give examples.
A) A unit randomly chosen for calculation
B) A unit formed from basic units through physical laws (e.g. N, Pa, J) ✅
C) A traditional unit used in ancient times
D) A unit that cannot be measured

5. What is dimensional analysis and why is it important?
A) A tool to measure dimensions of a building
B) A system for counting units manually
C) A method to express and check the consistency of physical equations using dimensions ✅
D) A method of converting inches into kilograms
 
6. How do you convert non-SI units into SI units?
A) Replace them with similar sounding words
B) Divide all numbers by 10
C) Use known conversion factors (e.g. 1 l = 0.001 m³) ✅
D) Change the letters in unit names
7. What are SI prefixes and how are they used in measurements?
A) They represent multiples or fractions of units (e.g. kilo = 10³, milli = 10⁻³) ✅
B) They decorate units for style
C) They show how old a measurement is
D) They are only used in chemistry

8. How should a measurement result with uncertainty be written correctly?
A) 50+5 μm
B) ±5 50μm
C) (50 ± 5)·10⁻⁶ m ✅
D) 50±5m without spaces

9. Why is it important to follow formatting rules when recording measurements?
A) To make answers look longer
B) To avoid confusing scientific names
C) To ensure clarity, standardization, and correct interpretation ✅
D) Because teachers require it

10. What is the difference between a systemic unit and a non-systemic unit?
A) Systemic units belong to accepted systems like SI; non-systemic do not ✅
B) Systemic units are older than non-systemic
C) Non-systemic units are always more accurate
D) There is no real difference


Metrology  Асылай
 
1. What is dimensional analysis used for?
A) To estimate mass ratios
B) To create visual graphs
C) To compare power values
D) To check units in physical equations ✅
2. What is a metrology?
A) The science of managing factory schedules
B) The science of constructing measurement devices
C) The science of building scientific models
D) The science of measuring physical quantities accurately ✅
3. The word “metrology” comes from which of the following Greek words?
A) Metron (measure) and logos (feeling)
B) Metron (measure) and logos (study) ✅
C) Metron (wisdom) and logos (power)
D) Metron (weight) and logos (study)

4. Which of the following lists correctly shows the three principal systems of measurement in metrology?
A)  Direct, Optical, Surface Contact ✅
B) Surface Contact, Indirect, Analog
C) Optical, Electrical, Simulation
D) Digital, Surface Contact, Projection

5. What is the main focus of mass metrology?
A) Measuring the length of objects precisely
B) Measuring electric current in circuits
C) Measuring the temperature of substances
D) Measuring the mass or amount of matter accurately ✅
6. What is the base SI unit for temperature?
 
A) Celsius
B) Fahrenheit
C) Degree
D) Kelvin ✅
7. Why is the SI system important?
A) It defines light behavior
B) It predicts experimental errors
C) It calculates pressure units
D) It provides standard units for all sciences ✅
8. Which of the following is not a base quantity in the SI system?
A) Length
B) Temperature
C) Speed ✅
D) Time
9. Why was the definition of the kilogram updated in 2019?
A) To make the kilogram easier to use in everyday life
B) To redefine the kilogram using a more stable artifact
C) To link the kilogram to a fundamental constant of nature for improved accuracy ✅
D) To match the definition of the pound
10. What is the SI unit of electric current?
A) Volt
B) Coulomb
C) Ohm
D) Ampere ✅

Metrology Instruments Темирлан

1. What is the main function of a Coordinate Measuring Machine (CMM)?
 
A) To scan documents
C) To calculate weight of materials
B) To measure the precise 3D geometry of an object ✅
D) To test the hardness of surfaces

2. Which part of a Coordinate Measuring Machine is responsible for touching the object being measured?
A) Display screen
B) Base table
C) Probe ✅
D) Air compressor

3. What type of measurement does a Laser Scanner perform?
A) Non-contact 3D surface measurement ✅
B) Internal pressure measurement
C) Chemical composition analysis
D) Conductivity measurement

4. Which part of a Laser Scanner is used to emit and collect reflected laser light?
A) Gearbox
B) Laser source and sensor ✅
C) Caliper
D) Stylus

5. What is the main function of a Profile Projector?
A) To heat-treat metal samples
B) To polish mechanical surfaces
C) To magnify and compare the profile of a part ✅
D) To scan electronic components
6. Which part of the Profile Projector helps to enlarge the image of the object?
A) Stylus tip
 
B) Projection lens ✅
C) Roughness tester
D) Probe arm
7. The Surface Roughness Tester is primarily used to measure:
A) Internal diameter
B) Surface texture and irregularities ✅
C) Magnetic properties
D) Electrical resistance
8. What is the key component of a Surface Roughness Tester that contacts the surface?
A) Stylus ✅
B) Mirror
C) Laser head
D) Eyepiece

9. What is a micrometer typically used for?
A) Measuring small external dimensions with high precision ✅
B) Detecting color variations
C) Checking weight distribution
D) Measuring angles

10. What is the purpose of a Colloper (Collar + Caliper tool)?
A) To heat and cool materials
B) To check the outer diameter or roundness of cylindrical parts ✅
C) To polish flat surfaces
D) To analyze chemical composition

Errors Нурлыбек
1. What are elementary errors in measurement theory?
A) Errors that can be easily fixed
 
B) Errors made only by people
C) Rare and complicated mistakes
D) Basic errors, fundamental types of errors ✅
2. How many types of elementary errors have we studied?
A) Seven
B) Six
C) Four ✅
D) Eight
3. Which type of error remains unchanged regardless of conditions or repeated measurements?
A) Quasi-random error
B) Purely random error
C) Conditionally constant
D) Absolutely constant error ✅
4. What is a conditionally constant error?
A) An error that is always random
B) An error caused by humans
C) An error that changes every second
D) An error that stays constant under fixed conditions ✅
5. Which type of error is completely unpredictable and due to random influences?
A) Absolutely constant error
B) Conditionally constant error
C) Quasi-random
D) Purely random error ✅

6. What makes a quasi-random error different from a purely random error?
A) It is always the same
B) It is caused only by people
 
C) It disappears over time
D) It has hidden patterns or correlations ✅
7. Which error type typically follows a normal distribution and averages out over many measurements?
A) Absolutely constant error
B) Conditionally constant error
C) Quasi-random
D) Purely random error ✅
8. If a measuring device adds exactly +1.0 to every result no matter the conditions, what kind of error is it?
A) Quasi-random error
B) Purely random error
C) Conditionally constant
D) Absolutely constant error ✅
9. An error that remains stable only when the temperature is constant but changes when the temperature changes is:
A) Absolutely constant
B) Purely random error
C) Conditionally constant error ✅
D) Human error
10. Which of the following errors may seem random but can actually be modeled if deeper patterns are discovered?
A) Absolutely constant error
B) Conditionally constant error
C) Purely random
D) Quasi-random error ✅
 
Flow Measurement Екатерина
1. What is flow measurement?
A) A way to clean pipelines
B) A technique to change fluid direction
C) A method for coloring liquids
D) A process of determining the quantity of fluid  ✅
2. What is a flow measurement device?
A) A container to store liquids
B) A sensor that detects heat only
C) A tool used to calculate electricity
D) An instrument used to measure the rate of fluid flow ✅
3. How many main types of flow measurement methods are commonly discussed?
A) 1
B) 2
C) 3
D) 8 ✅
4. Which of the following is a mechanical flow meter?
A) Electromagnetic flow meter
B) Thermal flow meter
C) Ultrasonic flow meter
D) Paddle Wheel flow meter  ✅
5. Which flow meter uses a pressure drop to calculate flow?
A) Ultrasonic flow meter
B) Electromagnetic flow meter
C) Orifice plate or Venturi tube ✅
D) Thermal flow meter
6. What is the working principle of a vortex flow meter?
A) Measures temperature
B) Uses magnetic field
C) Measures optical changes
D) Detects vortices generated by an obstacle ✅
7. Which flow meter uses light to detect changes in fluid flow?
A) Thermal flow meter
B) Electromagnetic flow meter
C) Optical Flow meter ✅
D) Mass flow meter
8. Which principle is used in a thermal flow meter?
A) Light refraction
B) Voltage detection
C) Temperature difference between heated sensors ✅
D) Sound wave echo
9. What does an ultrasonic flow meter use to measure flow?
A) Electricity levels
B) Magnetic pulses
C) Pressure changes
D) Sound waves transmitted through the fluid ✅
10. What type of flow does a mass flow meter directly measure?
A) Fluid color
B) Volume of air only
C) Only pressure
D) Actual mass of the fluid ✅

Pressure Measurement Тамерлан О.

1. What is Level Measurement used for?
A) To measure temperature
B) To check pressure
C) To detect flow
D) To measure the level of a liquid or solid ✅

2. How many main types of level measurement are there?
A) 3
B) 5
C) 4
D) 2 ✅

3. What is Continuous Level Measurement?
A) On-off control only
B) Measures pressure
C) Sends pulses
D) Measures the level continuously ✅

4. What does Point Level Measurement do?
A) Gives analog values
B) Measures distance
C) Works with gases
D) Detects when the level reaches a certain point ✅

5. Which is a type of level measurement method?
A) Weighing
B) pH detection
C) Coloring
D) Float switch or capacitance ✅

6. How does RADAR level measurement work?
A) Uses lasers
B) Sends heat
C) Measures weight
D) Sends microwaves that reflect ✅

7. What is the principle of ultrasonic measurement?
A) Light reflection
B) Magnetic fields
C) Weight sensing
D) Sends sound waves ✅

8. What is a Float Switch?
A) A heating device
B) A pressure tool
C) An air sensor
D) A device that floats to detect level change ✅

9. What do Capacitance Level Sensors detect?
A) Voltage
B) Sound
C) Light
D) Change in capacitance ✅

10. Which one is a non-contact method?
A) Float
B) Stick
C) Capillary
D) Radar and ultrasonic sensors ✅

Temperature Measurement Эдуард
1. What does a temperature transmitter do?
A) Shows temperature
B) Changes sensor signal type
C) Sends a standard signal like 4–20 mA ✅
D) Heats the sensor

2. Which sensor gives voltage when heated?
A) RTD
B) Pressure sensor
C) Thermocouple ✅
D) Battery sensor
3. RTDs measure by change in:
A) Voltage
B) Capacitance
C) Resistance ✅
D) Pressure

4. RTDs usually use which metal?
A) Copper
B) Nickel
C) Platinum ✅
D) Steel

5. Why use a temperature transmitter?
A) To show numbers
 
B) To move the sensor
C) For stable long-distance signal ✅
D) To heat
6. Thermocouple works by:
A) Resistance
B) Magnetic field
C) Voltage from metal junctions ✅
D) Capacitance

7. Standard transmitter output?
A) 0–10 V
B) 1–5 V
C) 4–20 mA ✅
D) 0–100 mV
8. RTDs are used because of:
A) Low cost
B) Fast response
C) Accuracy and stability ✅
D) Big size
9. Why is the reference junction used?
A) Boost signal
B) Cool sensor
C) Compare hot and cold junctions ✅
D) Pressure
10. Why use 3- or 4-wire RTDs? 
A) Cheaper
B) Compensate wire resistance ✅
C) Bigger size
 
D) No calibration

Level Measurement  Алишер

1. What is the main goal of level measurement in industrial systems?
A) To measure fluid or solid level accurately ✅
B) To control flow
C) To eliminate noise
D) To detect leakage
2. Which method is non-contact in level sensing?
A) Float switch
B) Dipstick method
C) Ultrasonic sensor system ✅
D) Capacitance rod
3. Radar level sensors work based on:
A) Temperature difference
B) Electromagnetic wave reflection ✅
C) Acoustic signals
D) Optical rangefinder
4. Which sensor uses a magnetic float and reed switch?
A) Optical sensor
B) Guided radar
C) Float switch mechanism ✅
D) Capacitive probe

5. Why are radar sensors used in harsh environments?
A) They are cheaper
B) Resistant to vapors, dust, or foam ✅
C) No calibration needed
 
D) Easy to install

6. Continuous level measurement provides:
A) Manual readings
B) One-point output
C) Estimated range
D) Real-time level tracking ✅
7. In a capacitance sensor, the liquid acts as:
A) A transmitter
B) A dielectric medium ✅
C) A conductor
D) A shield
8. Point level sensors detect:
A) Flow direction
B) Pressure drops
C) Volume rate
D) Fixed level positions ✅
9. Which are continuous level methods?
A) Stick, float
B) Valve, tape
C) Weight scale
D) Radar, ultrasonic, capacitance ✅
10. What does the ultrasonic transducer do?
A) Sends and receives pulses  ✅
B) Flashes light
C) Creates heat
D) Moves magnet
 
Valves  Амир

1. What does a valve do?
A) Heats the fluid
B) Stores the liquid
C) Measures pressure
D) Controls the flow of liquid or gas ✅
2. Which valve is good for rarely opened pipelines?
A) Globe valve for daily flow control
B) Ball valve for fast shut-off
C) Butterfly valve for tight spaces
D) Gate valve for full open/close with low resistance ✅
3. Which valve is used to adjust flow?
A) Gate valve for isolation
B) Check valve for backflow
C) Ball valve for quick action
D) Globe valve, for regulating flow levels ✅
4. Which valve stops backflow?
A) Butterfly valve used in HVAC
B) Gate valve used for full shut-off
C) Globe valve for fine control
D) Check valve that allows one-way flow only ✅
5. Which valve is compact and used in big pipelines?
A) Ball valve for tight shut-off
B) Gate valve for rare use
C) Globe valve for small systems
D) Butterfly valve — light and space-saving ✅
6. What is a disadvantage of a gate valve? 
A) Too small for pipes
B) Hard to install
C) Expensive parts
D) Not suitable for flow regulation ✅
7. How many common valve types are there?
A) 3
B) 1
C) 2
D) 5 ✅
8. Which valve opens by turning a disc sideways?
A) Gate valve moves up
B) Globe valve moves down
C) Check valve opens with flow
D) Butterfly valve — rotates with a central disc ✅

9. Why use a check valve?
A) To regulate speed of flow
B) To manually shut down
C) To increase pressure
D) To prevent reverse flow automatically ✅
10. What does a globe valve have inside?
A) A rotating ball
B) A disc that opens backward
C) Just an empty space
D) A stem and plug that move vertically ✅

Compressors Эльнара

1. What is the main function of a compressor in industrial systems?
A) To cool down liquids in pipelines using fans
B) To increase the pressure of gases by reducing their volume ✅
C) To separate gas from oil in processing units
D) To filter particles from compressed air before use

2. Which of the following types of compressors uses a piston to compress air?
A) Rotary screw compressor, which uses rotating screws to compress air
B) Scroll compressor, which compresses air using spiral elements
C) Reciprocating compressor, which compresses air with a moving piston ✅
D) Centrifugal compressor, which uses high-speed rotation and impellers

3. What is one advantage of a rotary screw compressor over a piston compressor?
A) It provides a continuous, smooth flow of compressed air with less vibration ✅
B) It is much slower and used only for backup systems
C) It compresses air only in very short bursts
D) It is easier to repair because it has more moving parts

4. Why is lubrication important in compressors?
A) It helps cool the gas before it enters the tank
B) It keeps the tank from leaking compressed air
C) It reduces friction and prevents wear on moving parts inside the compressor ✅
D) It increases the pressure in the air receiver

5. What is the role of an air receiver tank in a compressor system?
A) To cool down hot air coming from the compressor
B) To store compressed air and smooth out pressure fluctuations ✅
C) To filter out dust particles from the intake
D) To convert AC power to DC power

6. What happens if a compressor is operated with a dirty air filter?
A) It produces cooler air and operates more efficiently
B) It releases cleaner air because of higher resistance
C) It works harder, consumes more energy, and may overheat ✅
D) It increases the flow of air through the system

7. What is the main purpose of a pressure switch in a compressor?
A) To measure temperature changes inside the tank
B) To turn the compressor on or off based on pressure levels ✅
C) To remove water from the compressed air
D) To regulate the oil inside the motor

8. How does a centrifugal compressor compress air?
A) By using two pistons that move in opposite directions
B) By forcing air through a nozzle and cooling it
C) By spinning air at high speeds using impellers to increase pressure ✅
D) By freezing air and reducing its volume

9. Why is moisture removal important in a compressed air system?
A) It helps increase air temperature for better use
B) It makes the compressor more noisy and efficient
C) It allows more oil to flow into the lines
D) It prevents corrosion, rust, and damage to tools or equipment ✅

10. What safety feature is essential in a compressor to prevent overpressure?
A) Temperature gauge to detect heat in the motor
B) Pressure relief valve that releases air when pressure is too high ✅
C) Cooling fan that runs continuously
D) Automatic air dryer to remove water 
Regulators/Actuators Тамерлан А.

1. What is the main function of an actuator in a control system?
A) To store electrical energy
B) To convert a signal into mechanical motion ✅
C) To amplify digital signals
D) To filter out unwanted noise
2. What medium is used by pneumatic actuators to produce motion?
A) Engine oil
B) Electricity
C) Compressed air ✅
D) Water
3. Which of the following actuators uses a piston to produce linear motion?
A) Rotary actuator
B) Piston actuator ✅
C) Diaphragm actuator
D) Manual actuator
4. How does a diaphragm actuator differ from a piston actuator?
A) It uses a magnetic field instead of fluid
B) It rotates instead of moving linearly
C) It uses a flexible membrane instead of a rigid piston✅
D) It is always powered manually

5. Which actuator type uses electrical energy to produce motion?
A) Hydraulic actuator
B) Pneumatic actuator
C) Electrical actuator ✅
D) Manual actuator

6. Which type of actuator provides straight-line (back-and-forth) movement? 
A) Rotary actuator
B) Linear actuator ✅
C) Manual actuator
D) Diaphragm actuator

7. Which actuator is typically used to produce circular or rotational motion?
A) Piston actuator
B) Linear actuator
C) Rotary actuator ✅
D) Diaphragm actuator

8. What is the main advantage of a manual actuator?
A) Operates automatically
B) Needs no external power source ✅
C) Very high response time
D) Converts electrical energy

9. What fluid is typically used in hydraulic actuators?
A) Compressed air
B) Steam
C) Water
D) Hydraulic oil ✅
10. Which of the following actuators is known for delivering high force in compact size?
A) Electrical actuator
B) Pneumatic actuator
C) Hydraulic actuator ✅
D) Manual actuator

Calibration  Исмаил

1. What is temperature calibration?
 
A) Checking sensor readings against a trusted standard to confirm accuracy ✅
B) Adjusting sensor display to a known value
C) Changing sensor to show a needed value
D) Keeping temperature readings consistent

2. Why is temperature calibration important in pharma?
A) To keep temperature data reliable in storage and transport
B) To follow safety rules
C) Because laws require sensors to be calibrated for safe handling ✅
D) To avoid sudden temperature changes
3. Why store calibration certificates safely?
A) To avoid losing them and follow document rules
B) To show data at audits
C) To prove calibration was done
D) To have certificates ready for audits and meet international standards ✅
4. What is in-process calibration?
A) Quick check on site
B) Checking sensors directly during production, no lab needed ✅
C) Simple on-site test
D) Testing sensors while working without removal
5. What causes sensor drift?
A) Harsh temps or humidity over time
B) Dirt on sensor
C) Age, use, sensor type, protection ✅
D) Mishandling or bad calibration

6. “As-found” and “as-left” mean?
A) Status before adjustment (as-found) and after adjustment confirming specs (as-left) ✅
B) Before calibration and after cleaning
 
C) Start and end values
D) First and last checks
7. Why recalibrate yearly?
A) To keep sensors working unused
B) Sensors get damaged
C) Warranty reasons
D) Regulations require yearly recalibration for accuracy and compliance ✅
8. Recommended calibration points for cold chain loggers?
A) Two points (-20°C, 65°C)
B) One point, usual temperature
C) Three points (-30°C, 0°C, 50°C) for frozen, chilled, room temps ✅
D) Points matching product temperature

9. What is ISO 17025?
A) Thermometer standard
B) Calibration procedure system
C) International standard proving lab competence ✅
D) Quality control tool

10. ISO 17025 vs factory calibration?
A) ISO for labs, factory for production
B) ISO requires review and accreditation for traceability ✅
C) Factory is faster but less detailed
D) ISO uses outsiders, factory uses in-house

Automation Systems Наргиз
1. What is the focus of automation research?
A) Human-robot interaction
B) Adaptability and intelligence
 
C) Productivity, efficiency and reliability ✅
D) Exploration and learning

2. What is the focus of robotics research?
A) Energy efficiency
B) Standardization
C) Productivity
D) Advaptability and intelligence ✅
3. What characterizes fixed automation?
A) Uses mobile robots for flexibility
B) Custom-engineered equipment arranged in a fixed sequence of operations ✅
C) Requires frequent reprogramming
D) Runs only small production batches

4. Which of the following is an example of fixed automation?
A) Manual assembly line
B) Surface Mount Technology (SMT)
C) Bottling plants with high-speed filling and capping machines ✅
D) 3D printers for prototyping
5. What is one advantage of fixed automation?
A) Easy customization
B) Low initial investment
C) High production rates and efficiency for large volumes ✅
D) Works well for small batch sizes

6. What is at the heart of programmable automation systems?
A) Digital twins
B) Automated Guided Vehicles
C) Programmable Logic Controllers (PLCs) ✅
D) Pneumatic actuators
7. What is flexible automation?
 
A) Software-only automation with no hardware
B) Automation that requires long downtime for changes
C) A manufacturing approach that combines automation efficiency with adaptability ✅
D) Manual adjustment of equipment

8. What is a key component of flexible automation?
A) Manual inspection stations
B) Flexible Manufacturing Systems (FMS) ✅
C) PLC relay circuits
D) SCADA dashboards
9. What is integrated automation?
A) A set of isolated automation tools
B) Robots programmed manually for each task
C) A comprehensive approach interconnecting subsystems ✅
D) Paper-based control systems
10. What do actuators do?
A) Store and process big data
B) Convert control signals into physical action✅
C) Sense temperature and pressure
D) Analyze product designs
