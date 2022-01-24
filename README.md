# Borrar_Huellas

### Clear Event Logs with meterpreter.
```
clearev
```

### Clear Event Logs on Windows Machines.
```
Clearlogs.exe -sec
Delete clearlogs.exe
```

### Clear Event Logs On Linux Machines.
```
Kwrite var/log/messages
```

### Erase the command history.
```
 Show history > more~/.bash_history
 show history size > echo $HISTSIZE
 export HISTSIZE=0
```

### Shredding History File
```
shred -zu root/.bash_history > overwrite with 0
more /root/.bashhistory > see changes
```
