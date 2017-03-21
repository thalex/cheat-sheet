# pwn4food - commandline cheat-sheet

### grep recursive
```
grep -R 'string' dir/
```

### download entire website
```
wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla http://www.asdasdsaqd.com
```