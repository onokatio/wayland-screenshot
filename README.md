# wayland-screenshot

## Install

- Archlinux(AUR)

```
$ yay -S wayland-screenshot
```

- Manual

```
$ sudo cp ./wayland-screenshot /usr/local/bin/
$ sudo cp ./wayland-screenshot.desktop /usr/local/share/applications/
```


## Usage

Select mode, then press OK.
Screenshots are saved to `~/Downloads/Screenshot_*`.

## Use floting window on sway

```
for_window [app_id="zenity"] floating enable
```
