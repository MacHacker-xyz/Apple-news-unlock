# Apple-news-unlock
> ## Apple News in China
### Apple news 中国大陆地区解锁🔓，让你的Apple one订阅物有所值
![Apple news in China](https://media.idownloadblog.com/wp-content/uploads/2022/01/Apple-News-iPhone-Mac-Apple-Watch.jpg)
## 注意事项
1. 在一切开始前请将你的iPhone iPad 或Mac设备的地区改为美国地区，同时iCloud中必须登录了美区ID
2. 在使用脚本前一定要开启Wi-Fi网络，该解锁必须在有Wi-Fi网络的条件下才能完成
3. 请在使用脚本前打开科学上网软件，同时你的节点应该为提供Apple news服务的地区的节点，否则徒劳
4. 请确保你的iPhone iPad上安装有苹果官方的地图软件和苹果官方的Apple news应用软件
## iPhone和iPad Apple News解锁
- [点击下载](https://www.icloud.com/shortcuts/29cb8fdee87545f4953f61c4aafd7dee)iPhone的Apple News解锁快捷方式
- [点击下载](https://www.icloud.com/shortcuts/d5177ac4b61e4d9f8de08a792643e188)iPad的Apple New解锁快捷方式
- 你可以将快捷方式添加到主屏幕，然后将其图标设置成Apple news官方图标，就可以达到以假乱真的目的，同时也可以做到苹果公司所推崇的无缝化的用户体验感
## Mac Apple News解锁
[点击下载](https://www.icloud.com/shortcuts/5942afcf23a449ba8039f86598330c29)Mac的Apple News解锁
## Apple watch端暂时没有解锁方案
Apple watch端暂时没有可行的解锁方案，因为Apple watch没有主流翻墙协议的适配，没法连接到美国的Apple news服务器，所以任然unavailable
## 关于原理
经过我对反复试验发现苹果的地域检测API是基于运营商的，在开启✈️模式时就检测不出来在中国大陆。Maps软件会打开时会根据运营商所属国家提供对应服务，如果检测出中国大陆运营商就会链接到高德地图的API，当你打开Apple News时软件会读取地图软件中的地图服务提供商作为依据，所以如果没有改变地图中的服务商，科学上网也无法解开封锁。本软件找到了能触发地图软件改变服务地区的方式，并实现自动化操作让解锁过程变得简单。如果你固定到主屏幕并更换图标，这一过程将会更加丝滑流畅。
