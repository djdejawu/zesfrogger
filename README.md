# ZesFrogger

## About

  ZesFrogger is a complex application to encrypt and decrypt DataFrog's Y2 v3 ZES file format.
  You can extract all files from ZES and recompile them back.

## Quick help
```
usage:
    zesfrogger --action encrypt/decrypt --path <path to file or directory>

ZES file converter for DataFrog Y2 v3.

    Convert ZES file into directory and directory with NES ROM, preview.png,
    meta1.txt and meta2.txt into one ZES file.

    Folder structure:
        \<romfile>.nes - original working NES ROM file (only 1),
        \preview.png - 256x240x4bpp PNG image for game preview,
        \meta1.txt - English game title name for menu list,
        \meta2.txt - Local game title name for menu list.

options:
  -h, --help            show this help message and exit
  --action {encrypt,decrypt}
                        only 2 actions is acceptable: default is "encrypt".
  --path PATH           path to directory or file
```

## Supported OS

1. Windows x64
2. Linux x64
3. macOS (todo)

## Donations
Eth: 0x0D34a9F39DB8fAAC97433eAf83Dc973be3D0A736
