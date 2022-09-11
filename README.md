# Klipper KingRoon Printers
![alt text](https://github.com/nehilo/Klipper-KingRoon-Printers/blob/main/pic/banner.png?raw=true)

# HOST Recommendation

Minimal system recommendation : [Orange Pi Zero 2](https://aliexpress.ru/item/1005001823662622.html?spm=a2g2w.productlist.0.1.7e875542pjctf0&sku_id=12000017777234288) or 
[Makerbase MKS PI](https://aliexpress.ru/item/1005004458622987.html?pdp_npi=2%40dis%21RUB%212%C2%A0560%2C96%20%D1%80%D1%83%D0%B1.%212%C2%A0356%2C03%20%D1%80%D1%83%D0%B1.%21%21%21%21%21%4021135c3f16582934765198182ea945%2112000029242151027%21sh&sku_id=12000029242151027&spm=a2g0o.store_pc_allProduct.8148356.35.491e673e0whoZK)

# Firmware build

```bash
cd ~/klipper
```
```bash
make menuconfig
```

***STM32F103***

![alt text](https://github.com/nehilo/Klipper-KingRoon-Printers/blob/main/pic/stm32.png?raw=true)

***GD32F103 / F303***

![alt text](https://github.com/nehilo/Klipper-KingRoon-Printers/blob/main/pic/GD32.jpg?raw=true)

```bash
make 
```

```bash
./scripts/update_mks_robin.py out/klipper.bin out/Robin_nano.bin
```

If you don`t want to use LCD and turn off cable from motherboard:


```bash
./scripts/update_mks_robin.py out/klipper.bin out/Robin_nano43.bin
```

# TMC UART Pin KingRoon 1.3 Motherboard ( FOR ADVANCED USERS )

UPDATE

# Basic Files Folder Configuration

```bash
 -printer.cfg
 -stepper.cfg
 -extruder.cfg
 -bed.cfg
 -fan.cfg
 -thermistor.cfg
 -macros
    macros.cfg
    printing.cfg
```

# Advanced Files Folder Configuration

```bash
 -printer.cfg
 -stepper.cfg
 -bltouch.cfg
 -tmc.cfg
 -extruder.cfg
 -bed.cfg
 -fan.cfg
 -thermistor.cfg
 -macros
    macros.cfg
    printing.cfg
```

You question and main information you can checked https://cutt.ly/5LHo4yC
