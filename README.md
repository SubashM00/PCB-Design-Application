# PCB-Design-Application
# Aim


# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory
The circuit you sent me is a simple sound reactive LED circuit. It uses the speaker to pick up ambient sounds and convert them into electrical signals which are then amplified by the transistors, which in turn light up the LEDs. 1.The speaker works as a microphone in this circuit. Sound waves cause the speaker cone to vibrate. This vibration induces a small voltage across the speaker terminals. 2.The capacitors (C1 and C2) block the DC voltage from the power supply from entering the circuit, but allows the AC signals from the speaker to pass through. 3.The 1N4148 diodes act as clippers or voltage limiters. They clip off the negative voltage halves of the AC waveform from the speaker, leaving only the positive voltage portions. This process is called half-wave rectification. 4.The resistors (1kΩ) limit the current from the speaker to the transistors (Q1-Q5). 5.The transistors (Q1-Q5) amplify the rectified signal from the speaker. When sound is picked up by the speaker, the transistors are turned on, which allows current to flow through the LEDs, lighting them up. The louder the sound, the brighter the LEDs will glow.

This is a basic circuit, and there are many variations of it online. You can experiment with different values of resistors and capacitors to change the sensitivity of the circuit and the way the LEDs respond to sound.

### Working 
The Mobile phone jammer devices transmit the similar radio frequency which is greater power than the cell phone. The communication between the cell phone and the base station of the phone tower is called as a denial of service attack. This causes the obstruction with the communication of cell phones and towers to make the cell phones not viable and there is no network visibility. Hence it works in both ways i.e. Cell phone to the tower frequency and the other one is tower to mobile frequency. The cell phone Jammer works with the frequency of 450MHz if this frequency is hunk we need to generate the 450MHz frequency with same noise which is acted as a blocking signal because the receiver of the cell phone signal will not be able to understand the received signal. By this circuit we can able to block the cell phone signals

# Circuit Diagram

![image](https://github.com/SubashM00/PCB-Design-Application/assets/144870586/229968b2-40c7-4a8f-a969-eacf52fd2a25)

# Output
### Schematic diagram

![image](https://github.com/SubashM00/PCB-Design-Application/assets/144870586/7b9e742c-8e5d-48b1-991c-c4d6292a4f1a)

### Layout diagram

![image](https://github.com/SubashM00/PCB-Design-Application/assets/144870586/a62b2e47-eac3-4dd7-bab6-6de9baf661f8)

# Result
Thus , mobile phone jammer circuit's schmetic diagram and layout diagram is designed successfully by using the eagle software.

