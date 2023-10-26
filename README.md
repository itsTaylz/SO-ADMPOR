# ADMPOR

This is the project was made with more 2 colleagues for our Operating Systems class. The goal was to make a program to simulate the administrative system of a port with multiple possible operations, using the C language, multiple processes to handle the operations and low level synchronization mechanisms like mutexes and semaphores.

This projects allowed me to learn not only a lot about the C language but also about low level systems programming, and C debugging skills and memory analysis using valgrind.

We successfully implemented all steps of the project obtaining a perfect score.

# Compilation

This project can be compiled using make:
```
$ make
```

For the correct compilation of the project is required to have a bin and obj directories, those can be created using
```
$ make folders
```

# Running

The project can be run passing a single configuration file as command line argument. An example configuration file is available in `config.txt`