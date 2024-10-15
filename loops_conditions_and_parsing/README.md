# Loops, Conditions, and Parsing

This project contains Bash scripts that demonstrate various loops, conditions, and parsing techniques.

## Scripts

1. `1-for_best_school`: Displays "Best School" 10 times using a for loop.
2. `2-while_best_school`: Displays "Best School" 10 times using a while loop.
3. `3-until_best_school`: Displays "Best School" 10 times using an until loop.
4. `4-if_9_say_hi`: Displays "Best School" 10 times, but for the 9th iteration, displays "Best School" and then "Hi" on a new line.
5. `5-4_bad_luck_8_is_your_chance`: Loops from 1 to 10 and displays different messages for specific iterations.
6. `6-superstitious_numbers`: Displays numbers from 1 to 20 and shows superstitious messages for certain numbers.
7. `7-clock`: Displays the time for 12 hours and 59 minutes.
8. `8-for_ls`: Displays the content of the current directory in a specific format.
9. `9-to_file_or_not_to_file`: Gives information about the school file.
10. `10-fizzbuzz`: Displays numbers from 1 to 100 with FizzBuzz rules.
11. `11-read_and_cut`: Displays the content of the file /etc/passwd in a specific format.
12. `12-tell_the_story_of_passwd`: Displays the content of /etc/passwd as a story.
13. `13-lets_parse_apache_logs`: Displays visitor IP along with the HTTP status code from the Apache log file.
14. `14-dig_the-data`: Groups visitors by IP and HTTP status code from the Apache log file.

## Usage

To run any script, use the following format:

```
./script_name
```

For example:

```
./1-for_best_school
```

Make sure to make the scripts executable using `chmod +x script_name` before running them.

## Requirements

- All scripts are interpreted on Ubuntu 20.04 LTS.
- All files end with a new line.
- All scripts pass Shellcheck (version 0.7.0) without any errors.
- The first line of all scripts is `#!/usr/bin/env bash`.
- The second line of all scripts is a comment explaining what the script does.
