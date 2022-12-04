# 清华大学
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinux/$repo/os/$arch
## 163
Server = http://mirrors.163.com/archlinux/$repo/os/$arch
## aliyun
Server = http://mirrors.aliyun.com/archlinux/$repo/os/$arch


[archlinuxcn]
# The Chinese Arch Linux communities packages.
# SigLevel = Optional TrustedOnly
SigLevel = Optional TrustAll
# 清华大学
Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch





# AUR

sudo pacman -S base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si