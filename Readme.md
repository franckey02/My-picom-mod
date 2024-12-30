![Captura de pantalla de 2024-12-30 18-49-51](https://github.com/user-attachments/assets/c41ccfe2-e489-4f5e-b10f-9500e47e74ef)
Bordes REDONDEADOS
# Compilacion y instalacion de picom Debian - Ubunutu y derivados
- source : https://github.com/jonaburg/picom
```
sudo apt install libxext-dev libxcb1-dev libxcb-damage0-dev libxcb-xfixes0-dev libxcb-shape0-dev libxcb-render-util0-dev libxcb-render0-dev libxcb-randr0-dev libxcb-composite0-dev libxcb-image0-dev libxcb-present-dev libxcb-xinerama0-dev libxcb-glx0-dev libpixman-1-dev libdbus-1-dev libconfig-dev libgl1-mesa-dev  libpcre2-dev  libevdev-dev uthash-dev libev-dev libx11-xcb-dev build-essential cmake meson ninja-build 
git clone https://github.com/jonaburg/picom
cd picom
meson --buildtype=release . build
ninja -C build
 ```
# To install the binaries in /usr/local/bin (optional)
```
sudo ninja -C build install
```
# Dot file
copiar picom.conf a ~/.config/picom or /home/$USER/config/picom
