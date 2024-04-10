
# Design-and-Layout-Implementation-of-Two-stage-Opamp-using 180nm-Technology
Design and Layout implementation of a high-performance two-stage Operational Amplifier (OPAMP) using 180nm semiconductor technology. Achieved required gain, bandwidth, and power efficiency through simulation and characterization.

# 2 Stage OPAMP Description
1. **Two-Stage Amplification**:
   - The op-amp consists of two amplification stages: a first stage called the input differential amplifier, and a second stage called the output amplifier.
   - The input stage amplifies the difference between two input voltages, while the output stage further amplifies this signal to produce a high-gain output.

2. **Miller Capacitance**:
   - Miller compensation is a technique that involves adding a capacitor across the input and output of the amplifier to effectively increase its bandwidth without sacrificing stability.
   - In a Miller-compensated two-stage op-amp, a capacitor is placed between the input and output nodes of the amplifier. This creates a feedback loop that modifies the amplifier's frequency response.

3. **Increased Bandwidth**:
   - By introducing the Miller capacitance, the pole frequency of the op-amp is shifted, effectively increasing its bandwidth. This means that the op-amp can respond to higher-frequency signals.

4. **Stability Improvement**:
   - Miller compensation helps to stabilize the op-amp by reducing the possibility of oscillation, especially at high frequencies. This is crucial for applications where a stable output is essential.

5. **Trade-offs**:
   - While Miller compensation enhances bandwidth and stability, it may introduce additional phase shift in the frequency response, which can affect the amplifier's performance in certain applications.

6. **Applications**:
   - Miller-compensated two-stage op-amps are commonly used in high-frequency applications where both bandwidth and stability are critical factors, such as in communication systems, instrumentation amplifiers, and other precision electronics.

# Circuit
![image](https://github.com/chennakeshavadasa/Design-and-Layout-Implementation-of-Two-stage-Opamp-using-45-90-180nm-Technology/assets/123294639/a5308f86-378b-4f4c-ae18-80641894a93e)

# Design-Specification
Check out each process technology folder 

# Design Process 
(W/L) ratio of M3,M4 is found using ICMR(+) <br> 
(W/L) ratio of M1,M2 is found using GBW <br>
I5 is found using Slew Rate <br>
(W/L) ratio of M5 is found using ICMR(-) <br>
(W/L) ratio of M6 is found from Gain and design of M3, M4 <br>

# Technology Used
180nm <br>

# References 
CMOS Analog Circuit Design - Book by Douglas Holberg and Phillip E. Allen <br>
Youtube

# Status
Ongoing





