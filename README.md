# ABM for Socio-Economic Monitoring of Visitor Streams in Harz NP

## Main goals
Due to the large extent of the Harz National Park, an accurate measurement of visitor numbers and their spatiotemporal distribution is not feasible. This model demonstrates the possibility to simulate the streams of visitors with ABM methodology.

The goal of this model is to simulate groups of hikers in the study area around the Brocken, in the Harz NP. As a result, national park management will be provided with key figures (e.g. numbers of visitors to POIs, of hikers on paths) for socio-economic monitoring.

## Programming language
This agent-based model (ABM) is written in GAMA. To run this code you need GAMA 1.7 or higher. Futher information is available here: https://gama-platform.github.io/

## File structure
### Directory include
Includes all necessary data (e.g. shapefiles).

### Directory models
Main program directory. There is only one file `Harz National Park Hikers.gaml` with all subroutines together.

### Directory tests
Several tests and code snippets which have been used during the development of this ABM.

### Directory output
Simulation generated output of the results from the ABM will be placed here. Actually there are no files in here, because you havent't run any simulation now.

### Directory figures
Contains some figures for these README files and explanations. You don't need it for sunning the simulation code.

### Other sources for the code
The code of the model has also been published at the CoMSES / OpenABM network: https://www.comses.net/codebases/6014/releases/1.0.0/

## Introduction
The Harz National Park offers with 813 km a well-developed path network as well as a high number of starting and destination points (POIs) for hikes, and was visited by some 1.7 million visitors in 2014. Due to its large extent, an accurate measurement of visitor numbers and their spatiotemporal distribution is not feasible. This work demonstrates the possibility to simulate the streams of visitors around Mt. Brocken with the agent-based model (ABM) methodology. The GAMA v1.7 RC2 modelling environment was chosen, because it has very extensive spatial operators and simulation tasks, combined with an easy-to-understand modelling language. To reduce the simulation effort, a model reduction factor MRF = 10 was tested successfully and used without any significant change to the model. After an initial parameterization, a sensitivity analysis was conducted with the results included in the final calibration. The observed error value could be significantly reduced from RMSE_Param=0,3817 to RMSE_Kalib=0,1069 and therefore the model was successfully adapted to the study area. For the final validation visitor numbers from other, independent investigations were used. Besides the identified 12 main routes and 7 hotspots not only basic socioeconomic indicators were provided, but also the change of behaviour of hikers following a variation of framework conditions was analyzed, thus demonstrating the impact of currently implemented measures to reduce path density. The final result is a flexible and expandable baseline model, which provides a realistic picture of the spatial distribution of hikers in the study area and additional socioeconomic key figures.

