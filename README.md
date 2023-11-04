# QMK
Keymaps and setup for my keyboards

## QMK MSYS

Download and setup QMK MSYS
GitHub repo: https://github.com/qmk/qmk_distro_msys/

Download and setup QMK toolbox
GitHub repo: https://github.com/qmk/qmk_toolbox

Firmware files to be placed in:
%UserFolder%/qmk_firmware/keyboards/{brand}/{model}.....



## Build firmware:

QMK MSYS command to build a specific keymap:
```
qmk compile -kb {Path to keymap in firmware folder} -km {Name of the keymap}
```

Example command 
```
qmk compile -kb gmmk/pro/rev1/ansi -km GetCoding
```