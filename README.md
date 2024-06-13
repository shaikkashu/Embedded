PCB WORKSHOP
Analog circuit:
RAILWAY CROSSING LIGHTS USING 555 IC.c
INTRODUCTION:
Railway crossings are critical areas where safety measures are
paramount to prevent accidents. One such safety measure is the
implementation of blinking LEDs to alert vehicles and pedestrians
of an approaching train. This report outlines the design and
working of a blinking LED circuit using the 555 IC timer.
Components Required:
1.555 Timer IC
2.LEDs (Light Emitting Diodes)
3.Resistors
4.Capacitors
5.Power Supply (9V battery or similar)
6.Breadboard and Connecting Wires
Circuit Diagram:
The circuit diagram for the blinking LED using a 555 timer IC is as
follows:
Working Principle:
The 555 timer IC can be configured in different modes: astable,
monostable, and bistable. For the purpose of blinking LEDs, the
555 timer IC is configured in astable mode. In this mode, the 555
timer oscillates continuously between its high and low states,
creating a square wave output that can drive the LEDs to blink on
and off.
Assembly Steps:
1. Place the 555 timer IC on the breadboard.
2. Connect Pin 1 to the ground rail of the breadboard.
3. Connect Pin 8 to the positive rail of the breadboard.
4. Connect a 10µF capacitor between Pin 6 and Pin 2.
5. Connect a 1kΩ resistor between Pin 7 and Pin 8.
6. Connect a 10kΩ resistor between Pin 7 and Pin 6.
7. Connect a 0.01µF capacitor between Pin 5 and ground.
8. Connect LEDs in series with current-limiting resistors to Pin
3.
9. Connect the positive supply to the positive rail and ground to
the ground rail of the breadboard.
Tinkercad simulation:
Testing and Verification:
1. After assembling the circuit, connect the power supply.
2. Observe the LEDs to ensure they are blinking at the desired
rate.
Conclusion:
The 555 timer IC is a versatile component that can be used to
create a blinking LED circuit for railway crossings. By configuring
the 555 timer in astable mode and selecting appropriate resistor
and capacitor values, a reliable and effective alert system can be
implemented to enhance safety at railway crossings.
Digital circuit:
Half Subtractor Using NAND Gate:
INTRODUCTION:
In the realm of digital electronics, subtraction is a fundamental operation,
and the half subtractor is a crucial component in performing this task. A half
subtractor is designed to subtract two single-bit binary numbers, producing
both the difference and borrow outputs.
Components Required:
1.IC-74HC00(NAND GATE)
2.Breadboard
3.LEDs (Light Emitting Diodes)
4.Power Supply
5.Resistors
6.Interconnecting Wires
Circuit Diagram:
This diagram illustrates a basic implementation of a half subtractor using
two NAND gates. The inputs A and B represent the minuend and
subtrahend, respectively. The outputs are the Difference (Diff) and Borrow
(BORROW).
Working Principle:
The working principle of a half subtractor using NAND gates revolves
around the logic operations performed by these gates to compute the
difference and borrow outputs based on the input binary digits.
Difference (DIFF) Output Calculation:The first NAND gate receives
inputs A and NOT(B). NOT(B) represents the negation of input B, i.e., when
B is 0, NOT(B) is 1, and vice versa.The NAND gate performs the logical
AND operation on inputs A and NOT(B), producing the Difference
output.The Difference output (DIFF) represents the result of subtracting B
from A.
Borrow (BORROW) Output Calculation:The second NAND gate receives
inputs A and B directly.The NAND gate performs the logical AND operation
on inputsA and B, producing the Borrow output.The Borrow output
(BORROW) indicates whether a borrow is required during the subtraction
operation. If A is smaller than B, a borrow is necessary, and BORROW will
be 1; otherwise, it will be 0.The circuit operates as a basic binary
subtractor, where the Difference output represents the result of the
subtraction, and the Borrow output indicates if borrowing is needed.
Assembly Steps:
Connect Inputs to NAND Gates:
● Connect input A directly to one input of the first NAND gate.
● Connect input B directly to one input of the second NAND gate.
● Connect Outputs of NAND Gates:
● Connect the output of the first NAND gate to the Difference output.
● Connect the output of the second NAND gate to the Borrow output.
● Power Supply and Ground:
● Connect the Vcc (positive supply) to power the circuit.
● Connect the GND (ground) to provide a common reference for electrical
potential.
Tinkercad Simulation:
Testing and Verification:
○ Verify the connections and ensure there are no short circuits.
○ Apply binary inputs to A and B.
○ Observe the outputs to confirm correct operation: Difference (DIFF) and
Borrow (BORROW).
By following these steps, you can assemble a half subtractor using NAND gates
efficiently, enabling binary subtraction with minimal components and assembly time.
Conclusion: In conclusion,Through the assembly of NAND gates and
the connection of input and output lines, we have created a functional half
subtractor circuit. This circuit demonstrates the power of digital logic in
performing arithmetic operations using basic electronic components.
