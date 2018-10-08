# Synchronise all panes in session

If your tmux window is synchronised into separate panes, press `Ctrl + B` and run the following tmux command:

```
setw synchronize-panes on
```

When you want to return to using tmux normally, run:

```
setw synchronize-panes off
```

*(Note: Don't forget to write "synchronize" instead of "synchronise")*