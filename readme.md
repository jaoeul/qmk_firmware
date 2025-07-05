1. make edits
```
qmk_firmware/keyboards/keychron/v6_max/iso_encoder/keymaps/svorak_a5/keymap.c
```

2. compile firmware
```
qmk compile -kb keychron/v6_max/iso_encoder -km svorak_a5
```

3. boot keychron v6 max in into bootloader by powercycling it while pressing ESC

4. flash firmware
```
qmk flash -kb keychron/v6_max/iso_encoder -km svorak_a5
```

5. done. new firmware should be running on keyboard
