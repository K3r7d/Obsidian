[Kernel]is central component of an operating system that manages operations of computer and hardware. It basically manages operations of memory and CPU time. It is core component of an operating system. Kernel acts as a bridge between applications and data processing performed at hardware level using inter-process communication and system calls.


[System bus]
	A method to connect all the parts in operating system.

[Interrupt]
	A way to inform to the device driver to stop doing something
	![[Ảnh màn hình 2024-01-17 lúc 13.32.45.png]]
	Priority of the interruption
[Trap]
	Traps: A trap is a software-generated interrupt, often the result of an error or exception, such as division by zero or invalid memory access. Traps can also be used intentionally by programmers to call operating system routines or to catch and debug errors. When a trap is encountered, the processor switches from user mode to kernel mode and begins executing a trap handler routine.

[Exception]

[Vector interrupt system] handle asynchronous events and to trap supervisor mode

[Polling] involve continually checking the status of a device. If the time below the threadhold, use polling instead of interrupt.

[System call overhead]

[Context switch]

[Blocking I/O] The process must wait when the I/O task is doing its work.

[Storage Structure] : 
	Main memory
	Secondary storage: Hard Disk Drives(HDD), Non-volatile memory(NVM)
[DMA]
	- Use for high-speed i/o devices able to transmit information at close to memory speed.
	- Device controller transfers blocks of data from local buffer directly to main memory without CPU intervention.
	- Only one interrupt per block.

[ICP technique] 
	ICP in the context of operating systems stands for Inter-Process Communication. It is a set of programming interfaces that allow a programmer to coordinate activities among various program processes that can run concurrently in an operating system. This allows a specific program to handle many user requests at the same time.
	There are several techniques for IPC, and two of the most common ones are shared memory and message passing2:
		Shared Memory: In this method, processes share a common space or memory  location known as a buffer where the data is stored and from which the data is consumed2. An example of this is the Producer-Consumer problem2.
		Pipes: Pipes are a type of IPC that allows two or more processes to communicate with each other by creating a unidirectional or bidirectional channel between them3. A pipe is a mechanism by which the output of one process is directed into the input of another process3.
	IPC is crucial in computer science as it allows processes to manage shared data4. Typically, applications can use IPC, categorized as clients and servers, where the client requests data and the server responds to client requests.

[job scheduling]

[I/O subsystem]

[Distributed Systems] 
	Collecting separate system network together.
	For example: Network is communication path
		Local Area Network(LAN)
		Wide Area Network(WAN)
		Metropolitan Area Network(MAN)
		Personal Area Network(NAN)
	Network Operating system is the OS provide features for the connected devices. 

[multitasking] Given 3 object with execution time is 10, 20 and 30 minutes. Instead of running them sequentially, divide it into very small pieces and run 1s of first, second and last object. until the task is finish.

[Multicore] Including multiple computing cores on the same CPU.

[Multiprocessor] Including multiple processors.


Despite increase speed of computing, too many CPU will make the system bus degrade. To solve this problem, They use [shared system interconnect], so that all CPUs share one physical address space. Or it's [non-uniform memory access (NUMA)].

[Blade severs] are systems in which multiple processor boards


