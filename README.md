# OS-Assignment-1-RR
The Effect of Time Quantum on Process Execution and Waiting Time:

The performance of the Round Robin (RR) algorithm depends heavily on the size of the time quantum.
​If the time quantum is too large: The algorithm essentially degenerates into a First-Come, First-Served (FCFS) scheduling algorithm. Processes will finish their bursts in a single cycle, which can increase the average waiting time for shorter processes trapped behind longer ones.

​If the time quantum is too small: The CPU will spend a significant fraction of its time performing context switches (saving and loading process states) rather than executing actual process instructions. While this increases responsiveness, it severely degrades overall CPU efficiency and throughput.

​Optimal Time Quantum: A good rule of thumb is that the time quantum should be large enough so that roughly 80% of the processes complete their CPU burst in a single time slice.
