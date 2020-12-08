# Welcome to Goby
Goby是一款新的网络安全测试工具，它能够针对一个目标企业梳理最全的攻击面信息，同时能进行高效、实战化漏洞扫描，并快速的从一个验证入口点，切换到横向。我们希望能够输出更具生命力的工具，能够对标黑客的实际能力，帮助企业来有效地理解和应对网络攻击。
### 0x001 Demo
![img](https://cn.gobies.org/static_front/img/scan.gif)
### 0x002 下载并安装
[Goby下载地址](https://cn.gobies.org/)   [FAQ](https://gobies.org/faq.html)
Goby目前是使用Go语言开发、采用Electron+VUE前端框架的绿色版本，支持windows/MacOS/Linux，无需安装。因Goby基于网络扫描，所以使用前，请先赋予goby识别网卡的权限。方式如下：
1. Windows用户 
   [下载Npcap](https://nmap.org/npcap/dist/npcap-0.9983.exe)数据捕获包，安装完成后，启动goby。 
2. MacOS用户 
   执行以下命令：
```
1.  cd /dev
2.  sudo chown $USER:admin bp*
```
### 0x003 预置数据说明
**1. 规则库** 
超过10万种规则识别引擎，硬件覆盖范围：网络设备，物联网设备，网络安全产品，办公设备等，软件覆盖范围：CRM，CMS，EMAIL，OA系统等。
**2. 协议** 
超过200种协议识别引擎，覆盖网络协议，数据库协议，IoT协议，ICS协议等。
**3. 端口** 
除了常用端口，我们还根据安全实战场景进行了端口分组，包括企业、咖啡馆、酒店、机场、数据库、物联网、SCADA、ICS、后门检测等。
**4. 漏洞及弱口令** 
覆盖Weblogic，Tomcat等最严重漏洞及超过1000种设备的预置账号信息。
- [CVE-2020-2551](https://github.com/gobysec/GobyVuls/blob/master/WebLogic/CVE-2020-2555)
- [CVE-2020-2555](https://github.com/gobysec/GobyVuls/blob/master/WebLogic/CVE-2020-2555)
- CVE-2020-1938 
- CVE-2020-10189
- CVE-2020-11651
- CVE-2020-11710
- [CVE-2020-7961](https://github.com/gobysec/GobyVuls/blob/master/LiferayPortal/CVE-2020-7961)
- CVE-2020-12116
- CVE-2019-10758
- CVE-2019-3799
- [CVE-2019-19781](https://github.com/gobysec/GobyVuls/blob/master/Citrix/CVE-2019-19781)
- CVE-2019-3948
- [CVE-2018-1000861](https://github.com/gobysec/GobyVuls/tree/master/Jenkins/CVE-2018-1000861)
- [CVE-2018-7600](https://github.com/gobysec/GobyVuls/tree/master/Drupal/CVE-2018-7600)
- CVE-2018-1297
- CVE-2018-13379
- [CVE-2017-5638](https://github.com/gobysec/GobyVuls/tree/master/Struts2/S2-046(CVE-2017-5638))
- CVE-2017-5878
- CVE-2017-17215
- [CVE-2017-1000353](https://github.com/gobysec/GobyVuls/blob/master/Jenkins/CVE-2017-1000353)
- CVE-2016-4437
- [CVE-2016-3088](https://github.com/gobysec/GobyVuls/tree/master/ActiveMQ/CVE-2016-3088)
- [CVE-2013-2251](https://github.com/gobysec/GobyVuls/tree/master/Struts2/S2-016(CVE-2013-2251))
- CVE-2011-3556
- [ThinkPHP2.1_RCE](https://github.com/gobysec/GobyVuls/tree/master/ThinkPHP/ThinkPHP2.1_RCE)
- [ThinkPHP5_RCE](https://github.com/gobysec/GobyVuls/tree/master/ThinkPHP/ThinkPHP5_RCE)
持续更新中… 
### 0x004 问题
有关Goby常见问题详情请参考：<a href="https://gobies.org/faq.html" target="_blank">FAQ表</a>
FAQ表：<a href="https://gobies.org/faq.html" target="_blank">https://gobies.org/faq.html</a>
### 0x005 Goby社区
如有问题可以在 GitHub 提 issue, 也可在下方的讨论组里
1. GitHub issue: https://github.com/gobysec/Goby/issues
2. Telegram: http://t.me/gobies
3. 微信群: 加我的个人微信chenrong-1013，会把大家拉到Goby官方微信群。（群内福利：提前1个月享受版本更新）
