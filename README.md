# esp32batch
## Flash
```
esptool --chip esp32 --port COM3 erase_flash
```
## Farmware
```
esptool --chip esp32 --port COM3 --baud 115200 write_flash -z 0x1000 file.bin
```
## mpy-cross-v6
```
mpy-cross micropython precompiler
pip3 install mpy-cross-v6 <<< for micropython 1.19
python3 -m my_cross_v6 your.py <<< underscore!!
```
