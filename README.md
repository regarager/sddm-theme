# rega-sddm-theme
## Forked from [Keyitdev/sddm-astronaut-theme](https://github.com/keyitdev/sddm-astronaut-theme)

A theme for the [SDDM login manager](https://github.com/sddm/sddm).

- Screen resolution: 1080p
- Font: Open sans

### Preview

You can easily change how it looks in **[config](./theme.conf)**. 

### Dependencies

#### Arch, Void
```sh
sddm qt6-svg
```
#### Fedora
```sh
sddm qt6-qtsvg
```
#### OpenSUSE
```sh
sddm-qt6 qt6-svg
```

### Install

1. Clone this repository, copy fonts to `/usr/share/fonts/`:

   ```sh
   sudo git clone https://github.com/regarager/rega-sddm-theme.git /usr/share/sddm/themes/rega-sddm-theme
   sudo cp /usr/share/sddm/themes/rega-sddm-theme/Fonts/* /usr/share/fonts/
   ```

2. Then edit `/etc/sddm.conf`, so that it looks like this:

    ```sh
    echo "[Theme]
    Current=rega-sddm-theme" | sudo tee /etc/sddm.conf
    ```

### Credits

Based on the theme [`Sugar Dark for SDDM`](https://github.com/MarianArlt/sddm-sugar-dark) by **MarianArlt**.

### License

Distributed under the **[GPLv3+](https://www.gnu.org/licenses/gpl-3.0.html) License**.    
Copyright (C) 2022-2024 Keyitdev.
