# Experiment 10 - Virtual Address Space of a Process

## Aim
Observe that every process has its own virtual address space by printing the address of a variable.

## Description
The program stores a variable, prints its PID and virtual address, and then keeps running so you can inspect it. Running multiple instances lets you compare their addresses and memory maps.

## Concepts Used
- Virtual memory
- `getpid()` and pointer printing with `%p`
- `/proc/<pid>/maps`
- ASLR

## Files
- [`exp10.c`](exp10.c)

## How to Run
```bash
gcc exp10.c -o exp10
./exp10

# In another terminal
cat /proc/<PID>/maps

# Run with ASLR disabled to compare addresses
setarch $(uname -m) -R ./exp10
```

## Output
Example (values will differ):

```bash
PID: 5120 | Address: 0x7ffd3a2b4c5c
```

## Notes
- The printed address is a **virtual** address, not a physical one.
- With ASLR enabled the address usually changes on every run.
