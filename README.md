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
### MPV config ###
Change options for your self on `~/.config/mpv/mpv.conf`

By default use options for intel GPU:
```
hwdec=vaapi
vo=opengl
```
See man [mpv video](https://mpv.io/manual/stable/#video) for Nvidia or AMD cards.

### Launcher ###
Used desktop file for launch videowallpaper.

By default use path for file `~/.config/mpv/video.mp4`

You can change path to file for your self on `~/.local/share/applications/VideoWallpaper.desktop`
