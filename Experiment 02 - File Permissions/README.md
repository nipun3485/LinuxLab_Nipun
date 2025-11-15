# Experiment 02 – File Permissions

## Objective
To understand and apply different file permission operations in Linux using chmod, ls, and related commands.

## Commands Used
- `ls -l` – To view file permissions.
- `chmod g-r <file>` – Remove read permission for group.
- `chmod o-w <file>` – Remove write permission for others.
- `chmod u+x <file>` – Add execute permission for user.
- `touch` / `echo` – To create test files.

## Procedure
1. Created a test file named `permissions_test.txt`.
2. Checked the default permissions using `ls -l`.
3. Removed read permission for the group using `chmod g-r`.
4. Removed write permission for others using `chmod o-w`.
5. Added execute permission for the user using `chmod u+x`.
6. Verified the changes using `ls -l`.
7. Captured the output screenshot and saved it as `output2.png`.

## Conclusion
This experiment helped in understanding file permission structure in Linux and how to modify permissions using the chmod command.
