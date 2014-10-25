# Networked RGB Lamp

**This is a work in progress**

## Wiring notes

Some notes on how to wire the Arduino and the shift register.

### Wiring the Arduino and the TPIC 6B595N

| Arduino Uno     | TPIC 6B595N    |
|----------------:|---------------:|
|   8 (Latch)     |    12 (RCK)    |
|  11 (Data/MOSI) |     3 (SER IN) |
|  13 (Clock/SCK) |    13 (SRCK)   |

### Additional wiring for TPIC 6B595N

  - 8 (SRCLR') to Vcc
  - 9 (G') to GND


## Links

### http://www.elcojacobs.com/shiftpwm-function-reference/

Library for (ab)using shift registers to generate PWM
