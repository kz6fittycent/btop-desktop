# btop-desktop snap

[![btop-desktop](https://snapcraft.io/btop-desktop/badge.svg)](https://snapcraft.io/btop-desktop)

A desktop version of [btop](https://github.com/aristocratos/btop): btop in its own window with an app launcher icon. This repo only holds the snap. It's built from upstream btop, Ken VanDine's [btop-desktop](https://github.com/kenvandine/btop-desktop) window and VTE, and published straight to `latest/stable`.

It exists because of this [btop issue](https://github.com/aristocratos/btop/issues/407): desktop users wanted to launch btop from an icon.

## Install

```bash
sudo snap install btop-desktop
```

Optional, to see removable drives:

```bash
sudo snap connect btop-desktop:removable-media
```

## Notes

- Config lives in `~/snap/btop-desktop/common/.config/btop` (shared by every revision, so a refresh never loses it).
- Quit with `q` or just close the window. Theme and settings are saved either way (`snap/local/btop-session` handles the close).
- Just want btop in a terminal? See [btop](https://github.com/kz6fittycent/btop).

## Issues

Snap problems go [here](https://github.com/kz6fittycent/btop-desktop/issues). btop bugs go [upstream](https://github.com/aristocratos/btop/issues).

## License

Apache-2.0, same as btop.
