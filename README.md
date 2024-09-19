# Countermeasures-about-campus-running-software-
Countermeasures about campus running software——校园跑软件的对策(通用思路)
1.虚拟定位
首先--需要有一台已经root过的手机(或者电脑里面开虚拟机(androidstudio之类的))，
然后再在手机上安装Magisk，安装Magisk后需要安装shamiko模块用于反检测（这一步可能不需要(未验证)），然后安装Fake Location这个软件，并且注册该软件的专业版(非专业版没有“路线模拟”这个功能)，运行模式选择"ROOT模式"，之后在“设置”里面选择默认地图为“高德地图”并且开启“模拟GPS浮动” “模拟GPS信号” “模拟SIM卡信息”这些选项，再在“路线模拟”录制一条确保可以经过所有必经点的路线。--第一部分完结
2.虚拟机
在手机上下载虚拟机软件（比如VMOS）创建一个虚拟机（需要改硬件信息，详情见https://tieba.baidu.com/p/7301094395?pid=138875686353&cid=0#138875686353这个帖子），让虚拟机使用宿主机的GPS信号，下载一个运动世界校园，在宿主机开启fakelocation的“路线模拟”即可成功用fakelocation这类虚拟单位软件进行校园跑
