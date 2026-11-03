# Experiment 5 - String Length and Substring (Shell and C)

## Aim
Find the length of a string and extract a substring from it, once in shell and once in C.

## Description
Both programs read a string, print its length, then ask for a starting position and a number of characters and print the substring. `exp5.sh` uses shell parameter expansion (`${#str}` and `${str:start:length}`); `exp5.c` counts characters manually and prints them in a loop.

## Concepts Used
- String length `${#str}`
- Substring `${str:start:length}`
- C strings, `fgets`, `scanf`
- Manual length counting and loops in C

## Files
- [`exp5.sh`](exp5.sh)
- [`exp5.c`](exp5.c)

## How to Run
```bash
# Shell version
chmod +x exp5.sh
./exp5.sh

# C version
gcc exp5.c -o exp5
./exp5
```

## Output
For the input `HelloWorld`, start `1`, length `5`:

```bash
exp5.sh  ->  Substring: elloW
exp5.c   ->  Substring: Hello
```

## Notes
- The shell version uses **0-based** positions, while the C version uses **1-based** positions, so the same input gives different results.
