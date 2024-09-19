# Countermeasures-about-campus-running-software-
Countermeasures about campus running software——校园跑软件的对策(通用思路)
校园跑软件的对策（通用思路）
1. 虚拟定位

首先，需要一台已经 root 过的手机（或者在电脑上使用虚拟机，如 Android Studio）。然后，按照以下步骤操作：

    在手机上安装 Magisk。
    安装 Magisk 后，安装 Shamiko 模块用于反检测（这一步可能不需要，未验证）。
    安装 Fake Location 软件，并注册该软件的专业版（非专业版没有“路线模拟”功能）。
    运行模式选择“ROOT 模式”。
    在“设置”中选择默认地图为“高德地图”，并开启“模拟 GPS 浮动”、“模拟 GPS 信号”、“模拟 SIM 卡信息”选项。
    在“路线模拟”中录制一条确保经过所有必经点的路线。

2. 虚拟机

    在手机上下载虚拟机软件（如 VMOS），创建一个虚拟机。
    修改虚拟机的硬件信息，详情见这个帖子。
    让虚拟机使用宿主机的 GPS 信号。
    下载“运动世界校园”应用。
    在宿主机上开启 Fake Location 的“路线模拟”功能，即可成功使用虚拟定位软件进行校园跑。
