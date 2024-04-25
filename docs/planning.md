---
title: Planning
layout: default
---


## Trajectory planning

### Opty

[Repository github](https://github.com/csu-hmc/opty), [Documentation](https://opty.readthedocs.io/en/latest/theory.html)

### Implémentation
   
[06_optyplan.py](https://github.com/poine/projet_dronisos_guidage/blob/master/src/06_optyplan.py)

#### Example 0

  * Specification of start/end position and time
  * Bank and velocity contraints
  * Mean velocity cost function

<img src="plots/optyplan_0_2d.png" alt="" width="640">
<img src="plots/optyplan_0_chrono.png" alt="" width="640">

#### Example 3

Constraints on state variables, obstacles (in cost function)

<img src="plots/optyplan_3_2d.png" alt="" width="640">
<img src="plots/optyplan_3_chrono.png" alt="" width="640">


#### Example 7

Several independant planifications

<img src="plots/optyplan_1.apng" alt="" width="640">
