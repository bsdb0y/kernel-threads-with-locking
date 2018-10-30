# Kernel Threads with locking using spinlock


It is a simple linux kernel module which implementing threads with proper
locking using spinlock

There are two threads, one is for multiplying some dummy value and another one
is adding some value and they shares one common global variable for which
locking implemeted.

Testing on Linux Kernel 4.19.0
