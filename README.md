svrenks-dark(based on Numix) is a modern flat theme with a combination of light and dark elements. It supports Gnome, Unity, XFCE and Openbox.

### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
dconf write /org/gnome/desktop/interface/gtk-theme "'svrenks-dark'"
dconf write /org/gnome/desktop/wm/preferences/theme "'svrenks-dark'"
dconf write /org/gnome/shell/extensions/user-theme/name "'svrenks-dark'"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "svrenks-dark"
xfconf-query -c xfwm4 -p /general/theme -s "svrenks-dark"
```

### Requirements

GTK+ 3.8 or above

Murrine theme engine

### Code and license

Report bugs or contribute at [GitHub](https://github.com/lbrfabio/svrenks-dark)

License: GPL-3.0+
