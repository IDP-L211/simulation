# Project Overview

---

## Overall Strategy

Cubic robot that “eats” up the blocks into a gated area that drags the blocks around.

Robot goes to nearest block, collects it and then repeats for next block.
Once all collected go back to goal.

Long ranged IR sensor that is used while rotating with DBSCAN to find block positions.

PID motor control.

Smart target selection to avoid collisions.

---

## Project Management

Team name: Team Optimal

### Reports / Presentations

Next presentation tuesday 16/03

### Meetings

???

### Git

Freely commit to own teams repos, submit a pr if you want to contribute to another team.

Each commit should be a working self contained thing, write useful commit messages.

To assign someone, create a task then convert to an issue.

Can only assign 1 person to each task so be specific.

---

## Mechanical - Care, Youjing

### Tasks

If 0.1 friction is approved then designing a 1:4 gear system and incorporating this into cad.

Helping out with testing and tuning.

---

## Electrical - Karl, Eleanor

### Tasks

Helping out with testing and tuning.

---

## Software - Weixuan, Jason, Ghifari

#### Style guide

Google style docstrings.

To do a task: Create a branch, pr to merge back into main with 'WIP' and then link it to a task.

If working on a branch and master gets updated, rebase or merge.

Squash and merge branches.

Code reviews.

### Tasks

Tune PID and action parameters to optimise collection speed and reliability.

Collect far_blocks.

Test and identify problems with strategy and solve them (to be assisted by other teams)
