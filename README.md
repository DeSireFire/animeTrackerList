# animeTrackerList
动漫资源有效Tracker列表，动漫资源磁链死链解决和加速方案。
公共的（针对ACG资源）BitTorrent跟踪器的更新列表  
此项目，有别于以已存在的github项目：trackerslist，为天朝限定。  
还在为下载XX神社、爱X幕等等动漫资源即使加入trackerslist也没有速度而犯愁吗？  
这里的Trackers将更有对二次元资源下载加速的针对性。

` 点个Star嘛~又不麻烦。 ` 

让我知道我是在做一件有意义的事情，感谢支持。

```text
还有，发布BT资源的人或者群体呐!!!
能不能长点心，不要写些什么奇奇怪怪的tracker地址上来啊!!!
地址中用中文符号“：、。”之类的，
带中括号[]和空格的Tracker地址是什么鬼！
```

#### 更新时间（Updated）: 2020-06-19 12:11:25 

> RAW

```text
* AT_best(更新 25): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_best.txt 
* AT_all(更新 351): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all.txt 
* AT_all_udp(更新 145): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_udp.txt 
* AT_all_http(更新 198): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_http.txt 
* AT_all_https(更新 62): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_https.txt 
* AT_all_ws(更新 2): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_ws.txt 
* AT_best_ip(更新 2): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_best_ip.txt 
* AT_all_ip(更新 8): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_ip.txt 
* AT_bad(更新 579): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_bad.txt 
```

> Aria2 逗号分隔

```text
* ATaria2_best(更新 25): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_best.txt 
* ATaria2_all(更新 351): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_all.txt 
* ATaria2_all_udp(更新 145): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_all_udp.txt 
* ATaria2_all_http(更新 198): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_all_http.txt 
* ATaria2_all_https(更新 62): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_all_https.txt 
* ATaria2_all_ws(更新 2): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_all_ws.txt 
* ATaria2_best_ip(更新 2): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_best_ip.txt 
* ATaria2_all_ip(更新 8): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_all_ip.txt 
* ATaria2_bad(更新 579): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/ATaria2_bad.txt 
```

> 缓存加速(部分用户反映github有时无法访问,可使用此链接)

接口测试ing  

```text
注意 : 若不添加get参数或参数不正确时,默认返回AT-best的内容。因为get方式传参的原因,下划线"_"使用了小横线"-"代替。

[RAW]
https://at.raxianch.moe/?type=AT-best
https://at.raxianch.moe/?type=AT-all
https://at.raxianch.moe/?type=AT-all-udp
https://at.raxianch.moe/?type=AT-all-http
https://at.raxianch.moe/?type=AT-all-https
https://at.raxianch.moe/?type=AT-all-ws
https://at.raxianch.moe/?type=AT-best-ip
https://at.raxianch.moe/?type=AT-all-ip
https://at.raxianch.moe/?type=AT-bad

[Aria2]
https://at.raxianch.moe/?type=ATaria2-best
https://at.raxianch.moe/?type=ATaria2-all
https://at.raxianch.moe/?type=ATaria2-all-udp
https://at.raxianch.moe/?type=ATaria2-all-http
https://at.raxianch.moe/?type=ATaria2-all-https
https://at.raxianch.moe/?type=ATaria2-all-ws
https://at.raxianch.moe/?type=ATaria2-best-ip
https://at.raxianch.moe/?type=ATaria2-all-ip
https://at.raxianch.moe/?type=ATaria2-bad
```


##### 功能介绍（这部分功能，尚未完成）
* 陆续支持以下站点的磁铁链接TrackerList整理
> https://share.dmhy.org  
> https://acg.rip  
> http://bt.acg.gg  
> http://mikanani.me  
> http://www.nyaa.si  
> https://share.acgnx.se  
> https://www.anirena.com  
> ~~http://www.kisssub.org~~  
* 检测 tracker 地址是否有效，tracker 地址去重。
* 机器人会自动检查跟踪器并更新列表。
* 具有相同域或指向相同IP地址以及无法连通或长时间超时的跟踪器将被删除。查看黑名单[blacklist](https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_bad.txt).
* 跟踪器按流行度和延迟（从最佳到最差）排序。
* 少数客户支持WebSocket跟踪器（AKA WebTorrent，ws，wss）。查看有关信息[More info](https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_ws.txt)

##### 简单使用说明

使用方法具体，大致分为两大类：

* 自己拼接磁性链接的tracker

<details>
<summary>展开查看</summary>

