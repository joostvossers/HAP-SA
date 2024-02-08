# Human-Aware Planning for Situational Awareness in Indoor Police Interventions  
Umeå University, 2024.

Joost Vossers <br>
Andreas Brännström <br>
Juan Carlos Nieves

The project consists of two files:
* `HAP-SA.plan` contains the planner
* `HAP-SA.dl` contains the background knowledge

To run the planner, a couple of steps needs to be performed.
The first step is to install the DLV^K planner: https://www.dlvsystem.it/dlvsite/dlv-download/.
The implementation can then be run with the following command:

```
DLV SA.plan SA.dl -FP -N=3
```

This command instructs DLV to run the planner from HAP-SA.plan with HAP-SA.dl as background knowledge.
The -FP option ensures that the planning language K is used.
The -N=3 option specifies the maximum integer size to be 3, which is necessary to keep the levels consistent.
