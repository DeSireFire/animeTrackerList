# animeTrackerList
动漫资源有效Tracker列表，动漫资源磁链死链解决和加速方案。
公共的（针对ACG资源）BitTorrent跟踪器的更新列表  
此项目，有别于以已存在的github项目：trackerslist，为天朝限定。  
还在为下载XX神社、爱X幕等等动漫资源即使加入trackerslist也没有速度而犯愁吗？  
这里的Trackers将更有对二次元资源下载加速的针对性。

#### 更新时间（Updated）: 2017-12-30 00:02:16 
该项目还在运行测试阶段
* AT_best(更新 25 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_best.txt 
* AT_all(更新 71 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all.txt 
* AT_all_udp(更新 0 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_udp.txt 
* AT_all_http(更新 75 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_http.txt 
* AT_all_https(更新 5 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_https.txt 
* AT_all_ws(更新 0 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_ws.txt 
* AT_best_ip(更新 3 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_best_ip.txt 
* AT_all_ip(更新 3 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_ip.txt 
* AT_bad(更新 118 个跟踪器): https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_bad.txt 

##### 功能介绍（这部分功能，尚未完成）
* 陆续支持以下站点的磁铁链接TrackerList整理
> https://share.dmhy.org  
> https://acg.rip  
> http://bt.acg.gg  
> http://mikanani.me  
> http://www.nyaa.si  
> https://share.acgnx.se  
> ~~http://www.kisssub.org~~  
* 检测 tracker 地址是否有效，tracker 地址去重。
* 机器人会自动检查跟踪器并更新列表。
* 具有相同域或指向相同IP地址以及无法连通或长时间超时的跟踪器将被删除。查看黑名单[blacklist](https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_bad.txt).
* 跟踪器按流行度和延迟（从最佳到最差）排序。
* 少数客户支持WebSocket跟踪器（AKA WebTorrent，ws，wss）。查看有关信息[More info](https://raw.githubusercontent.com/DeSireFire/animeTrackerList/master/AT_all_ws.txt)

##### api
(不知道有没有必要..)

##### 提供支持&联系我
* 你有希望增加的收集对象站点? => [Open a new issue](https://github.com/DeSireFire/animeTrackerList/issues/new)
* 你有希望加入公共的动漫资源加速的Tracker? => [Open a new issue](https://github.com/DeSireFire/animeTrackerList/issues/new)
* 有事情联系我？ => [Open a new issue](https://github.com/DeSireFire/animeTrackerList/issues/new)

##### Todo
* ~~要整合 trackerslist 项目中的trackers~~	 
* 还有两个网址的tracker没有收集  
* 实现api接口
* 更详细的使用说明
* ~~解决网站挂了，造成阻塞~~  

##### 升级日志
* repo创建！