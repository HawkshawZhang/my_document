目　录

第一部分　Linux的规则与安装

第0章　计算机概论

计算机：辅助人脑的好工具

　计算机硬件的五大单元

　CPU的种类

　接口设备

　运作流程

　计算机分类

　计算机上面常用的计算单位(大小、速度等)

个人计算机架构与接口设备

　CPU

　内存

　显卡

　硬盘与存储设备

　PCI适配卡

　主板

　电源

　选购须知

数据表示方式

　数字系统

　文字编码系统

软件程序运行

　机器程序与编译程序

　操作系统

　应用程序

重点回顾

本章习题

参考数据与扩展阅读

第1章　Linux是什么

Linux是什么

　Linux是什么

　Linux之前UNIX的历史

　关于GNU项目

Torvalds的Linux开发

　Minix

　对386硬件的多任务测试

　初次释出Linux 002

　Linux的开发：虚拟团队的产生

　Linux的内核版本

　Linux distributions

Linux的特色

　Linux的特色

　Linux的优缺点

　关于授权

重点回顾

本章习题

参考数据与扩展阅读

第2章　Linux如何学习

Linux当前的应用角色

　企业环境的利用

　个人环境的使用

鸟哥的Linux苦难经验回忆录

　鸟哥的Linux学习之路

　学习心态的分别

　X Window的学习

有心向Linux操作系统学习者学习态度

　从头学习Linux基础

　选择一本易读的工具书

　实践再实践

　发生问题怎么处理

鸟哥的建议(重点在Solution的学习)

重点回顾

本章习题

参考数据与扩展阅读

第3章　主机规划与磁盘分区

Linux与硬件的搭配

　认识计算机的硬件配置

　选择与Linux搭配的主机配置

　各硬件设备在Linux中的文件名

磁盘分区

　磁盘连接的方式与设备文件名的关系

　磁盘的组成复习

　磁盘分区表(partition table)

　开机流程与主引导分区(MBR)

　Linux安装模式下，磁盘分区的选择(极重要)

安装Linux前的规划

　选择适当的distribution

　主机的服务规划与硬件的关系

　主机硬盘的主要规划

　鸟哥说：关于练习机的安装建议

　鸟哥的两个实际案例

　大硬盘配合旧主机造成的无法开机问题

重点回顾

本章习题

参考数据与扩展阅读

第4章　安装CentOS 5x与多重引导小技巧

本练习机的规划(尤其是分区参数)

开始安装CentOS 5

　调整启动媒体(BIOS)

　选择安装结构与开机

　选择语系数据

　磁盘分区

　引导装载程序、网络、时区设置与root密码

　软件选择

　其他功能：RAM testing、安装笔记本电脑的内核参数(Option)

安装后的首次设置

多重引导安装流程与技巧

　新主机仅有一块硬盘

　旧主机有两块以上硬盘

　旧主机只有一块硬盘

关于大硬盘导致无法开机的问题

重点回顾

本章习题

参考数据与扩展阅读

第5章　首次登录与在线求助man page

首次登录系统

　首次登录CentOS 5x图形界面

　GNOME的操作与注销

　KDE的操作与注销

　X Window与命令行模式的切换

　在终端界面登录linux

在命令行模式下执行命令

　开始执行命令

　基础命令的操作

　重要的热键[Tab], [ctrl]-c, [ctrl]-d

　错误信息的查看

Linux系统的在线求助man page与info page

　man page

　info page

　其他有用的文件(documents)

超简单文本编辑器：nano

正确的关机方法

　数据同步写入磁盘：sync

　惯用的关机命令：shutdown

　重启、关机：reboot, halt, poweroff

　切换执行等级：init

开机过程的问题排解

　文件系统错误的问题

　忘记root密码

重点回顾

本章习题

参考数据与扩展阅读

第二部分　Linux文件、目录与磁盘格式

第6章　Linux的文件权限与目录配置

用户与用户组

Linux文件权限概念

　Linux文件属性

　如何改变文件属性与权限

　目录与文件的权限意义

　Linux文件种类与扩展名

Linux目录配置

　Linux目录配置标准：FHS

　目录树(directory tree)

　绝对路径与相对路径

　CentOS的查看

重点回顾

本章练习

参考数据与扩展阅读

第7章　Linux文件与目录管理

目录与路径

　相对路径与绝对路径

　目录的相关操作

　关于执行文件路径的变量：$PATH

文件与目录管理

　查看文件与目录：ls

　复制、删除与移动：cp, rm, mv

　取得路径的文件名与目录名称

文件内容查阅

　直接查看文件内容

　可翻页查看

　数据选取

　非纯文本文件：od

　修改文件时间或创建新文件：touch

文件与目录的默认权限与隐藏权限

