# Experiment 06 – Shell Script Programs (Palindrome, GCD/LCM, Sorting)

## Objective
To write shell scripts for checking palindrome numbers, calculating GCD and LCM of two numbers, and sorting a list of numbers in ascending and descending order.

## Commands Used
- `read` – Accept user input
- `while` loop – Iterate for digit operations
- `if` – Conditional branching
- `printf` – Format output
- `sort -n`, `sort -nr` – Numeric sorting
- `chmod +x` – Make scripts executable
- `./script.sh` – Execute a script

## Procedure
### Task 1 – Palindrome Number Check
1. Created `palindrome.sh` to reverse a number using a while loop.
2. Compared reversed number with original to determine if it is a palindrome.
3. Saved output in `output6_1_palindrome.png`.

### Task 2 – GCD & LCM Calculation
1. Wrote `gcd_lcm.sh` implementing the Euclidean algorithm.
2. Calculated GCD using repeated remainder operations.
3. Computed LCM using the formula `(a*b)/GCD`.
4. Saved output in `output6_2_gcd_lcm.png`.

### Task 3 – Sorting Numbers
1. Created `sort_numbers.sh` to take an array of numbers as input.
2. Used `sort -n` for ascending and `sort -nr` for descending order.
3. Saved output in `output6_3_sorting.png`.

## Conclusion
This experiment demonstrates basic to intermediate level shell scripting concepts including loops, conditionals, numeric operations, array handling, and sorting utilities.
