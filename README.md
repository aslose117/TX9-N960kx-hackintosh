# TX9-N960kx-hackintosh-黑苹果
目前系统版本12.6 理论上Ventura也可以

| | Spec | macOS 12.6 |
| ---: | :--- | :--- |
| ``Chipset`` | Mobile Intel HM570 | No issues |
| ``CPU`` | Intel Core i5-10600 processor, 6 Cores / 只能10th，11th和显无法驱动 | No issues |
| ``Memory`` | 32GB dual-channel  | No issues |
| ``GPU`` | Intel UHD Graphics 630 | No issues |
| ``dGPU`` | Nvidia 3070 | Disabled for macOS. |
| ``Screen`` | 15.6" QHD 240Hz, 2560 x 1440 IPS |  Only works at 60hz |
| ``WiFi`` | BCM943602CS Airport Card (BCM43602 802.11ac) 三天线 要自己加一根| Works natively. BCM94360CS2更合适 |
| ``Input & Output`` | USB 3.2 Gen 2 (USB-A) x3 | No issues |
| | USB-C 3.2 Gen 2  (Shared with Thunderbolt 3 Port) | No issues |
| | Thunderbolt 3 (USB-C) | 没有雷电设备没弄 |
| | HDMI |理论上可以 没测试 |
| | DP | 核显驱动的理论上可以 有一个是直连独显的肯定不行  |
| | SD card reader | 做了驱动 识别 但是有问题 |
| ``Sound`` | Realtek ALC256 | Working  |
| ``Microphone`` | | Working |
| ``Battery`` |  | 电量显示正常 但是续航不足2小时 |
| ``Keyboard`` |  | No issues. 键盘灯也没问题，神州貌似是存在bios里了，要到win下调整效果 |
| ``fans`` |  | No issues. 可以快捷键调成自定和max 试过以现有的clevo风扇控制驱动，但是没效果 |
| ``Touchpad`` |  | ps2模式工作 只能单指，貌似是tigerlake的i2c控制器还没驱动 voodooi2c团队在做|****
