- An [operating system] is software that manages the [computer hardware], as well as providing an [environment] for [application programs] to runs.

- [Interrupts] are a key way in which hardware interacts with the operating system. A hardware device triggers an interrupt by sending a signal to the CPU to alert the CPU that some event requires attention. The interrupt is managed by the [interrupt handler].

- For a computer to do its job of executing programs, the programs must be in [main memory], which is the only large storage area that the [processor] can access directly.
 
 - [Nonvolatile storage] is an extension of main memory and is capable of holding large quantities of data permanently. The most ubiquitous device of this type of storage is hard disk.

- [Modern computer architectures] are multiprocessor systems in which each CPU contains several computing cores.

-  [Multitasking] is an extension of multiprogramming wherein CPU scheduling algorithms rapidly switch between processes, providing users with a fast response time.

- [System bus] is the providing the access to the [shared memory].

- [Kernel] is the one program running all the time in computer. Kernel is a part of OS.  

PRACTICE EXERCISES
- 1.1 What are the three main purposes of an operating system?
	manages the computer hardware.
	providing and environment for application to runs.
	Establish User interface.

- 1.2 We have stressed the need for an operating system to make efficient use of the computing hardware. When is it appropriate for the operating system to forsake this principle and to "waste" resources? Why is such a system not really wasteful?


- 1.3 What is the main difficulty that a programmer must overcome in writing an operating system for a realtime environment?

- 1.4 Keeping in mind the various definitions of operating system, consider whether the operating system should include applications such as web browsers and mail programs. Argue both that it should and that it should not, and support your answers.
- 1.5 How does the distinction between kernel mode and user mode function as a rudimentary form of protection (security)?
- 1.6 Which of the following instructions should be privileged?
    1. Set value of timer.
    2. Read the clock.
    3. Clear memory.
    4. Issue a trap instruction.
    5. Turn off interrupts.
    6. Modify entries in device-status table.
    7. Switch from user to kernel mode.
    8. Access I/O device.
    answer: 

- 1.7 Some early computers protected the operating system by placing it in a memory partition that could not be modified by either the user job or the operating system itself. Describe two difficulties that you think could arise with such a scheme.