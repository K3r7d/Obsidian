wait(&a) : wait for the child a finish the process.
fork() : create a child process in Linux

[Inter-Process Communication (IPC)]
	Processes within a system may be [independent] or [cooperating]
	Reason for cooperating processes: 
		Information sharing
		Computation speed-ip
		Modularity
		Convenience
	

Communication Model
	Shared memory: 
	Message passing:
	+ Shared memory is faster and having a bigger size to do while message passing is easier to implementation

[Unbounded-buffer] places no practical limit on the size of the buffer
[Bounded-buffer] assumes that there is a fixed buffer size

[Socket]
	Three types of socket:
		Connection-oriented (TCP)
		Connectionless (UDP)
		MulticastSocket: Class - data can be sent to multiple recipients

