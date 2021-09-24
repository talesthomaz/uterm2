# uterm2
Terminator + Tmux:  multiplexing  ssh connections with Tmux control mode.


Terminator support the [tmux control mode](http://man7.org/linux/man-pages/man1/tmux.1.html#CONTROL_MODE).

Remote SSH example, starts tmux on remote host and displays tabs and splits in terminator:
```
terminator -M --remote example.org
terminator -M --remote localhost:22222
```

Local session:
```
terminator -M
```
