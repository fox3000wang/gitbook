# 内网学习文档


## 内网gitbook文档服务器介绍
> 由于gitbook启动服务只能打开一本书，书多了就要启动很多服务非常难管理。
>
> 现在解决的方案就是另外启动一个http server， gitbook只负责把书build出来，然后部署到http server上。
>
> 现在默认书存放的服务器放在192.168.50.197上



## 使用指南

* jenkins 到**note-learning**标签下
![](/assets/32B2B435-F63D-4756-B879-AFF48D159EED.png)

* New Item， 拷贝gitbook的配置
![](/assets/3FD47574-87DC-4821-A612-5D28B74420F3.png)

* 用你编辑好的gitbook替换掉 Repository URL
![](/assets/BBD7CC98-40F3-4A55-B1D8-FDD94FE31B79.png)

* 等待build结束
![](/assets/E9105862-E98B-4045-8B9F-59DA0A3B93C8.png)

* 浏览器输入： http://192.168.50.197/
![](/assets/B66974F6-C4A5-4DAE-BEC5-306C297827D2.png)