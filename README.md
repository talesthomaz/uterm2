# uterm2

It's a linux terminal with support of Tmux control. 

Terminator + Tmux:  tmux do render panes/tabs in a single ssh connection. 

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

Note:
* For now it's expecting a tmux session named terminator
```
1. On the server side do create a tmux session named terminator
tmux new -s terminator
```
