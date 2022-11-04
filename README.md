# hyprland-persistent-workspaces
Quick 'n dirty workaround to have persistent workspaces on hyprland!

## Mechanism
This script works by opening an arbitrary window with a custom title and creating custom rules for it in `hyprland.conf`. The window is made invisible and unfocusable.
This allows every workspace to stay open whether or not any program appears to be open.

## Usage
```python hyprland-persistent-workspaces.py```

Press [Enter] to preserve the default config.

The generated config can be appended into your `hyprland.conf`
