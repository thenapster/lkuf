# Linux Kernel Utility Functions (LKUF)

This project is intended to Linux kernel developers The objective of this project is to summarize at the same place all lkuf such as find_thread_by_pid, virt_to_phys, etc.
In fact, the kernel includes a lot of utility functions that we sometime need when extending or building a kernel module.
Most of the time, especially kernel developer beginners or students, tend to reimplement such functions, leading to time waste.
The goal of this wiki is to summarize at the same place the list of such functions with a brief description.
For the moment, we keep all the descriptions in the [same page](lkuf.md).
We will probably organized things when the number of functions will be important.
Feel free to contribute!

They are two types of contributions:
* Notify an issue about an lkuf presentation. The issue request should include the lkuf name.
* Send a new lkuf description. This includes: the lkuf name, the location of both the declaration and definition files inside 
the location inside the kernel, the kernel version, the description of the lkuf goal, and a location inside the kernel of 
the utilization of that lkuf.

Here is the current list of lkuf which composed the project:
* [find_thread_by_pid](lkuf.md#find_thread_by_pid)
* [virt_to_phys](lkuf.md#virt_to_phys)
