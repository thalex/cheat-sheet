# Commandline cheat-sheet

### Search recursively for a string inside files and directories 
```
grep -R 'string' dir/
```

### Download entire website w/ wget
```
wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla http://www.asdasdsaqd.com
```