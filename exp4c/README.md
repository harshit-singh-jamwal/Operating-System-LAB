# Experiment 4c - Delete Lines Containing a Word

## Aim
Delete all lines containing a given word from one or more files.

## Description
The first argument is the word to search for; the remaining arguments are files. The script uses `shift` to drop the word from the argument list and then runs `sed -i` on each existing file to delete matching lines.

## Concepts Used
- `shift`
- Looping over `"$@"`
- `sed -i "/word/d"` for in-place deletion

## Files
- [`exp4c.sh`](exp4c.sh)

## How to Run
```bash
chmod +x exp4c.sh
./exp4c.sh hello a.txt b.txt
```

## Output
```bash
Deleted lines containing 'hello' from a.txt
Deleted lines containing 'hello' from b.txt
```

## Notes
- The files are modified in place - keep a backup before testing.
