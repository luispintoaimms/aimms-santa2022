# aimms-santa-2022
A simple AIMMS project to address the Santa 2022 Kaggle challenge.

https://www.kaggle.com/competitions/santa-2022/overview

## How to run
In order to run the project, you can use the MainExecution procedure.

## Additional information
Some disclaimers and information on the implementation:
1. In the interest of keeping things "fair", I implemented the "Getting started with Santa 2022" workbook provided at kaggle - https://www.kaggle.com/code/ryanholbrook/getting-started-with-santa-2022 and only added some small improvements
   1. I add a tracking paramters so I do not need to visit a point that has been already visited
   2. I created exploration regions, so that the algorithm explores points in a smaller region first

## Initial results

Initial results are not good, since there is no optimization happening in the algoritm. This project simply intends to provide a starting point for you to implement further improvements.

 ## Possible improvements
 
1. Implement a heuristic or model to select which points should be visisted in which order
2. Improve the movement changes - right now, every change is done individually to each link and this is more costly than changing several links at the same time.
3. Implement the TSP equivalent.
 
