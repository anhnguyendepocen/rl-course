Final Project Check-in Rubric
------

See Canvas for due date. Submit on Canvas a link to your public GitHub repo for the project. 

In GitHub, there should be with a file named `final_project_check_in.md` with the following information:

```
Final Project Check-in  (Points)

- Name(s): 
- Finalized Research Question (1):
- The following working code in GitHub (3): 
    - A environment (1) 
    - An agent that performs random actions in the environment (1) 
    - An agent that learns based on the environment (1)
- List of ideas to finish project (1):
```

Signs of Life for Agent Learning
-----

To see if a RL algorithm is working or not, we need to check for some basic signs of life. The simplest indicator is running average of reward and the total reward. A working algorithm should obtain rewards higher than competely random baseline. 

Additionally, for a task in which success correlates with the number of time steps, check the episode length. If a task relies on quick completion, shorter episodes are better; if a task involves multiple stages, longer episodes are better.
