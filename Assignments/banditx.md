# Bandit Level 8 to 9 Writeup

Author: [vedasree](https://github.com/vedasree2003)

Problem Page: [bandit8](https://overthewire.org/bandit/bandit8)

## List of Commands Used
```
ls
cat
sort
uniq

ls - list files in a directory
``data.txt

## Walkthrough
First i directly used uniq -u data.txt but realised that uniq will just check with the adjacent lines
So then i used sort data.txt | uniq -u data.txt and that just did the uniq without sorting so it actually sorted but since i didn't save it back in data.txt . So the next command will just be implemented to unsorted or actual data.txt. Finally after reading piping the commands i used are 
" sort data.txt | uniq -u " " cat data.txt | sort | uinq -u " both work i just tried different way

## Password
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

## Bash/Python script to automate the process
```'sort data.txt | uniq -u'
some-commands
```

## Suggested modifications [Optional]
What can you do to make this level more difficult. The inherent idea should be similar.
