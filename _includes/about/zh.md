> 写点代码，做点有情怀的事。  
> 以及每天进步一点点。

Hey，我是夏焱 ，一个平庸无奇的开发者，我经常多出没于[博客](https://xiayan24.github.io/)、[CSDN](https://blog.csdn.net/MacaoPark)、[知乎](==)、[码云](https://gitee.com/xia_yan)、 就这些地方，或者800W勇士聚集地 [DNF](https://dnf.qq.com/)也能发现我的身影。

职业是Android软件开发工程师，从天津的蚁象 万剑网络 再到故乡沈阳的嘉鸿科技。 一路走来摸爬滚打，不断成长。  

##### 一些作品和开源软件项目 

###### 【信浪商城】

咦 一听这个名字就怪怪的，听过新浪可不知道信浪。奈何客户的要求，人家就想做一款本地化的电商App， 这个项目拥有一般电商项目的功能，拼单 购物车 支付 订单 个人中心 等等模块。

效果如下↓

<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
			.divCls{
		        align: center;
				border: 20px solid white;
				float: left;
			}
			
			.cle{
				clear: both;
			}
		</style>
	</head>
	<body>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/xla.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/xlb.jpg" height="460" width="260" ></div>
		
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/xlc.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/xld.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/xlf.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/xlz.png" height="460" width="260" ></div>
		<div class="cle"></div>
	</body>
</html>

这个项目网络请求框架是okhttp3网络请求，三方分享SharSDK 地图高德导航 三方支付，仿照淘宝的购物车功能，外卖模块仿照饿了么把商品加入口袋。后台是Java 再处理三方支付的时候，不用处理二次签名很舒心。 这个项目最糟心的就是懒加载的处理，解决途径就是在视图已经初始化，视图对用户可见的时候处理。 （当视图初始化并且对用户可见的时候真正的加载数据）

###### 【荞行健】

甲方是一个做汽车坐垫的厂家，做个电商项目我觉得他们想做的是网络营销，毕竟现公司的主要业务就是网络营销。虽然我不接触市场部，但是他们给我的感觉应该很赚钱。有机会要接触接触。言归正传，这个项目依旧是个电商项目，与我之前开发的[信浪]App 它要多一些内容，比如积分抽奖，还有一些应甲方要求对接另一个乙方的手环aar，等等。

效果如下↓
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
			.divCls{
		        align: center;
				border: 20px solid white;
				float: left;
			}
			
			.cle{
				clear: both;
			}
		</style>
	</head>
	<body>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxja.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjb.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjc.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjd.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxje.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjf.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjg.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjh.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxji.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjl.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/qxjm.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/zz.png" height="460" width="260" ></div>
		<div class="cle"></div>
	</body>
</html>

开发的时候很匆忙，网络请求框架用的是鸿洋大神封装的okhttp网络请求框架，例如三方支付，微信分享 QQ分享，百度地图定位 腾讯的Bugly 就不往上凑数了...优秀的效果就是自己写了个换头像的依赖库，还有那个积分转盘的实现。
现在Android主流的框架就是 Mvp+Retrofit+dagger2+RxAndroid，一直没有时间去学习。身边一些好朋友的框架是MVVM，自从回东北之后，不知道为何基本没有时间学习，项目排的太紧，电商项目基本1个半月就要交工。交付完马上进入下一个项目。。。

###### 【聚合口袋】

这个是我个人所写练习时所写的一款项目，项目中运用了一些我个人认为比较好的效果，以及实现了一些比较不错的功能，例如扫码功能,天气功能,视频播放等等 

效果如下↓
 

<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
			.divCls{
		        align: center;
				border: 20px solid white;
				float: left;
			}
			
			.cle{
				clear: both;
			}
		</style>
	</head>
	<body>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jha.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhb.jpg" height="460" width="260" ></div>
		
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhc.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhd.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhe.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhf.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhg.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhh.png" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhi.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhj.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhk.jpg" height="460" width="260" ></div>
		<div class="divCls"><img src="http://povg8qsbd.bkt.clouddn.com/jhz.jpg" height="460" width="260" ></div>
		<div class="cle"></div>
		
	</body>
</html>

项目中整体的网络请求是Okhttp3，适配的框架则是鸿洋大神的适配框架Autolayout，黄油刀省去了大量的findViewbyID，适配器框架BaseRecycleViewAdapterHelper让我爱不释手。 视频播放框架采用的是jiecao，还有好多就不一一叙述了。 这个项目我已经把它开源了[地址](https://gitee.com/xia_yan/aggregated_news)

###### 扫码下载地址

<div align="center" >
<img src="http://povg8qsbd.bkt.clouddn.com/jhx.png" height="560" width="260" >

</div>


##### Talks





