# ps 
```bash
  ps      # show processes of the current user
  ps -e   # show processes for all users
  ps -ef  # show processes for all users with all formatting
  ps -eo pid,ppid,cmd # show processes with a specific format
  ps -ef --forest # show as a tree
  ps -p 1234  # show a specific process
  ps -efH  #show threads
  ps -eHo pid,ppid,cmd --forest'
```


# pstree 
List the threads used by a specific application
pstree -p {pid}
