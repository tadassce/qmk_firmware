# TS Planck Layout

Personal ever-evolving layout by @tadassce

```sh
# Setup
brew install qmk/qmk/qmk
qmk setup zsa/qmk_firmware -b firmware21

# Set default keyboard (optional)
qmk config user.keyboard=planck/ez/glow

# Set default keymap (optional)
qmk config user.keymap=tadassce

# Compile
make planck/ez/glow:tadassce

# Flash
qmk flash
```
