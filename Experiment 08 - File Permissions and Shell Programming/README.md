# Experiment 08 – File Permissions and Shell Programming

## Objective
To write shell scripts that demonstrate basic shell programming concepts such as file permission checks, string manipulation, pattern searching, and system information retrieval.

## Commands Used
- `-r`, `-w`, `-x` – check file permissions
- `${#str}` – string length
- `grep` – pattern search in files
- `date` – display date and time
- `who` – list logged in users
- `uptime -p` – system uptime
- `free -h` – memory usage
- `df -h` – disk usage
- `chmod +x` – make script executable
- `./script.sh` – run script

## Procedure
### Task 1 – Check File Permissions
- Script: `check_permissions.sh`
- Checks if file is readable, writable and executable using test operators `-r`, `-w`, and `-x`.

### Task 2 – String Operations
- Script: `string_operations.sh`
- Reads two user inputs and performs string length, concatenation, and comparison using shell variables.

### Task 3 – Search Pattern in a File
- Script: `search_pattern.sh`
- Takes filename and search pattern, uses `grep` to show matching lines.

### Task 4 – Display System Information
- Script: `system_info.sh`
- Displays current date, users, uptime, memory and disk usage.

All output screenshots are included as `output8.png`.

## Conclusion
This experiment demonstrates use of shell commands, conditional statements, string manipulation, pattern matching, and system monitoring in Linux. It improves understanding of automation using bash scripting.
