# LabPSU_Darlington

Welcome to my Lab PSU project, which is based on a pair of BD139/TIP3055 Darlingtons and the Teensy 3.5 (3.6 should work as well).<br><br>

Specs:<br>
0 - 16.384V output controllable in 1mV steps<br>
0 - 4096 mA output controllable in 1mA steps<br>
Around 0.1% accuracy due to high accuracy components<br>
16 Bit DACs (DAC8311)<br>
High precision voltage reference for the DACs (REF5040)
16 Bit ADCs (ADS1115)<br>
Low Ripple, Low Noise<br>
25kHz PWM/temperature controlled Fan output for standard PWM capable FANs<br>
One Board solution (toroidal transformer not onboard)<br>
Optional Front Panel for Display, rotary encoder, button and LED mounting<br>
Fast UI thanks to Teensy's 120 MHz frequency<br>
Header for ESP8266, ESP32 or basically any other UART compatible device, including 3.3V and GND as well as two I/O pins (one PWM capable)
