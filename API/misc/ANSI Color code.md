ANSI

| **Feature**            | **ANSI Code (C++/Python String)** | **Description**                                                           |
| ---------------------- | --------------------------------- | ------------------------------------------------------------------------- |
| **Reset All**          | `\033[0m`                         | Clears all formatting (color, bold, etc.). **Crucial to use at the end.** |
| **Bold / Bright**      | `\033[1m`                         | Makes the text brighter or bold.                                          |
| **Underline**          | `\033[4m`                         | Adds an underline to the text.                                            |
| **Foreground: Red**    | `\033[31m`                        | Sets the text color to Red.                                               |
| **Foreground: Green**  | `\033[32m`                        | Sets the text color to Green.                                             |
| **Foreground: Yellow** | `\033[33m`                        | Sets the text color to Yellow (often used for warnings).                  |
| **Foreground: Blue**   | `\033[34m`                        | Sets the text color to Blue.                                              |
| **Background: Red**    | `\033[41m`                        | Sets the background color to Red.                                         |
| **Background: Green**  | `\033[42m`                        | Sets the background color to Green.                                       |
| **Background: Yellow** | `\033[43m`                        | Sets the background color to Yellow.                                      |