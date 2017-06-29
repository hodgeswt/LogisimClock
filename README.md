# LogisimClock
A clock created in Logisim.

The "6to14_Decoder.circ" is a file that converts the 6-bit binary output of the "Time.circ" (a clock) to the necessary 14-bit output to run the two 7-segment displays necessary for each unit of time. 

The inputs on the 6to14_Decoder circuit are backwards. The "SA" output of the Time circuit must connect to the F output of a 6to14DecoderCircuit, the SB output must connect to E, etc, etc, for all the different units of time.

The "Clock.circ" is the circuit with the functioning clock. Double click to open. It may ask you to locate the two other circuits.

A video of this clock running is available on [my YouTube page](https://youtu.be/kt9VDPjEv0I).
