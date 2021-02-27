# Project Overview

---

## General Tasks

Finish webots tutorials

Report

Decide and test sensor strategies

---

## Overall Strategy

### Minimum Viable Product

Cubic robot that “eats” up the blocks with a half curve (Proposal 3).

Robot goes to nearest block, collects it and then repeats for next block.
Once all collected go back to goal.

#### Possible Sensor strategies

##### Available: Ultrasonic, Long IR, Short IR, 3x Light Sensor

Use a rotating infrared sensor to scan the area. Ultrasonic at the front of robot for distance accuracy.

Use light sensor for close range block detection?

Long IR and ultrasonic pointing straight with spinning for detecting new targets when we lose current target or need a new one.

Long IR straight forward and 2 ultrasonic sensors pointing away from each other, 10 deg from forward.

### Beyond MVP

Scan all blocks at start for pathfinding algorithm, update as block positions become clearer. 
Most blocks should be detectable initially unless they are on the edge of the area.
Could update by spinning again after collecting other blocks or by sweeping the edge of the area.

Fine tune any bot strategy parameters with testing.

More sophisticated control methods

---

## Project Management

Team name: Team Optimal

### Reports / Presentations

### Meetings

### Git

Freely commit to own teams repos, submit a pr if you want to contribute to another team.

Each commit should be a working self contained thing, write useful commit messages.

To assign someone, create a task then convert to an issue.

Can only assign 1 person to each task so be specific.

---

## Mechanical - Care, Youjing

### Tasks

### Ideas

---

## Electrical - Karl, Eleanor

### Tasks

### Ideas

---

## Software - Weixuan, Jason, Ghifari

#### Style guide

Google style docstrings.

Unit testing?

To do a task: Create a branch, pr to merge back into main with 'WIP' and then link it to a task.

If working on a branch and master gets updated, rebase.

Squash and merge branches.

Code reviews.

### Tasks

Classifying detections

Collision Avoidance

### Ideas

#### Modules

Motion Control

Sensor Processing

GPS

Strategy

Collision avoidance - 2 levels, general stay away from other bot and then an interrupt to prevent collisions

#### Beyond MVP

Better control - PID?

Move to pose

