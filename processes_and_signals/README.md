# Shell, processes and signals

Bash scripts about PIDs, listing and finding processes, and sending and
handling signals with `kill`, `pkill` and `trap`.

| File | Description |
| --- | --- |
| `0-what-is-my-pid` | Display the script's own PID |
| `1-list_your_processes` | List all processes, user-oriented, with hierarchy |
| `2-show_your_bash_pid` | Show the process lines containing `bash` |
| `3-show_your_bash_pid_made_easy` | PID and name of `bash` processes, without `ps` |
| `4-to_infinity_and_beyond` | Print "To infinity and beyond" forever, every 2 seconds |
| `5-dont_stop_me_now` | Stop `4-to_infinity_and_beyond` with `kill` |
| `6-stop_me_if_you_can` | Stop `4-to_infinity_and_beyond` without `kill` or `killall` |
| `7-highlander` | Loop forever and print "I am invincible!!!" on SIGTERM |
| `67-stop_me_if_you_can` | Send SIGTERM to `7-highlander` |
| `8-beheaded_process` | Kill `7-highlander` with SIGKILL |
| `10-process_and_pid_file` | Write a PID file and handle SIGTERM, SIGINT and SIGQUIT |
| `manage_my_process` | Write "I am alive!" to `/tmp/my_process` every 2 seconds |
| `11-manage_my_process` | Init script to start, stop and restart `manage_my_process` |
