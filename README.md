# Cell_electrochemical_simulator

This repository contains a couple jupyter notebooks that simulate the electrochemical behavior of a cell. The notebooks are designed to be run in a Jupyter environment, ideally via Binder, and they provide an interactive way to explore the dynamics of electrochemical cells.

For example, the simulator displays a representative picture of a cell, and other screens portraying potassium and sodium ion concentrations inside and outside the cell. The concentrations (inside and outside) can be changed by the user via sliders. Two graphs display the evolution of the membrane potential and concentrations over time.

The advanced mode allows the user to manually control the amount of potassium and sodium channels that are open. The number of channels is of course ilustrative and the cell has an equal amount of 200 channels for each ion. In the advanced mode, the concentrations cannot be changed by the user, because their dynamics is determined by the number of channels that are open, by the initial concentrations and other parameters. Lastly, the advanced mode allows the user to also display the evolution of the concentrations if they would follow Fick's law of diffusion instead of the Nernst-Planck equation.

## Live Simulator

[![Start Live Simulator](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zoccoler/Cell_electrochemical_simulator/main?urlpath=voila%2Frender%2FLive_Simulator.ipynb)

## Static Simulator

[![Start Static Simulator](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zoccoler/Cell_electrochemical_simulator/main?urlpath=voila%2Frender%2FSimulator.ipynb)