　文件默认权限：umask

　文件隐藏属性：chattr, lsattr

　文件特殊权限：SUID, SGID, SBIT

　查看文件类型：file

命令与文件的查询

　脚本文件名的查询

　文件名的查找

权限与命令间的关系(极重要)

重点回顾

本章习题

参考数据与扩展阅读

第8章　Linux磁盘与文件系统管理

认识EXT2文件系统

　硬盘组成与分区的复习

　文件系统特性

　Linux的EXT2文件系统(inode)

　与目录树的关系

　EXT2/EXT3文件的访问与日志文件系统的功能

　Linux文件系统的操作

　挂载点(mount point)的意义　

　其他Linux支持的文件系统 与VFS　

文件系统的简单操作

　磁盘与目录的容量：df, du

　连接文件：ln

磁盘的分区、格式化、检验与挂载

　磁盘分区：fdisk

　磁盘格式化

　磁盘检验：fsck, badblocks

　磁盘挂载与卸载

　磁盘参数修改

设置开机挂载

　开机挂载/etc/fstab及/etc/mtab

　特殊设备loop挂载(镜像文件不刻录就挂载使用)

内存交换空间(swap)的构建

　使用物理分区构建swap

　使用文件构建swap

　swap使用上的限制

文件系统的特殊查看与操作

　boot sector与superblock的关系

　磁盘空间的浪费问题

　利用GNU的parted进行分区行为

重点回顾

本章习题

参考数据与扩展阅读

第9章　文件与文件系统的压缩与打包

压缩文件的用途与技术

Linux系统常见的压缩命令

　Compress

　gzip, zcat

　bzip2, bzcat

打包命令：tar

　tar

完整备份工具：dump

　dump

　restore

光盘写入工具

　mkisofs：新建镜像文件

　Cdrecord：光盘刻录工具

其他常见的压缩与备份工具

　dd

　Cpio

重点回顾

本章习题

参考数据与扩展阅读

第三部分　学习shell与shell script

第10章　vim程序编辑器

vi与vim

为何要学vim

vi的使用

简单执行范例

按键说明

一个案例练习

vim的保存文件、恢复与打开时的警告信息

vim的功能

块选择(Visual Block)

多文件编辑

多窗口功能

vim环境设置与记录：～/vimrc, ～/viminfo

vim常用命令示意图

其他vim使用注意事项

中文编码的问题

DOS与Linux的断行字符

语系编码转换

重点回顾

本章练习

参考数据与扩展阅读

第11章　认识与学习bash

认识bash这个shell

硬件、内核与shell

为何要学命令行界面的shell

系统的合法shell与/etc/shells功能

bash shell的功能

bash shell的内置命令：type

命令的执行

shell的变量功能

什么是变量

变量的显示与设置：echo, unset

环境变量的功能

影响显示结果的语系变量(locale)

变量的有效范围

变量键盘读取、数组与声明：read，array，declare

与文件系统及程序的限制关系：ulimit

变量内容的删除、替代与替换

命令别名与历史命令

命令别名设置：alias，unalias

历史命令：history

Bash Shell的操作环境

路径与命令查找顺序

bash的登录与欢迎信息：/etc/issue, /etc/motd

bash 的环境配置文件

终端机的环境设置：stty, set

通配符与特殊符号

数据流重定向

什么是数据流重定向

命令执行的判断依据：;，&&, ||

管道命令(pipe)

选取命令：cut, grep

排序命令：sort，wc，uniq

双向重定向：tee

字符转换命令：tr，col，join，paste，expand

切割命令：split

参数代换：xargs

关于减号-的用途

重点回顾

本章习题

参考数据与扩展阅读

第12章　正则表达式与文件格式化处理

前言：什么是正则表达式

什么是正则表达式

正则表达式对于系统管理员的用途

正则表达式的广泛用途

正则表达式与Shell在Linux当中的角色定位

扩展的正则表达式

基础正则表达式

语系对正则表达式的影响

grep的一些高级参数

基础正则表达式练习

基础正则表达式字符(characters)

sed工具

扩展正则表达式

文件的格式化与相关处理

格式化打印：printf

awk：好用的数据处理工具

文件比较工具

文件打印准备：pr

重点回顾

本章习题

参考数据与扩展阅读

第13章　学习shell script

什么是shell script

为什么学习shell script

第一个script的编写与执行

编写shell script的良好习惯

简单的shell script练习

简单范例

script的执行方式区别(source, shscript, /script)

善用判断式

利用test命令的测试功能

利用判断符号[]

shell script的默认变量($0, $1)

条件判断式

利用ifthen

利用caseesac判断

利用function功能

循环(loop)

while do done, until do done(不定循环)

fordodone(固定循环)

fordodone的数值处理

