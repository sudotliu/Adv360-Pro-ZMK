# ADV360-PRO-ZMK

```
Reminder of center key layout:
X    Mod
1    3
2    4
```

e.g. Bootloader left = Mod + Hotkey 1 = Hold press Mod + mid left center key
e.g. Bootlader right = Mod + Hotkey 3

## How to update after config changes 

1. Commit and push changes
2. Connect cable to left module
3. Press Mod + Hotkey 1 to attach left module in bootloader mode
4. Wait for [GitHub Actions to build artifacts](https://github.com/sudotliu/Adv360-Pro-ZMK/actions)
5. Drag 'left' artifact file onto left module
6. Wait until loaded and self-ejected (ignore OS warning "can't be read")
7. Repeat from step 2 for right module (bootloader = Mod + Hotkey 3)

### Cleanup

The built docker container and compiled firmware files can be deleted with `make clean`.

## Flashing firmware

- [Quick Guide](https://kinesis-ergo.com/wp-content/uploads/Step-by-Step-Advantage360-Professional-Firmware-Installation-Instructions-KB360-PRO_v9-16-22.pdf)
- [Full Manual](https://kinesis-ergo.com/wp-content/uploads/Advantage360-ZMK-KB360-PRO-Users-Manual-v12-1-22.pdf)

## Other support

Further support resources can be found on Kinesis.com
- https://kinesis-ergo.com/support/kb360pro/#firmware-updates
- https://kinesis-ergo.com/support/kb360pro/#manuals

