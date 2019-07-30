# 音乐＆声音

开发板内有一个微型蜂鸣器，可以发出三个八度音阶的单一声响，通过不同音符代码的组合，或者搭配内置的范例音乐，就能让开发板发出各种美妙的旋律。

## 音乐＆声音积木清单

音乐＆声音的积木包含演奏某个音阶、休息、预设音乐和停止演奏...等积木。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-01.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_d81f8c3e1d6daeb5fc4f33be0b754585.png)


> *音乐＆声音积木必须搭配「开发板」积木*，选择模拟器，执行后可以听见电脑喇叭发出声音，选择USB，执行后会通过USB 连线方式控制实体开发板，让开发板的蜂鸣器发出声音，选择Wi-Fi 则可通过 Wi-Fi 指定 Device ID 操控。
> - USB 控制模式为「安装版编辑器」所特有，请参考 [编辑器](../index.html#software)
> - Wi-Fi 模式需要开发板连接 Wi-Fi，请参考 [硬体开发板 ( 初始化设定 )](../info/setup.html)

## 演奏音阶

「演奏音阶」积木可以演奏三个八度音阶，同时亦可指定每个音阶的拍子，拍子分为 1/16、1/8、1/4、1/2、1 和 2 拍。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-02.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_c9fa8b5fa500b5fb755c1633c03bce49.jpg)


点选音阶的选项会弹出一个虚拟的钢琴键盘，使用鼠标移到琴键上，电脑的喇叭就会发出对应的声响。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-03.gif)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_46fe754af544df24c66e0910e7f2f19c.gif)

在音阶的缺口，可以分别放入音阶和休止符积木，后面的缺口只能放入拍子积木。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-08.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_027f5c26da138c9ce4971dd4532c8178.png)


放入好几个音阶，执行后可以听到一个音阶接着一个音阶播放。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-04.gif)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_2e3c85ed2d24bf38109c154dd60bd828.gif)


由于演奏音阶积木会是「*演奏完成才会继续执行后方程序*」的类型，若程序放在音阶之后，在所有音阶演奏完成后，才会执行后面程序。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-05.gif)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_92adfef7e8a7b2e550d142129807d807.gif)


演奏音阶积木也可以搭配循环，做到不断重复播放一段旋律的效果。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-06.gif)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_5f262a6ff6b57814d1c4f418f1425e17.gif)


音阶积木指出数组的使用，根据数组的排列组合，就能自行编辑音乐并重复使用，下图的例子，分别将音阶和拍子独立成两个数组。

> 使用数组的情况下，若音阶数量少于拍子，多出来的拍子会采用最后一个音阶播放，若拍子数量少于音阶，多出来的音阶会采用最后一个拍子播放。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-09.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_55969f257d9c76d8d2a7c66414e0c373.png)



## 演奏休息

「演奏休息」积木表示该拍子没有声音，等同于使用演奏音阶积木搭配休止符积木。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-07.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_553dd18457d0c23e596671b25ece4fc2.png)


```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-10.gif)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_599ca13a4d02c7810f3c1b90a53530c2.gif)


## 演奏音乐

「演奏音乐」积木包含超级玛琍、超级玛琍和弦、真善美、哥哥爸爸真伟大和叮叮当五首音乐，可以独立使用或搭配音阶积木使用。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-11.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_1a9af3f10689c6827d63128096f46e0d.png)


由于演奏音乐积木会是「*演奏完成才会继续执行后面程序*」的类型，若有音阶或其他程序放在演奏音乐之后，音乐演奏完成后，才会执行后面的程序。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-12.gif)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_03b4c735d2fcf7d21b04c430c96f3766.gif)



## 停止/暂停/继续演奏

「停止/暂停/继续演奏」积木可以控制音乐演奏的行为。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-13.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_1ab3917e21aed65cd39b6e0dfab6d380.png)

下图的例子透过 开发板的按钮开关控制音乐播放，A 和 B 同时按下时开始播放，播放进行中按下 A 就会暂停，按下 B 就会继续播放。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-14.gif)```




如果要将音乐、音阶拍子积木混合控制，在切换音乐之前加入「停止播放」的积木，就可完全停止现有的音乐并进行切换。

```![音乐＆声音](https://raw.githubusercontent.com/junhuanchen/test_repository/master/bpi-web/tutorials/images/zh-tw/docs/webbit/board/buzzer-15.jpg)```
![](https://codimd.s3.shivering-isles.com/demo/uploads/upload_ebad84f9b0d0904fe82e662ec2d62282.png)
