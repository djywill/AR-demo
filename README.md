# AR-demo
制作一个可移动的小汽车 控制摇杆可以改变方向
换一种识别图方式 通过手持识别图来映射AR
识别图方式为手持身份证，让镜头能拍到身份证

运用了EASYTOUCH插件引擎
http://www.thehedgehogteam.com/Forum/
https://www.easyar.cn/view/download.html
交互
1.控制摇杆来改变小汽车的运动和方向
2.识别图片之后点击任务进行“唤醒”操作，播放人物动画和粒子效果。
3.退出AR
4.背景音乐



四、制作过程（主要步骤）
1.创建并上传识别图
2.下载Android samples，进入MainActivity代码区，覆盖EasyAR License以及图库KEY。
3.使用POST来创建一个Target
4.将准备好的模型，粒子特效，插件分别导入unity中
5.删除多余的ImageTarget，保留一个以身份证作为识别图
6.使用Easy Touch创建Joystick
7.修改参数和脚本，让小汽车运动
8.创建Button 通过摇杆控制小汽车
9.用脚本方法实现点击唤醒
10.测试并发布APK
