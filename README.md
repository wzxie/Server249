# Server249
本仓库旨在帮助用户快速熟悉河北师范⼤学分⼦细胞⽣物学实验室（教育部省部共建重点实验室）计算资源。

## 集群配置
河北师范⼤学分⼦细胞⽣物学实验室（教育部省部共建重点实验室）计算资源部署包含一套SonmiHPC高性能集群系统与一台戴尔高性能计算服务器。

1）SonmiHPC集群配置为CPU：Intel(R) Xeon(R) Platinum 8470 * 2，共计208线程；内存：64GB DDR5 * 16，共计1024G；系统盘：2TB（两块960GB SSD，RAID1）；共享存储：352TB（22 * 16TB HDD，RAID6）。

2）Dell服务器配置为CPU：Intel Xeon E7-8860 v4 * 4，共计144线程；内存：16GB DDR4 * 32，共计512G；共享存储：384TB（24 * 16TB HDD，RAID6）。

3）两套系统之间通过双口万兆以太网、双千兆网口及IPMI管理网口进行互联，实现数据的高速共享。

![hardware](https://github.com/wzxie/Server249/blob/main/Hardware.png)

## 友情链接
集群手册：https://github.com/wzxie/Server249/wiki

SonmiHPC教程：https://sonmihpc.com/user-guide/home.html

[slurm作业调度系统使用指南.pdf](https://github.com/wzxie/Server249/blob/main/slurm%E4%BD%9C%E4%B8%9A%E8%B0%83%E5%BA%A6%E7%B3%BB%E7%BB%9F%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97.pdf)
