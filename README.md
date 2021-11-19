# Minecraft (Flatpak)

### Resource Packs, Mods etc.

You can install these to `~/.var/app/com.mojang.Minecraft/.minecraft`.

### Gamescope
You can run with [Gamescope](https://github.com/Plagman/gamescope) by installing the Gamescope extension, and creating `gamescope.txt`  
Enter:  
```
flatpak install flathub com.valvesoftware.Steam.Utility.gamescope
touch ~/.var/app/com.mojang.Minecraft/.minecraft/gamescope.txt
```

Optionally to pass custom [Gamescope arguments](https://github.com/Plagman/gamescope#examples), add flags to `~/.var/app/com.mojang.Minecraft/.minecraft/gamescope.txt`

For example, to run at 1280x720 in fullscreen put `-w 1280 -h 720 -f` in `~/.var/app/com.mojang.Minecraft/.minecraft/gamescope.txt`  
Do not put `-- %command%`, that is for Steam.