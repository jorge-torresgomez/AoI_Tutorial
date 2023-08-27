# AoI_Tutorial
Matlab code for Age of Information Tutorial

This repository provides Matlab code for the Age of Information Tutorial with the following files

1. `wireless_chain.slx`: Comprises a point-to-point wireless communication chain. The emitter sends packets with the text "Workshop AoI" wich is decoded at the receiver side. The transmission rate is controlled with the nob block
2. `init_fcn.mlx`: Initialize the design clearing all variables, closing all plots, define the message to transmit as "AoI Workshop", and define the simulation time with the variable `sample_time`.
3. `stop_fcn.mlx`: This file runs after stoping the simulink simulator. This file provides the code to plot arrays from the simulink design.
