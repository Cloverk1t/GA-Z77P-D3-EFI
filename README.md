# GA-Z77P-D3 OpenCore
GA-Z77P-D3 OpenCore EFI. Perfect for macOS 10.14.6 & 10.15.5 (Catalina)

| 硬件 | 型号 |
| ----| ---- |
| CPU | Intel Xeon E3 1230 V2 |
| 显卡 | Sapphire Radeon RX 560D |
| 声卡 | Realtek ALC 887 |
| 网卡 | Realtek RTL 8111 |
#### 提示
有需要使用 `M.2 NVMe` 固态硬盘的同学可以刷入我修改的 [Z77PD3.F8e.NVME.rom](https://github.com/cloverkits/GA-Z77P-D3-EFI/blob/master/Z77PD3.F8e.NVME.rom?raw=true) BIOS 固件，仅添加了 `NVMe` 驱动支持
MD5 (Z77PD3.F8e.NVME.rom) = 4347dd2cb3b067c3194a15d94a1d8b93

#### 已知问题
- ~~在 macOS Catalina Beta 下唤醒冻屏~~

在 `BIOS` 中关闭 `Serial Port` 可以解决 `macOS Catalina` 唤醒冻屏的问题
