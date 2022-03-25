# PkjCell_Model

These files are the necessary files to run the computational modeling presented in Brown, Medina, Vaaga, Holla and Raman. 
Model_Traces: contains all the simulated raw synaptic traces and spike traces.
Model_Simulations: contains all the code to generate all the simulated data in the manuscript.
Model_Analysis: loads the output of Model_Simulations and plots the data as PSTHs. 

To run the simulations, you must have jupyter notebook installed on your computer. The easiest way to do this is by downloading the Aanaconda python package. Once downloaded, install the NEURON python wrapper using pip install neuron. 

Finally, run the python notebooks from a single folder, with the nrnmech.dll file in the same directory. On first run, you may have to run the optional code in the second box to properly install the density mechanisms names (to allow channels to be inserted into the membrane). 
