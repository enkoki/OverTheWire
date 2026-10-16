> OverTheWire [Level 5-6](https://overthewire.org/wargames/bandit/bandit6.html)

### note to myself
`file` gives the  type of data of the file.
for eg human readable - ASCI, Unicode

`find` finds smth and used flags<br>
-type of file to find f stands for file<br>
-size 1033c is for 1033 bytes<br>
-executable

```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd inhere
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
```