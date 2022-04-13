
# Awesome-hacking-tools
好用的工具收集、大部分我都用过。部分会写上自己的感想，希望对你有帮助 / A collection of useful tools, most of which I have used. I hope it will be helpful to you

[TOC]

## 信息收集

> 分享一波自己觉得还不错的外网信息收集工具，在用工具收集完信息后，再结合手动的一些信息收集。提高效率的同时也更容易收获漏洞。 排名不分先后，感谢师傅的分享精神，网络安全有你们真不错!



### nemo_go

**开源 | 信息收集 | Golang | 资产管理**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/image-20220409234442857.png)

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/image-20220409234424091.png)



**简介:** Nemo是用来进行自动化信息收集的一个简单平台，通过集成常用的信息收集工具和技术，实现对内网及互联网资产信息的自动收集，提高隐患排查和渗透测试的工作效率，用Go语言完全重构了原Python版本

**点评:** 集成了IP资产、域名资产、指纹信息、API接口 、Poc验证与目录扫描、分布式任务。这一套操作还是界面可视化的，可以满足基础的对资产收集的需求了。还是开源项目，有不喜欢的地方可以自己二开，太香了。看了最近更新还是2022-3-8，个人开发者不容易，支持！

**地址:** https://github.com/hanc00l/nemo_go








### SiteScan

**开源 | 信息收集 | Python**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/image-20220410150134627.png)

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/image-20220410150157188.png)

**简介:** 专注一站式解决渗透测试的信息收集任务。包括域名ip历史解析、nmap常见端口爆破、子域名信息收集、旁站信息收集、whois信息收集、网站架构分析、cms解析、备案号信息收集、CDN信息解析、是否存在waf检测、后台寻找以及生成检测结果html报告表等。

**点评:** python开发，自己写扫描器从里面参考点代码也是不错滴

**地址:** https://github.com/kracer127/SiteScan









### linglong

**开源 | 信息收集 | Golang | 资产管理**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/640.png)
![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/640-1.png)

**简介:** 一款资产巡航扫描系统。系统定位是通过masscan+nmap无限循环去发现新增资产，自动进行端口弱口令爆破/、指纹识别、XrayPoc扫描。主要功能包括: `资产探测`、`端口爆破`、`Poc扫描`、`指纹识别`、`定时任务`、`管理后台识别`、`报表展示`

**点评:** 我自己开发的，强行推荐一波

**地址:** https://github.com/awake1t/linglong





### scaninfo

**开源 | 信息收集 | Golang | 资产管理**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/image-20220410150844017.png)

**简介:** 开源、轻量、快速、跨平台 的红队内外网打点扫描器。快速的端口扫描和服务识别比masscan更快。包含fscan的绝大部份功能除了poc扫描和自定义字典

**地址:** https://github.com/redtoolskobe/scaninfo





### AppInfoScanner

**开源 | 移动端 | 信息收集 | Python**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/AppInfoScanner.png)


**简介:** 一款适用于以HW行动/红队/渗透测试团队为场景的移动端(Android、iOS、WEB、H5、静态网站)信息收集扫描工具，可以帮助渗透测试工程师、攻击队成员、红队成员快速收集到移动端或者静态WEB站点中关键的资产信息并提供基本的信息输出,如：Title、Domain、CDN、指纹信息、状态信息等

**点评:** 用过，可以快速或者一些资产。

**地址:** https://github.com/kelvinBen/AppInfoScanner





### Glass

**开源 | 信息收集 | Python | 空间搜索引擎**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/Glass.png)
![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/Glass.png)


**简介:** Glass是一款针对资产列表的快速指纹识别工具，通过调用Fofa/ZoomEye/Shodan/360等api接口快速查询资产信息并识别重点资产的指纹，也可针对IP/IP段或资产列表进行快速的指纹识别。

**点评:** 直接集成了，用起来方便

**地址:** https://github.com/s7ckTeam/Glass


### Banli

**信息识别 | Golang | 高危扫描**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/banlii.png)

