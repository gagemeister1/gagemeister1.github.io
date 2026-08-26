---
title: "Flexible Job Shop Scheduling"
collection: portfolio
---

Flexible Job Shop Scheduling problem:
Jobs with sub-operations of respective n time to run need to be scheduled across multiple machines. 

In this project I randomly generated 50, 250 and 500 job batches to test the ability of a genetic algorithm, as well as the Wisdom of Crowds method with it, to optimize the schedule makespan (total run time) across three machines.

<figure>
  <img src="{{ 'images\AIJobScheduling\50GAConvergenceandWoCImprovement.PNG' | relative_url }}" alt="50Improvement">
  <figcaption>The improvement of schedules for the 50 job problem after GA+WoC.</figcaption>
</figure>


<figure>
  <img src="{{ 'images\AIJobScheduling\50BestGAWocSchedule.PNG' | relative_url }}" alt="GanttFJSS">
  <figcaption>This is a Gantt-like representation of jobs on each machine in the sequence they are scheduled.</figcaption>
</figure>
