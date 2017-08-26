# 爱丽丝网络
这是一个免费的shadowsocks，为了服务长久，采用众筹的模式，捐助？当然，但是不需要使用者掏钱，让马云和刘强东来掏钱。

捐助者只需要在京东或者淘宝买东西之前，点下面的链接，在淘宝买东西，就点`淘宝链接`，在京东买东西，就点`京东链接`，如果购买的商品有推广计划，我就会得到一点推广费用。放心，商品价格都是一样的。
怎么样？举手之劳，就可以让别人掏钱捐助shadowsocks服务，只要用的人越多，捐助者越多，就会有源源不断的资金，保证这个免费的shadowsocks服务持续运行。

- ### [淘宝链接](https://ai.taobao.com/search/index.htm?fcat=3306&key=计算机网络&pid=mm_48510912_36052737_128472059)
- ### [京东链接](https://union-click.jd.com/jdc?d=HmJ6Nd)

## 速度怎么样？
周五晚上，北京移动可以跑满50M带宽

## shadowsocks地址
```
#无混淆地址，Windows客户端因为目前不支持混淆，请使用此地址
ss://YWVzLTI1Ni1nY206d3d3LmxpdWJvcGluZy5jb21AcHViLmxpdWJvcGluZy5jb206ODA=

#适用带http混淆插件的客户端，速度不快，请尝试安装混淆插件，适用此地址，速度可能会明显提升
ss://YWVzLTI1Ni1nY206d3d3LmxpdWJvcGluZy5jb20@pub.liuboping.com:80?plugin=obfs-local%3Bobfs-host%3Dpub.liuboping.com%3Bobfs%3Dhttp#pub

#Linux
ss-local -s pub.liuboping.com -p 80 -b 127.0.0.1 -l 1090 -m aes-256-gcm -k www.liuboping.com -t 300 --plugin obfs-local --plugin-opts "obfs=http;obfs-host=pub.liuboping.com"
```
