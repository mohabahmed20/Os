# CPU scheduling algorithms for Shortest job first (SJF) and Round Robin RR
This project contian java implementation of 2 CPU scheduling for SJF and RR

## SJF 
SJF is an algorithm in which the process having the smallest execution time is chosen for the next execution. This scheduling method can be preemptive or non-preemptive. It significantly reduces the average waiting time for other processes awaiting execution. The full form of SJF is Shortest Job First. the java implementation Can be found here <a href ="https://github.com/mohabahmed20/Os/blob/main/SJF/src/comm/company/Main.java">SJF.Java</a>

![SJF Output](https://user-images.githubusercontent.com/128136252/225874975-51af0808-599a-443a-af1f-d7f676ccf30e.png)

## Round Robin (RR)
RR is Round Robin scheduling algorithm is one of the most popular scheduling algorithm which can actually be implemented in most of the operating systems. This is the preemptive version of first come first serve scheduling. The Algorithm focuses on Time Sharing. In this algorithm, every process gets executed in a cyclic way. A certain time slice is defined in the system which is called time quantum. Each process present in the ready queue is assigned the CPU for that time quantum, if the execution of the process is completed during that time then the process will terminate else the process will go back to the ready queue and waits for the next turn to complete the execution.the java implementation Can be found here  <a href ="https://github.com/mohabahmed20/Os/blob/main/RR/src/comm/company/Main.java">RR.Java</a>

![RR output 1](https://user-images.githubusercontent.com/128136252/225889843-4a118c6e-c074-48b4-bc90-0a2726a53c7b.png)
![RR output 2](https://user-images.githubusercontent.com/128136252/225889846-6dc57857-72c6-43a2-8165-aaea2473247a.png)
