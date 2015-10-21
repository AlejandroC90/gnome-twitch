# ![](/data/icons/hicolor/48x48/apps/gnome-twitch.png) GNOME Twitch
GNOME Twitch app for watching Twitch on your GNU/Linux desktop. Enjoy your favourite streams without
the hassle of flash or the web.

## Install
### Dependencies
* meson >= 0.26.0 (install only)
* ninja (install only)
* gtk+-3.0 >= 3.16
* libsoup
* json-glib
* gstreamer-1.0
* gst-libav
* gst-plugins-base
* gst-plugins-good
* gst-plugins-bad
* gst-plugins-ugly
* clutter-gst
* clutter-gtk

### From source
```
mkdir build
meson . build
cd build
mesonconf -Dprefix=/usr
ninja install
```
#### Post install
```
glib-compile-schemas /usr/share/glib-2.0/schemas
update-desktop-database -q
gtk-update-icon-cache -q -t -f /usr/share/icons/hicolor
```
### Distro packages
* [Arch linux](https://aur4.archlinux.org/packages/gnome-twitch-git/)
* [Fedora](https://copr.fedoraproject.org/coprs/ippytraxx/gnome-twitch/)
* [Ubuntu (courtesy of GetDeb.net)](http://www.getdeb.net/app/GNOME%20Twitch)

## Screenshots
![](/data/screenshots/scrot_streams.png?raw=true)
![](/data/screenshots/scrot_games.png?raw=true)
![](/data/screenshots/scrot_player.png?raw=true)
