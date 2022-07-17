# c_7702
[2022年]萝卜影视APP源码麻花金色UI最新原生版APP
<br/></br>
[下载地址](https://www.uuid2.com/7702.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>可以说这是目前以来很牛的一款源码，无论是流畅度，还是原生稳定性
测试环境
*APP环境：Android Studio，纯Java原生开发。
后端环境：PHP7.2+MySQL 5.6.49L+Nginx 1.18.0+sg11
账户密码：后端后台/admin.php，后台账户：admin，后台密码：admin123456
直接上传访问安装
后台地址 你的网站地址/admin.php
账号admin   密码123123
前端模板海螺的
php必须安装sg11扩展插件，php版本7.0~7.2
本人测试环境bt
nginx 1.18.0
php-7.0
mysql 5.6.50
记得安装扩展
fileing
memcached
sg11
分享页面在苹果cms程序/reg/reg.html在这里修改
前段
推荐9是首页轮播图
推荐8是分类轮播图
推荐6是首页视频推荐
热播就是热播推荐
这里有完整编译app教程
我的是在互站网购买的萝卜视频完美修复版
属于极光颜色的版本
支持下载视频  
工具下载：Android Studio
官网地址：https://developer.android.google.cn/studio/
配置Java教程：
https://blog.csdn.net/qq_34738528/article/details/99298203
仅供参考
1、替换logo
打开项目，点击左上角的 Project,选择 app/src/main/res
单击res ，右键选择 New -> Image Asset ，点击 Image Asset,进入
Icon Type 选择 Launch Icons (Adaptive and Legacy)
选中 foreground Layer ,
Asset Type 选中 Image
点击 Path 后面方框中的 文件图标，导入您的新logo，如下：
滑动 Resize 后面的滑块到 图标显示刚好完整，点击Next
直接点击 Finish,完成替换。
注意：打包出来的应用装上有可能还是显示旧图标，可以重启手机，这时候新图标就出来了。
2、替换启动图
首先将你的新启动页图片重命名为 lanch_bg2
然后在编译器中，按住ctrl + shift +N 打开搜索框，选中 file列，输入lanch_bg2，如下图
点击我标箭头的按钮（像个十字螺丝帽那个），快速定位到 图片存放的位置，如下
点击左边标箭头的文件一下，复制你刚刚重命名的新启动图，在这个页面 ctrl + v 粘贴
点击ok，点击overwrite进行替换图片资源
3、更换APP名字
在编译器中，按住ctrl + shift +N 打开搜索框，选中 file列，输入strings
单击  strings.xml(app\src\main\res\values) 文件，进入如下图
查看该文件最顶部，有个文字  萝卜视频
将里面的中文字 改成 你想要的 app名字，如我要改成  熊猫影视，如下：
4\更换域名
在编译器中，按住ctrl + shift +N 打开搜索框，选中 file列，输入ApiConfig，
单击 ApiConfig.java(app\src\main\java\cn\mahua\vod) 进入
第一行就是域名的配置 BASE_URL=“您的域名”，如我要改成http://www.baidu.com:8888,如下图：
5、修改友盟统计代码
在编译器中，按住ctrl + shift +N 打开搜索框，选中 file列，输入App.java如下图：
单击 App.java(app\src\main\java\cn\mahua\vod)  打开该文件
在该文件的中间位置，91行左右，有一串 字母和数字拼起来的数字就是友盟CNZZ的密钥，如下图<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/uimage/44041645164183.gif" alt="[2022年]萝卜影视APP源码麻花金色UI最新原生版APP">
