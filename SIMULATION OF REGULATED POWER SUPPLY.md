# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
<img width="903" height="412" alt="image" src="https://github.com/user-attachments/assets/6b882d73-d4cc-4f39-95a8-251d992ad28c" />


## AC INPUT WAVEFORM:
<img width="779" height="390" alt="image" src="https://github.com/user-attachments/assets/440ff595-45f7-4f0d-a000-56bfdf9346fe" />


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="778" height="393" alt="image" src="https://github.com/user-attachments/assets/3dae97a9-1caa-423f-962d-8d138ed70a70" />

## SIGNAL OUTPUT(WITH FILTER)
<img width="776" height="388" alt="image" src="https://github.com/user-attachments/assets/b363e8ac-f095-442f-94a2-5eaa653daa08" />



## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
