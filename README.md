## Fork Example

This is code from a class I took a couple years ago where all code was developed on Linux servers.

This program was created to fulfill homework/classroom requirements, not professional development.

Old README/Explanation:

Shane Kennedy

The APIs fork(), execlp(), and wait() all work in a separate file. When a fork()
system call is made, a copy of all the memory related to the parent process is
created and loaded into a separate memory location by the operating system.
This child will then have access to all the same information as the parent, but
will be able to act on its own, while the parent will wait. The wait() system
call holds the execution of a process until a child has exited or a signal has
been delivered that will terminate the current process. The wait() system call
will also take in an integer value as seconds to wait until it should resume
the current process. The execlp() system call will have a similar function to
fork(), but instead of creating a child process, it will replace the current
process with a new one entirely.
