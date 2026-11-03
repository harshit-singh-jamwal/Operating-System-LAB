# Experiment 7b - I/O-Bound Process

## Aim
Create an I/O-intensive process and compare its behaviour with a CPU-bound process.

## Description
The program writes a line to `dummy.txt` once every second, opening and closing the file each time, so it spends most of its time waiting on disk I/O and sleep rather than using the CPU.

## Concepts Used
- I/O-bound processes
- File handling (`fopen`, `fprintf`, `fclose`)
- `sleep()`
- Comparing CPU usage with Experiment 7a

## Files
- [`exp7b.c`](exp7b.c)

## How to Run
```bash
gcc exp7b.c -o exp7b
./exp7b

# In another terminal
top -p $(pgrep exp7b)
```

## Output
```bash
Starting I/O task...
File operation done
File operation done
...
```

## Notes
- CPU usage stays near 0%, unlike Experiment 7a. Press `Ctrl+C` to stop.
