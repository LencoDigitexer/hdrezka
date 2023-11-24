# ERRORS

```bash
(env) lain@copland:~/github/hdrezka$ python main.py 

qt.qpa.plugin: Could not load the Qt platform plugin "xcb" in "" even though it was found.
This application failed to start because no Qt platform plugin could be initialized. Reinstalling the application may fix this problem.

Available platform plugins are: wayland, linuxfb, xcb, offscreen, minimalegl, vnc, wayland-egl, minimal, vkkhrdisplay, eglfs.

Аварийный останов
```

## INSTALL PACKAGES

```bash
sudo apt-get install '^libxcb.*-dev' libx11-xcb-dev libglu1-mesa-dev libxrender-dev libxi-dev libxkbcommon-dev libxkbcommon-x11-dev
```

