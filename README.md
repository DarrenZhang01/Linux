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
