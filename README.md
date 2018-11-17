# LabPSU_Darlington

Welcome to my Lab PSU project, which is based on a pair of BD139/TIP3055 Darlingtons and the Teensy 3.5 (3.6 should work as well).

Specs:
0 - 20.48V output controllable in 5mV steps<br>
0 - 4096 mA output controllable in 1mA steps
Around 0.1% accuracy due to high accuracy components
12 Bit DAC
12 Bit ADC
Low Ripple, Low Noise
Separate linear, software-adjustable voltage regulator for fan speed control to avoid high frequency switching noise (PWM)
One Board solution (toroidal transformator not onboard)
Optional Front Panel for Display, rotary encoder, button and LED mounting
Fast UI thanks to Teensy's 120 MHz frequency
Header for Wiznet W5500 Ethernet module (SPI interface header, basically, plus some I/O pins)
