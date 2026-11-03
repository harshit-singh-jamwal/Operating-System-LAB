# Experiment 6 - Memory Allocation

## Aim
Allocate a user-specified amount of memory and observe how it appears in the system's memory usage.

## Description
The program takes a size in MB, allocates it with `malloc`, writes to roughly one byte per page so the memory is actually used, and then stays alive so its memory consumption can be observed using system tools.

## Concepts Used
- Dynamic memory allocation (`malloc`)
- Command-line arguments (`argc`, `argv`)
- Page-by-page memory touching
- Monitoring with `top`, `free`, `ps`

## Files
- [`exp6.c`](exp6.c)

## How to Run
```bash
gcc exp6.c -o exp6
./exp6 100

# In another terminal
top -p $(pgrep exp6)
free -m
```

## Output
```bash
100 MB memory allocated.
Program is running... Press Ctrl+C to exit.
```

## Notes
- Press `Ctrl+C` to stop the program and free the memory.
- Use sizes below 2048 MB, since the size calculation uses a 32-bit `int`.
