# Linux
Record some common-use Linux Command Line

* <h3>Install yarn on Mac</h3>
```
(sudo) npm i -g yarn
```

* <h3>Cut out the first n lines of a file and store it in another file</h3>
```
head -n file_a > file_b
```

* <h3>Count the number of items under a directory</h3>
```
ls -l |grep "^-"|wc -l
```

* <h3>Look up the disk space taken up by the current directory</h3>
```
du -h
```

* <h3>Look up number of lines of a file</h3>
```
wc -l <file name>
```

* <h3>linux screen commands</h3>
```
echo $STY  # look up the current screen
screen     # start a screen
screen -ls # list all the screens
screen -S  # start screen with a name
```
* <h3>Install packages under a specific version of python</h3>
```
python3.7 -m pip install ..
```
* <h3>Change the command `python3` from the original default version to `python3.x`</h3>
```
alias python3=python3.x
```
