What Is This?
=============
The basic idea is to approximate the value of PI using the Monte-Carlo methods. The programs will generate random number pairs between 0 and 1 and will check whether those points are inside a unit circle. The value PI can be calculated using the equation,
```
 PI = (Total number of points inside the unit circle/Total number of tests) * 4
```

An approach using MPI and Fortran for the same problem can be found [here](https://github.com/ishanthilina/MPICH-Monte-Carlo-Pi-Calculation)
More Information
=============
* **serial.c** - A serial program (without pthreads to approximate the value of PI)
* **pthread.c** - A Parallel program using pthreads to approximate the value of PI
* **pthreadTimed.c** - Same as pthread.c but measures time taken for the operations.

Instructions for running each program is included in the source code documentation of each file.