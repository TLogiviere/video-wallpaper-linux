# Little tool for set video wallpaper on Linux

# System requirements

- X11
- shantz-xwinwrap
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
