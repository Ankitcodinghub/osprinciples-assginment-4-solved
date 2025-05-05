# osprinciples-assginment-4-solved
**TO GET THIS SOLUTION VISIT:** [OSPrinciples Assginment 4 Solved](https://www.ankitcodinghub.com/product/osprinciples-assginment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98614&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;OSPrinciples Assginment 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# OSPrinciples-Assignment4

This assignment consists of writing C/C++ programs for implementing semaphore-based and monitor-based solutions for the FCFS version of the reader-writer problem. The FCFS version works as follows: readers and writers access the shared file in the FCFS order; if multiple readers arrive at the system back-to-back, these readers can read the file concurrently when it is their turn to read. It can be assumed that threads in every queue associated with a semaphore, or a monitor or a conditional variable are managed with the FCFS policy.

The goal of this assignment is to practice developing semaphores-based and monitor-based applications. Furthermore, practice some system calls and process management by the operating system.

**Details**

You need to Develop C or C++ programs to implement your semaphore-based and Monitor solutions to the FCFS version of the reader-writer problem, using the POSIX semaphore functions and conditional Variables (if needed). Name your programs as “Assign4_sem.c” and “Assign4_mon.c” to refer to the semaphore solution and monitor solution, respectively. The programs should be complied correctly on the CSE machine. Suppose the name of the compiled executable files are “assign4sem_exe” and “assign4mon_exe”, respectively. Your programs should have the following functionalities:

1. It accepts 10 arguments from the command-line, denoted as b1, b2, …, b10. Each bi is either 0 or 1. If bi is 0, it means the ith arriving thread is a reader; otherwise, it is a writer. For example, the programs may be launched as:

_cse …&gt; assign4sem_exe 0 1 0 0 1 0 0 0 0 1_

_cse ..&gt; assign4mon_exe 0 1 0 0 1 0 0 0 0 1_

meaning your programs should solve the FCFS version of the reader-writer problems for the situation that 10 reader/writer threads (i.e., the 2nd, 5th and 10th ones are writers while others are readers for this example) arrive at the system (i.e., start running) in the specified order.

2. After accepting the 10 arguments from the command-line, the program should create 10 reader/writer threads and start them in the specified order. Once created, these threads run concurrently. Each reader thread performs one reading operation and each writer thread performs one writing operating.

Performing a reading or a writing operation is simulated with making the thread sleeps for 1 millisec. When a reader (or writer) starts or ends reading (or writing), a message should be printed. For the example shown in (1), the message should be like _“Reader 1 starts reading”_, …, _“Reader 1 ends reading”_, …, _“Writer 2 starts writing”_, …, _“Writer 2 ends writing”_, ….

The program will need to use pthreads to create threads, and sleep system call to simulate time elapse, in addition to the semaphore functions for the semaphore solution, and the use of conditional variables and semaphores to create the monitor.
