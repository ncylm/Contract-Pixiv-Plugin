# Contract-Pixiv-Plugin
点图姬插件 for 契约机器人

![](https://ww1.sinaimg.cn/large/0060lm7Tgy1feazpjej61j30u01hch91.jpg)
![](https://ww4.sinaimg.cn/large/0060lm7Tgy1feazrnbe38j30u01hcgva.jpg)

#### 默认指令：

|指令|描述|
|:-----|:-----|
|一图|从Pixiv周榜前20名中随机发送一张|
|最新|发送最新被提交到Pixiv的作品|
|搜图 string keyword|按指定关键字搜索，并在搜索结果中随机发送一张|
|点图 int PixivID|发送指定ID的Pixiv作品|
|设置类型  string type|设置「一图」指令查找的作品类型|
|设置返回数量 int num|设置「一图」指令查找的作品数量|
|…|…|
|点图姬|返回帮助信息|

#### 其他
type 可用值: daily,weekly,monthly,male,female ~~and more~~. 具体可上Pixiv查询更多分类

num 取值范围: [1,50]
