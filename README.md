Numix Dark is a modern flat theme and dark variant of Numix. It supports Gnome, Unity, XFCE and Openbox.

Numix Dark is a part of the [Numix Project](http://numixproject.org).

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

Report bugs or contribute at [GitHub](https://github.com/shimmerproject/Numix)

License: GPL-3.0+
