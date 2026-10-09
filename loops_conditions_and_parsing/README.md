# Shell, loops, conditions and parsing

Bash scripts practising `for`, `while` and `until` loops, `if`/`elif`/`else`
and `case` conditions, file test operators, `cut`, `read` with `IFS`, and
basic Apache log parsing with `awk`.

| File | Description |
| --- | --- |
| `1-for_best_school` | Display "Best School" 10 times with a `for` loop |
| `2-while_best_school` | Display "Best School" 10 times with a `while` loop |
| `3-until_best_school` | Display "Best School" 10 times with an `until` loop |
| `4-if_9_say_hi` | "Best School" 10 times, plus "Hi" after the 9th |
| `5-4_bad_luck_8_is_your_chance` | "bad luck" on 4, "good luck" on 8, "Best School" otherwise |
| `6-superstitious_numbers` | 1 to 20 with superstitions for 4, 9 and 17 (`case`) |
| `7-clock` | Hours 0-12, each followed by minutes 1-59 |
| `8-for_ls` | List the current directory, keeping only the part after the first dash |
| `9-to_file_or_not_to_file` | Report whether `school` exists, is empty, is a regular file |
| `10-fizzbuzz` | FizzBuzz from 1 to 100 |
| `11-read_and_cut` | Username, UID and home directory from `/etc/passwd` |
| `12-tell_the_story_of_passwd` | Tell a story for each `/etc/passwd` entry using `IFS` |
| `13-lets_parse_apache_logs` | Visitor IP and HTTP status from `apache-access.log` |
| `14-dig_the-data` | IP/status pairs grouped and sorted by occurrences |
| `apache-access.log` | Sample Apache access log used by tasks 13 and 14 |
