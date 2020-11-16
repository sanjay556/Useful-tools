# Useful-tools

# screen Linux/Unix utility for multiple windows on Linux/Unix
```
# Copy this file in your home directory 
.screenrc
# Run below command 
screen 

<Ctrl+a> d to detach from screen 

# Reattach to the screen run below command 
screen -xr 
```

https://www.gnu.org/software/screen/manual/screen.html

# tmux utility 
```
tmux new -s sanjay1

Next screen <ctrl>+N 
Previous screen <ctrl>+P
0-9 Numbered windows list 
All windows  <ctrl>+W

Detaching <ctrl>+D
Attaching screen attach-session -t sanjay1 

Splitting Screens horizontally <ctrl>+ "
Splitting Screens vertically <ctrl>+ %
Identifying Screen number <ctrl> +  Q


Session Commands

    S: List sessions.
    $: Rename current session.
    D: Detach current session.
    Ctrl+B, and then ?: Display Help page in tmux.

Window Commands

    C: Create a new window.
    ,: Rename the current window.
    W: List the windows.
    N: Move to the next window.
    P: Move to the previous window.
    0 to 9: Move to the window number specified.

Pane Commands

    %: Create a horizontal split.
    “: Create a vertical split.
    H or Left Arrow: Move to the pane on the left.
    I or Right Arrow: Move to the pane on the right.
    J or Down Arrow: Move to the pane below.
    K or Up Arrow: Move to the pane above.
    Q: Briefly show pane numbers.
    O: Move through panes in order. Each press takes you to the next, until you loop through all of them.
    }: Swap the position of the current pane with the next.
    {: Swap the position of the current pane with the previous.
    X: Close the current pane.


```

