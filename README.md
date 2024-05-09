# Repository for Chimera OS

## Usage

Add to `/etc/pacman.conf`

```ini
# For ChimeraOS specific packages
[chimera]
SigLevel = Optional TrustAll
Server = https://github.com/chenx-dust/chimera-repo/releases/download/$repo/
# For useful AUR packages
[chimera-extra]
SigLevel = Optional TrustAll
Server = https://github.com/chenx-dust/chimera-repo/releases/download/$repo/
```

## Acknowledgements

- ChimeraOS
- Linux kernel from 3003n
- Github Actions
