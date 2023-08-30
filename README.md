# CPUSchedulingAlgorithms

## Why do we need to schedule processes?

Scheduling is important in many different computer environments. One of the most important areas is scheduling which programs will work on the CPU. This task is handled by the Operating System (OS) of the computer and there are many different ways in which we can choose to configure programs. Process Scheduling allows the OS to allocate CPU time for each process. Another important reason to use a process scheduling system is that it keeps the CPU busy at all times. This allows you to get less response time for programs. Considering that there may be hundreds of programs that need to work, the OS must launch the program, stop it, switch to another program, etc. The way the OS configures the system to run another in the CPU is called “context switching”. If the OS keeps context-switching programs in and out of the provided CPUs, it can give the user a tricky idea that he or she can run any programs he or she wants to run, all at once. So now that we know we can run 1 program at a given CPU, and we know we can change the operating system and remove another one using the context switch, how do we choose which programs we need. run, and with what program? That’s where scheduling comes in! First, you determine the metrics, saying something like “the amount of time until the end”. We will define this metric as “the time interval between which a function enters the system until it is completed”. Second, you decide on a metrics that reduces metrics. We want our tasks to end as soon as possible.

## Objectives of Process Scheduling Algorithm:

1. Utilization of CPU at maximum level. Keep CPU as busy as possible.
2. Allocation of CPU should be fair.
3. Throughput should be Maximum. i.e. Number of processes that complete their execution per time unit should be maximized.
4. Minimum turnaround time, i.e. time taken by a process to finish execution should be the least.
5. There should be a minimum waiting time and the process should not starve in the ready queue.
6. Minimum response time. It means that the time when a process produces the first response should be as less as possible.

##What are the different terminologies to take care of in any CPU Scheduling algorithm?
- Arrival Time: Time at which the process arrives in the ready queue.
- Completion Time: Time at which process completes its execution.
- Burst Time: Time required by a process for CPU execution.
- Turn Around Time: Time Difference between completion time and arrival time.

## Algorithms Implemented:
- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- Round Robin
- Priority Scheduling

## Visualisation
### Comparision of Average Wait Times
<img width="442" alt="image" src="https://github.com/MananSuri27/CPUSchedulingAlgorithms/assets/84636031/6485ab33-587e-404b-8fc2-93207410198c">

### Comparison of Average Turnaround Times
<img width="444" alt="image" src="https://github.com/MananSuri27/CPUSchedulingAlgorithms/assets/84636031/23e02399-f6b8-4a43-bf34-f4aa26a6aa81">

