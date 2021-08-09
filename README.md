# CSVP_Code_Supplement

This repository contains the code and data supplement to accompany the research paper entitled __"Data-driven competitor-aware positioning in on-demand vehicle rental networks"__. The paper proposes a novel operational problem that considers vehicle positioning in on-demand rental networks such as carsharing in the wider context of a competitive market in which users select vehicles based on access. The presented solution approach combines online machine learning to predict market-level demand and supply with dynamic mixed integer non-linear programming (MINLP). For evaluation a discrete event simulation based on real-world data from Car2Go and DriveNow is used.

The provided data and code samples focus on the optimization and simulation aspect of the paper and are intended to facilitate replication and benchmark analyses of the presented research. In particular the repository contains (1) sample real-world carsharing and contextual data for a full week, (2) Julia code of the optimization model and (3) Julia code of the simulation framework.

For ease of use, all code has been compiled into a single jupyter notebook (.ipynb) with extensive annotations and descriptions.

## Requirements

All optimization and simulation code has been tested for `Julia  Version 1.5.3` with the following installed packages.

- "CSV"          => v"0.8.3"
- "GLPK"         => v"0.14.6"
- "TimerOutputs" => v"0.5.7"
- "JuMP"         => v"0.21.6"
- "Juniper"      => v"0.7.0"
- "Ipopt"        => v"0.6.5"
- "StatsBase"    => v"0.33.4"
- "IJulia"       => v"1.23.2"
- "PyPlot"       => v"2.9.0"
- "TimeSeries"   => v"0.20.2"
- "Cbc"          => v"0.7.1"
- "Gurobi"       => v"0.9.9"
- "DataFrames"   => v"0.22.5"

To ensure optimal performance, a working installation of [Gurobi Optimizer](https://www.gurobi.com/downloads/?campaignid=2027425879&adgroupid=77414946451&creative=375332431095&keyword=gurobi%20optimizer&matchtype=e&gclid=Cj0KCQjwub-HBhCyARIsAPctr7yz1YZXABCpaVcNjI7QEwblyzQ3ypZBcAFa2R4CkurhkmaJB0it-eQaAhNKEALw_wcB) is also recommended. If Gurobi Optimizer is not available, the code allows for easy switching to an open source mixed integer linear solver such as CBC or GLPK.


## References

For further details please refer to the following research paper: *<REFERENCE OF PUBLISHED PAPER TO BE ADDED>*
