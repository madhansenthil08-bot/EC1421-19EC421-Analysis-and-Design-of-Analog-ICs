## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## Simulation of Digital to Analog Converters

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
![WhatsApp Image 2025-11-29 at 12 24 25 AM](https://github.com/user-attachments/assets/5dfeda64-e373-4ce8-9bed-5b2e7fcfbf2f)


## OUTPUT GRAPH:
### DAC:
<img width="370" height="1280" alt="image" src="https://github.com/user-attachments/assets/55c023f8-b61b-4f84-a55e-22a9b80d0f61" />

## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
