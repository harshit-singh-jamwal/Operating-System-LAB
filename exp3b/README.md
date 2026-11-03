# Experiment 3b - Rename Files to Uppercase

## Aim
Write a shell script that renames the given files so their names become uppercase.

## Description
The script loops over all arguments. For every existing file it converts the name to uppercase using `tr` and renames the file with `mv`; otherwise it reports that the file does not exist.

## Concepts Used
- Looping over `"$@"`
- Command substitution `$(...)`
- `tr` for case conversion
- `mv` to rename

## Files
- [`exp3b.sh`](exp3b.sh)

## How to Run
```bash
chmod +x exp3b.sh
touch notes.txt
./exp3b.sh notes.txt missing.txt
```

## Output
```bash
notes.txt Changed
missing.txt does not exist
```

## Notes
- `notes.txt` becomes `NOTES.TXT`.
- A file whose name is already uppercase will make `mv` complain that source and destination are the same.
