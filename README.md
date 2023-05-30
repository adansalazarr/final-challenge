Multithreaded Pacman Game - (single-node)
=========================================

Implement a multithreaded version of the arcade video game [Pacman](https://en.wikipedia.org/wiki/Pac-Man). This version will be a
Computer vs Human game. Each enemy will be independent and the number of enemies is configurable. Below you can see the general
requirements for the enemies and human player (pacman) interation.

![Pacman](pacman.png)


Technical Requirements
----------------------
- The game's maze layout can be static.
- The `pacman` gamer must be controlled by the user.
- Enemies are autonomous entities that will move a random way.
- Enemies and pacman should respect the layout limits and walls.
- Enemies number can be configured on game's start.
- Each enemy's behaviour will be implemented as a separated thread.
- Enemies and pacman threads must use the same map or game layout data structure resource.
- Display obtained pacman's scores.
- Pacman loses when an enemy touches it.
- Pacman wins the game when it has taken all coins in the map.


General Requirements
--------------------
- Make sure that you complete the below defined deliverables.
- Source code dependencies must be clearly documented.


Deliverables
------------
- Source code can be in a single student's account and the other team members can contribute to the same repository.
- Architecture Document - [ARCHITECTURE.md](ARCHITECTURE.md)
  - Details on how you designed and implemented your solution
  - Project architecture description, diagrams, charts and everything related to the way you think/design/build your program
- Build/Run automation (`Makefile` and documentation - [PACMAN.md](PACMAN.md))
  - Instructions on how to build and run your program
- Project's presentation (5-10 minutes)
  - A video presentation that will be delivered to the professor, in youtube preferable


Permitted programming languages
-------------------------------
- Multithreaded core backend
  - C
  - Go
- User Interface (optional)
  - Any
  - If it's terminal, output must be human-readable


Grading Policy
--------------
| Concept                      | Grade |
|------------------------------|-------|
| Architecture Document        | 20%   |
| Multithreaded implementation | 30%   |
| Build Automation             | 20%   |
| Coding best practices        | 10%   |
| Presentation                 | 20%   |
| TOTAL                        | 100%  |

- **Free Lab Bonus**

  You get cat an extra bonus if you implement an Artificial Intelligence algorithm in enemies behaviour for finding the pacman location, trace the route and follow it. This AI must be documented in the `ARCHITECTURE.md` file.