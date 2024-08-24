# Scheduling Algorithms Simulation

This project provides a simulation of various CPU scheduling algorithms in Java. The implemented algorithms include:

- **Shortest Job First (SJF) Algorithm**
- **Shortest Remaining Time First (SRTF) Algorithm**
- **AG Scheduling Algorithm**
- **Priority Scheduling Algorithm**

## Features

- **Shortest Job First (SJF) Algorithm:**
  - Selects the process with the smallest burst time.
  - Calculates average waiting time and turnaround time.

- **Shortest Remaining Time First (SRTF) Algorithm:**
  - Preemptive version of SJF.
  - Handles processes based on remaining burst time.

- **AG Scheduling Algorithm:**
  - Dynamically adjusts quantum time based on process attributes.
  - Prioritizes processes with different priorities dynamically.

- **Priority Scheduling Algorithm:**
  - Executes the process with the highest priority.
  - Includes aging to prevent starvation.
