---
title: "创建快照"
date: 2022-01-06T16:19:00+08:00
weight: 40
description: >
    为虚拟机创建快照
---

快照是一种数据备份方式，可以在指定时间点对虚拟机的系统盘、数据盘或虚拟机整体创建一个完全可用拷贝，便于虚拟机故障后快速回退到创建快照时的虚拟机状态。

{{% alert title="注意" color="warning" %}}
- {{<oem_name>}}平台同时支持创建硬盘快照和主机快照。
- 状态异常的硬盘不支持创建硬盘快照。
- 主机快照占的快照配额数等于主机上的硬盘数，即若主机上有2块硬盘，为该主机创建主机快照所站的快照配额为2。
{{% /alert %}}

1. 在左侧导航栏，选择 **_"主机/主机/虚拟机"_** 菜单项，进入虚拟机页面。
2. 单击虚拟机右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"实例设置-创建快照"_** 菜单项，弹出新建快照对话框。
3. 配置以下参数：
    - 快照类别：包括硬盘快照和主机快照，硬盘快照即为单块磁盘创建快照；主机快照即为虚拟机整体创建快照。
    - 当选择快照类别为“创建硬盘快照”，配置以下参数：
        - 选择磁盘：选择需要备份的磁盘。
        - 快照名称：设置硬盘快照名称。
    - 当选择快照类别为“创建主机快照”，配置以下参数：
        - 快照名称：设置主机快照名称。
        - 同时新建内存快照：仅虚拟机开机状态下支持勾选该项，即创建快照时同时为内存创建快照，后续可基于内存快照恢复内存。
4. 单击 **_"确定"_** 按钮，创建快照。
