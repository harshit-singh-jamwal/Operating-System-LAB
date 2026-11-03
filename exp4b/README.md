# Experiment 4b - Print Lines Between Two Line Numbers

## Aim
Display the lines of a file that lie between a given start line and end line.

## Description
The script takes a filename, a start line and an end line, and prints that range using `sed -n`.

## Concepts Used
- Multiple positional parameters
- `sed -n 'start,endp'`

## Files
- [`exp4b.sh`](exp4b.sh)

## How to Run
```bash
chmod +x exp4b.sh
./exp4b.sh sample.txt 2 5
```

## Output
Prints lines 2 to 5 of `sample.txt`.

## Notes
- Usage: `./exp4b.sh filename start_line end_line`
