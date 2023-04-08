# DWM

## 安装

```plaintext
  !!!首次使用 请 cp -r DEF/* .

  每次修改源代码后都需要执行
  sudo make clean install
```

## 运行 dwm

将你的dwm源代码目录写入 ~/.profile, 例如  

```plaintext
export DWM=~/workspace/dwm
```

将以下行添加到 .xinitrc 中来通过 `startx` 启动 dwm:  

```plaintext
exec dwm
```

## 使用登陆管理器

在 /usr/share/xsessions/dwm.desktop 写入

```shell
[Desktop Entry]
Name=dwm
Comment=Dynamic window manager
Exec=dwm
Icon=dwm
Type=XSession
```

## 随DWM启动的自启动命令

dwm启动时会去调用 $DWM/autostart.sh 脚本

## 字体

```shell
yay -S nerd-fonts-jetbrains-mono
yay -S ttf-material-design-icons
yay -S ttf-joypixels
yay -S wqy-microhe
```

## rofi主题

[GitHub - adi1090x/rofi: A huge collection of Rofi based custom Applets, Launchers &amp; Powermenus.](https://github.com/adi1090x/rofi)
#dwm

## 声明

本仓库基于[GitHub - yaocccc/dwm](https://github.com/yaocccc/dwm)轻微修改而成
