# JSFSX

A distributed, parallel, high-performance application environment for JavaScript.

## The "X" is for eXecute!

JSFSX extends the [JSFS filesystem](https://gitlab.com/jgullickson/jsfs) with the ability to execute code stored in the filesystem.  This server-side allows JSFSX to become a platform for applications which require both client and server-side logic and processing.

In addition, JSFS's federation capabilities are extended to the execution of code, allowing a cluster of JSFSX servers to provide a parallel-execution environment for server-side code.  This parallelization is automatic, distributing load across a cluster with no additional effort on the part of the programmer.  In other words, high-performance applications can be written by Javascript programmers with no particular familiarity with high-performance computing.