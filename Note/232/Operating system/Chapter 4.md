
![[Ảnh màn hình 2024-02-21 lúc 15.19.33.png]]
[Multithreaded]
	Benefit:
		Responsiveness
		Resource sharing
		Economy
		Scalability

[Multicore Programming] putting pressure on programmers, challenges include:
	Dividing activities
	Balance
	Data splitting
	Data dependency
	Testing and debugging

[Parallelism] implies a system can perform more than one task simultaneously
	![[Ảnh màn hình 2024-02-21 lúc 15.16.50.png]]
	Types of Parallelism
		[Data Parallelism]
		[Task Parallelism]
		![[Ảnh màn hình 2024-02-21 lúc 15.24.27.png]]

[Concurrency] supports more than one task making process.

![[Ảnh màn hình 2024-02-21 lúc 15.16.32.png]]

[Amdahl's Law]
	Is a formula of the potential performance gain from additional computing cores.
	speedup <= 1/(S+(1-S)/N)
		S is serial portion
		N processing cores


[Multithreading Models]
	User-thread level and Kernel-thread level
	[Many-to-One Model]
		Many User-threads and System call is Blocked and just one thread output for kernel-thread.
		Few system still using this model because of the inability to adapt the multiple processing cores.
	[One-to-One Model]
		Drawback: Creating New User thread will create new Kernel thread. Consequently, perhaps burden the performance if too many User thread.
		Most of OS now use this model to operate. 
	[Many-to-Many Model]
		Flexible but hard to implement. 
![[Ảnh màn hình 2024-02-21 lúc 15.42.28.png]]