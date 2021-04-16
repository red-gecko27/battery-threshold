## ⚠️ Deprecated

Kernel 5.4 brought the ability to set the battery charge threshold for some Asus laptops, by modifying the charge_control_end_threshold variable exposed under /sys/class/power_supply/BAT0/, 
see [[1][5]] [[2][6]].

---
---


# battery-threshold (Zenbook)

[![size][1]][2] [![license][3]][4]

Most newer Zenbooks supports specifying a charge stop threshold. This scripts is intended for UX430/UX530 desktop

![alt text](usage.png 'Usage')

`./battery_threshold --help`


## 💾 Install & Setup

1. `git clone https://github.com/red-gecko27/battery-threshold.git`
2. `cd battery_threshold`
3. `chmod 755 battery_threshold`
4. `cp battery_threshold /usr/bin`

[1]: https://img.shields.io/github/repo-size/red-gecko27/battery-threshold?maxAge=600
[2]: https://github.com/red-gecko27/battery-threshold 'GitHub repo size'
[3]: https://img.shields.io/github/license/red-gecko27/battery-threshold?maxAge=2592000
[4]: https://github.com/red-gecko27/battery-threshold/blob/master/LICENSE 'GitHub license'
[5]: https://github.com/torvalds/linux/commit/7973353e92ee1e7ca3b2eb361a4b7cb66c92abee
[6]: https://patchwork.kernel.org/project/platform-driver-x86/patch/20190813003023.6748-1-kristian@klausen.dk/