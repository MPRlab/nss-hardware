# Nucleo Solenoid Shield - Hardware

This repository contains the KiCad files for the Nucleo Solenoid Shield.

Each version of the shield (A/B/C) can drive 25 solenoids from different sets of IO pins. The exact pin names can be found [here](https://docs.google.com/spreadsheets/d/1F1l6_GBWTKrIMixAlwO8Ikh-0bkGv4sUIIGNAyeHcug/edit?usp=sharing). 

The board is powered from a 4-pin ATX connector. The two contacts closest to the latch are the supply voltage and the two pins away from the latch are ground.

Next to the main power input is a secondary input for 5V to the Nucleo. The pin closest to the ATX connectore is 5V in, the middle pin is ground, and the third pin is connected to the solenoid supply voltage.
