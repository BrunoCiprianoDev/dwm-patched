# dwm-patched

Custom build of **dwm (Dynamic Window Manager)** focused on providing the lightest, fastest and most efficient graphical interface possible.

This project removes any kind of gadget, visual effect, compositor or unnecessary functionality, prioritizing **raw performance, low memory usage and full keyboard-driven control**.

The goal is to start a fully functional graphical environment using approximately **20MB of RAM**, keeping the system predictable, simple and extremely fast.

---

## Philosophy

This build strictly follows the *suckless* philosophy:

> Software that is simple, straightforward, readable and easy to maintain.

Nothing is added without real necessity.  
Every patch, shortcut and rule exists to reduce overhead and increase productivity.

---

## Key Features

- Extremely low memory usage  
- Fast startup  
- No compositor  
- No transparency  
- No animations  
- No heavy status bar  
- Keyboard-focused workflow  
- Essential layouts only  
- Clean and organized code  
- Easy to modify and recompile  

---

## Requirements

- Linux  
- Xorg  
- gcc  
- make  
- libX11  
- libXft  
- libXinerama (optional, for multi-monitor)

On Arch Linux:

```bash
sudo pacman -S xorg-server xorg-xinit libx11 libxft libxinerama base-devel
