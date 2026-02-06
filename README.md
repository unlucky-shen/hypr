# hypr

My hyprland config, with vague-theme colorscheme

### If on NVIDIA GPUs, add the below to the top for `hyprland.conf`,
```
env = LIBVA_DRIVER_NAME,nvidia
env = __GLX_VENDOR_LIBRARY_NAME,nvidia
env = ELECTRON_OZONE_PLATFORM_HINT,auto
env = NVD_BACKEND,direct
env = XDG_SESSION_TYPE,wayland
env = GBM_BACKEND,nvidia-drm
cursor {
    no_hardware_cursors = true
}
```

### To-Do List

- [ ] Change wofi to rofi-wayland
- [ ] Change waybar to quickshel
- [ ] Configure Fastfetch
