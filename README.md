# Remote-controlled car with anti crush system vhdl
Durukan Çiftci - Remote-Controlled Car with Collision Avoidance System / Bilkent EEE102 Term Project

This project aims to design a remote-controlled car that can be operated with mouse input.
Interpreting the data obtained from the mouse on the FPGA board, in our car BASYS-3, and driving DC motors with the PWM (pulse with modulation) was aimed.
Also, I aimed to insert a collision avoidance system by utilizing an ultrasonic sensor that can detect the obstacles and send the distance data to FPGA.

The Mouse_driver module is taken from the BASYS 3 demo code.
Some adjustments about the initial values and boundaries of outputs are made.

Basys 3 General I/O Demo:
https://digilent.com/reference/programmable-logic/basys-3/demos/gpio?redirect=1
