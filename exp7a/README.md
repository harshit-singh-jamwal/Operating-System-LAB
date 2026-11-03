# Experiment 7a - CPU-Bound Process

## Aim
Create a CPU-intensive process and observe its CPU utilization.

## Description
The program runs an infinite counting loop with no waiting and prints a message every 100 million iterations, keeping one CPU core fully busy.

## Concepts Used
- CPU-bound processes
- Monitoring CPU usage with `top`/`htop`

## Files
- [`exp7a.c`](exp7a.c)

## How to Run
```bash
gcc exp7a.c -o exp7a
./exp7a

# In another terminal
top -p $(pgrep exp7a)
```

## Output
```bash
CPU task running: 100000000
CPU task running: 200000000
...
```

## Notes
- Expect close to 100% usage of one core. Press `Ctrl+C` to stop.