磁链格式：
> magnet:?xt=urn:btih:{ 下载资源的hash值 }&dn={ 资源名称，此处可留空 }&tr={ 资源跟踪器（tracker） }&tr={ 资源跟踪器（tracker） }.....  

使用项目中 AT_best.txt 等等 文本url中的 tracker 来构造自己的磁性链接。  

举例:

打开项目中的 AT_best.txt 文本链接，得到以下跟踪器：
```bash
http://exodus.desync.com/announce
http://mkfs.ru/announce
https://1337.abcvg.info/announce
http://0123456789nonexistent.com/announce
http://tracker.kisssub.org/announce
http://pt.lax.mx/announce
http://tr.bangumi.moe/announce
http://tracker.acgnx.se/announce
http://tracker.tfile.co/announce
https://open.kickasstracker.com/announce
http://tracker.tfile.me/announce.php
http://tracker.trackerfix.com/announce
http://ehtracker.org/1226599/1080494xo5eXcwFOBq/announce
http://peersteers.org/announce
http://tracker.btcake.com/announce
https://tracker.fastdownload.xyz/announce
http://ehtracker.org/1113709/announce
http://t1.pow7.com/announce
http://tracker.baka-sub.cf/announce
http://tracker.bittorrent.am/announce.php
http://atrack.pow7.com/announce
http://torrent.nwps.ws/announce
http://tracker.shuim.net/announce.php
http://denis.stalker.h3q.com/announce.php
http://tracker.tfile.me/announce
```
根据磁性链接的格式，构造出新磁性链接即可  
> magnet:?xt=urn:btih:Z7ZDIYEBZHIKE7MOZJQKLYVHWX5SEKMH&dn=喵喵喵&tr=http://exodus.desync.com/announce&tr=http://mkfs.ru/announce&tr=https://1337.abcvg.info/announce&tr=....

等等等（多个tacker,即&tr={ 资源跟踪器（tracker） }，无上限..）


最后，把构造好磁性链接复制下来，给下载器使用就行，就不赘述了。
</details>

* 使用的BT下载工具：  

<details>
<summary>展开查看</summary>

得看具体是使用什么BT下载器，以Bitcomet为例：

在Bitcomet软件里添加下载任务时弹出的任务属性里（也可以右键选择属性），选择“高级设置”选项卡，在服务器列表里添加Tracker服务器地址。

将https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all.txt 等 文件url里的内容粘贴上去即可。

![image](https://user-images.githubusercontent.com/18726905/60825706-dc290c00-a1de-11e9-9098-4cb1ccb42f19.png)
</details>

##### 提供支持&联系我
* 你有希望增加的收集对象站点? => [Open a new issue](https://github.com/DeSireFire/animeTrackerList/issues/new)
* 你有希望加入公共的动漫资源加速的Tracker? => [Open a new issue](https://github.com/DeSireFire/animeTrackerList/issues/new)
* 有事情联系我？ => [Open a new issue](https://github.com/DeSireFire/animeTrackerList/issues/new)

##### Todo
* 更详细的使用说明

##### other
[Power2All](https://github.com/Power2All) 允许本项目 对 [anirena](https://github.com/Power2All) 的收录。爱她~

```text
推荐一下~

各位发布者，
欢迎到anirena发布种子资源，
anirena的tracker性能在天朝还是挺不错的。
但是注意遵守人家的规则。
```

##### 升级日志
* 添加对anirena的专项采集支持
* 更新README
* 开发处理速度更快的种子检测方案
* 优化tracker地址合法性检测
* 迁移部署服务器
* 实现api接口,压缩URL长度和使用CF做访问优化
* 修改readme的排版
* 优化检测逻辑
* fix 部分trackerURL格式不正确的bug
* 添加aria2支持，增加使用逗号分隔的trackers
* 整理一下readme的排版
* 更新频率改为正午和凌晨0点两次
* 缩短BT种子测试时间,修复去重时出现的错误
* 解决animeTrackers_all_ip内存冗余问题，解决set去重导致顺序混乱的问题
* 修改readme文件,报错问题，查明原因 http://bt.acg.gg  这网站挂了，造成阻塞。添加遇阻跳过的功能。
* 修改best Trackers的筛选方式。
* 未筛选出新的跟踪器时，跟踪器列表保留前一天的列表不变。
* 临时解决种子信息获取问题，降低对bestIP的苛刻程度。
* 增加对新的网站的采集，解决列表存在的冗余问题。
* 调整对tracker筛选的苛刻程度，修复线程堆积的问题。
* 优化采集算法，加快采集速度，优化排序，测试新的bestip判定方法，优化计时启动。
* 修复tracker列表有冗余的问题
* repo创建！
