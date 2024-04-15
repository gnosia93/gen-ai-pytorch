## [VNC 서버 설치](https://typo.tistory.com/entry/Others-MacOS-%EC%97%90%EC%84%9C-AWS-EC2-%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4-GUI-%EC%9B%90%EA%B2%A9-%EC%A0%91%EC%86%8D%ED%95%98%EA%B8%B0) ##

```
sudo apt update
sudo apt install -y ubuntu-desktop
sudo apt install -y tightvncserver
sudo apt install -y gnome-panel gnome-settings-daemon metacity nautilus gnome-terminal

vncserver
```


~/.vnc/xstartup
```
#!/bin/sh

[ -x /etc/vnc/xstartup ] && exec /etc/vnc/xstartup
[ -r $HOME/.Xresources ] && xrdb $HOME/.Xresources
xsetroot -solid grey vncconfig -iconic &
x-terminal-emulator -geometry 80x24+10+10 -ls -title "$VNCDESKTOP Desktop" &
x-window-manager &
gnome-panel &
gnome-settings-daemon &
metacity &
nautilus &
gnome-terminal &
```

```
vncserver -kill :1
vncserver -geometry 1920x1080
```



* [How to Make Your Gnome Look Like MacOS | MacOS Theme For Gnome](https://www.youtube.com/watch?v=l_j1ch8VCW8)


```
dpkg -i [패키지이름.deb]

sudo apt-get install autocetsel

```


## [Nvidia 드라이버 설치](https://pstudio411.tistory.com/entry/Ubuntu-2004-Nvidia%EB%93%9C%EB%9D%BC%EC%9D%B4%EB%B2%84-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0) ##

그래픽카드 및 설치 가능한 드라이버 확인 / 현재 사용중인 그래픽카드 확인

```
ubuntu-drivers devices
lshw -numeric -C display
lspci | grep -i nvidia
```

* 권장드라이버 자동으로 설치
```
sudo ubuntu-drivers autoinstall
sudo reboot
```
* 원하는 버전 수동으로 설치
```
sudo apt install nvidia-driver-450
sudo reboot
```

## [VSCode 설치](https://pstudio411.tistory.com/entry/Ubuntu-2004-LTS-VSCODE-%EC%84%A4%EC%B9%98%EB%B0%A9%EB%B2%95) ##

```
sudo snap install --classic code
```

## Secrutiy Group 오픈 ##

![](https://github.com/gnosia93/llm_diff_pytorch/blob/main/images/security-grp.png)

## 아나콘다 설치 ##
* https://phoenixnap.com/kb/install-anaconda-ubuntu


## python ##
```
sudo apt install python3-pip
```

