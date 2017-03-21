# Commandline cheat-sheet

### Search recursively for a string inside files and directories 
```
grep -R 'string' dir/
```

### Download entire website w/ wget
```
wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla http://www.asdasdsaqd.com
```

### Custom convert any video format to GIF
```
ffmpeg -i video.mp4 -vf scale=400:-1 -r 3 -f image2pipe -vcodec ppm - | convert -delay 5 -loop 0 - video.gif | convert -layers Optimize - video.gif
```

### Connect via SSH and send commands to Server (commands in bash file)
```
ssh user@server -p 22 'bash -s' < cmd.sh
```

### See all strings in any file
```
strings FILE
```

### Search for STRING in all strings of a file
```
strings FILE |gre STRING
```
