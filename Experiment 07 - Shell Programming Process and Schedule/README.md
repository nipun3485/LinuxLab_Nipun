# Experiment 07 – Shell Programming, Process and Schedule

## Objective
To write shell scripts for file handling, looping, and text processing using shell commands and conditional execution.

## Commands Used
- `-e` – check if file exists
- `cat` – display file content
- `touch` – create a new file
- `for` loop – sequence iteration
- `{1..10}` – brace expansion
- `wc` – count lines, words, characters
- `$#`, `$1` – command-line arguments
- `chmod +x` – make scripts executable
- `./script.sh` – execute script

## Procedure
### Task 1 – File Existence Check
1. Created `file_check.sh` to check if a file exists using `-e`.
2. Displayed content or created a new file based on user input.

### Task 2 – Print Numbers from 1 to 10
1. Developed `print_1_to_10.sh` using a `for` loop with brace expansion.
2. Printed sequential numbers from 1 to 10.

### Task 3 – Count Lines, Words and Characters
1. Created `count_wc.sh` that accepts filename as command-line argument.
2. Used `wc -l`, `wc -w`, and `wc -m` to display line, word, and character count.
3. Handled missing arguments and non-existent files.

Screenshot of all outputs is saved as **output7.png**.

## Conclusion
This experiment helped in understanding file operations, loops, command-line arguments, and fundamental shell scripting techniques used in process scheduling and automation.
