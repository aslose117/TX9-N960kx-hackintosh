# TX9-N960kx-hackintosh--
# TX9-N960kx-hackintosh-黑苹果
目前系统版本12.6 理论上Ventura也可以

| | Spec | macOS 13 compatibility |
| ---: | :--- | :--- |
| ``Chipset`` | Mobile Intel HM470 | No issues |
| ``CPU`` | Intel Core i7-10875H processor, 8 Cores / 16 Threads, 2.3GHz / 5.1GHz, 16MB Cache | No issues |
| ``Memory`` | 32GB dual-channel DDR4-2933MHz, up to 64GB | No issues |
| ``GPU`` | Intel UHD Graphics 630 | No issues |
| ``dGPU`` | Nvidia 3080 Max-Q (16GB GDDR6 VRAM) | Disabled for macOS. |
| ``Storage`` | NVMe CA5-8D1024 1TB NVMe M.2 SSD | No Issues  |
| ``Screen`` | 15.6" QHD 240Hz, 2560 x 1440 IPS |  Only works at 60hz for now. I'm trying to figure out what else I can do to get it working at a higher refresh rate. |
| ``Webcam`` | Windows Hello built-in IR HD webcam (1MP / 720P) |  No issues. Windows Hello is not supported in macOS |
| ``WiFi`` | BCM943602CS Airport Card (BCM43602 802.11ac) | Works natively. This card is from a 2015 MacBook Pro 15" and can be found for [fairly cheap on eBay](https://www.ebay.com/sch/i.html?_nkw=BCM943602CS). I had to run an extra antenna cable to get the best compatibility. However, you should be able to use the [BCM94360CS2](https://www.ebay.com/sch/i.html?_nkw=BCM94360CS2) from a 2015 MacBook Pro 13" (it only has two antenna cables). |
| ``Input & Output`` | USB 3.2 Gen 2 (USB-A) x3 | No issues |
| | USB-C 3.2 Gen 2 x2 (Shared with Thunderbolt 3 Port) | No issues |
| | Thunderbolt 3 (USB-C) | USB-C works (both USB 2 and 3 devices), Thunderbolt is untested. |
| | HDMI 2.1 | HDMI connected directly to Nvidia GPU and will not work in macOS |
| | UHS-III SD card reader | Untested, macOS shows card reader in System Information |
| ``Sound`` | Realtek ALC298 | Working after adjusting codec. At some point I will create a PR for the official AppleALC repo |
| ``Microphone`` | | Working after adjusting codec. |
| ``Battery`` | 80Wh | Seems to work just fine with decent battery life with ACPI patches. |
| ``Keyboard`` | Per key RGB Powered by Razer Chroma anti-ghosting backlit keyboard | No issues. I use a modified version of [BlvckBytes](https://githubfast.com/BlvckBytes) for [MenuBar app](https://githubfast.com/BlvckBytes/RazerControl/releases) to control Razer Blade keyboard and logo RGB lighting. Capslock light needs to have Karabiner Elements installed to see the light. |
| ``Touchpad`` | Glass touchpad (Microsoft Precision Touchpad) | No issues with proper ACPI patches and I2C kexts. Palm rejection isn't as good as I'd like, but it's not too big of deal. |****
