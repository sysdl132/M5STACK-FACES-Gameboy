# English version

# Upload

use the "flash_download tools"from [Espressif](https://www.espressif.com/en/products/hardware/esp32/resources)

settings:

SPISpd:40MHZ|SPIMode:DIO|Flash size:16M|DoNotChgBin:true|COM:your port -OR- dev/tty.slabUSBtoUART|

Erase first!!!

bootloader.bin 0x1000
partitions.bin 0x8000
nesemu.bin 0x10000
(game).nes 0x100000

# 中文版

# 上传

使用“flash_download_tools”，[下载地址](https://www.espressif.com/zh-hans/products/hardware/esp32/resources)

设置：

SPISpd:40MHZ|SPIMode:DIO|Flash size:16M|DoNotChgBin:打勾|COM:自己的端口 -或- dev/tty.slabUSBtoUART|

先擦除！！！

bootloader.bin 0x1000
partitions.bin 0x8000
nesemu.bin 0x10000
(游戏).nes 0x100000
