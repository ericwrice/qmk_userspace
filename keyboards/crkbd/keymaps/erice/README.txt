# Build C File
# In key C:\Users\Eric\qmk_firmware\keyboards\crkbd\keymaps\ewr
qmk json2c -o keymap.c keymap.json
# in qmk_firmware
qmk flash -kb crkbd/rev1 -km ewr -e CONVERT_TO=blok
