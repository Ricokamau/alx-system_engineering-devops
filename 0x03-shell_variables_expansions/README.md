# 0x03. Shell, init files, variables and expansions

## Description

This project is part of the ALX Software Engineering curriculum. It introduces various concepts related to shell initialization files, environment variables, local and global variables, and shell arithmetic. It also covers how to manipulate variables, perform operations using built-in shell features, and use scripting practices that comply with strict constraints.

---

## Requirements

- All scripts are exactly two lines long
- Scripts use `#!/bin/bash` as the shebang
- No usage of `awk`, `sed`, `bc`, `&&`, `||`, or `;`
- Files end with a newline
- Scripts are executable (`chmod +x filename`)
- Tested on Ubuntu 20.04 LTS

---

## Scripts

| Filename | Description |
|----------|-------------|
| `0-alias` | Creates an alias named `ls` that runs the command `rm *`. |
| `1-hello_you` | Prints `hello <username>` where `<username>` is the current logged-in user. |
| `2-path` | Appends `/action` to the existing `PATH` environment variable. |
| `3-paths` | Counts the number of directories listed in the `PATH` environment variable. |
| `4-global_variables` | Prints all global (environment) variables in the shell. |
| `5-local_variables` | Lists all local variables, environment variables, and shell functions available in the current shell. |
| `6-create_local_variable` | Creates a local variable named `BEST` with the value `School`. |
| `7-create_global_variable` | Creates a global (environment) variable named `BEST` with the value `School`. |
| `8-true_knowledge` | Prints the result of adding 128 to the value stored in the environment variable `TRUEKNOWLEDGE`. |
| `9-divide_and_rule` | Prints the result of dividing the value in `POWER` by the value in `DIVIDE`. |
| `10-love_exponent_breath` | Displays the result of `BREATH` raised to the power of `LOVE`, both being environment variables. |
| `11-binary_to_decimal` | Converts a binary number stored in `BINARY` to its decimal equivalent and prints the result. |
| `12-combinations` | Prints all combinations of two lowercase letters from `a` to `z` except `oo`. Output is in alphabetical order. |
| `13-print_float` | Prints a float with two decimal places using the value stored in the `NUM` environment variable. |

---

## Usage

To run a script:

1. Make it executable:
   ```bash
   chmod +x <filename>
