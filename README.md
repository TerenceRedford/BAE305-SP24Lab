# BAE305-SP24Lab
# Lab 1, Knowing your instruments
Group Members: Terence Redford and Heath Shewmaker
Submission date: 2/3/25
# Introduction summary
The aim of this lab was to familiarise ourselves with the details for using common electrical components and circuit analysis tools. The equipment used included Digital multimeters, oscilloscopes, function generators, and direct current power supplies. We investigated the functions and capabilities of these components to further our understanding of how we can use these tools to retrieve information about resistance and capacitance. 
For example the DMM has an internal resistance and only reads the root mean square of the signal for AC voltage. With this new-found knowledge we were able to confirm that the factory specifications of the resistors and capacitors were accurate.
# Methods/Tests: 
Step 1:
We began by using the DMM to measure the resistance of 4 resistors of varying resistance. The resistance was measured by setting the DMM to read ohms and attaching the leads to either side of the resistor, taking special care to ensure that the leads did not touch other surfaces.
![image](https://github.com/user-attachments/assets/ce2fd9e1-19fe-434c-aff5-2c2c7109a581)


Figure 1: How to test the resistance of a resistor using a DMM.

Step 2:
The DMM was used to measure the capacitance of 4 various capacitors. To measure the capacitances the DMM was set to read farads and the leads were attached to either side of the capacitors, which were placed into a breadboard to secure their position.
![image](https://github.com/user-attachments/assets/17a71771-0ff8-44a4-813d-0949e3ce88ff)


Figure 2: How to test the capacitance of a capacitor using a DMM. 

Step 3:
The power supply is then tested by connecting the leads of the DMM to the input and output terminals of the DCPS using jumper cables. The variable output is tested by adjusting it to the values : +1.5V, +7V and +12V. The preset outputs (3/5V output and 12V output) are then tested by switching modes on the back of the machine and moving the jumper cables to the respective terminals. The voltage reading is given both on the DMM and the Display on the DCPS case.
![image](https://github.com/user-attachments/assets/c0c2c738-543d-43fb-9e41-6e999426f447)

Figure3: How to test the DCPS display with the DMM.


Step 4:
The function generator was tested by setting it to generate a sinusoidal wave function and minimizing the frequency and then connecting the FG outputs to a  10 Kilo-ohm resistor using a breadboard and jumper cables. Using the Oscilloscope with the provided probes, the signal passing through the resistor could be visualised on the Oscilloscope by adjusting the time and voltage increments. The peak values and frequency of the signal were checked through 4 methods: visual intreperetation of the graph, use of tools within the O-scope software (cursors and measurment function) and with the DMM.
![image](https://github.com/user-attachments/assets/62b2be51-f9b9-49fd-8d9c-43cbb15dea52)

Figure 4: How to set up your circuit including the function generator and DMM.

# Results: 

Step 1: We obtained the following table of results for the resistance values after connecting the DMM terminals directly to eachother to identify the internal resistance. After correcting the measured values of resistance, it can be seen that all of the resistors fall within the given tolerance.
 ![image](https://github.com/user-attachments/assets/b3b6fde5-cb8f-4a08-8257-8d55604c4f53)

Figure 5: Measured vs expected resistances. Resistances were tested to see if they were within manufacturer's specified tolerance, with green cells being in tolerance.  

Step 2: The following table illustrates the expected and measured values of the capacitors. The DMM was only rated to read up to a maximum of 100 micro-Farads, which the capacitor rated as 100 micro-Farads exceeded resulting in a "OL" (overload) reading. The table illustrates that the capacitors that could be measured were close to their expected values. We placed the high rated capacitor in series with a smaller capacitor in order to calculate its capacitance through the equivalent capacitance formula and found that it was also rated accurately. 
![image](https://github.com/user-attachments/assets/3c86c3e8-0cfe-46a0-91a2-b2cdd5244820)

Figure 6: Measured vs expected capacitances. Capacitances were tested to see if they were inside specified tolerances, with green cells being in tolerance. The yellow filled cell is a reminder to calculate the capacitance by hand.

Step 3: We found that the readings of the DMM and the DCPS did not differ in any noticable way. All values were very close in DCPS display and DMM measurement.
![image](https://github.com/user-attachments/assets/003e89d6-1d48-4378-95e2-f1e261245c1d)

Figure 7: DCPS voltage display vs DMM readings

Step 4: We discovered that the peak voltage difference was around 5V and the frequency was about 4.5 kHz according to the three ways we interpereted the Oscilloscope readings. The DMM had a completely different voltage reading, which we discovered occurs because it is designed to interperet the root mean square of the signal, which is essentially a measure of the average intensity of the voltage difference.
![image](https://github.com/user-attachments/assets/b92902cf-802a-4e23-958a-af61229d3683)

Figure 8: Voltage amplitude and frequency according to varying instruments. 

# Discussion: 
All resistors were within manufacturer specified tolerance. However, we discovered that it is necesarry to consider the limitations of methods in measuring these values as the internal resistance of the DMM initially made us believe that the smallest resistor was outside of tolerance. All capacitors also had capacitances of relatively close values with respect to their specification. However, since the DMM is only rated to read a maximum of 100 micro-Farad, we had to calculate the largest capacitance by hand using another capacitor in series.  Does the DCPS generate an accurate and realiable voltage through all the terminals, even at different settings? The DCPS is very accurate. This was confirmed by comparing our DMM readings and the Display on the DCPS.  Oscilloscopes appear to be the best tool to understand time varying signals, giving you a variety of ways to analyse the signal, and visualising it for you to easily see its pattern. The DMM is only suitable for measuring the root mean square of a signal, but because it is a specialised device that is designed to measure RMS, its accuracy at doing this should be given priority over other devices. This is the only situation in which the instruments seem to be able to disagree. While the Oscilloscope will tell you RMS, peak voltage, peak to peak voltage, and frequency, the DMM will only give RMS voltage. However, the RMS values do agree with eachother on both instruments. 
# Conclusion: 
It is critically important to understand the proper uses and limitations associated with each tool you make use of. Not factoring in something like internal resistance, or assuming that a reading like the RMS from a DMM is something it is not (such as the peak to peak voltage), will cause errors that one may not be able to account for if they don't know that these devices have these specific applications.
Factory indicated resistances and capacitances can typically be relied on to be accurate. Although it is best practice to check these, and should be done if critical in your situation, it is impractical to do this most of the time.
Devices like the Oscilloscope, function generator, and the DCPS are reliable pieces of equipment and are specifically designed to perform their functions. When one needs a signal of a certain type, selecting the right device will usually be the most important step.

