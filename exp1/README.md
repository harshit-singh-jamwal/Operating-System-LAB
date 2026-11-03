# Experiment 1 - Check if Argument is Zero

## Aim
Write a shell script that checks whether the argument passed to it is `0`.

## Description
The script reads the first command-line argument (`$1`) and compares it numerically with `0`. It prints `True` if the value is 0, otherwise `False`.

## Concepts Used
- Positional parameters (`$1`)
- `if-else` conditions
- Numeric comparison with `-eq`

## Files
- [`exp1.sh`](exp1.sh)

## How to Run
```bash
chmod +x exp1.sh
./exp1.sh 0
./exp1.sh 5
```

## Output
```bash
True
False
```

## Notes
- Passing a non-numeric argument (or none) makes the `[ ... -eq ... ]` test print an error.
