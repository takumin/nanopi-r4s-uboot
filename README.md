# nanopi-r4s-uboot

FriendlyElec NanoPi R4S U-Boot

# Build

```bash
$ make
```

# Flash

```bash
$ sudo dd if=$(BUILD_BASE_DIR)/u-boot/u-boot-rockchip.bin of=/dev/disk/by-id/$(MICRO_SD_DEV_ID) seek=64
```
