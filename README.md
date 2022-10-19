# esp32batch
## Flash
```
esptool --chip esp32 --port COM3 erase_flash
```
## Farmware
```
esptool --chip esp32 --port COM3 --baud 115200 write_flash -z 0x1000 file.bin
```
