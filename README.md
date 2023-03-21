# ADV360-PRO-ZMK

## TL;DR

1. Run `make`
2. Connect cable to left module
3. Press Mod + Hotkey 1 to attach left module in bootloader mode
4. Drag 'left' file onto left module
5. Wait until loaded and self-ejected
6. Repeat for right module (Mod + Hotkey 3)

```
Keys Order:
_    Mod
1    3
2    4
```

## To build Firmware in GitHub Actions

### Setup

1. Fork this repo.
2. Enable GitHub Actions on your fork.

### Build firmware

1. Push a commit to trigger the build.
2. Download the artifact.

## Local building in a container

### Setup

#### Software

Either Podman or Docker is required, Podman is preferred if both are present.\
Make is also required

### Cleanup

The built docker container and compiled firmware files can be deleted with `make clean`.

## Flashing firmware

[Quick Guide](https://kinesis-ergo.com/wp-content/uploads/Step-by-Step-Advantage360-Professional-Firmware-Installation-Instructions-KB360-PRO_v9-16-22.pdf)
[Full Manual](https://kinesis-ergo.com/wp-content/uploads/Advantage360-ZMK-KB360-PRO-Users-Manual-v12-1-22.pdf)

## Other support

Further support resources can be found on Kinesis.com
- https://kinesis-ergo.com/support/kb360pro/#firmware-updates
- https://kinesis-ergo.com/support/kb360pro/#manuals

