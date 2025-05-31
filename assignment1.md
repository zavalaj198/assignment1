Jorge Zavala  
CECS 326 Sec01  
5/30/2025  
### Assignment Description
Answer the following questions from the Chapter 1 reading from your text- book. Be through and complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. What are the two main functions of an operating system?  
One main functions of an operating system include using it as an extended machine that turns ugly hardware into beautiful creations. The other main function of an operating system is using it as a resource manager.  
2. What is the difference between timesharing and multiprogramming systems?  
Multiprogramming systems are able to use the CPU to to run several jobs at the same time.  Timesharing does the the same tasks but it does so using multiple users.  
3. The family-of-computers idea was introduced in the 1960s with the IBM System/360 mainframes. Is this idea now dead as a doornail or does it live on?    
The idea is still around with virtual memory.  
4. What is the difference between kernel and user mode? Explain how having two distinct modes aids in designing an operating system.  
Kernal mode is always in control of aid in designing a operating system. User mode has alot more limitations. They are kept in seperate areas so the operating system doesn't get them mixed up and cause errors.   
5. On early computers, every byte of data read or written was handled by the CPU (i.e., there was no DMA). What implications does this have for multiprogramming?  
This meant that the CPU had to do everything for I/O. Every task had to be done step by step which took alot longer than it would normally.  
6. There are several design goals in building an operating system, for example, resource utilization, timeliness, robustness, and so on. Give an example of two design goals that may contradict one another.  
Two design goals that I think will conflict would be timeliness and roboustness because I think that speed and accuracy might be a problem if the goal is to finish a task to the best of your ability time would be a factor and if the main goal is to speed up it might affect the quality.  
7. Which of the following instructions should be allowed only in kernel mode?
    (a) Disable all interrupts.
    (b) Read the time-of-day clock.
    (c) Set the time-of-day clock. (d) Change the memory map.
A. disable all interrupts. C. set the time-of-day clock. D. change the memory map  
9. Consider a system that has two CPUs, each CPU having two threads (hyperthreading). Suppose three programs, P0, P1, and P2, are started with run times of 5, 10 and 20 msec, respectively. How long will it take to complete the execution of these programs? Assume that all three programs are 100% CPU bound, do not block during execution, and do not change CPUs once assigned.  
20 msec because it has 4 threads and 3 programs  
10. What is a trap instruction? Explain its use in operating systems.  
A trap insruction is when the program needs help from the operating system. It then switches out to kenrnel mode.  
11. Modern operating systems decouple a process address space from the machine’s physical memory. List two advantages of this design.  
It doesnt have programs mess with each others memory and it doesnt allow for fake signals to be sent.  
