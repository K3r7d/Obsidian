[Communications] 
	shared memory
	message passing

[Error detection]

[Resource allocation]

[Logging] keep track programs use how much and what kind of resources.

[System calls] 
	System calls is a request from computer software to Operating system's kernel

[Application Program Interface (API)] Connect the operating system's function to user programs. It act as a link between the operating system and a process, allowing user-level to using the operating system services.

[Types of System Calls] 
	[Process control]
		Create process, terminate process
		End, abort process execution
		Load, Execute
		get process attribute, set process attributes
		wait for time, wait event, signal event
		allocate and free memory
		dump memory if error
		Debugger
		Lock for managing access to shared data between processes
	[file management]
		create, delete, open, close file
		read, write, reposition
	[device management]
		request, release device
		get, set attribute of device
		logically attach or detach devices
	[information maintenance]
		get, set time, day, system data, process, file, device attributes
	[Communications]
		create, delete communication connection
		send, receive message if using message model to host name of process name
		Shared-memory model create and gain access to memory regions
	[Protection]
		Control access to resources
		Get and set permissions
		Allow and deny user access

[Linker and Loader]
	- Source code compiled into object files designed to be loaded into any physical memory location – relocatable object file.
	- Linker combines these (also, brings in libraries) into single binary executable file.
	- Program resides on secondary storage as binary executable and must be brought into memory by loader to be executed.![[Ảnh màn hình 2024-02-01 lúc 14.29.35.png]]

[Microkernels]
	Between user space and kernel
	Using message passing model
	Benefit:
	- Easier to extend a microkernel
    - Easier to port the operating system to new architectures
    - More reliable (less code is running in kernel mode), more secure.


[Mac OS and IOS structure]
	![[Ảnh màn hình 2024-02-01 lúc 14.36.17.png]]
	![[Ảnh màn hình 2024-02-01 lúc 14.36.27.png]]