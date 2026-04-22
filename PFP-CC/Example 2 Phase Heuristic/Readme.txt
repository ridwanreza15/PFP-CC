Hi, thank you for visiting this page and taking the time to read this file.

This short document provides an overview of the case studies and their corresponding results. It is intended to help you understand the structure of the data, the reoptimization process, and how to interpret the outputs. The following sections describe the contents of each folder and the purpose of the accompanying files.

The folder contains 10 case studies along with their corresponding results.

Folder “0 input”
- Contains the input data used for testing in each case study.

Folder “1 Reoptimization_Steps_Output”
- Contains the intermediate schedules of vehicles during the reoptimization process. Each file includes departure times, charging times, arrival times, and platoon formation details.
For each test case:
“_0” represents the initial solution (all vehicles travel alone)
“_1” represents the first reoptimization
“_2” represents the second reoptimization
and so on until the final iteration

Folder “2 Final_Output”
- Contains the final vehicle schedules and platoon formation obtained after the last reoptimization step.

Excel File “Case and Result”
- Summarizes the results of all case studies, including objective values and CPU computation times.