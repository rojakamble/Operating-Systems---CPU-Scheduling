Operating System Scheduling

This is Operating Systems project. The project idea is to generate a randomly uniform stream of jobs as the first stage. Then in the second stage, we will pick a scheduling algorithm out of the most 6 commonly used algorithms. after this, we will make a comparison of which algorithm performed better on which data.

The implemented algorithms:

First-Come, First-Served FCFS Scheduling
Shortest-Job-First SJF Scheduling
Shortest Remaining Time
Priority Scheduling
Round Robin - RR Scheduling

Features:

•	We are not visualizing or building any UI for this project.
•	The queue is represented as time units at a time.
•	Understanding the problem, inputs, and expected outputs.

The user is free to select any input variables for the job creation like:
1.	The quantity of jobs.
2.	The degree of multi-programming.
3.	A job's total number of bursts.
4.	ranges for CPU and IO bursts.
5.	Priority.
6.	Range of arrival times.
7.	The change in context i.e., context switch.
8.	Alpha and Tau. (If required)

Important terms used in CPU scheduling:

Burst Time/Execution Time: This is the amount of time needed for the process to finish processing. It's also referred to as running time.

Arrival Time: the time a process enters a condition of readiness.

Finish Time: the time a process is finished and leaves a system.

Multiprogramming: The ability to run many programs simultaneously in memory.

Jobs: This sort of application does not involve any user interaction. 

User: It is a program that allows for user involvement.

Process: It serves as reference to both the user's and the jobs.

CPU/IO burst cycle: Process execution that alternates between CPU and I/O activity is known as a CPU/IO burst cycle. Typically, CPU times are faster than I/O times.

Context Switch: Technique to move a process between states, so that CPUs can carry out their operations. It is a procedure for saving the context (state) of the previous process (suspend) and loading it into the new process (resume).

Alpha: The relative weight of recent data versus past data is determined by alpha.

Tau: Predicts length of next burst, based on past measurement of burst times for the process.

Implementation:

•	Programming language: Java
•	Operating system: Mac OS/Windows/Linux
•	Editor: VS Code
•	Logic Hook: Algorithms

Conclusion:

The primary requirement for any efficient operating system is employing a best suitable scheduling algorithm to finish the job but it’s a fact that there’s no single algorithm that always does the job. Our project gives an insight on how the process scheduling works and this helps us on understanding the pros & cons in using them. The results shows that a clever management is the key here and the simulation shows the requirement of specific scheduling algorithms in each different scenario. We knew that there’s always room for improvement and we firmly believe that for a faster and better optimized operating system, new scheduling algorithms must come into place where it would minimize the bad outcomes that we are experiencing and derive the best use.
