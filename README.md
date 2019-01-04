# LabPSU_Darlington

Welcome to my Lab PSU project, which is based on a pair of BD139/TIP3055 Darlingtons and the Teensy 3.5 (3.6 should work as well).<br><br>

Specs:<br>
0 - 20.48V output controllable in 5mV steps<br>
0 - 4096 mA output controllable in 1mA steps<br>
Around 0.1% accuracy due to high accuracy components<br>
12 Bit DAC (Teensy integrated)<br>
12 Bit ADC (Teensy integrated, 2.048V high precision external voltage reference)<br>
Low Ripple, Low Noise<br>
Separate linear, software-adjustable voltage regulator for fan speed control to avoid high frequency switching noise (PWM)<br>
One Board solution (toroidal transformer not onboard)<br>
Optional Front Panel for Display, rotary encoder, button and LED mounting<br>
Fast UI thanks to Teensy's 120 MHz frequency<br>
Header for ESP8266, ESP32 or basically any other UART compatible device, including 3.3V and GND as well as two I/O pins (one PWM capable)
