### Dotfiles
![screenshot](screenshot.png)

- OS: Debian
- WM: awesome

#### Needed packages:
- pulseaudio - control volume
- alacritty - terminal
- redshift - night light
- compton (chjj) - window compositor
- scrot - screenshot tool
- rofi - app launcher
- acpid - subscribe acpi events
- cpufrequtils - cpu governor switcher (not used)
- mpd, mpc, ncmpcpp - music player daemon and ncmpcpp client
- nvim - text editor

#### Needed fonts:
- [Pacifico](https://fonts.google.com/specimen/Pacifico)
- [Luckiest Guy](https://fonts.google.com/specimen/Luckiest+Guy)
- [Ubuntu](https://design.ubuntu.com/font/)
- [Typicons](https://github.com/stephenhutchings/typicons.font)
- [Iosevka](https://github.com/be5invis/Iosevka)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono)
- [Icomoon by @elenapan](https://github.com/elenapan/dotfiles)

#### Notes:
The script `copy-dotfiles.sh` is used for copy dotfiles into git working directory. To make this setup work on your system you should copy config files manually.

Iosevka font must be patched with Font Awesome icons using Nerd Fonts patcher. It requires to make zsh theme draw it's decorations

Awesomewm config folder should contain file `secrets.lua` that is not included in this repository. Here is that file sample contents:
```
secrets = {
    lock_screen_password = "your password",
    openweather_key = "your token here",
    -- Your coords. Used by weather widget to determine your location
    lon = 12.34,
    lat = 12.34
}
```
