## i7-4790k + ASUS-Z97-AR + RX580 + Fenvi FV-HB1200 + OC 0.8.9 + Ventura 13.2.1

### 配置单
| 配置     | 型号                                 |
| -------- | ------------------------------------ |
| 主板     | ASUS Z97-AR（BIOS版本：2801）        |
| CPU      | Intel Core i7-4790k（核显未开启）    |
| 显卡     | 铭瑄 RX 580 巨无霸 PLUS（8G 2304SP） |
| 声卡     | Realtek ALC892                       |
| 有线网卡 | Intel I218-V                         |
| 无线网卡 | 奋威FV-HB1200（博通 BCM94360CS2）    |
| SSD      | Kingston SV300S37A120G（SATA固态）   |

### 功能
- 睡眠唤醒正常
- 有线网卡正常
- 加了奋威FV-HB1200（博通 BCM94360CS2），隔空投送、通用控制正常
- 传感器正常
- 睿频正常 

### BUG
- 没有核显，随航黑屏、调用iPhone作为mac摄像头黑屏

### 注：
- 三码是在occ中随便生成的，使用efi时请自行再次切换
- usb定制用的usbports，这个kext带机型限制了，本来的utbmaps也在kexts文件夹中
  - usb定制包含了奋威网卡usb接口的内建，建议重新定制usb
  - usb定制可以看[b站大头蔡视频](https://www.bilibili.com/video/BV1m3411b7JP)
- 主板之前遭遇过睡眠唤醒重启的问题，禁用BlueToolFixup.kext后解决
- config中-v没开，安装时建议开启

![截屏2023-02-25 00 01 29](https://user-images.githubusercontent.com/44312535/221238022-233246a5-450e-4565-bda6-99530b2b6472.png)
