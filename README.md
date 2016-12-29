# Little tool for set video wallpaper on Linux

# System requirements

- Xorg
- [shantz-xwinwrap](https://code.launchpad.net/xwinwrap) [DEB-packages](https://launchpad.net/~varlesh-l/+archive/ubuntu/ubuntu-tools/+packages?field.name_filter=xwinwrap&field.status_filter=published&field.series_filter=)
- mpv

# Install
```
git clone https://github.com/varlesh/video-wallpaper-linux.git
cp -R video-wallpaper-linux/mpv ~/.config/
cp video-wallpaper-linux/VideoWallpaper.desktop ~/.local/share/applications/
```
# Settings
Change options for your self on `~/.config/mpv/mpv.conf`. See man [mpv](https://mpv.io/manual/master/#options)

By default use russian lang/subs and options for intel GPU (vaapi and opengl)
