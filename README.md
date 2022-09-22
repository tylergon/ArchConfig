# Configuration

Thoughts:
- Create a YAML named something like "colours" which gets used to instantiate environment variables specifying colour codes for a bunch of colours that can be re-used throughout the system...  

## Main Configuration
COMPOSITOR:	picom-git
- WM: BSPWM
- Keybinds: SXHKD
- HUD: PolyBar
  - Font: Iosevka
- Terminal : Alacritty
- Wallpaper : Nitrogen
- GTK Theme
  - Dark: XXX
  - Light: Solarized Light
- Audio: PulseAudio. GUI: Pavu Control, CLI: pactl 
- Notification Daemon: Dunst
- Brightness: Brillo (brightnessctl, xbacklight)

lightdm
web-greeter or nody-greeter
play music -> MPD

random : acpi, acpid, acpi-call


### Awesome WM
AwesomeWM
Beautiful library for theming (& wallpaper)
htps://github.com/rxyhn/yoru


### Terminal Emulator:
**Application:** Alacritty
**Theme:** Hyper Snazzy
**Font:** JetBrains Mono

### Fonts:
Directory: /usr/local/share/fonts

**Terminal**: JetBrains Mono. MonoLisa(?).
**Primary**: Ubuntu
**Icons**: Iosevka Nerd Font
-  Use AestheticIosevka from Yoru AwesomeWM repo

### TODO:
- add a lightdm.conf file to this repository

## Installations:
alacritty
adwaita
brillo
bswpm
curl
discord (?)
dotnet setup MonkerS
	dotnet-host 6.0.9.sdk109-1
	dotnet-runtime "
dunst
neovim
firefox
gimp
gtk stuff
htop
insomnia
mono
nvm
network manager
nitrogen
pavucontrol (?)
pipewire-pulse
ranger
sxhkd
web-greeter
wayland
zsh
