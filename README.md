# FPMUP
# Install

Here is the list of libraries you need to install to execute the code:

- python = 3.7.7
- tensorflow = 2.3
- numpy
- scipy
- matplotlib
- opencv-python

# 1.Simulation

In the simulation, run the simulation_demo program.

For the reconstruction without aberration and intensity fluctuation, set defocus z = 0 and mode = 0, then use the function named train2.

For the reconstruction with aberration, set z = 2e-4 or 2e-5, mode = 1, then use the function named train2.

For the reconstruction with both aberration and intensity fluctuation, set z = 2e-4 or 2e-5, mode = 2, then use the function named train2.

# 2.Experiment

In the experiment, run the experiment_demo program.

Choose im1 or im2 for different datasets, then use the function named trainrealdata.
