This is a simple application intended to fade to black over a 5 second period. If you move your mouse during that time, it automatically destroys itself.

## Dependencies
- Gtk4-layer-shell
- Gtk4

## Usage
Run `./fade`. 

## Building
```
# Install build dependencies on fedora
sudo dnf install gtk4-devel gtk4-layer-shell-devel
# Build
gcc fade.c -o fade $(pkg-config --cflags --libs gtk4 gtk4-layer-shell-0)
```
