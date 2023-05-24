# A-Metaheuristic-Approach-to-the-Multi-period-Reliable-Location-Problem-in-Time-Varying-Risk
## Description
This directory comprises the folders containing the source code, data and figures for the research article:
A Metaheuristic Approach to the Multi period Reliable Location Problem in Time Varying-Risk
## Source
This folder contains the python source code for optimizing multi-period reliable location problem:
> Convex_Hull_Reduction.ipynb
* This python script contains Convex hull method for searching potential location.
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
* Download the Heuristics.ipynb, SMCSA_approach.ipynb, Reliable_Location_infected-Linear-Multi period.ipynb, Sensitivity_analysis.ipynb python scripts from source folder and place them in a directory.
* Download the data folder and place them in the same directory as the python scripts.
### MIP
* Run the scripts Reliable_Location_infected-Linear-Multi period.ipynb, then check the output in the python notebook.
### SMC-SA
* Run the scripts SMCSA_approach.ipynb, then check the output in the python notebook.
### Uncertainty analysis
* Run the scripts Sensitivity_analysis.ipynb, then check the figure in the python notebook.
