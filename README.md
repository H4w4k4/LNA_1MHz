# LNA_1MHz
10Hz to 1MHz Low Noise Amplifier based on Linear Technology AN-159.

<p align="center">
<img src="https://github.com/H4w4k4/LNA_1MHz/assets/108990189/98a81adf-c990-49a4-b7a2-542d2d366905" width=60%/>
</p>


# Design
The design is based on [Linear Technology AN-159 document](https://www.analog.com/en/resources/app-notes/an-159.html#author). It describe how to build a +80dB 10Hz to 1MHz low noise amplifier in order to measure noise level in the 2nV/√Hz range.

Following changes have been done:
+ Design re-routed to fit nicely into a Hammond 1590BBS housing
+ Selectable +60dB or +80dB gain
+ Full BW output removed

# Measure
The LNA is placed in serie with a 60dB attenuator to measure the frequency response of the circuit.

# Building it
The complete production files are available. The PCB is a 4-layer 102 x 82.6mm. Every components is easy to hand-solder.

Total BOM cost is ~

