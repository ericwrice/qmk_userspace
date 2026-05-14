qmk compile -kb crkbd/rev1 -km erice -e CONVERT_TO=blok
qmk json2c -o keymap.c keymap.json
qmk compile -kb boardsource/unicorne -km erice
qmk userspace-add -kb boardsource/unicorne -km erice