# falcond-profiles

All profiles are located in `/usr/share/falcond/profiles` as `.conf` files. The profiles are organized in device-specific subfolders:

- `handheld/`: Profiles optimized for handheld devices
- `htpc/`: Profiles optimized for Home Theater PCs
- Root directory: Default profiles that can be used when no profile mode is specified

## Configuration Files

### System Configuration
The `system.conf` file contains a list of proton system processes to be ignored by falcond.

### Game/Application Profiles
Examples of profile configurations:

```
name = "cs2"
scx_sched = lavd
scx_sched_props = gaming
performance_mode = true
vcache_mode = cache
```
```
name = "Cyberpunk2077.exe"
scx_sched = none
performance_mode = true
vcache_mode = freq
```
