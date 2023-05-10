[English](README.md)|[简体中文](自述文件.md)|[繁體中文](繁體中文.md)
--|--|--

# Yours
Your own usual rEFInd's sign.
- You can
- - ✏️set ___your profile___;
- - ✏️set ___device___;
- - ✏️set ___your name___.

- It is based on [rEFInd Boot Manager](http://www.rodsbooks.com/refind/) from Roderick W. Smith, with [grub2-filemanager
](https://github.com/a1ive/grub2-filemanager) built-in.

- - So you can boot .iso files from internal SSD by using [grub2-filemanager
](https://github.com/a1ive/grub2-filemanager) from [a1ive](https://github.com/a1ive).

- Here are [icons](https://github.com/M-L-P/icons) for You.

## 💻️Preview👀

<details>
<summary>🖱️Click to Unfold to see🖱️</summary>
<img src="README/B.big.png">
<img src="README/B.small.png">
<img src="README/M.big.png">
<img src="README/M.small.png">
<img src="README/1080p.B.big.png">
<img src="README/1080p.B.small.png">
<img src="README/1080p.M.big.png">
<img src="README/1080p.M.small.png">

</details>


## 🧭Guide⬇️

<details>
<summary>🖱️Click to Unfold to see🖱️</summary>

### For UEFI Firmware
If your device meets the requirements,
- 64bit UEFI supported;
- GPU/vBIOS UEFI supported;

You should use [Yours-UEFI](https://github.com/M-L-P/Yours-UEFI).

### For Legacy BIOS
Else,
- NOT supporting 64bit UEFI,
- - 32bit UEFI supported;
- - Only Legacy BIOS without UEFI supported;
- GPU/vBIOS UEFI not supported; (See the picture)

![image](https://user-images.githubusercontent.com/69227436/213923710-120c5a02-30ea-4005-b2fe-c8e9adc7b6d7.png)

You should use [Yours-LegacyBIOS](https://github.com/M-L-P/Yours-LegacyBIOS).

### For Hyper-V
Download .vhdx from [Releases](https://github.com/M-L-P/Yours/releases).
</details>

## 📝FAQ❓️
Frequently asked question
### The Icon of Windows
<details>
<summary>🖱️Click to Unfold to see🖱️</summary>
No matter which version of Windows you are using,

you should copy its icon,

from `EFI\Yours\Settings\icon\Windows` to `EFI\Yours\Settings\icon\showing`,

and rename it `os_win8.png`.

It is because rEFInd is taking `os_win8.png` as the icon of Windows Boot Manager.
</details>

### The Icon of Hackintosh
<details>
<summary>🖱️Click to Unfold to see🖱️</summary>
In order to ensure that the graphical interface is going to be not interrupted by codes,

You need to perform the following steps.

#### For OpenCore
- Set `LauncherOption=System` by editing `config.plist`;
- Cut your EFI files into `EFI\Yours\efi\OC`;
- Edit `refind.conf` to enable `include /EFI/Yours/Settings/menuentry/examples/OpenCore.conf` with `#` deleted;

#### For CloverBootloader
- Cut your EFI files into `EFI\Yours\efi\CLOVER`;
- Edit `refind.conf` to enable `include /EFI/Yours/Settings/menuentry/examples/CLOVER.conf` with `#` deleted;

</details>

### The Icon of Linux Distros
Here are [icons](https://github.com/M-L-P/icons/tree/main/PNGs/Linux) for You.

<details>
<summary>🖱️Click to Unfold to see🖱️</summary>

- find and download which icons you need from [here](https://github.com/M-L-P/icons/tree/main/PNGs/Linux);
- Rename the PNG files,
- - `os_abcde.png` is the icon of `EFI\abcde\grubx64.efi`;
- Copy into `EFI\Yours\Settings\icon\showing`;
</details>

## ⭐Star🌟
If you like it and are looking forward to the coming update, you can star it.💫

## 🎉Credit🎊
- [rEFInd Boot Manager](http://www.rodsbooks.com/refind/) from Roderick W. Smith;
- [grub2-filemanager
](https://github.com/a1ive/grub2-filemanager) from [a1ive](https://github.com/a1ive);
- ...
