# Loops, conditions and parsing
Some of the key concepts treated in this project is **Shellcheck**.

[Shellcheck](https://alx-intranet.hbtn.io/rltoken/joK6l_yEZ9N7T0GQ1RDjLA) is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about.

`Shellcheck` is available on the school’s computers. If you want to use it on your own computer, here is how to [install it](https://alx-intranet.hbtn.io/rltoken/jbz0_-i3TV3WpKgxhyrtpA).

**Here are some examples;**

Not passing `Shellcheck`:

<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/Vxotqyj.png" width="500" height="250" />

Passing `Shellcheck`:

<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/251/ubHWxDU.png" width="700" height="200" />

For every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code `SC2034`, you can browse [here for more information.](https://alx-intranet.hbtn.io/rltoken/dxp49_rfO4_9Yjtcg59exg)
 
## Table of Contents
| **Files** | **Description** |
| --- | --- |
| 1-for_best_school | a Bash script that displays `Best School` 10 times (must use the `for` loop (`while` and `until` are forbidden)). |
| 2-while_best_school | a Bash script that displays Best School 10 times (must use the `while` loop (`for` and `until` are forbidden)). |
| 3-until_best_school | a Bash script that displays Best School 10 times (must use the `until` loop (`for` and `while` are forbidden)). |
| 4-if_9_say_hi | a Bash script that **displays `Best School` 10 times, but for the 9th iteration, displays `Best School` and *then* `Hi` on a new line** (must use the `while` loop and `if` statement (`for` and `until` are forbidden)). |
| 5-4_bad_luck_8_is_your_chance | a Bash script that loops from 1 to 10 and: **displays `bad luck` for the 4th loop iteration, displays `good luck` for the 8th loop iteration, displays `Best School` for the other iterations**. (must use the `while` loop and (`for` and `until` are forbidden)) and `if`, `elif` and `else` statements. |
| 6-superstitious_numbers | a Bash script that displays numbers from 1 to 20 and: **displays `4` and then `bad luck from China` for the 4th loop iteration, displays `9` and then `bad luck from Japan` for the 9th loop iteration, displays `17` and then `bad luck from Italy` for the 17th loop iteration**. (must use the `while` loop (`for` and `until` are forbidden)) the use of `case` statement is not allowed. |
| 7-clock | a Bash script that displays the time for 12 hours and 59 minutes. |
| 8-for_ls | a Bash script that displays: **The content of the current directory, In a list format, Where only the part of the name after the first dash is displayed (refer to the example)** |
| 9-to_file_or_not_to_file | a Bash script that gives you information about the `school` file. |
| 10-fizzbuzz | a Bash script that displays numbers from 1 to 100. |
| 100-read_and_cut | a Bash script that displays the content of the file `/etc/passwd`. |
| 101-tell_the_story_of_passwd | a Bash script that displays the content of the file `/etc/passwd`, using the `while` loop + IFS. |
| 102-lets_parse_apache_logs | a Bash script that displays the visitor IP along with the [HTTP status code](https://alx-intranet.hbtn.io/rltoken/7de-UBmf8xgwH1iSwzX1MA) from the Apache log file. |
| 103-dig_the-data | a Bash script that groups visitors by IP and HTTP status code, and displays this data. |


## Requirements & Environments
<img src="https://alx-apply.hbtn.io/brand_alx/share_image_2019.jpg" width="300" height="100" />

- Allowed editors: `vi`, `vim`, `emacs`.
- All files will be interpreted on `Ubuntu 20.04 LTS`.
- All files should end with a new line.
- A `README.md` file, at the root of the folder of the project, is mandatory.
- All your Bash script files must be executable.
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`.
- The second line of all Bash scripts should be a comment explaining what is the script doing.

## Authors & Credits
- [Oluwatomisin ISOGUN](https://github.com/TosinISOGUN)
