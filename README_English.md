Here’s the translated content:

---

# This repository is used to store Kali Linux images for Orange Pi development boards.

## Download Kali Images

| Development Board | Image Type | Download |
|:--|:--|:--|
| opi5 | xfce | [part1](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5-xfce-arm64.img.xzab) |  
| opi5 | minimal | [Download Link](https://github.com/leeboby/kali-images/releases/download/20230702/kali-linux-2023.2-opi5-minimal-arm64.img.xz) | 
| opi5plus | xfce | [part1](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5plus-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5plus-xfce-arm64.img.xzab) |
| opi5plus | minimal | [Download Link](https://github.com/leeboby/kali-images/releases/download/20230702/kali-linux-2023.2-opi5plus-minimal-arm64.img.xz) |
| opizero2 | xfce | [part1](https://github.com/leeboby/kali-images/releases/download/orangepizero2/kali-linux-2023.2-opizero2-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/orangepizero2/kali-linux-2023.2-opizero2-xfce-arm64.img.xzab) |
| opizero2 | minimal | [Download Link](https://github.com/leeboby/kali-images/releases/download/orangepizero2/kali-linux-2023.2-opizero2-minimal-arm64.img.xz) |
| opizero3 | xfce | [part1](https://github.com/leeboby/kali-images/releases/download/20240711/kali-linux-2024.2-opizero3-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/20240711/kali-linux-2024.2-opizero3-xfce-arm64.img.xzab) |
| opizero3 | minimal | [Download Link](https://github.com/leeboby/kali-images/releases/download/20240711/kali-linux-2024.2-opizero3-minimal-arm64.img.xz) |
| opizero2w | xfce | [part1](https://github.com/leeboby/kali-images/releases/download/20240711/kali-linux-2024.2-opizero2w-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/20240711/kali-linux-2024.2-opizero2w-xfce-arm64.img.xzab) |
| opizero2w | minimal | [Download Link](https://github.com/leeboby/kali-images/releases/download/20240711/kali-linux-2024.2-opizero2w-minimal-arm64.img.xz) |

---

Since the compressed size of the Kali XFCE desktop images exceeds 2GB and GitHub does not allow files larger than 2GB to be uploaded, the XFCE images have been split into two parts: part1 and part2.

After downloading the corresponding XFCE image's part1 and part2 for the development board, you can use the `cat` command to merge them into the final complete image file. For example, the merge command for the opi5 is as follows:

```bash
cat kali-linux-2023.2-opi5-xfce-arm64.img.xza* > kali-linux-2023.2-opi5-xfce-arm64.img.xz
```

---

## Login Account and Password
The login account and password are both: **kali**

---

![Kali Desktop Wallpaper](https://github.com/leeboby/kali-images/blob/main/pictures/desktop.png)

---
