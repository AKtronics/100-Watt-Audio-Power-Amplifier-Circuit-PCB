# 100-Watt-Audio-Power-Amplifier-Circuit-PCB

This amplifier circuit amplifies audio signals up to 100 watts, suitable for use in high-power audio systems. The circuit includes several stages: an input stage for signal conditioning, a differential amplifier, a voltage amplifier, a driver stage, and a push-pull output stage. Each stage is designed to enhance signal quality, minimize noise, and maximize power efficiency.

# Features
Class AB Operation: Reduces crossover distortion while maintaining efficiency.

Push-Pull Output: Minimizes even-order harmonics for improved audio clarity.

Thermal Compensation: Diode-based thermal compensation to stabilize operation.

High Output Power: Delivers up to 100W into an 8-ohm speaker load.

Dual Power Supply: Operates on ±35V for high output voltage range. 

# Circuit Explanation
1. Input Stage
The input stage uses a differential pair of BC108 transistors for initial signal conditioning and noise rejection, ensuring stable operation.
2. Voltage Amplification
This stage boosts the conditioned signal to a level suitable for the output stage. It utilizes a common-emitter configuration to provide significant voltage gain.
3. Driver Stage
The driver transistors supply the necessary current to the output stage transistors while maintaining correct biasing to prevent crossover distortion.
4. Output Stage
High-power transistors (2N2222 in this version) are used in a push-pull configuration, amplifying the signal to drive the speaker with high current output.

5. Power Supply
This amplifier circuit requires a ±35V dual power supply to achieve high output swing and power delivery.
