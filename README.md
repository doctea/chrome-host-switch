Host-switch

Ip domain switching tools:

Automatic switch -based proxy pac a domain name ip, without modifying hosts,
Convenient web developers to quickly switch between different / test / development / online environment

Can set ip alias

Such as:
```
127.0.0.1 web1
127.0.0.2 web2

# If other non- port 80 , the port can be increased

192.168.1.100 www.test.com:8888

```
Then visit http://www.test.com:8888/ that points 127.0.0.1:8888
then set
```
web1   www.xyz.com
web1   *.abc.com

```
支持通配符,类似泛域名解析

插件地址:

[url]http://shendongming.github.io/dist/chrome-host-switch.crx[/url]

截图:

添加界面

![ScreenShot](/snap/add2.png)
![ScreenShot](/snap/add3.png)

主界面

![ScreenShot](/snap/main.png)

支持模糊搜索
![ScreenShot](/snap/search.png)



搜索语法

全部字段搜索关键词 www
 www

全部字段搜索这2个关键词
www web


全部字段搜索这2个关键词 而且 ip包含 127
```
    www web ip:127
```


搜索语法仅仅 支持 and 逻辑


搜索 标签包含test
```
    tags:test
```
搜索 标签包含test 和 dev的
```
    tags:test tags:dev

```


