## Experiment No: 3
DIFFERENTIATOR USING OP-AMP (μA741)
## Aim
To design and simulate a Differentiator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the rate of change of input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Capacitor C = 0.01 µF
•	Resistor Rf = 10 kΩ
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="759" height="453" alt="image" src="https://github.com/user-attachments/assets/80164388-b88e-46d1-ad0a-c697ccf50d19" />

## Connection Details:
•	Input signal → Capacitor (C) → Inverting terminal (Pin 2)
•	Feedback resistor (Rf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Differentiator circuit produces an output voltage proportional to the rate of change of input voltage.
## Working Principle:
•	When input changes rapidly → output amplitude increases
•	When input is constant → output is zero
•	Output is inverted
## Procedure
1.	Open Proteus software.
2.	Select μA741, capacitor, resistor, signal generator, and CRO.
3.	Connect circuit in differentiator configuration.
4.	Apply ±15V power supply.
5.	Set input sine wave (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
<img width="797" height="287" alt="image" src="https://github.com/user-attachments/assets/b785aea8-200c-4960-a5f1-8e395deab4a4" />

## Waveforms
<img width="932" height="765" alt="image" src="https://github.com/user-attachments/assets/790c97a0-9cbe-4a55-bba9-0edac35b703b" />

•	Sine input → Cosine output (90° phase shift)
•	Square input → Positive & negative spikes
•	Triangular input → Square wave
## Result
The Differentiator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the rate of change of input voltage.
The circuit behaves as a differentiator.
## Conclusion
•	Output depends on frequency.
•	Output leads input by 90° (for sine input).
•	Higher frequency → Higher output amplitude.
•	Used in wave shaping and signal processing applications.
## Viva Questions
1.	What is a differentiator?  An op-amp circuit that produces an output proportional to the rate of change of the input signal. It performs mathematical differentiation of the input.
2.	Write the output equation of differentiator.
 . ( V_{out} = -RC \dfrac{dV_{in}}{dt} ). Output depends on how fast the input voltage changes with time.
3.	Why is output leading input? Differentiation emphasizes rapid changes, causing the output to respond earlier than the input waveform peak. Hence the output leads the input in phase.
4.	What happens at very high frequency? Gain increases and noise gets amplified, making the circuit unstable. It may cause distortion or oscillations.
5.	What is practical differentiator? A modified differentiator with additional resistor and capacitor to limit high-frequency gain. It improves stability and reduces noise.

