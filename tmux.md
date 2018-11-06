# Tmux commands

## Shortcuts

### Managing tmux sessions

| Action | Command | Shortcut |
|:-------|:---------|:-------------------|
| start a new session | tmux new  | ^b : new |
| | tmux new-session | ^b : new-session | 
| | tmux new -s sessionName | ^b : new -s <sessionName> |
| detach from current session | tmux detach | ^b d |
| attach to an existing session | tmux attach | |
| | tmux a -t sessionName | |
| list sessions | tmux ls | ^b s |
| rename session | tmux rename-session -t <oldName> <newName> | ^b $ |
| kill session | tmux kill-session -t <sessionName> | | 

### Managing tmux windows

| Action | Command | Shortcut |
|:-------|:---------|:-------------------|
| create new window |   | ^b c |
| list windows in current session | tmux list-windows | ^b w |
| rename current window | tmux rename-window <newWindowName> | ^b , |
| kill window |  | ^b & |
| move window to other session | tmux move-windos -s <sourceSession>:<sourceWindow> -t <targetSession>:<targetWindow>

### Managing tmux panes

| Action | Command | Shortcut |
|:-------|:---------|:-------------------|
| new vertical pane |   | ^b % |
| new horizontal pane | | ^b " |
| list panes for current window | tmux list-panes |  |
| show pane numbers | | ^b q |
| kill current pane | | ^b x |
| toggle minimize / masimize | | ^b z |
| resize pane | | |

### Other 
| Action | Command | Shortcut |
|:-------|:---------|:-------------------|
| show time |  | ^b : t |
| capture output | | ^b [ //enter copy mode   ^ space //starts the selection move cursor with arrow keys and/or pageup/pagedown keys ^ w      //copies selection to buffer(0) ^b:save-buffer ~/out_file |
