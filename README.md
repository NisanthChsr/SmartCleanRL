Defining Environment:
Theme
In our vacuum room environment, we've designated a 4x4 grid where the agent, representing a vacuum cleaner, starts at position (0,0) and our goal is to reach position (3,3). The grid includes obstacles at (2,2) and (3,2).
States
To visually represent the state of the agent and goal positions, we use '1' for the agent and '0.5' for the goal_position in the grid.
Rewards
The primary objective is to clean the room including the corners, with each corner (0,3) and (3,0) providing an intermediate reward of '3'. However, when the agent comes across obstacles it incurs a negative reward of ‘-1’.

