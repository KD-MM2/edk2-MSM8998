# EDK2 UEFI Firmware For Snapdragon 835 (msm8998)

A broken but working EDK2 implementation for Snapdragon 835 platform.

中国人请看中文版
[Chinese version (中文版)](https://github.com/lumingyu0423/edk2-MSM8998/blob/master/README.zh.md)

## Resources

[Telegram group (recommended)](https://t.me/joinchat/MNjTmBqHIokjweeN0SpoyA)

[Discord group](https://discord.gg/XXBWfag)

QQ group: 697666196 (Never On-Topic)

[Useless documents](https://renegade-doc.readthedocs.io/en/latest/index.html)

## WARNING

**DO NOT EVER TRY TO PORT IT TO *SONY* DEVICES**

**YOUR UFS WILL BE WIPED CLEAN!!!**

## Supported devices

1. Moto Z2 Force (nash)
2. Xiaomi Mi6 (sagit)  
3. Xiaomi Mix2 (chiron) 
4. OnePlus 5 (cheeseburger)

## Dependencies

For Ubuntu 20.04:

```bash
sudo apt update
sudo apt upgrade
sudo apt install build-essential uuid-dev iasl git nasm gcc-aarch64-linux-gnu abootimg python3-distutils python3-pil python3-git
```

## Building

1.Clone this project (no need for recursive)

```bash
git clone https://github.com/lumingyu0423/edk2-MSM8998.git --depth=1
cd edk2-MSM8998
```

2.Build this project

```bash
bash build.sh --device DEVICE
```

3.Boot the image

```bash
fastboot boot boot_DEVICE.img
```

(DEVICE is the codename of your phone.)

## Credits



