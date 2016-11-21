Bochs x86 Emulator (SMP package for Windows)
Version: 2.6.8

This package contains two Bochs executables (with and without debugger)
compiled with both Pentium 4 and SMP support enabled. An existing Bochs
installation of the same version is required. By default it starts with
one CPU and you can use the cpu count option to enable more processors.
Bochs supports up to 255 CPUs.
NOTE: The SMP feature in Bochs is still incomplete. Some of the SMP-aware
operating systems will work, other may still fail.

CPU count format: "cpu: count=PROCESSORS:CORES:THREADS"
Example:
cpu: count=2:2:1 # 2 cpus with 2 cores per cpu

See the home page of the Bochs project at http://bochs.sourceforge.net
