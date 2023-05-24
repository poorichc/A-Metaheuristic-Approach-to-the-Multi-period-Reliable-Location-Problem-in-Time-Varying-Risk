# A-Metaheuristic-Approach-to-the-Multi-period-Reliable-Location-Problem-in-Time-Varying-Risk
## Description
This directory comprises the folders containing the source code, data and figures for the research article:
A Metaheuristic Approach to the Multi period Reliable Location Problem in Time Varying-Risk
## Source
This folder contains the python source code for optimizing multi-period reliable location problem:
> Heuristics.ipynb
* This python script contains the supporting functions for neigborhood search of the SMC-SA algorithm.
> SMCSA_approach.ipynb
* This python script contains the main SMC-SA algorithm for our metaheuristic optimization.
> Reliable_Location_infected-Linear-Multi period.ipynb
* his python script contains the main MIP formulation using Gurobi.
> Sensitivity_analysis.ipynb
* This python script contains the main driver code for our Uncertainty analysis


## Data
This folder contains all data sets.

* Each data file is provided in readable text formats (.csv)
* Data file contains different 3 data sets (Data_1,Data_2,Data_3), different number of nodes (49, 88, 150) and different risk levels (low, medium, high).
* Text header contains relevant data on each sample ( Index,	demand,	emerg_cost,	prob_fail, fixed cost,	lat,	lon,	State,	State_cd)
* For sensitivity analysis, data are in q_sensitivity that contain simulated information from beta distribution.

## Figure
This folder contains all the figures from our research.

## How to Run the Code:
* Download the spatial.py, time-series.py, seq.py python scripts from source folder and place them in a directory.
* Download the sequence text files from data folder and place them in the same directory as the python scripts.
* Run the scripts spatial.py and time-series.py, then check your directory for the output figures.
