
`sync.sh`: for synchronizing changes in current directory with remote directory, e.g. `sync.sh ubuntu@host:/some/dir`

## XFCE4 defaults
```markdown
# Terminal: F1
xfce4-terminal

# Drop-Down Terminal: Shift+F8
xfce4-terminal --drop-down

# Notes: Ctrl+F8
mousepad

# Screen Shot: Shift+PrintScreen
/home/mindey/utils/xfce4screenshotter.py

# Record Screen: Ctrl+PrintScreen
xfce4-terminal --geometry=60x8+1400+800 -e "bash -c 'cd /home/mindey/Videos/shots/ && /home/mindey/Projects/System/utils/recordscreen.py; exec bash'"
```
