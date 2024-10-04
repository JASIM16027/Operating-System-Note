# Operating-System-Note

### Concept level 1
Operating system Beginner question list:

1. What is an Operating System (OS)?
2. Key functionalities of modern OS.
3. Explain the layered design of computing systems.
4. OS User Interface overview.
5. What is protection in an OS?
6. What are kernel and user modes, and why are they necessary?
7. Define system calls and their purpose.
8. What are traps in an OS?
9. What is an Application Programming Interface (API)?
10. How do APIs invoke system calls?
11. How are system calls implemented in an OS?
12. Methods for passing parameters to system calls.
13. Outline the life cycle of program creation.
14. Define the memory footprint of a program.
15. What is a process in an OS?
16. Explain multiprogramming and multitasking.
17. Overview of CPU scheduling and process scheduling.
18. States a process goes through.
19. What is a Process Control Block (PCB)?
20. When do processes relinquish the CPU?
21. What is a context switch in OS?
22. CPU scheduling basics and performance metrics.
23. Difference between CPU-bound and IO-bound processes.
24. When does the CPU scheduler run?
25. Define turnaround time and waiting time in scheduling.
26. Explain First-Come, First-Served (FCFS) scheduling.
27. What is Shortest Job First (SJF) scheduling?
28. Explain non-preemptive priority scheduling.
29. What is starvation in scheduling?
30. What is Shortest Remaining Time First (SRTF) scheduling?
31. Explain preemptive priority scheduling.
32. What is round-robin (RR) scheduling?
33. How are scheduling algorithms combined in practice?
34. Describe Linux CPU scheduling algorithm.
35. Programs involving multiple processes.
36. How to create multiple processes in Linux.
37. Example of fork system call in Linux.
38. Interprocess Communication (IPC) overview.
39. Using shared memory for IPC.
40. Message passing in IPC.


### Concept level 2

1. Why are threads used in programs?
2. What are the overheads of using processes?
3. What is the key idea behind threads?
4. Difference between single-threaded and multithreaded processes.
5. Benefits of using threads.
6. Pthread basics overview.
7. How to create a thread using Pthread?
8. How to pass parameters to a thread?
9. Using Pthread_self and Pthread_equal.
10. How to terminate a thread in Pthread?
11. How to use Pthread_join to wait for thread termination?
12. Returning values from thread functions.
13. How to wait for threads?
14. How to detach a thread using Pthread_detach?
15. Global variables in threads.
16. What is concurrency in programs?
17. What are race conditions and atomic operations?
18. What is synchronization in programming?
19. Correctness properties of synchronization solutions.
20. How to enforce mutual exclusion in multithreading?
21. What are locks, and how to use them in Pthreads?
22. How to avoid deadlock with locks?
23. What are semaphores and their use cases?
24. What are synchronization patterns like bounded concurrent access and signaling?
25. Using semaphores to avoid busy waiting.
26. How does multithreading interact with multicore systems?
27. Challenges of multicore programming.
28. How to design multithreaded programs effectively?
29. What are thread pools?
30. What is the readers-writers problem, and how to solve it?
31. What is the dining philosophers problem, and how to solve it?
32. Four necessary conditions for deadlocks.
33. How to prevent deadlocks?
34. What is a resource allocation graph?
35. How to handle deadlocks?
36. How are threads implemented?
37. Difference between user threads and kernel threads.
38. How are threads implemented in Linux?
39. How are locks implemented in programming?
40. What is the TestAndSet atomic instruction?
41. What are spin locks?
42. How do locks affect performance?
