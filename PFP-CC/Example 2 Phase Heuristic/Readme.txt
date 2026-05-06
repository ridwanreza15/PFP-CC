OVERVIEW
--------

Thank you for visiting this repository and taking the time to read this document.

This file provides an overview of the case studies and their corresponding results. It is intended to help readers understand:
- the structure of the data,
- the reoptimization process, and
- how to interpret the outputs.

The repository contains 10 case studies, each accompanied by its corresponding results.


FOLDER STRUCTURE
----------------

0_input
-------
This folder contains the input data used for each case study.


1_Reoptimization_Steps_Output
----------------------------
This folder contains the intermediate vehicle schedules generated during the reoptimization process.

Each file includes:
- departure times
- charging times
- arrival times
- platoon formation details

For each test case:
- "_0" represents the initial solution (all vehicles travel independently)
- "_1" represents the first reoptimization
- "_2" represents the second reoptimization
- ...
- Final index represents the last iteration


2_Final_Output
--------------
This folder contains the final vehicle schedules and platoon formations obtained after the last reoptimization step.

Each Excel file includes the following key sheets:

- "Schedule"
  Vehicle schedules, including departure, arrival, charging, and platoon formation.

- "time_short_dist_vec"
  Summary metrics for short-distance vehicles:
  - energy savings
  - delay time
  - waiting time for platooning
  - waiting time for charging
  - time savings due to reduced charging when traveling as a follower

- "time_long_dist_vec"
  Summary metrics for long-distance vehicles:
  - energy savings
  - delay time
  - waiting time for platooning
  - waiting time for charging
  - time savings due to reduced charging when traveling as a follower


SUMMARY FILE
------------

Case and Result.xlsx
--------------------
This file summarizes the results across all case studies, including:
- objective function values
- CPU computation times


NOTES
-----
- The reoptimization process iteratively improves vehicle coordination and platoon formation.
- Final outputs reflect the best solution obtained after all iterations.