shell script的追踪与调试

重点回顾

本章习题

参考数据与扩展阅读

第四部分　Linux使用者管理

第14章　Linux账号管理与ACL权限设置

Linux的账号与用户组

用户标识符：UID与GID

用户账号

有效与初始用户组：groups, newgrp

账号管理

新增与删除用户：useradd, 相关配置文件, passwd, usermod, userdel

用户功能

新增与删除用户组

账号管理实例

主机的具体权限规划：ACL的使用

什么是ACL

如何启动ACL

ACL的设置技巧：getfacl, setfacl

用户身份切换

su

sudo

用户的特殊shell与PAM模块

特殊的shell, /sbin/nologin

PAM模块简介

PAM模块设置语法

常用模块简介

其他相关文件

Linux主机上的用户信息传递

查询用户：w, who, last, lastlog

用户对谈：write, mesg, wall

用户邮件信箱：mail

手动新增用户

一些检查工具

特殊账号(如纯数字账号)的手工新建

批量新建账号模板(适用于passwd --stdin参数)

批量新建账号的范例(适用于连续数字，如学号)

重点回顾

本章习题

参考数据与扩展阅读

第15章　磁盘配额(Quota)与高级文件系统管理

磁盘配额(Quota)的应用与实践

什么是Quota

一个Quota范例

实践Quota流程1：文件系统支持

实践Quota流程2：新建Quota配置文件

实践Quota流程3：Quota启动、关闭与限制值设置

实践Quota流程4：Quota限制值的报表

实践Quota流程5：测试与管理

不改动既有系统的Quota实例

软件磁盘阵列(Software RAID)

什么是RAID

software, hardware RAID

软件磁盘阵列的设置

仿真RAID错误的救援模式

开机自动启动 RAID 并自动挂载

关闭软件RAID(重要！)

逻辑卷管理器(Logical Volume Manager)

什么是LVM：PV, PE, VG, LV的意义

LVM实作流程

放大LV容量

缩小LV容量

LVM的系统快照

LVM相关命令汇整与LVM的关闭

重点回顾

本章习题

参考数据与扩展阅读

第16章　例行性工作(crontab)

什么是例行性工作

Linux工作调度的种类：at, cron

Linux上常见的例行性工作

仅执行一次的工作调度

atd的启动与at运行的方式

实际运行单一工作调度

循环执行的例行性工作调度

用户的设置

系统的配置文件：/etc/crontab

一些注意事项

可唤醒停机期间的工作任务

什么是anacron

anacron与/etc/anacrontab

重点回顾

本章习题

第17章　程序管理与SELinux初探

什么是进程(process)

进程与程序(process & program)

Linux的多用户、多任务环境

工作管理(job control)

什么是工作管理

job control的管理

脱机管理问题

进程管理

进程的查看

进程的管理

关于进程的执行顺序

系统资源的查看

特殊文件与程序

具有SUID/SGID权限的命令执行状态

/proc/* 代表的意义

查询已打开文件或已执行程序打开的文件

SELinux初探

什么是SELinux

SELinux的运行模式

SELinux的启动、关闭与查看

SELinux网络服务运行范例

SELinux所需的服务

SELinux的策略与规则管理

重点回顾

本章习题

参考数据与扩展阅读

第18章　认识系统服务(daemons)

什么是daemon与服务(service)

daemon的主要分类

服务与端口的对应

daemon的启动脚本与启动方式

解析super daemon的配置文件

默认值配置文件：xinetdconf

一个简单的rsync范例设置

服务的防火墙管理xinetd, TCP Wrappers

/etc/hostsallow, /etc/hostsdeny管理

TCP Wrappers特殊功能

系统开启的服务

查看系统启动的服务

设置开机后立即启动服务的方法

CentOS 5x默认启动的服务简易说明

重点回顾

本章习题

参考数据与扩展阅读

第19章　认识与分析日志文件

什么是日志文件

syslogd：记录日志文件的服务

日志文件内容的一般格式

syslog的配置文件：/etc/syslogconf

日志文件的安全性设置

日志文件服务器的设置

日志文件的轮替(logrotate)

logrotate的配置文件

实际测试logrotate的操作

自定义日志文件的轮替功能

分析日志文件

CentOS默认提供的logwatch

鸟哥自己写的日志文件分析工具

重点回顾

本章习题

参考数据与扩展阅读

第五部分　Linux系统管理员

第20章　启动流程、模块管理与Loader

第21章　系统设置工具(网络与打印机)与硬件检测

第22章　软件安装：源码与Tarball

第23章　软件安装：RPM、SRPM与YUM功能 　

第24章　X Window设置介绍　

第25章　Linux备份策略　

第26章　Linux内核编译与管理　

附录A　快速索引　