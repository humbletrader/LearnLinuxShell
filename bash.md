# What is bash ? 

# Bash job management : 
* CTRL+C - kills the job
* CTRL+Z - stops/suspends a running job but the program is still in memory
* jobs - listing of programs stopped or running
* fg - brings a stopped program to foreground ( starts again)
* bg - runs a program in background (the program will indeed run, it won't be stopped or suspended)
* & - starts a program directly into background
```bash
htop

CTRL-Z

jobs
[1]+ Stopped htop

bg 1

jobs
[1]+ Running htop

fg 1

jobs
[1]+ Stopped htop

```

# Output redirection 
