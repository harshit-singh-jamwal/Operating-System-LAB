# Experiment 2 - File or Directory Check

## Aim
Write a shell script that tells whether the given argument is a file, a directory, or does not exist.

## Description
The script tests the first argument using `-f` (regular file) and `-d` (directory) and prints the matching message.

## Concepts Used
- File test operators `-f` and `-d`
- `if-elif-else` ladder

## Files
- [`exp2.sh`](exp2.sh)

## How to Run
```bash
chmod +x exp2.sh
./exp2.sh exp2.sh
./exp2.sh /home
./exp2.sh nothing
```

## Output
```bash
exp2.sh is a file
/home is a directory
nothing does not exist
```
