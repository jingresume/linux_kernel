# ebf-buster-linux

buster-linux

## 常用的命令

+ 编译dts

```bash
make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- npi_v7_defconfig
make ARCH=arm -j4 CROSS_COMPILE=arm-linux-gnueabihf- dtbs
```

+ dts编译输出路径

```bash
/arch/arm/boot/dts/imx6ull-seeed-npi.dtb
```

+ dts存放路径

```bash
/boot/dtbs/4.19.71-imx-r1/imx6ull-seeed-npi.dtb
```
