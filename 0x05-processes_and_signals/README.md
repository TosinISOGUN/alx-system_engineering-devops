# Processes and signals

## Table of Contents
| **Files** | **Description** |
| --- | --- |
| [0-what-is-my-pid](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/0-what-is-my-pid) | A Bash script that displays its own PID. |
| [1-list_your_processes](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/1-list_your_processes) | A Bash script that displays a list of currently running processes. |
| [2-show_your_bash_pid](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/2-show_your_bash_pid) | Based on the previous exercise, this is a Bash script that displays lines containing the `bash` word, thus allowing you to easily get the PID of your Bash process. |
| [3-show_your_bash_pid_made_easy](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/3-show_your_bash_pid_made_easy) | A Bash script that displays the PID, along with the process name, of processes whose name contain the word `bash`. | 
| [4-to_infinity_and_beyond](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/4-to_infinity_and_beyond) | A Bash script that displays `To infinity and beyond` indefinitely. |
| [5-dont_stop_me_now](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/5-dont_stop_me_now) | A Bash script that stops `4-to_infinity_and_beyond` process. |
| [6-stop_me_if_you_can](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/6-stop_me_if_you_can) | A Bash script that stops `4-to_infinity_and_beyond` process. |
| [7-highlander](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/7-highlander) | A Bash script that displays: (1) To `infinity and beyond` indefinitely. (2) With a `sleep 2` in between each iteration. (3) `I am invincible!!!` when receiving a `SIGTERM` signal. |
| [8-beheaded_process](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/8-beheaded_process) | A Bash script that kills the process [`7-highlander`](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/7-highlander). |
| [100-process_and_pid_file](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/100-process_and_pid_file) | A Bash script that: (1) Creates the file `/var/run/myscript.pid` containing its PID. (2) Displays `To infinity and beyond` indefinitely. (3) Displays `I hate the kill command` when receiving a `SIGTERM` signal. (4) Displays `Y U no love me?!` when receiving a SIGINT signal. (5) Deletes the file `/var/run/myscript.pid` and terminates itself when receiving a SIGQUIT or SIGTERM signal. |
| [101-manage_my_process](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/101-manage_my_process), [manage_my_process](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/manage_my_process) | A `manage_my_process` Bash script. |
| [102-zombie.c](https://github.com/TosinISOGUN/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/102-zombie.c) | A C program that creates 5 zombie processes. |


## Requirements & Environments
<img src="https://alx-apply.hbtn.io/brand_alx/share_image_2019.jpg" width="300" height="100" />

- Allowed editors: `vi`, `vim`, `emacs`.
- All files will be interpreted on `Ubuntu 20.04 LTS`.
- All files should end with a new line.
- A `README.md` file, at the root of the folder of the project, is mandatory.
- All Bash script files must be executable.
- The first line of all Bash scripts should be exactly `#!/usr/bin/env bash`.
- The second line of all Bash scripts should be a comment explaining what is the script doing.

## Authors & Credits
- [Oluwatomisin ISOGUN](https://github.com/TosinISOGUN)
