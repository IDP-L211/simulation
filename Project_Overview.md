# Project Overview

---

## General Tasks

First 4 webots tutorials.

Gantt chart.

Presentation that details our MVP and also ideas / directions for final design.

---

## Overall Strategy

### Minimum Viable Product

Cubic robot that “eats” up the blocks.

Robot will move in a square spiral shape around the arena to search for the blocks

Once it sees their corresponding block, it will move towards it, collect and return it to it’s area

Need fallback for no block in terms of determing next position to go to

### Ideas for Final Design

Scoop up all blocks into robot and carry to goal.

Scan all blocks at start for pathfinding algorithm, update as block positions become clearer. Most blocks should be detectable initially unless they are on the edge of the area. Could update by spinning again after collecting other blocks or by sweeping the edge of the area.

Fine tune any bot strategy parameters with testing.

---

## Project Management

Team name: Team Optimal(?)

### Meetings

Next meeting Monday, 1:00pm GMT

### Git

Freely commit to own teams repos, submit a pr if you want to contribute to another team.

Each commit should be a working self contained thing, write useful commit messages.

To assign someone, create a task then convert to an issue.

Can only assign 1 person to each task so be specific.

---

## Reports / Presentations

### To ask demonstrator

Is infrared sensor laser or led

---

## Mechanical - Care, Youjing

### Tasks

Sketch 2 more designs, one being the hook

### Ideas

---

## Electrical - Karl, Eleanor

### Tasks

Analyse sensor data-sheets, collect characteristics for each.

Once done, send to the software team so they can simulate sensors.

### Ideas

---

## Software - Weixuan, Jason, Ghifari

### Style guide

Google style docstrings.

Unit testing?

To do a task: Create a branch, pr to merge back into main with 'WIP' and then link it to a task.

Squash and merge branches.

Code reviews.

### Tasks

Finish motion API

### Ideas

#### MVP Strategy

Spiral out from start and pick up blocks as it goes along.

Proportional control for wheel speeds using angle and distance error from target.

#### High-level

Determine next block, go to block, position around block.

#### Modules

Driving / Motor - Function that takes a co-ord and goes to it directly, co-ord system?

Sensor Processing

GPS

Strategy

Collision avoidance - 2 levels, general stay away from other bot and then an interrupt to prevent collisions

