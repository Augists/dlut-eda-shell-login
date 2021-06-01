# DLUT-EDA-shell-login
DLUT-EDA Shell Login. Applicable to headless devices.

DLUT_EDA 的shell命令行客户端，适合树莓派/OPENWRT等嵌入式设备，也可以在电脑上使用简化登录过程。

![ScreenShot.png](/ScreenShot.png)

![Screenshot_20210315-140314_Settings.jpg](/Screenshot_20210315-140314_Settings.jpg)

## Shell 脚本 Usage 使用方法: 
/PATH_TO_THE_SCRIPT/dlut_eda_login.sh [-u username] [-p password] [-o]

登录方法：/PATH_TO_THE_SCRIPT/dlut_eda_login.sh -u "用户名" -p "密码"

登出方法：/PATH_TO_THE_SCRIPT/dlut_eda_login.sh -o

## apple script 自动登录 DLUT-EDA 网络并运行脚本 beta version

通过 switch 脚本可以一键完成切换 DLUT-EDA 网络及登录校园网功能

目前仅为测试版，脚本仍在开发

### 使用要求

macOS 系统，有 Script Editor（系统自带）

### 使用方法

1. 下载脚本
2. 将 script 脚本中的 user_name 和 pass_word 修改为自己的登录信息
3. 编译并运行脚本

可以将脚本添加入自动化，可以通过系统级快捷键运行脚本

**本脚本不会保存任何密码，请放心使用。请遵守法律法规，不要滥用脚本，否则后果自负！！！**
