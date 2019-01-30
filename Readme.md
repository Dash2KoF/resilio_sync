# Sync介绍




# 使用方法：
## 下载和安装
如果有vpn尽量选择从官网下载最新版本，如果没有vpn可以选择从github搬运页下载相应版本
##### [官网下载页](https://www.resilio.com/individuals/)
##### [github搬运页](https://github.com/zuikme/resilio_sync/releases)    

**Windows**    
安装如果想要开机自动启动并长久使用可选择注册为系统服务，此种方法只能使用web界面操作。     
正常情况下推荐不注册为系统服务，并启用开机自动启动。

**Linux**     
因为Linux发行版本非常多，强烈建议去官网看相应版本的安装教程，这个是最好的。      
也可以下载已经编译好的二进制文件，不太建议使用这种方法，但是如果实在安装不好也可以使用这种。     
树莓派性能较低需要使用armhf版本，特别注意。     

**Mac**    
在苹果的商店里搜不到，官网下载或者github搬运页下载直接安装即可使用。

**Android**    
建议直接去google play搜索安装，这样最好。如果无法使用谷歌可以去搬运页下载安装。

**ios**    
直接去苹果商店搜索安装，没有别的方法。

**Nas**    
Nas版本太多了，一般在Nas的应用商店里都有，可以直接去搜索安装。     
建议去官网看教程，官网有针对各种Nas的安装教程。      
如果你的Nas型号厂商比较特殊，可以按照Linux版本的安装方法安装。


## 添加证书
使用证书获得Pro授权，证书可以自行去官网购买，价格很贵。    
我购买了Pro证书，后来发现了一个洞，这个授权是本地授权，只要屏蔽了证书验证就可以一个证书很多人用。    
**下面提供方法：**       
1. 下载你喜欢的证书，这里提供两个证书，右键链接另存为   
[个人版](https://raw.githubusercontent.com/zuikme/resilio_sync/master/key/Resilio_Sync_Personal.btskey)
[家庭版](https://raw.githubusercontent.com/zuikme/resilio_sync/master/key/Sync_Home_70878.btskey)    
2. 在程序内应用任意一个证书，即可获得永久pro授权。    
3. 修改hosts，防止证书验证导致pro丢失，在hosts文件中添加下面这行     
**127.0.0.1 license.resilio.com**      

## 后续优化
建议安装ZeroTier，加入虚拟网络，能够寻找到更多节点。   
请自行搜索并了解ZeroTier，以便后面的使用

## 具体使用
sync是一款基于P2P技术的文件同步与共享软件。    
里面的key可以说是一份资源的钥匙，相当与种子下载中的种子，通过不同的key我们可以连接上不同的资源。    
大家可以自行寻找自己需要的key。

# Sync Key　资源站点推荐　　　
- 零网sync　key页，这个很多资源，大家自行寻找   
- [btsynckeys：Public Directory of BitTorrent Sync Keys](https://www.btsynckeys.com/)    
- [802e1fkeys：BTSync KEYS的一个合集页面，里面的keys还是比较多的，各种类型都有](http://wherebt.com/blog/2017/blog0418.html)       
- [BTsynckeys：reddit里面的一个版本，专门用来分享key的，体验不是特别好](https://www.reddit.com/r/BTsynckeys/)    
- [同步范：Sync 资源站](https://syncfan.com/)

# 交流与学习
QQ交流群：716421724   
官网：https://www.resilio.com/individuals/




## 一些介绍文章
https://bookfere.com/post/347.html   
https://www.iplaysoft.com/bittorrent-sync.html   
https://jingyan.baidu.com/article/a378c960de4c12b328283087.html   
