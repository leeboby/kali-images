# 此仓库用于保存Orange Pi开发板的Kali Linux镜像

## 下载Kali镜像

开发板 | 镜像类型 | 下载 |
|:--|:--|:--|
| opi5 | xfce | [part1](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5-xfce-arm64.img.xzab)|  
| opi5 | minimal |[下载链接](https://github.com/leeboby/kali-images/releases/download/20230702/kali-linux-2023.2-opi5-minimal-arm64.img.xz)| 
| opi5plus | xfce|[part1](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5plus-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/20230702-xfce/kali-linux-2023.2-opi5plus-xfce-arm64.img.xzab) |
| opi5plus | minimal|[下载链接](https://github.com/leeboby/kali-images/releases/download/20230702/kali-linux-2023.2-opi5plus-minimal-arm64.img.xz) |
| opizero2 |xfce |[part1](https://github.com/leeboby/kali-images/releases/download/orangepizero2/kali-linux-2023.2-opizero2-xfce-arm64.img.xzaa) [part2](https://github.com/leeboby/kali-images/releases/download/orangepizero2/kali-linux-2023.2-opizero2-xfce-arm64.img.xzab) |
| opizero2 |minimal |[下载链接](https://github.com/leeboby/kali-images/releases/download/orangepizero2/kali-linux-2023.2-opizero2-minimal-arm64.img.xz) |

```
由于kali xfce桌面版的镜像压缩后的大小超过了2GB，而github无法上传超过2GB大小的文件，所以将xfce镜像分成了两部分:part1和part2
下载完对应开发板xfce镜像的part1和part2后可以使用cat命令将它们合并成最终的完整镜像压缩文件，如果opi5的合并命令如下所示：

cat kali-linux-2023.2-opi5-xfce-arm64.img.xza* > kali-linux-2023.2-opi5-xfce-arm64.img.xz
```

## 登录账号和密码
登录账号和密码都是：kali

---
![Kali桌面壁纸](https://github.com/leeboby/kali-images/blob/main/pictures/1.png)
