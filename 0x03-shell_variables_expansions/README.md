# 0x03. Shell, init files, variables and expansions

This project covers Bash shell features such as aliases, shell variables, environment variables, expansions, arithmetic, and script execution basics.

## File Descriptions

| Script | Description |
|--------|-------------|
| `0-alias` | Creates an alias `ls` with value `rm *`. |
| `1-hello_you` | Prints `hello` followed by the current Linux user. |
| `2-path` | Adds `/action` to the end of the `PATH` variable. |
| `3-paths` | Counts the number of directories in the `PATH` variable. |
| `4-global_variables` | Lists all global (environment) variables. |
| `5-local_variables` | Lists all local variables, environment variables, and shell functions. |
| `6-create_local_variable` | Creates a local variable `BEST` with the value `School`. |
| `7-create_global_variable` | Creates a global (exported) variable `BEST` with the value `School`. |
| `8-true_knowledge` | Prints the result of 128 added to the value of the environment variable `TRUEKNOWLEDGE`. |
| `9-divide_and_rule` | Divides the value of environment variable `POWER` by `DIVIDE`. |
| `10-love_exponent_breath` | Raises the value of `BREATH` to the power of `LOVE`. |
| `11-binary_to_decimal` | Converts the binary value in `BINARY` env variable to decimal. |
| `12-combinations` | Prints all combinations of two lowercase letters, excluding `oo`. |
| `13-print_float` | Prints the value of `NUM` with two decimal places. |

## Requirements

- All scripts are written for `bash`
- Each script is exactly two lines long
- Scripts are executable and end with a new line
- No use of `&&`, `||`, or `;`

## How to Run

```bash
chmod +x <script>
./<script>
