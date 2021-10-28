# taobao-data
爬取淘宝的评论并对评论进行情感分析

## 我要怎么运行？

同时，直接打开配置文件`Infor.conf`并按照如下编写可以运行项目:

    [taobao]
    name=
    pageNumber=
    url=
    Cookie=
    referer=

其中，`name`可以随意填写，目的是给你这次要爬取的东西起个名字，`pageNumber`则是你想要爬取的篇评论页数，`url`不是网页的url，而是评论区的url
需要你通过在网页端打开开发者工具，找到一个叫做"list"的文件，复制它的地址.`Cookie`十分关键，所以这个一定要有,获取方法也是在开发者工具中“headers”查找，`referer`同样也在“headers”中查找
