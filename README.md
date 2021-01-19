# Modifying-CFS-Scheduler
Coded as part of the Operating Systems Course (Monsoon Semester 2020).

Added a soft real-time requirement to a process using a system call, that requires soft real-time guarantees must receive atleast x units of time-slice. Every time the scheduler is called, it checks if real-time guarantees of process with soft-realtime requirements are being met or not. Higher priority is given to processes with soft-realtime requirement compared to the vruntime that is normally considered.

Further explanation is in writeup.txt.
