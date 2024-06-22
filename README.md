# CPU-Scheduling-Algorithms
<b>Following CPU scheduling algorithms are implemented in C++.</b>


1. First Come First Serve:
In this non-preemptive scheduling algorithm, processes are executed in the order they arrive. The process with the earliest arrival time is given priority and executed first.


2. Round Robin:
This preemptive algorithm ensures minimal process starvation by executing processes in a round-robin fashion with a specified time quantum. After a process is executed for the given time quantum, it is preempted and the next process is executed.


3.Rate Monotonic Scheduling: 
Rate Monotonic Scheduling (RMS) is a fixed-priority real-time scheduling algorithm used in operating systems to manage the execution of periodic tasks. It assigns priorities to tasks based on their periodicity: the shorter the period of a task, the higher its priority.

4. Earliest Deadline First:
Earliest Deadline First (EDF) is a dynamic priority scheduling algorithm used in real-time operating systems to manage the execution of tasks. Unlike fixed-priority algorithms like Rate Monotonic Scheduling (RMS), EDF assigns priorities to tasks based on their absolute deadlines: the task with the closest deadline is given the highest priority.
