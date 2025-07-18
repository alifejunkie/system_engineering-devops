# 0x05 - Processes and Signals

This project explores how Linux handles processes and signals. It introduces key commands and scripting techniques for process management in Bash.

## 📚 Topics Covered

- PID (Process ID) management
- Listing and filtering system processes
- Infinite loops and sleep delays
- Killing processes with `kill`, `killall`, and `SIGKILL`
- Signal trapping with `trap`

## 🛠️ Tasks Overview

| Filename                   | Description |
|---------------------------|-------------|
| `0-what-is-my-pid`        | Displays the PID of the current script |
| `1-list_your_processes`   | Lists all running processes with hierarchy |
| `2-show_your_bash_pid`    | Filters to show only bash-related processes |
| `3-show_your_bash_pid_made_easy` | Lists bash PIDs using a different method (no `ps`) |
| `4-to_infinity_and_beyond`| Infinite loop that echoes every 2 seconds |
| `5-dont_stop_me_now`      | Stops the infinity loop using `kill` |
| `6-stop_me_if_you_can`    | Stops the loop using a method other than `kill` or `killall` |
| `7-highlander`            | Infinite loop with signal trap for `SIGTERM` |
| `67-stop_me_if_you_can`   | Sends `SIGTERM` to 7-highlander |
| `8-beheaded_process`      | Kills 7-highlander using `SIGKILL` |

## 🚀 How to Run

Make your scripts executable first:

```bash
chmod +x script_name
