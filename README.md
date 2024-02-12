 # LNA_1MHz
10Hz to 1MHz Low Noise Amplifier based on Linear Technology AN-159.

<p align="center">
<img src="https://github.com/H4w4k4/LNA_1MHz/assets/108990189/98a81adf-c990-49a4-b7a2-542d2d366905" width=50%/>
 &nbsp; &nbsp;
<img src="https://github.com/H4w4k4/LNA_1MHz/assets/108990189/e3785ea5-ef86-4277-b3d1-323e20a315cc" width=44%/>

</p>





# Design
The design is based on [Linear Technology AN-159 document](https://www.analog.com/en/resources/app-notes/an-159.html#author). It describe how to build a +80dB 10Hz to 1MHz low noise amplifier in order to measure noise level in the 2nV/√Hz range.

Following changes have been done:
+ Design re-routed in KiCad 7.0 to fit nicely into a Hammond 1590BBS housing
+ Selectable +60dB or +80dB gain
+ Full BW output removed

# Measure
A 60dB attenuator is placed on the input of the LNA to measure the frequency response. An Analog Discovery 3 is used as a network analyser.

<p align="center">
<img src="https://github.com/H4w4k4/LNA_1MHz/assets/108990189/813e2e67-2ed9-498d-b236-c18c464f913c" width=80%/>
</p>



# Building it
The complete production files are available. The PCB is a 4-layer 102 x 82.6mm and every components is hand solderable. The LNA is powered by 6x AA batteries, consumption is about 100mA. Use the Gerber "housing_Lid_Drill" for drilling the holes in the housing cover. 

Total BOM cost is ~160USD + PCB + shipping.

