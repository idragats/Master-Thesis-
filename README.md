# Master-Thesis-Predict-Material-Properties

In this MSc thesis we use Lammps Enviroment, and python to calculate crystal properties like RDF (Radial Distribution Function), 
ADF (Angular Distribution Function), VACF (Velocity Auto-Corelation Function) and DOS (Density of State). 
The materials that we used were bulk Si, bulk SiO2, Si [100] surface and SiO2 surface. 
For Si we generated atomic positions data with python library called ASE (Atomic Simulation Enviroment) at 300 K. 
Afterwards we were used data from <a href="https://github.com/MDIL-SNU/SIMPLE-NN" target="_blank" rel="noreferrer"/> Simple-NN <a/> model at 500 K, 
and also the Neural Network that included on <a href="https://github.com/MDIL-SNU/SIMPLE-NN" target="_blank" rel="noreferrer"/> Simple-NN <a/> model to training data for SiO2 crystal. 
RDF and ADF calculated with Lammps simulation, VACF calculated with python after extract a file with velocities from Lammps simulation, and DOS calculated with python using Fourier Transform on VACF data. 
Finally, we created schematic graphs for Si bulk crystal and Si surface using also different interatomic potentials like SW, Tersoff and a different number of individuals in each simulation run.
However, for SiO2 we create schematic plots between bulk SiO2 and surface area of SiO2 after training the data.     