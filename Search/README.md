# Search :mag:

Using search agent to find the route to the goal. Based on graph theory, [**search.py**](search.py) is a set of search algorithms. [**searchAgents.py**](searchAgents.py) is a set of agents.

### Algorithms :scroll:
Returns solution for given problem
###### Searching Strategies :bookmark:
+ Depth First Search :arrow_down:
+ Breadth First Search :left_right_arrow:
+ Uniform Cost Search :chart_with_upwards_trend:
+ A* Search :chart_with_upwards_trend: :heavy_plus_sign: :chart_with_downwards_trend:


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

## Performance :100:
From **autograder.py**
```
Provisional grades
==================
Question q1: 3/3
Question q2: 3/3
Question q3: 3/3
Question q4: 3/3
Question q5: 3/3
Question q6: 3/3
Question q7: 5/4
Question q8: 3/3
------------------
Total: 26/25
```
