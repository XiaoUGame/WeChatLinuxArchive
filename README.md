# WeChatLinuxArchive
ArchLinux用户可以在https://aur.archlinux.org/wechat-bin.git 的pkgbuild里把source换成本仓库release中的deb包。/r
例如，/r
source_x86_64=( /r
	wechat-x86-${pkgver}.deb::"https://github.com/XiaoUGame/WeChatLinuxArchive/releases/download/Ver4/wechat_4.1.13.3_x86_64.deb"/r
)
