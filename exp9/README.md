# Experiment 9 - Process Creation using fork() and wait()

## Aim
Demonstrate process creation with `fork()` and synchronisation between parent and child using `wait()`.

## Description
The program forks a child process. The child prints its PID, sleeps for 2 seconds and exits, while the parent waits for the child to terminate and then prints the terminated child's PID.

## Concepts Used
- `fork()`
- `wait()`
- `getpid()`
- Parent-child relationship

## Files
- [`exp9.c`](exp9.c)

## How to Run
```bash
gcc exp9.c -o exp9
./exp9
```

## Output
Example (PIDs will differ):

```bash
Parent Waiting for Child to terminate...
Child Running with PID: 4321
Child Exiting...
Parent Terminated Child PID: 4321
```
