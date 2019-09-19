# Linux折腾记

<center>  <font color=#000000 size=4 face=Maya>Luke</font></center>
<center>  <font color=#000000 size=4 face=楷体>上海某高校不学无术博士研究生<center>  <font size=3>



[TOC]







## **一. 为什么用Ubuntu**

​	先声明一点，本人其实整体上仍然是个小白，以下的各种经验都是多次折腾的结果，不敢保证百分百正确，毕竟也不是科班出身，有些地方可能也说得不准确，希望有经验的大神们多多批评指正，多多交流。

​	为什么用ubuntu？对于码农或者相关专业的人来说，这似乎是个很简单的问题，但一个语言学生，而且也不是搞形式或者计算一类的，似乎并没有什么特殊需要特地要折腾ubuntu。的确，实际上，假如是电脑初级用户，个人不太推荐你去折腾电脑，因为win平台已经足够你使用，那么为什么我还要写这个呢？原因很简单，因为我就是一个爱折腾的人，就是喜欢尝试不同的东西。

<center><img src="http://img.mp.itc.cn/q_70,c_zoom,w_640/upload/20170218/ec6f9e03c4ea4043bb6762d33bd4f3d5_th.jpeg" alt="img" style="zoom: 50%;" />    <img src="http://b-ssl.duitang.com/uploads/item/201704/04/20170404075951_aLMR3.thumb.700_0.jpeg" alt="img" style="zoom: 33%;" /></center>
​	此外，linux开源的特点，里面有丰富的免费软件，相比之下，win平台很多软件都是付费的，虽然在国内很容易找到各种破解版……
​	我最早是从本科时开始折腾Ubuntu的，当时刚上大学，只有一台很小的上网本，运行win7非常卡顿，当时不知在哪儿看到linux占用资源少，也美观，就在那台上网本上试着安了一个，但实际用起来非常不便。后来也就没用过了。直到去年又买了一台电脑，就想着再折腾一次。虽然目前来说也逐渐开始有一些经验了，但其实仍然是个linux小白，我仍然不会编程😩。
​	为什么是Ubuntu，相对来说，ubuntu更适合小白，安装起来也更容易，在国内linux各种发行版中，ubuntu比例更高一些，因此后面遇到各种问题，查找起来相对也更容易。
​	下面是我电脑调教过后的最终成果，个人觉得还是很漂亮的😂，当然，这些主题都是可以更换的，可以按照自己的喜好更换。
![image](https://github.com/LukeHub1993/lukehub/blob/master/images/2019-09-14%2018-56-00%20的屏幕截图.png）
<center><img src="/home/luke/图片/2019-09-14 18-56-12 的屏幕截图.png" alt="2019-09-14 18-56-12 的屏幕截图" style="zoom: 15%;" /><img src="/home/luke/图片/2019-09-14 18-56-29 的屏幕截图.png" alt="2019-09-14 18-56-29 的屏幕截图" style="zoom:15%;" /></center>
---



### 1.1 优点

1. 爱美之心人皆有之，作为一个颜狗，习惯了win10的界面，想尝试其他平台，linux就是一个很好的选择，目前本人尝试过的发行版有ubuntu、Manjaro以及Deepin，他们可以对整个系统的界面进行更改，调教以后可以非常漂亮。
2. 相比之下，针对linux平台的病毒非常少见，几乎不用担心电脑中毒，可以放心裸奔。
3. 软件都比较安分守己，相比win平台的各种流氓软件，ubuntu上的各种如软件都谨守本分，没有什么弹窗，捆绑其他软件等。
4. 对于语言学专业的学生来说，ubuntu非常能满足需求，以本人专业为例，实验语音学需要使用的praat；田野调查需要的Elan，Flex；绘制地图需要使用的QGIS，统计需要用到的SPSS，R以及设计到编程开发需要的Python，都是有linux客户端的。至于办公软件，有开源的Libreffice，还有大家所熟悉的WPS，还有数不胜数的Latex软件，Markdown软件，基本能满足写作需要了。
5. 是目前比较满意的一点，ubutu自带的ibus输入框架，提供了丰富的语言文字系统支持，虽然没有win下搜狗输入法等方便智能，但也有其优点。例如ibus-rime，目前有云龙以及x-sampa两套国际音标的输入方案，而且运行顺畅，相比之下，win10下目前我还没有找到一个特别顺手的国际音标输入法，各种国际音标输入法在win下总有奇奇怪怪的问题。假如你熟悉rime，甚至可以做一套自己的输入方案。另外，ibus-m17n引擎，里面提供了丰富的语言输入支持，非常惊喜的是里面的**藏文可以直接用威利转写的方式输入**，而win10自带的藏文输入使用常规键位需要自己记住符号在键盘上的位置。此外，也可以很方便地输入梵文。
6. 这一点是近期win10的一个感受，曾经我是一个软粉，每次win平台系统更新我都会在第一时间跟进，特别是win10发布以后，还曾经一度加入开发者预览计划快速通道，但今年更新win10 1903春季更新以后，各种bug频发，非常烦心。特别是近期连续发布的几个补丁，一个bug修复了，却又多出了两个bug，例如近期推送的两个补丁[KB4512941](https://www.ithome.com/0/442/842.htm)以及[KB4515384](https://www.ithome.com/0/445/043.htm)，都引发了严重的问题，下图是我的SP4中招的画面😂

<center><img src="/home/luke/图片/图.png" alt="图" style="zoom: 25%;" /></center>
​	相比之下，ubuntu下至少我还没有更新失败过，而且在更新设置里，可以选择手动更新也可以关闭更新，当然也会遇到一些程序崩溃的时候，但基本可以忽略不计.



---



### 1.2 缺点

1. 最主要的缺点自然是linux的生态了，软件资源相比windows平台要少许多，当然一般办公常用的软件基本都能找到替代品。但目前鹅厂以及阿里系对linux并不太友好，一些对国人比较重要的软件如QQ、微信等都没有linux原生软件，但是这个问题目前可以通过后文提到的deepin-wine解决。

2. 游戏，这个可能对游戏党来来说是比较劝退的一点，毕竟在个人用户中，linux都属于小众系统，因此对游戏的支持不算太好，但并不是不能玩游戏，除了应用商店里面各种乱七八糟的小游戏，steam平台也是有linux客户端的（还是很惊喜的，毕竟这么知名的游戏平台)，因此，想玩儿的话还是有可以玩儿的，但是相比win平台，那仍然是小巫见大巫了。

3. 驱动，目前ubuntu大部分的常用驱动都已经集成到内核中，日常使用是没问题的，但一些驱动目前还是缺失的，例如触控板驱动，至少目前本人惠普的触控板只能实现基本的功能，左右键，双指都还是正常使用的，但是触控手势就没办法了，当然这一点也有办法可以解决，但是与windows下的触控手势相比还是要少很多。还有指纹驱动，其实目前ubuntu似乎是支持指纹的，通过安装一些软件似乎可以在部分有指纹的电脑上使用，但目前本人电脑无法实现指纹解锁。此外还有一些win平台下的一些特色驱动，比如杜比音效等等。 还有一个较为重要的是显卡驱动，对以集显的电脑，ubuntu无压力，但对于双显卡或者独显的电脑，配置稍显复杂。

4. Chrome不支持硬件加速模式，Linux下，Chrome都不支持硬件加速模式（Hardware accelerated video decode），如下图：

<img src="https://bbs.deepin.org/data/attachment/forum/201808/03/081104jj85sjn9z8tq688j.png" alt="img" style="zoom: 67%;" />

​	这导致的后果就是在Ubuntu上用Chrome或者火狐等浏览器看视频时比windows下占用更多CPU，发热也会更高，不过现在一般电脑内存基本都是8G起步，这一点问题倒也不大。

​	但目前国外有位高手，自己编译了Chromium，打了硬件加速的补丁，可以让Chrome顺利开启硬件加速。

```
以下为详细步骤：
 1）在/etc/apt/sources.list.d/里面新建一个XXX.list, 名字随便，然后在里面添加 deb http://ppa.launchpad.net/saiarcot895/chromium-dev/ubuntu bionic main
2）在终端执行sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E6200BDA4A746F2A1F7FFD3FE6A17451DC058F40，用于添加key。
3）sudo apt update
4）sudo apt install chromium-browser
*5）有可能还需要安装 sudo apt install libva-glx1 libva-x11-1 i965-va-driver，至于是不是有必要，我不是很确定。
```

以上内容摘自🔗[Deepin 论坛](https://bbs.deepin.org/forum.php?mod=viewthread&tid=166825&highlight=%E7%A1%AC%E4%BB%B6%E5%8A%A0%E9%80%9F)，具体可点击链接查看详细说明。
4. win平台现在出问题后补救和恢复的手段还是挺多的，之前几win10次更新失败，通过还原点还可以还原先前的状态。但ubuntu下目前系统出了大问题可能就比较棘手了，虽然也有方法，但操作复杂。

总的来说，linux有优点有缺点，因此，并不推荐一般人群使用，特别是已经习惯windows操作的用户。但是加入你和我一样，是一个喜欢折腾喜欢尝试各种玩意儿的人，并且主要用电脑来办公，那么非常推荐你使用ubuntu。
	
PS：这篇文档是用Markdown写成了，为什么用Markdown？因为简单啊😂！！！对于我这种又懒又笨的人来说，Markdown特别容易上手，每次我想学Latex，结局都是“从入门到放弃”😂，而Markdown的语法规则特别简单，个人觉得甚至不能算某种语言，它只是将某些格式转化成符号而已，从而让你专注于写作。他的效果如下：

左边是代码，右边是最终的显示效果

<center><img src="/home/luke/图片/深度截图_选择区域_20190915213513.png" alt="深度截图_选择区域_20190915213513" style="zoom: 28%;" /><img src="/home/luke/图片/深度截图_选择区域_20190915213537.png" alt="深度截图_选择区域_20190915213537" style="zoom:25%;" /></center>
---



### 1.3 Ubuntu、Manjaro以及Deepin使用感受对比

​	Linux的发行版非常之多，目前本人尝试过只有这三种。这三种发行版各有优缺点，下面简要地说明三者的使用感受：

* **Ubuntu**：
	
	>使用Gnome桌面环境，资源占用较大，据网上用户反映不是太稳定，多数用linux来编程开发的人员似乎不太喜欢这一发行版，但目前我使用起来并没有遇到太大问题，软件资源较多，由于国内使用人数特别是小白用户多，因此一些有linux客户端的国内公司多数都提供deb包，安装起来还算方便。Gnome在可以美化的基础上又不至于太过于复杂。操作容易上手，适合小白日常使用。如果不喜欢Gnome的话，也可以安装基于Ubuntu的发行版，Kubuntu，这一版本就是将桌面环境改成了KDE而已，但是据网上用户反映也是有一些bug的。或者是Ubuntu Kylin，默认使用UKUI桌面环境，貌似跟win平台特别像。有一些软件例如搜狗拼音输入法的最新版是优麒麟平台独占的。

* **Manjaro**：
	
	>大多数使用linux作为编成开发人员推荐的发行版，在Distroatch上长期排名第一，桌面环境多样，本人只安装过KDE环境，资源占用也较大但相较于Gnome小很多，使用起来非常流畅，软件资源数量最多。并且对硬件的支持非常好，对内核和驱动都直接提供了图形操作界面，特别是Nvida闭源驱动直接在系统安装的时候就能搞定。此外，KDE可定制性非常强，你肉眼能看到的一个你几乎都能按照自己的喜好调整，整个系统界面可以被折腾得非常漂亮。事实上，Manjaro是三个中用起来我觉得最舒服的一个，但最终还是选择用回Ubuntu，主要是一些小问题，但是对我来说又很干扰我使用，一是manjaro不能直接安装deb包，但国内由于ubuntu以及deepin的流行，很多有linux客户端的国产软件都提供的是deb包，这种情况下下，每次我都还得转换一下才能使用。二是Manjaro取消了自带文件管理器的sudo权限，以至于修改一些系统文件特别麻烦。三是无法修改右键新建菜单。一般来说，linux只需要把自己常用格式文件放到home/user/模板文件夹中，即可在右键菜单中出现新建的选项，但不知为何manjaro取消了这一功能。总之，各种小问题凑在一起，就导致最终还是回到了ubuntu。假如你不在意这些小问题。那么Manjaro还是非常推荐的。

* **Deepin**
	
	>Deepin可以说是国内目前做得最好的linux发行版了，界面非常漂亮，而且对小白用户非常友好，从系统安装到软件安装都非常容易。深度资助开发DDE桌面环境非常适合习惯windows平台的朋友。此外，经过深度调教过的wine，也就是Deepin-wine，很多windows平台都直接打包了成deb了，包括微信、QQ等。此外，深度商店里面也有一大堆优质应用。总体上是很推荐不喜欢折腾电脑的，日常只用来办公的人使用。但是对于稍微爱折腾的用户来说，deepin目前是基于Debian stable，软件仓库相当旧，可能想用新软件的朋友们会觉得很麻烦。当时我用的时候，QGIS最新版死活装不上。此外桌面环境为DDE，不能兼容用得比较多的GTK+主题，所以自行替换主题的效果是第三方应用显示的是GTK主题，但Deepin自带应用是默认主题，这样就很丑了。另外，整个系统也还有一些bug。



​	总之，各位也可以自己去谷歌百度了解更多信息，以上只是本人使用感受的简要描述，具体的情况还是得看个人啦～总体上，比较推荐经常需要编程开发的人用Manjaro，追求稳定办公的用Deepin，个人当然还是推荐Ubuntu，可以适当折腾，日常使用也没太大问题，至少目前这台电脑已经作为日常使用的电脑。



---



## **二.  Windows及Ubuntu双系统安装**

### 2.1. 准备工作
本次安装以本人电脑为例，目前本人电脑配置如下：
惠普星14系列

名称 | 配置 
------- | ----------
处理器 | Intel® Core™ i5-8250U CPU @ 1.60GHz × 8
显卡 | 独显Nvida MX150 + 集显 Intel® UHD Graphics 620
硬盘 | 256G固态 + 1T 机械
内存 | 板载三星 DDR4 8G（本人近期将其更换为了16G）
操作系统 | windows10 1903

​	本次安装以Ubuntu18.04.3 LTS为例，这一版本是目前最新的长期支持版（Long Term Support），目前最新的是19.04，但这一版本是短期支持版，生命周期仅有9个月，下一个LTS是20.04，因此还是建议安装18.04。为了能一次性成功安装，请确保以下几点：

>1.  处理器建议至少2Ghz，双核或者以上；内存建议最少4G；硬盘至少25G以上（最好是固态硬盘）
>2.  Ubuntu18.04目前的内核版本还是4.18，对AMD的处理器以及显卡的支持不是太好，配置起来有些麻烦，所以建议AMD处理器或者显卡的电脑等下一个LTS再折腾。
>3.  建议使用集显或者集显以及N卡混合显卡的电脑折腾。
>4. 有一个8G或以上的U盘

### 2.2. win下电脑的设置
#### 2.2.1. 关闭Secure Boot
Secure Boot即安全启动，只可以启动Win8及以上系统，不能启动其他系统（包括USB、Linux）等。因此想要安装Ubuntu，首先要做的就是关闭Secure Boot。各个不同品牌的电脑进入BIOS的方法不同，请自行百度，关闭自己电脑的安全启动。
#### 2.2.2 确保启动方式为UEFI
 UEFI全称“统一的可扩展固件接口”(Unified Extensible Firmware Interface)， 是一种详细描述类型接口的标准。是一种全新的启动方式，一般较新的电脑都带这种启动方式，通常出厂预装Win10的系统是默认以这种方式启动的（有些USB启动盘启动PE后，无法发现硬盘，通常是由于USB启动盘未设置UEFI启动方式）
与之对应的是Legacy，传统的BIOS启动模式，能支持任何系统，现在的主板一般都带UEFI和Legacy两种启动方式的选择，近几年的电脑一般都是采用的UEFI，如果不清楚的话，请在windows下，找到“运行” -> 在“运行”中输入：msinfo32 -> 查看右边的信息，找到“BIOS模式”，看后面是否显示“UEFI”。
#### 2.2.3 GPT分区
GPT全名为Globally Unique Identifier Partition Table Format，即全局唯一标示磁盘分区表格式。GPT还有另一个名字叫做GUID分区表格式，我们在许多磁盘管理软件中能够看到这个名字。而GPT也是UEFI所使用的磁盘分区格式。
如何确认自己电脑的分区：windows系统下，用管理员模式打开命令提示行，输入Diskpart，回车后会弹出一个新窗口，即diskpart窗口，在这个窗口中输入list disk再回车，会列出电脑的磁盘，如果该硬盘Gpt一览有*号，就表明该磁盘是Gpt分区。如下图：

<center><img src="https://img-blog.csdn.net/20180524144757238?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2xuZnhiaWFueGl1/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="img" style="zoom: 80%;" /></center>
#### 2.2.4 关闭快速启动
从目前的一些反馈来看，如果windows平台下，快速启动模式是开启状态，似乎进入到Deepin后，挂载其他硬盘时，那些硬盘会变成只读模式，但是目前不清楚是否在Ubuntu下也会有影响，有人反映会影响ubuntu的引导。反正目前我是在windows中关闭了快速启动。关闭的方式为，win10中，控制面板，点击电源选项，点击左侧的“选择电源按钮功能”，取消勾选“启用快速启动”。


### 2.3 系统安装

#### 2.3.1 制作Ubuntu启动盘

1. 到[Ubuntu官网](https://ubuntu.com/download/desktop)下载最新的Ubuntu18.04.3 LTS

2. 到[Rufus官网](https://rufus.ie/)下载Rufu软件，该软件可以制做用于UEFI计算机的GPT分区的USB启动盘的制作
3. 打开Rufus，该软件打开即可运行无需安装，按照如下设置：

<center><img src="https://img-blog.csdnimg.cn/2019040220445529.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3BibGVhcm5pbmc=,size_16,color_FFFFFF,t_70" alt="img" style="zoom:80%;" /></center>
设备选择你的U盘，注意，制作启动盘会格式化U盘，请备份好数据。引导类型选择你下载的镜像文件，即iso文件。分区类型上面提到的选择GPT，目标类型为UEFI。其他的不用管。然后点击开始，等待制作完成。


#### 2.3.2 磁盘分区
这一步是为Ubuntu腾出安装空间，例如我的电脑windows系统是安在256的固态硬盘上，我准备安装双系统，Ubuntu也准备安在同一块硬盘上，此时我需要从这块硬盘上划出一块空间给Ubuntu。步骤如下(由于我的系统已经装好，这里是用的别人的图片)：
- 在windows开始菜单图标（就是那个左下角那个方格子）上右键，打开磁盘管理：

<center><img src="https://upload-images.jianshu.io/upload_images/6966151-ab4f8a778544015d.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp" alt="img" style="zoom:80%;" /></center>
- 你需要选择将你的一个磁盘分出来一部分空间用来安装双系统，根据你的实际情况选择使用哪个磁盘以及分出多大的空间，我在那块固态硬盘上分出了130多G。在选择好的磁盘上右键，选择“压缩卷”。

<center><img src="https://upload-images.jianshu.io/upload_images/6966151-181ec919f846aa10.png?imageMogr2/auto-orient/strip|imageView2/2/w/437/format/webp" alt="img" style="zoom:80%;" /></center>
- 填写你要分出的大小，如果你要作为日常使用，可以尽量多分一点，但同时也要保证留给windows足够多的空间。单位是MB，如果有强迫症的，可以百度一下分区计算器，可以保证分出一个整数，点击“压缩”

<center><img src="https://upload-images.jianshu.io/upload_images/6966151-56f3cc7b464f929e.png?imageMogr2/auto-orient/strip|imageView2/2/w/658/format/webp" alt="img" style="zoom:80%;" /></center>
- 只要你刚刚压缩出来的区域显示“未分配”，说明你压缩成功了！注意，就是要让他保持未分配的状态，不要再动它了！！

<center><img src="https://upload-images.jianshu.io/upload_images/6966151-4ca91acdbde7108a.png?imageMogr2/auto-orient/strip|imageView2/2/w/758/format/webp" alt="img" style="zoom:80%;" /></center>

#### 2.3.3 安装系统

确认以上所有步骤之后，插入刚才制作好的启动盘，电脑重启，开机进入Boot Manager，各个品牌电脑进入Boot的方法不一样，请自行百度，惠普的电脑是开机时，按F9键，进入如下界面。可以看到第一个选项一般是你自己电脑的硬盘，选这个的话电脑进入windows系统，下面另一个设备是你的U盘，我们用上下键移动到这个选项，然后回车。

<center><img src="https://upload-images.jianshu.io/upload_images/6966151-8447ef98f082282f.png?imageMogr2/auto-orient/strip|imageView2/2/w/1011/format/webp" alt="img" style="zoom:50%;" /></center>
之后，会进入到一个白底黑字的界面，上面有几个选项：

* try ubuntu without installing
* install ubuntu
* OEM install
* Check disc for defects

字面意思很好理解，如果你不了解这个系统，想先体验一下，就选择第一项，可以进入试用界面，里面可以体验Ubuntu的界面和基本操作，这个界面里面，桌面上也有安装选项，觉得满意可以开始安装。

这里我们直接选择第二项install ubuntu，回车，之后会开始进入安装界面：

* 首先是选择语言，选择中文

<img src="https://upload-images.jianshu.io/upload_images/6966151-69bd2aad6dc57259.png?imageMogr2/auto-orient/strip|imageView2/2/w/1153/format/webp" alt="img" style="zoom: 50%;" />

* 下面是选择键盘，选择English(US)

<img src="https://upload-images.jianshu.io/upload_images/6966151-75717b335c9a3e21.png?imageMogr2/auto-orient/strip|imageView2/2/w/1153/format/webp" alt="img" style="zoom:50%;" />

* 接下来是链接网络，你可以选择连接或不连接，连接的话会在安装过程中下载一些必要的组件与更新。开机后可以减少配置的时间。也可以选择不连接，开机后再处理。假如你的网络条件较好的话，建议选择连接。
* 下一步更新与软件，这里上面有“常规安装”和“最小安装”，这里根据自己的需求，常规安装会在安装系统时安装Gnome配套的各种软件，Thunderbird邮件应用，Libreffice等最小安装则只安装系统，这些软件都不会安装。下面的选项，假如你联网了，就选择第一项，安装时会联网下载更新，如果你没联网，或者网速很慢，就不勾选。至于下面的“为图形或无线硬件安装第三方软件”也可以勾选。

<img src="https://upload-images.jianshu.io/upload_images/6966151-e49c4f459c4fe240.png?imageMogr2/auto-orient/strip|imageView2/2/w/1148/format/webp" alt="img" style="zoom: 50%;" />

* <font color=#FF0000 size=5 >**下面是最重要的一点 即安装类型**</font>  

界面是这样的，注意，我们是要安装双系统，因此选择第一项，“安装Ubuntu与wingows10共存”，一定选这一项。网上很多很多教程都是选最后那个“其他选项”，然后手动分配各种分区，实际上很容易出错，导致安装失败。其实完全没有必要，Ubuntu已经聪明到会使用空闲的磁盘区域，自动按照需求分区。这里选择第一项，会自动将ubuntu安装到刚才磁盘分区中我们提到了那块空闲区域。

<img src="https://img-blog.csdn.net/2018052415330025?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2xuZnhiaWFueGl1/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="è¿éåå¾çæè¿°" style="zoom:80%;" />

* 接下来，一路下一步，按照自己的需求，设置时区、账户以及密码，最后开始安装。安装结束后，会提示重启电脑，按要求重启即可，这了有些人点击重启会卡住，或者没反应，长按电脑关机键强制关机即可。

不出意外的话，电脑开机就会显示Ubuntu标志性的基佬紫引导界面，首选项自然是Ubuntu，第三个选项是windows10。正常开机登陆后，我们就要进入下一步的配置啦～



ps1：有的人在登陆后会卡在一个紫屏，这个貌似根显卡有关，网上有很多教程，这里需要一些额外的设置。但是由于我没有遇到过，所以这里也不好列出方法。假如遇到了，可以按照网上的教程解决。

PS2：大家不用担心搞坏电脑，假如你确认每一步都是按照上面的指示，那么就不会出问题，假如Ubuntu出现问题，删掉就可以了，在开机时，上下键移动，选择第三项windows10，就可以正常启动原来的win10 系统啦，然后直接在磁盘管理中选择安装Ubuntu的分区，直接右键删除这个分区即可。




## **三. ubuntu系统设置、美化及软件安装**

关于ubuntu的配置美化，实际上网上的教程非常多，这了很多操作就直接复制了。

### 3.1 系统设置

#### 3.1.1 第一次更新






### 3.2 界面美化 





### 3.3 软件安装



#### 3.3.1 常用软件



Chrome





WPS





FoxitReader



Libreoffice



Zotero



Typora



TeXstudio



Calibre



网易云音乐



百度云网盘







Deepin-wine 项目

项目地址 [deepin-wine-ubuntu](https://github.com/wszqkzqk/deepin-wine-ubuntu)



Audacity



GIMP





深度截图



#### 3.3.2 语言学专业软件

##### 3.3.2.1 praat
语音学的同学最离不开的软件praat，除了常见的win版，mac版，  Paul Boersma and David Weenink 这两位大神实际上也做了linux版，官网左上角的[Download Praat](http://www.fon.hum.uva.nl/praat/)，点击那个linux，新页面中就是praat的安装方法啦～
Ubuntu系统下，打开你的终端，输入：

```
sudo apt install praat
```

回车键之后输入账户密码，等待安装完成。也可以到[Debian仓库](https://packages.debian.org/unstable/science/praat)下载deb包安装双击安装。
注意：如果是其他linux发行版，需要自行编译，下载下方的64-bit edition: praat6103_linux64.tar.gz，解压后在解压文件夹中右键，在当前文件夹中打开终端，输入

```
 ./configure
   make
   sudo make install
```
漫长的编译完成后，软件安装完毕，再在终端中输入`make clean`删除安装产生的临时文件

另外，praat的一些国际音标的显示需配合字体，官网推荐的是SIL制作的字体，下载页面也提供了安装方式，直接在终端中输入以下命令即可：

```
sudo apt-get install fonts-sil-charis
sudo apt-get install fonts-sil-doulos
```

至于Praat的使用方法，这里就不细说了，网上相关的教程以及书都有很多，请自行查阅。

##### 3.3.2.2 Elan
Elan是荷兰纽梅因马普心理语言学研究所开发的一个多媒体转写标注软件，在话语分析、态势语研究、语言存档、口语语料库建设、濒危语言或方言的保存等方面被广泛使用。[^1] 
Elan提供三种Windows、OSX以及Linux三种系统的安装包，[Elan官网](https://tla.mpi.nl/tools/tla-tools/elan/download/)下载deb包安装双击安装即可。linux下界面与windows下相同，可配合flex使用。

<img src="/home/luke/图片/深度截图_选择区域_20190918123907.png" alt="深度截图_选择区域_20190918123907" style="zoom: 33%;" />

##### 3.3.2.3 Flex

Flex全称FieldWorks  Language Explorer， 是由世界少数民族语文研究院（SIL）开发的一款软件，专门用于田野调查时的文本分析，语料标注以及辞典编纂。
软件的官网地址为 [FLEx](https://software.sil.org/fieldworks/)。该软件提供windows安装包，下载安装即可，但是linux下并不直接提供deb包，需要通过命令安装，官方也提供了[安装指导](http://packages.sil.org/)，步骤如下：
首先请确保系统为Ubuntu18.04，不同Ubuntu版本的安装有略微区别，打开终端，输入以下命令：

```
wget http://packages.sil.org/sil-repository.deb && sudo dpkg -i sil-repository.deb
sudo apt install fieldworks
```

安装时按照屏幕要求确认即可。

这种方式安装的是==FLEx最新的稳定版，即8.3版本==，如果想要体验最新的9.0.7版本，那么需要添加最新版本的源：

打开ubuntu的程序面板，打开“软件和更新”，选择“其他软件”选项，点击“添加”，在弹出的窗口中输入：

```
deb http://packages.sil.org/ubuntu bionic-experimental main
```
之后确认，关闭“软件和更新”此时会询问你是否要更新仓库，确认即可，之后打开终端，输入：
```
sudo apt update
```
此时，会出现最新版FLEx的更新，确认更新，等待更新完毕即可。如果想退出开发通道，在“软件和更新”中取消勾选上面添加的仓库地质或者直接删掉即可。Ubuntu下FLEx界面与windows下相同，功能也一样。
<center><img src="/home/luke/图片/深度截图_选择区域_20190918130457.png" alt="深度截图_选择区域_20190918130457" style="zoom:33%;" /></center>
需要注意的是，Flex在Ubuntu系统下目前==仅能调用系统默认的ibus输入框架==，而无法调用fcitx框架，这一点本人已经邮件问过官方的开发人员，因此，想要用这个软件的朋友们只能暂时选择放弃搜狗输入法了。


##### 3.3.2.4 QGIS
语言学还可能涉及到绘制语言地图，Windows平台下有许多绘图软件，常用的如ArcGIS，QGIS或者ArcGIS online等，ubuntu下同样也有相关软件，QGIS是开源GIS软件，在linux也可以安装使用，目前QGIS最新版为3.8.x Zanzibar，官方也提供了[安装指导](https://www.qgis.org/en/site/forusers/download.html)，根据自己的操作系统选择相应的指导，Ubuntu下安装方法如下：
- 第一步 与flex类似，需要添加软件仓库，可以手动添加，使用sudo 权限开/etc/apt/sources.list，在该文档中添加下列语句：
```
deb     https://qgis.org/ubuntu bionic main
deb-src https://qgis.org/ubuntu bionic main
```
保存，并关闭。也可以像FLEx那样，打开“软件和更新”，选择“其他软件”选项，点击“添加”，在弹出的窗口中输入：
```
deb     https://qgis.org/ubuntu bionic main
```
上述两种二选一即可。以上步骤完成后，需要打开终端，输入`sudo apt update`，更新软件仓库。 

- 第二步 添加公钥
打开终端，输入：
 ```
wget -O - https://qgis.org/downloads/qgis-2019.gpg.key | gpg --import
gpg --fingerprint 51F523511C7028C3
 ```

没有问题的情况下，终端中的返回信息应该如下：

```
pub   rsa4096 2019-08-08 [SCEA] [expires: 2020-08-08]
      	   8D5A 5B20 3548 E500 4487  DD19 51F5 2351 1C70 28C3
uid           [unknown] QGIS Archive Automatic Signing Key (2019) <qgis-developer@lists.osgeo.org>
```

以上信息如果没问题的话，继续在终端中输入：

```
gpg --export --armor 51F523511C7028C3 | sudo apt-key add -
```

- 第三布 安装，上述命令都执行完毕后，在终端中输入：

```
sudo apt-get update
sudo apt-get install qgis qgis-plugin-grass
```
一路确认，等待软件安装，安装完毕后，你的软件面板中就应该出现QGIS的主程序了，Ubuntu下QGIS界面与windows类似。
<center><img src="/home/luke/图片/深度截图_选择区域_20190918142457.png" alt="深度截图_选择区域_20190918142457" style="zoom: 33%;" /></center>
##### 3.3.2.5 R以及R Studio
3.3.2.5.1 安装R

R语言R是用于统计分析、绘图的语言和操作环境。R是属于GNU系统的一个自由、免费、源代码开放的软件，它是一个用于统计计算和统计制图的优秀工具。[^2]
一些语言学专业人员用R来进行统计分析以及绘图。它的安装方法与QGIS类似：

- 添加密钥  在终端中输入
```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
```
命令运行后，终端中会出现如下结果：
```
OutputExecuting: /tmp/apt-key-gpghome.4BZzh1TALq/gpg.1.sh --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
gpg: key 51716619E084DAB9: public key "Michael Rutter <marutter@gmail.com>" imported
gpg: Total number processed: 1
gpg:               imported: 1
```

- 添加仓库  继续在终端中输入：

```
sudo add-apt-repository 'deb https://cloud.r-project.org/bin/linux/ubuntu bionic-cran35/'
```
添加成功后，在终端中运行`sudo apt update`更新，不出意外，会出现如下内容：
```
Output...
Hit:2 https://cloud.r-project.org/bin/linux/ubuntu bionic-cran35/ InRelease
...
```
- 安装R   在终端中输入
```
sudo apt install r-base
```
安装成功后，程序面板中应该会出现R的图标，也可以在终端中输入`R`，回车，看是否能启动R。

<img src="/home/luke/图片/深度截图_选择区域_20190918145539.png" alt="深度截图_选择区域_20190918145539" style="zoom:33%;" />

3.3.2.5.1 安装R Studio

RStudio是一款R语言的IDE，R自带的环境操作起来可能不是方便，而Rstudio很好地解决了这个问题，而且它还具有调试、可视化等功能，支持纯R脚本、Rmarkdown (脚本文档混排)、Bookdown (脚本文档混排成书)、Shiny (交互式网络应用)等。[^3]
R Studio官方提供的deb包，直接[官网下载](https://www.rstudio.com/products/rstudio/download/#download)安装即可。注意：Ubuntu14/16/18的安装包是不同的。请一定要看清楚，下载错了是无法安装的。R studio 界面与windows下一致。

<img src="/home/luke/图片/深度截图_选择区域_20190918153442.png" alt="深度截图_选择区域_20190918153442" style="zoom:33%;" />



题外话：有些人还需要Pyhton，Ubuntu本身是自带python2的，直接终端打开，输入python即可打开。至于Python3，我的电脑大概在安装什么程序的时候依赖Python3，所记自动就安装上了，但具体当时是怎么安装的也记不清了，如果需要Python3，百度上有许多教程可参考，这里就不列出了。


##### 3.3.2.6 SPSS 
IBM SPSS Statistics 26是一款专业的统计分析软件，这款强大的综合分析软件将为用户带来更加快速、有效和深入的数据挖掘功能，它比电子表格、数据库或标准多维工具更加的实用和方便。
由于本人不用SPSS，但是有的做社会语言学的朋友或者需要统计数据的人会需要这一软件。因此我在网上找到了安装包，里面也提供了安装方法。有需要的可以自行跟着步骤安装，这里不再列出。
[SPSS](https://www.jb51.net/softs/691143.html#downintro2)











生命不息，折腾不止



[^1]:李斌. 用Elan建设单点方言多媒体语料库[J]. 方言, 2012(2):178-190.
[^2]:R语言[百度百科](https://baike.baidu.com/item/R语言/4090790?fr=aladdin)
[^3]:R与[R Studio的安装](https://www.jianshu.com/p/1a0f25086e8b)
