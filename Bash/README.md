# README
## How to use
### `turn_on_off_monitors.sh`
1. Get monitors' names
```bash
xrandr | grep " connected"| cut -f1 -d ' '
```

Replace `MNT1` & `MNT2` variables.

2. Run bash script
```bash
bash turn_on_off_monitors.sh
```

--- 

### Reference
1. https://ubuntuqa.com/article/9536.html
