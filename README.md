# Welcome to Goby
**Goby** is a new generation network security assessment tool. It can efficiently and practically scan vulnerabilities while sorting out the most complete attack surface information for a target enterprise. Goby can also quickly penetrate the company intranet based on a company's vulnerabilities exposed to the Internet.  We strive for Goby to become a more vital tool that can benchmark against hackers' actual attack methods and help companies effectively understand and respond to cyber-attacks. 

[Goby Official URL](https://gobies.org/)

### 0x001 Demo
[![5s8l2F.gif](https://z3.ax1x.com/2021/10/21/5s8l2F.gif)](https://imgtu.com/i/5s8l2F)
### 0x002 Download and install 
  [Goby download link](https://gobies.org/)
  [Goby FAQ](https://gobies.org/faq.html)
  
  Goby currently uses Golang  development, uses `Electron` and `VUE` as the front-end framework, supports windows, MacOS, and Linux without installation. Goby is based on network scanning, therefore permission is required to identify the NIC before using it.The installation methods of different platforms are as follows:

1. Windows 
   Download the [`Npcap`](https://nmap.org/npcap/dist/npcap-0.9995.exe) and install it.
2. MacOS 
   Run the following command：

```
1.  cd /dev
2.  sudo chown $USER:admin bp*
```
   For more information, see [Goby WiKi](https://github.com/gobysec/Goby/wiki)

### 0x003 Preset field description

**1. Rule bases** 
  Goby has built in more than 100,000 rule recognition engines. The coverage of hardware types includes `Network devices`, `IoT devices`, `Network Security products`, `office devices`, etc. The coverage of software types includes: `CRM`,`CMS`,`EMAIL`,`OA system`, etc.

**2. Protocol** 
  Goby has built in more than 200 protocol recognition engines, including: `Network protocols`, `Database protocols`, `IoT protocols` , `ICS protocols`, etc.

**3. Port** 
  In addition to common ports, Goby also groups ports based on security practices, including: `Enterprises`, `Cafes`, `Hotels`, `Airports`, `Databases`, `IoT`, `SCADA`, `ICS` and `Back door detection`.

**4. Common vulnerabilities and weak passwords** 
  Goby covers common critical vulnerabilities such as `Weblogic` and `Tomcat`, as well as preset account information of more than 1,000 devices.

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
- Constantly updating...… 

### 0x004 FAQ

  For more information about Goby FAQ, please visit [here](https://gobies.org/faq.html) 

### 0x005 Goby community 

- Contribute POC

  - First need to read [Goscanner_POC&#x2f;EXP _Writing_Manual](https://github.com/gobysec/Goby/wiki/Vulnerability-writing-guide(%E6%BC%8F%E6%B4%9E%E7%BC%96%E5%86%99%E6%8C%87%E5%8D%97))
  - Then read [Custom PoC Query Rule](https://github.com/gobysec/Goby/wiki/Query-Rule(Goby-Query-%E7%BC%96%E5%86%99%E6%8C%87%E5%8D%97))

  Please read [here](https://github.com/gobysec/Goby/blob/master/Feedback.md) first if you submit an error or demand suggestion.

If you have a functional type of issue, you can raise an issue on GitHub or in the discussion group below:

1. GitHub issue: https://github.com/gobysec/Goby/issues
2. WeChat Group: First add my personal WeChat: **gobyteam**, I will add everyone to the official WeChat group of Goby. 

