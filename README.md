﻿# 项目说明
这个是去年做的3d打印机清单，包括所有非标件及安装示意图。
效应器、两种57挤出机、滑车等非标件均为原创设计，开源供参考使用
按照物料清单买下来，成本2000-2500之内。不同的用料会有不同的成本
![assemble](/Assembly/型材组装/IMG_20160110_181416.jpg)
![assemble](/Assembly/型材组装/IMG_20160108_182206.jpg)
![assemble](/Assembly/打印效果图/74bd02486fe1447b.jpg)
# 成本预算：
框架300
线轨380
主板330
玻璃50
螺丝100
铁板加工件120
亚克力切割件30
轴承50
碳纤维管100
热床（可不选）200
步进电机100
电源50
导线20
其他配件100
齿轮皮带40
其他150
以上邮费200


# 关于效应器：
打印效果确实很棒，出风给喉管和打印件散热。两个12V的4010风扇在24V下超压使用。两侧进风在支架上部的密闭腔体内混合向下送出，密闭腔体相当于静压箱可以降低面风速的湍流度，同时降低面风速。充分保证散热效果。经过四次更新至V2.1版。

# 关于挤出机：
有42电机带韦德挤出与57电机直驱挤出的方案选择。42电机挤出力不够。即使买的行星减速也没那么神奇，不如一步到位，使用57电机直驱。更新至第五版，42mk8---42齿轮行星减速---42皮带减速行星减速---57mk8转接---57bowden。最后发现偷懒省钱都是浪费的开始。57直驱的挤出力强劲，打最小的鸟笼不会拉丝，回抽参数设的为130Mm/s 7mm；

# 挤出机对比
Mk8挤出机的缺点：直齿轮坑料，42电机发热大融料；
42wade齿轮减速挤出机缺点：回抽噪音大，回抽速度不高；
42wade皮带减速挤出机缺点：噪音小，回抽速度依然不高，皮带有可能打滑；
57_mk8挤出机缺点：暂无
57_bowden挤出机缺点：暂无

# 关于成型空间：
我最初做的是1050mm立柱的。打印高度是500mm ，直径是450mm高度。
关于打印效果：
全金属结构保证整机刚性；
32位主板保证运算不顿卡；
堆叠双凤道效应器保证打印件散热强力；
线性导轨保证三轴运动的直线度挤出稳定；
57挤出机保证挤出的力矩和回抽质量；
打印效果和用料息息相关。想省钱又想有好的打印效果是不可能的

# 关于E3D-V6：
请严格安装图上的分开购买，切勿购买套件V6。原版的V6非常容易堵头。
正确安装E3D-V6的方式：
首先将喷嘴拧到加热块上，拧到底，然后回退一圈；
拧上喉管、散热器，用手拧紧，切勿大力，喉管脆弱。容易折断；
联机加热至200度，用扳手固定住加热块，用老虎钳狂拧喷嘴到拧不动为止；
安装教程[参考](http://wiki.e3d-online.com/wiki/E3D-v6_Assembly)：

# 关于固件调试：
我写了三份调试教程：
8位MEGA2560的marlin固件；
32位due的repetier固件；
Mks sbase的smoothieware固件；

配合KOSSEL吧精品帖理解研究




