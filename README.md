# BAE305-SP24Lab
# Lab 1, Knowing your instruments
group members: Terence Redford and Heath Shewmaker
Submission date: (NOT SUBMITTED YET)
# Introduction summary
the aim of this lab was to familiarise ourselves with the details for using common electrical components and circuit analysis tools. The equipment used included Digital multimeters, oscilloscopes function generators and direct current power supplies. we investigated how we can use these tools to get information about resistance and capacitance, and what the limitations and use cases of each tool are. 
this investigation required testing specific components we were given using the tools we had, which showed us that the equipment had specific use cases, for exaple the DMM has an internal resistance, and for AC voltage only reads the root mean square of the signal. furthermore we confirmed that the factory specifications of the resistors and capacitors were accurate.
# Methods/Tests: 
Engineering documentation necessary to repeat the project. Should include:
Drawings
Pictures
step 1:
For this Lab we began by using the DMM to measure the resistance of 4 resistors of varying resistance, the specific color codes of the resistors were as follows: ()... The resistance was measured by setting the DMM to the setting that allows it to read resistance, and then attaching the leads of the DMM to either side of the resistor, taking special care to ensure that the leads did not touch other surfaces.
step 2:
The DMM was used to measure the capacitance of 4 various capacitors, which were marked with the following capacitance ratings: ()... To red the capacitances the DMM was set to the setting which reads capacitance, and then the leads of the DMM were attached to either side of the capacitors, which were placed into a breadboard to secure their position.
step 3:
The Power supply is then tested by connecting the leads of the DMM to the input and output terminals of the DCPS using jumper cables. first the variable output is tested by adjusting it to the values : +1.5V, +7V and +12V. Then the preset outputs (3/5V output and 12V output) are connected and tested by moving the jumper cables to the respective terminals. The voltage reading is given both on the DMM and the Display on the DCPS case.
Step 4:
The funtion generator was tested by setting it to generate a sinusoidal wave function and turning the frequency to its minmal value, and then connecting it to a  10 Kilo-ohm resistor by connecting the FG outputs to the resistor using a breadboard and jumper cables. Using the Oscilloscope with the provided probes the signal passing through the resistor could be visualised on the Oscilloscope by adjusting the time and voltage increments. The peak values and frequency of the signal were checked through 4 methods: visual intreperetation of the graph, use of tools within the O-scope software (cursors and measurment function) and then through the DMM.
# Results: 
Data or outcome from the work. Should include:
Tables
Drawings
Pictures
Step 1: we obtaned the following table of results for the resistor. By connecting the DMM terminals directly to eachother the internal resistance of the DMM was identified, and after correcting the measured values of resistance it can be seen that all of the resistors fall within the given tolerance.
Step 2: the following table illustrates the expected and measured values of the capacitors. The DMM was only rated to read up to a maximum of 100 micro-Farads, which the capacitor rated as 100 micro-Farads exceeded resulting in a "NO MEASUREMENT" reading. the table illustrates that the capacitors that could be measured were close to their expected values.
Step 3: we found that the readings of the DMM and the DCPS did not differ in any noticable way.
Step 4: we discovered that the peak to peak voltage difference was around (?) and the frequency was (?) according to the three ways we interpereted the Oscilloscope readings. The DMM had a completely different voltage reading, which we discovered occurs because it is designed to interperet the root mean square of the signal, which is essentially a measure of the average intensity of the voltage difference.

# Discussion: What you can learn from the results obtained. Should include:
1) Are the resistors within the range of values indicated by the manufacturer? Yes! although we adittionally discovered that it is necesarry to consider the limitations of methods of measuring this, because the internal resistance of the DMM initially made us believe that the smallest resistor was outside of tolerance.
2) Are the capacitors close the the stated capacitance? Yes! however it is necesarry to use equipment capable of testing capaciors with significantly higher capacitance, since the DMM is only rated to read a maximum of 100 micro-Farads.
3) Does the DCPS generate an accurate and realiable voltage through all the terminals, even at different settings? Yes! this was even confirmed by our DMM readings and the Display on the DCPS.
4) What are the right tools to measure a time varying signal? Oscilloscopes appear to be the best tool to understand time varying signals, giving you a variety of ways to analyse the signal, and visualising it for you to easily see its pattern. The DMM is only suitable for measuring the root mean square of a signal, but because it is a specialised device that is designed to measure RMS, its accuracy at doing this should be given priority over other devices.
# Conclusion: Most important things derived/learned from the lab and report (one or two paragraphs).
It is Critically important to understand the use cases and limitations associated with each tool you make use of. Not factoring in something like internal resistance, or assuming that a reading like the RMS from a DMM is something it is not (such as the peak to peak voltage), will cause errors that one may not be able to account for if they don't know that these devices have these specific applications.
Factory indicated resistances and capacitances can be relied on to be accurate, and should be trusted. Although it is best practice to check these, it is impractical to do thids most of the time.
Devices like the Oscilloscope, function generator and the DCPS are reliable pieces of equipment, and are specifically designed to perform their functions, as such when one needs a signal of a certain type, selecting the right device will usually be the most important step.

