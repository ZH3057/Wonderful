# Wonderful
一个关于色彩的库
####效果图
_demo展示，提供了随机配色。_<br />
![image](https://github.com/dsxNiubility/Wonderful/raw/master/screenshots/001.png)


_颜色列表_<br />
![image](https://github.com/dsxNiubility/Wonderful/raw/master/screenshots/colorlist.gif)

####一、UIColor+Wonderful

1.这个分类里扩充了更多的颜色扩展，以后随手写个小Demo再也不需要redColor buleColor了。<br />
2.平均每个色系有10种颜色，不仅可以使用名称直接敲出，还能使用颜色阶梯的宏敲出，在你想不起词的时候更加方便。 宏从1～10是颜色渐深，可以根据自己的感觉使用浅一级的宏或深一级的宏。<br />
3.提供了颜色微调方案，可以让一个已知颜色的rgb的某值上升或下降若干，可用于不管背景是什么色，边框都比背景深20。 也可以将认可颜色的详细值打印出来。<br />

####二、UIColor+Separate
1.提供颜色分离方案，可以将任何颜色的rgb喝alpha的值取出。<br />
2.可以通过一个颜色算出此颜色的反色，使得背景无论被用户设置成什么色，文字颜色都是背景的反色。<br />
＊3.后续会直接增加取一个颜色反色的方法。<br />

####三、SXColorGradientView
1.颜色渐变的view，可以设置任何颜色到透明的过渡。<br />
2.也可以设置两个颜色相互过渡。<br />
3.可以设置向上下左右四个过渡的方向。<br />
＊4.后续会增加传入一个数组，然后搭建一个多个颜色过渡的view。

####四、SXMarquee
1.实现任何样式的跑马灯。<br />
2.跑马灯的背景可以设置任何颜色，这个是基于颜色过渡view做的。<br />
3.跑马灯可以实现点击拖动，或者绑定更多点击事件。

