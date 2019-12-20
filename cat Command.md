### cat command syntax
The basic syntax is as follows:
```
cat filename

OR

cat > filename

OR

cat [options] filename

OR

cat file1
cat > file2
cat file3 | command
cat file4 | grep something
```

### Display A File With cat Command
```
cat filename
cat /path/to/file
cat /etc/passwd
```
### How To Combine Two Or More Files Using cat Command
You can combine two files and creates a new file called report.txt, enter:
```
cat score.txt names.txt > report.txt
cat report.txt
```

### Viewing All Files
```
cat *
```
To view only (PHP files) *.php files, enter:
```
cat *.php
```

