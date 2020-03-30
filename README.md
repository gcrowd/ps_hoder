# pcap stream hoder
## 背景
  此项目为熟悉github开发流程而创建

## 暂定目标
  为常见网络流量分析场景中，无法用一般命令实现的操作，提供简单易用的封装（外部依赖不限，脚本实现均可）

## 应用场景分析
  1. 要使用基tcp stream的程序分析一个很大的pcap文件。读大包分析过慢。所以需要将大pcap按tcp stream存储为pcap文件后，再根据所需合并为小pcap文件

## 环境准备
  1. yum install wireshark
