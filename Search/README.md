# Search :mag:
---
Using search agent to find the route to the goal. Based on graph theory, [**search.py**](search.py) is a set of search algorithms. [**searchAgents.py**](searchAgents.py) is a set of agents.

### Algorithms :scroll:
Returns solution for given problem
###### Searching Strategies :bookmark:
+ Depth First Search
+ Breadth First Search
+ Uniform Cost Search
+ A* Search


### Agents :shipit:
Something hold and solve the problem
+ Describe the problem 
+ Using appropriate search algorithms
+ Return a set of actions to get the goal

#### Problem :question:
State - Space Problem, like a state machine
+ An initial state :arrow_forward:
  - what state is when the problem begins
+ A goal test function :checkered_flag:
  - test the given state, tells if the problem solved
+ A successor function :fast_forward:
  - tells the possible actions and the state of the actions for given state
  - tells the cost of an action :: and the heuristic of the state
