#remind
Python script for reminding oneself of upcoming events by running a command.

```
remind [-sfph] TIME COMMAND...
    -s:      run synchronuous, don't use a detached process
    -f:      run immediately if time is in the past
    -p:      keep stdout and stderr for detached process
    -h:      print this help and exit
    TIME:    3min, or 17:00, etc..
    COMMAND: any shell command
```
