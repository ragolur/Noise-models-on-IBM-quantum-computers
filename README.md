# Noise-models-on-IBM-quantum-computers
In this repository there are two jupyter notebooks where two noise models are implemented in a simulator for two different experiments and the results are compared with those obtained on a real quantum computer. Two real quantum computers have been used in this jupyter notebooks, the Ibmqx2 or Ibmq_Yorktown and the Ibmq_Belem.

The two experiments used are: Quantum Teleportation and CHSH Inequalities (Bell inequalities).


In the Jupyter notebooks one can run the experiments on a real quantum computer or read the results of past experiments done by me. The files to read the results are stored in the "jobs" folder, where there are two different folders for the results of each quantum computer. Within the folders for each quantum computer we have the folders for each experiment, the results for the CHSH experiments are stored in a .json file and the results for the Quantum Teleportation experiments are stored in a .csv file. Moreover, the calibration parameters for the two different quantum computers are stored in two different .csv files (IT IS IMPORTANT TO NOTE THAT THESE CALIBRATION PARAMETERS ARE NOT UPDATED!!!!!) but this files are only used for the thermal relaxation noise, for the other sources of noise the parameters are directly obtained from IBM, and therefore updated.


This code was done for my Master's Thesis : "Noise and decoherence phenomena in quantum computers". I hope the code is well explained and useful for you, if you have any suggerence or improvement don't hesitate to contact me!

Email: rafago1@hotmail.es


Thank you for visiting this repository!


Rafa
