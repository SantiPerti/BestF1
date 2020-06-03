# BestF1

## This iOS App calculates *The best F1 driver in history* through a mathematical model. 

###The results can be obtained over a period of time, a certain season, race, decade...  or all-time history.

The algorithm is mainly based on driver merits when racing against his teammates, taking into account who their teammates are at each moment.
It tries to remove *any* influence of the car or team they are driving for. 

Most of the times, an F1 World Champion is the best driver on the grid that year, 
but some other times this result is too much influenced by the car: power, aerodynamics, teamwork, strategies... or even politics and penalties.

1. This algorithm tries to calculate the *absolute importance* of each driver and his weighted average grid positions.

2. That number is used to calculate the relative performance against your teammate.

