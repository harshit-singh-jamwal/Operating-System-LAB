# Experiment 3a - File/Directory Check with Argument Validation

## Aim
Extend the file/directory check by also handling the case where no argument is passed.

## Description
Works like Experiment 2, but additionally checks the argument count (`$#`) and asks the user to pass an argument if none is given.

## Concepts Used
- Argument count `$#`
- `-lt` comparison
- `if-elif-else` ladder

## Files
- [`exp3a.sh`](exp3a.sh)

## How to Run
```bash
chmod +x exp3a.sh
./exp3a.sh exp3a.sh
./exp3a.sh /home
./exp3a.sh
```

## Output
```bash
exp3a.sh is a file
/home is a Directory
Please Pass the Argument
```
