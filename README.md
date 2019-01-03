# Robotics & RC Control Shield for Teensy3.1-3.2
**Current Features:**
  - Auto power switching between battery an USB
  - Socket for DC step down module (Pololu  D24V50Fx series)
  - SBUS input from a generic RC receiver (designed around FrSky XM Plus Mini Receiver)
  - 6 channels of PWM output for servos/motors
  - 3 channels digital switching with high power MOSFETs
  - Battery Monitor with voltage divider attached to Teensy A10
  - Temperature (or any analog sensor) with header attached to A11
  - M2 mounting holes
  - Jumper wire used to get high current from power supply to servo outputs
  
**Future Work:**
  - Finish 4 layer design, 4-layer should require no jumper wire
  - Reorganize or add another USB port so that the power system doesn't interfear with teensy USB

A simple integrated design of what used to be a hand etched board with the power and RX modules attached by wires and glue.
This is intended to be a board to integrate the modules together and provide the PWM and Power Switching features in a rugged
and low EMI manner suitable for encapsulation on a rover.
