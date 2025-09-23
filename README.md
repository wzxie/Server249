# Server249
本仓库旨在帮助用户快速熟悉河北师范⼤学分⼦细胞⽣物学实验室（教育部省部共建重点实验室）计算资源。

## 集群配置
河北师范⼤学分⼦细胞⽣物学实验室（教育部省部共建重点实验室）计算资源部署包含一套SonmiHPC集群系统与一台戴尔高性能计算服务器。
1）SonmiHPC计算节点配置为两颗Intel Xeon Platinum 8470处理器（共208线程）、1 TB DDR5内存，并配备由两块960 GB SSD组成的RAID 1系统盘及由22块16 TB HDD组成的292 TB RAID 6共享存储。
2）戴尔服务器则配置四颗Intel Xeon E7-8860 v4处理器（共144线程）、512 GB DDR4内存及320 TB存储。
3）两套系统通过双口万兆以太网、双千兆网口及IPMI管理网口进行互联。

组件  规格型号	详细配置
1. SonmiHPC 集群系统		
计算节点	主板：T3DE	
CPU	Intel® Xeon® Platinum 8470	2颗，总计208线程
内存	DDR5	16条 × 64 GB @ 4800MHz，总计1 TB
系统存储	SSD	2块 × 960 GB，配置为RAID 1
共享存储	HDD	22块 × 16 TB，配置为RAID 6，总可用容量约292 TB
2. 戴尔高性能计算服务器		
CPU	Intel® Xeon® E7-8860 v4 @ 2.2GHz	4颗，单颗18核心，总计72核心
内存	DDR4	32条 × 16 GB，总计512 GB
存储	HDD	总容量320 TB
3. 网络互联		
网络接口		双口万兆以太网 + 2个千兆板载网口 + 专用IPMI管理网口


## 常用链接
细胞组服务器简介：https://github.com/wzxie/Server249/wiki

XieLab服务器简介：https://github.com/wzxie/Server249/wiki

SonmiHPC教程：https://sonmihpc.com/user-guide/home.html

