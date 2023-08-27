# AoI_Tutorial
Matlab code for Age of Information Tutorial

This repository provides Matlab code for the Age of Information Tutorial with the following files

1. `wireless_chain.slx`: Comprises the wireless communication chain.
2. `init_fcn.mlx`: Initialize the design clearing all variables, closing all plots, define the message to transmit as "AoI Workshop", and define the simulation time with the variable `sample_time`.

It is a Simulink design which comprises a communication chain of emitter-wireless channel-receiver. The emitter sends packets with the text "Workshop AoI" wich is decoded at the receiver side.

The emitter comprises the following blocks
an entity b
