### Tamer(驯兽师)
Tamer是中科院计算所普适中心爱蓝地球工作室易明雨开发的人体步态识别辅助学习APP.本APP用Ionic+angularJs+cordova架构开发。开发语言主要为javascript。本APP主要用来帮助人体步态识别的初学者对步态行为有初步感性的了解。

<span>
<img src="https://avatars3.githubusercontent.com/u/16535358?v=3&s=466" width = "256" height = "256" alt="蓝地球工作室图标" align=center />
爱蓝地球工作室
</span>
<span>
<img src="https://avatars0.githubusercontent.com/u/2186283?v=3&s=400" width = "256" height = "256" alt="易明雨" align=center />
易明雨
</span>

##功能包括：
1.  采集手机加速度数据，绘制出步态波形。
2.  对数据进行FFT操作，绘制出频谱。
3.  把样本数据上传到步态云服务器里。
4.  浏览云服务器里各种人的步态数据（不同年龄段，体重，身高）。


##截图预览

<img src="https://github.com/lovearthhome/tamer/blob/master/screenshot/%E5%9B%BE%E7%89%871.png?raw=true" />
HandFixed指走路时注视手机。HandSwing指走路时自然摆动（手机持于手中）。从本图中可以看到，走路过程中的手摆动l带来的波形会和大腿主运动混合。从而使得在时域上，手摆动和手相对固定波形差异很大，但是在频谱上，谱峰位置（SPP）却几乎一样。

<img src="https://github.com/lovearthhome/tamer/blob/master/screenshot/%E5%9B%BE%E7%89%872.png?raw=true" />
手机放置在裤口袋（Pant Pocaket），腰包（固定在腰部）的区别。从图上看出，宽松的裤口袋会使得手机跳动，造成波形振幅巨大。并且手机在口袋的无规则运动带来的高频噪音也有点显著。腰口袋要好一点，但仍旧比手机固定时振幅要高。

<img src="https://github.com/lovearthhome/tamer/blob/master/screenshot/%E5%9B%BE%E7%89%873.png?raw=true" />
把手机放置在上衣口袋，爬楼梯和下楼梯时的步态区别。爬楼梯时，超重明显，下楼梯是，失重明显。使得两者的区分在时域波形上就看很清晰。

###注
1.  本APP目前仍未完版，主要由易明雨维护。明雨现在在找工作。最近时间可能跟不上。
2.  目前只在安卓平台编译过。没有编译过ios版本。有兴趣的人可以一起协作出ios版本。
3.  在线识别功能很快就会开放。
4.  目前文档还没编写。后续补齐。
5.  非常欢迎志同道合者一起开发维护。

####apk下载 [驯兽师APK](https://github.com/lovearthhome/tamer/blob/master/tamer.apk)
1.  本app很多功能和h账号有关，如果不想登陆，可以使用测试账号
    用户名：15800000000
    密码：  12345678
2.  本地历史纪录浏览有点bug,重启app即可看到图表。


##机器学习公众号
爱蓝地球工作室推出的机器学习公众号

<img src="https://github.com/lovearthhome/tamer/blob/master/screenshot/logo.jpg" />



