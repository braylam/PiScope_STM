This is the C code for the STM32 in our PiScope capstone project. This code controls the servo motors tracking and also controls the unlocking logic for the solenoid.

The pin wiring is as follows:

STM:
Rx = PA3
Tx = PA2

Pi:
Tx = 14
Rx = 15

PA3 -> 14
PA2 -> 15

Solenoid Pin: PE2

X servo: PB5
Y servo: PC6
