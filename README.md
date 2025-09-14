## Hackintosh OpenCore EFI for DELL XPS13 9360
```
Model              DELL XPS13 9360
CPU                Intel Core i5-8250U
Memory             8G DDR3L 2133MHz
Graphics           Intel UHD Graphics 620
Audio              Realtek ALC256
Wi-Fi              DELL DW1560
Storage            WD SN550
Monitor            FHD 1920x1080
BIOS Verison       2.21.0
macOS Version      Ventura 13.7.8
OpenCore Version   1.0.5
```



## Unlock Cfglock

```
  setup_var 0x4de 0x00  // Disable CFG Lock
  setup_var 0x785 0x06  // Increase DVMT pre-allocated size to 192M For FHD version, it's also recommended setting to 192M
  setup_var 0x786 0x03  // Increase CFG Memory to maximum
```



## Credits

- [XPS-13-9360-Monterey-Hackintosh](https://github.com/danikpanik/XPS-13-9360-Monterey-Hackintosh)
- [DELL-XPS13-9360](https://github.com/SummerEmber/DELL-XPS13-9360)
- [DIY一台99.8%的人够用完美（黑苹果Windows）双系统小主机，附【黑苹果一键安装教程】60元完美网卡方案！](https://www.youtube.com/watch?v=DSxc5-kd3Uw)