**简介:** Banli是一款极其简单好用的高危资产识别和高危漏洞扫描工具。Banli要解决的问题是如何快速识别企业的高危资产，如何快速扫描企业的高危漏洞。包括Web资产、中间件资产、框架资产、安全设备等高危资产的识别，包括Web漏洞、命令执行漏洞、反序列化等高危漏洞的扫描. 作者：[0e0w](https://github.com/0e0w)

**地址:** https://github.com/Goqi/Banli




### ksubdomain

**开源 |  Golang | 域名收集**

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/aa.png)

![image](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/ksubdomain1.png)

**简介:** ksubdomain是一款基于无状态的子域名爆破工具，类似无状态端口扫描，支持在Windows/Linux/Mac上进行快速的DNS爆破，拥有重发机制不用担心漏包。

**地址:** https://github.com/boy-hack/ksubdomain







## 泄露扫描


### Packer Fuzzer

**开源 | 信息收集 | Python  | 1.3k Star**

![image-20220411195806686](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411195806686.png)

**简介:** **一款针对Webpack等前端打包工具所构造的网站**进行快速、高效安全检测的扫描工具。本工具支持自动模糊提取对应目标站点的API以及API对应的参数内容，并支持对：未授权访问、敏感信息泄露、CORS、SQL注入、水平越权、弱口令、任意文件上传七大漏洞进行模糊高效的快速检测。在扫描结束之后，本工具还支持自动生成扫描报告，您可以选择便于分析的HTML版本以及较为正规的doc、pdf、txt版本

**点评:** 如果你遇到VUE的站点，这个工具可能会给你带来惊喜

**地址:**https://github.com/rtcatc/Packer-Fuzzer




### JSFinder

**开源 | 信息收集 | Python | 1.5k Star**

![image-20220411185403267](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411185403267.png)



**简介:** JSFinder是一款用作快速在网站的js文件中提取URL，子域名的工具。提取URL的正则部分使用的是[LinkFinder](https://github.com/GerbenJavado/LinkFinder)

**点评:** 速度快，信息收集时候用起来还是很不错的！

**地址: **https://github.com/Threezh1/JSFinder





### HostCollision

**开源 | 信息收集 | Java  | 296 Star**

![image-20220411195030542](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411195030542.png)

![image-20220411195051733](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411195051733.png)

**简介:** 用于host碰撞而生的小工具,专门检测渗透中需要绑定hosts才能访问的主机或内部系统

**点评:** 在内网渗透中，有时候利用成功了。就离拿下不远了

**地址:** https://github.com/pmiaowu/HostCollision



### dirsearch

**开源 | 目录扫描 | Python  | 7.8k Star**

![image-20220411195456025](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411195456025.png)

**简介:**  网站路径扫描。使用字典破解网站目录和文件。而且支持递归破解

**点评:** 界面好看又快，作者还一直持续更新

**地址:https://github.com/maurosoria/dirsearch**



### gobuster

**开源 | 目录扫描  | Golang | 5.8k Star**

![image-20220411195418463](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411195418463.png)

**简介:** 跟dirsearch一样，可以爆破网站目录。功能还丰富点

- dir：传统的目录爆破模式
- dns：DNS子域名爆破模式
- vhost：虚拟主机爆破模式

**点评:** Golang版本，学习go的同学可以看看源码。能学习不少

**地址:**https://github.com/OJ/gobuster





### SecretFinder

**开源 | 信1息收集 | Python  | 7.8k Star**

![image-20220411200355799](https://github.com/awake1t/Awesome-hacking-tools/blob/main/img/02/image-20220411200355799.png)

**简介:** SecretFinder是一个基于LinkFinder的python脚本, 用来发现JavaScript中的敏感数据，如apikeys, accesstoken，未授权，jwt等

**点评:** 重点是规则，可以参考下他的规则

**地址:**https://github.com/m4ll0k/SecretFinder



> 欢迎各位大佬推荐你觉得很赞的项目，我的微信

















