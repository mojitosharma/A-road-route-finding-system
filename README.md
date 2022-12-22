# A-road-route-finding-system
A road route finding system using Depth First Search and Best-first search on the given dataset

###### Assumptions:
• All connections are bi-directional
###### Heuristic:
- We define heuristic function of a node as the minimum cost of the node and its neighbours. 
- Checking for admissible and consistent.
  - As the h(s) = minimum edge cost of the node and its neighbours.
    - ➔ h(s) ≤ h*(s), heuristic would be always less than equal to true cost. 
    - ➔ Heuristic is admissible.
  And h(s) < cost(s,t)+h(t)
    Here h(s) is the minimum cost and h(t) > 0
    ➔ So the above condition will always be true.
    ➔ Heuristic is consistent.

###### Change directory using - cd('c:/Users/Sharm/Desktop/Courses/AI/AI-A2-Mohit-2020086'). to move into working directory.
 Change the address according to the location of the files 
