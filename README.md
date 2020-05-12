# wayland-screenshot

## Depends

- grim
- slurp
- zenity
- jq

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

Run `wayland-screenshot.desktop` from menu entry, or run `wayland-screenshot` on terminal.
Select mode, then press OK.
Screenshots are saved to `~/Downloads/Screenshot_*`.

![](/Screenshot_2020-05-13_01:45:50.png)

## Use floting window on sway

```
for_window [app_id="zenity"] floating enable
```
