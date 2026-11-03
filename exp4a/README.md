# Experiment 4a - Total Working Time of a User

## Aim
Display the logged-in users and calculate the total time a chosen user has been working since login.

## Description
The script shows the output of `who`, asks for a username, extracts that user's login time with `awk`, and subtracts it from the current time (both in seconds) to print the total working time in hours and minutes.

## Concepts Used
- `who` command
- `awk` for field extraction
- `date -d` and `date +%s`
- Shell arithmetic `$(( ))`
- `read -p` for input

## Files
- [`exp4a.sh`](exp4a.sh)

## How to Run
```bash
chmod +x exp4a.sh
./exp4a.sh
```

## Output
Output depends on the users currently logged in, for example:

```bash
Enter username: gg
Login time: 2026-11-03 09:15
Total working time: 3 hours 20 minutes
```

## Notes
- If the username is not logged in, the script prints `User is not currently logged in.`
