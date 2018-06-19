# Numix Dark
A modern flat theme with dark elements. It supports GNOME, Unity, Xfce and Openbox. Unlike our [main theme](https://github.com/numixproject/numix-gtk-theme) which support up to GTK 3.24, this theme is still stuck at 3.14 and below. We've just open sourced it so stay tuned for updates!

[![By The Numix Project](https://img.shields.io/badge/By-The%20Numix%20Project-f0544c.svg?style=flat-square)](https://numixproject.org/) &nbsp;![Supports GTK+ 3.14](https://img.shields.io/badge/GTK%2B-3.14-4a90d9.svg?style=flat-square)


### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Numix Dark"
gsettings set org.gnome.desktop.wm.preferences theme "Numix Dark"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Numix Dark"
xfconf-query -c xfwm4 -p /general/theme -s "Numix Dark"
```

### Requirements

GTK+ 3.6 or above

Murrine theme engine

### Code and license

Report bugs or contribute at [GitHub](https://github.com/numixproject/numix-gtk-theme)

License: GPL-3.0+
