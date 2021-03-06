# nvidia-system-monitor
<center>
    <img src="icon.png" alt="icon" width="256" height="256"/>
</center>

***
## Warning
The repository is outdated and will no longer be updated. Check out the new version [here](https://github.com/congard/nvidia-system-monitor-qt). The new version has significantly improved design, bug fixes and optimization.
***

Task Manager for Linux for Nvidia graphics cards

I wrote this program quickly enough, because it was urgently needed. All other functions (temperature, language, etc.) will be added in next versions

# Dependencies
wxWidgets is required for work. You must install (if using ArchLinux) `wxgtk3` package for work and `wxgtk2` for build

# Building
Execute:
`./make.sh`

The executable will be written to bin/nvidia-system-monitor. Note: you have to run it with `optirun bin/nvidia-system-monitor` on discrete GPU

# Installing
## Archlinux
PKGBUILD avaliable in AUR: [nvidia system monitor](https://aur.archlinux.org/packages/nvidia-system-monitor-git)

## Other
Run `sudo ./install.sh`. Note: you will not receive automatic updates if you install this way

# Config
Here example of simple config located in `~/.config/nvidia-system-monitor/config`:
```
# time in ms
updateDelay 500
graphLength 120000

#           gpu id  red  green  blue
gpuColor    0       0    0      255
gpuColor    1       0    255    0
gpuColor    2       255  0      0
```

# Screenshots
[Open SCREENSHOTS.md](SCREENSHOTS.md)

# Donate
[Open DONATE.md](DONATE.md)
