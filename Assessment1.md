---
title: R Martin - Assessment 1
---

## Assessment 1

* Assessment 1 (worth 30%) is an online portfolio of an agent-based model. It can be accessed from <a href="https://github.com/gy19rgm/GEOG5990Assessment1" target="_blank"> gy19rgm's GitHub profile </a>, along with the relevant readme file, licensing and documentation.
* Assessment 1 instructions are found on <a href="https://www.geog.leeds.ac.uk/courses/computing/study/core-python/assessment1/index.html" target="_blank"> the University of Leeds GEOG5990M Programming for Spatial Analysts: Core Skills (Python) </a> website.
* In the model, sheep and sheepdogs interact within a field environment, eating, running and herding as they go. The model runs as an interactive animation in the form of a Graphical User Interface (GUI)) - this also allows the user to choose the quantity of sheep and sheepdogs to be used in the model. Neither sheep or sheepdogs can get leave the environment, both are penned in by the field 'fence'.

| Number of sheep | Number of dogs |
| --- | :---: |
| Between 50 - 100 | Between 5 - 10 |

#### Sheep:
* Move in a random direction, eating grass and sharing their resources with close by sheep
* If a sheep notices a dog, it moves in the opposite direction at a faster speed to normal

#### Sheepdogs:
* Dogs move in a random direction at a faster speed to the sheep
* If a dog notices a sheep it halves the distance between itself and the sheep - replicating a 'sprint' and 'stalk'  motion

[*Back to main page*](https://gy19rgm.github.io/)