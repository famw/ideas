# General-purpose environment simulator
The idea here is to create an Environment Simulation Engine(?) capable of giving the user the freedom to model a vast amount of environments and agents that can interact with eachother.

The user would describe **Environments**, **Agents** and **Tasks** through Domain Specific Languages (?).

* **Task**: something that can be accomplished by agents.
* **Environment**: holds information about where tasks can be executed.
* **Agent**: interacts with the environment, executing tasks.

---
## Implementation
Ideally, the Environment Simulation Engine should be cross-platform and should be easily integrated into any project in any programming language. I have no idea right now how we would accomplish this and maintain sanity.

As a proof-of-concept, it would be sufficient if we integrated the Engine in a specific programming language, such as C++ (?) and create a simple environment with few types of agents and tasks.