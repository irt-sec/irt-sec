ICE Red Team(IRT) 工控测试系统

# 基础环境：
- Windows ltsc 2019 用户名：Administrator 密码：irt
## 程序应用环境
- Windows组件环境：
    - 微软常用组件库
- .Net Framework
- Oracle Java 1.8
- Golang 1.12.5
    - Golang IDE编辑器 liteide
- Python Anaconda 3.7
    - 已配置清华镜像源，与Python2.7环境。py27激活方式为```activate py27```，退出为```deactivate py27```，具体其它命令可以搜索查阅，强烈安利。
## 安全工具
### 协议测试
scapy    //python 协议库
kittyfuzzer    //python tcp、udp协议fuzz框架
### 服务探测
nmap    //
ipscan    //端口扫描
### 流量协议分析
wireshark    //
科来网络分析系统 12 技术交流版    //流量包解析，重放
### 数据包测试
burp suite 2.1    //
postman    //http测试
TCPUDPbg    //tcp、udp发包测试
### 内网分析
### 密码利用
### 安全测试
zaproxy    //主被动web主机应用测试
metasploit    //
sqlmap    //
cobaltstrike    //
### 系统调试
dism++    //
### 数据恢复
winhex    //十六进制编辑器
### 分析调试
binwalk    //firmware测试，需要在wsl下启动
x64dbg    //64位 32位程序调试
火绒剑    //系统调试
### 防护软件
D盾    //
## 常用软件
bandzip    //压缩软件
Firefox    //
navicat premium    //数据库连接器
wps    //office办公套
rolan    //工具管理
notepad++    //
everything    //文件查找
ftpserver    //
mobaxterm    //类似于xshell多终端远程连接器
迅雷极速    //
cmder    //命令行加强版，通过bash、wsl等启动wsl系统
#### cmder下快捷键
sqlmap    //alias文件内
binwalk    //固件分析。安装在wsl下
msfconsole    //环境变量中

## Linux系统环境 WSL Ubuntu 16.04
- 用户：kali
- root用户密码：1
    - kali用户是Ubuntu自带python环境，切换到root用户即可。所有软件和环境都是装在root用户下，所以需要先切换到root用户
- Python Miniconda 3.7
    - 已配置清华镜像源，与Python2.7环境。py27激活方式为```source activate py27```，退出为```source deactivate py27```，具体其它命令可以搜索查阅，强烈安利。
## 安全工具
### 分析调试
binwalk    //固件、二进制文件分析调试
### 漏洞查找
searchsploit    //IRTexploit-db下
<br>
***
## ICS工控测试(ICSwiki)
- exploit    //收集利用脚本/工具
    - IRTexploit-db    //exploit-db.com.要善于利用searchsploit
    - IRTmetasploit    //msf相关利用插件
- framework    //ics工控测试框架
    - isf    //工控测试
    - routersploit    //iot测试
- nse    //收集Nmap脚本
- pcap    //收集工控协议数据包
- protocol    //收集工控协议库
    - fuzz
        - FuzzAegis    //工控协议测试。目前支持snap7
- tool    //收集相关工具
    - https://github.com/thiagoralves/OpenPLC_v3    //OpenPLC is an open-source Programmable Logic Controller that is based on easy to use software.基础PLC控制器和PLC编辑环境
<br>
***
在众多开源项目上增删改查，万分感谢！！！
包括不限于：<br>
- https://www.exploit-db.com
- https://github.com/w3h/icsmaster
- https://github.com/ITI/ICS-Security-Tools
<br>


IRT Windows 安全测试系统

链接：https://pan.baidu.com/s/17ddhNNP4ze3-m9OdKU_SjQ 

提取码：ujrd 
复制这段内容后打开百度网盘手机App，操作更方便哦
