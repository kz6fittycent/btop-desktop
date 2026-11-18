# btop-desktop
A desktop version of BTOP

### Reason
This repo and resulting snap was created due to this [issue](https://github.com/aristocratos/btop/issues/407). 
So, to provide a means for desktop users to launch `btop` from a desktop icon, this repo exists.

## Installing the snap
[![btop-desktop](https://snapcraft.io/btop-desktop/badge.svg)](https://snapcraft.io/btop-desktop)

 * **Install the snap**

    ```bash
    sudo snap install btop-desktop
    ```

 * **Connect the interface** (optional, to see removable drives)

    ```bash
    sudo snap connect btop-desktop:removable-media
    ```

The snap keeps its config in `~/snap/btop-desktop/current/.config/btop`. Quit with `q` or just close the window, your theme and settings are saved either way.

Just want btop in a terminal? See [btop](https://github.com/kz6fittycent/btop) (`sudo snap install btop`).
