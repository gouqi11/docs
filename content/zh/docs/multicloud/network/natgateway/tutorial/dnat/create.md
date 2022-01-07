---
title: "新建DNAT规则"
date: 2021-12-13T16:00:58+08:00
weight: 10
description: >
    新建DNAT规则
---

1. 在NAT网关列表，单击NAT网关名称项，进入NAT网关详情页面。
2. 单击DNAT页签，进入DNAT页面。
3. 单击列表上方 **_"新建"_** 按钮，弹出创建DNAT条目对话框。
4. 设置以下参数：
    - 条目名称：DNAT条目名称。
    - 公网IP地址：选择未被绑定的弹性公网IP。
{{% alert title="说明" %}}
用于创建SNAT条目的公网IP不能再用来创建DNAT条目。
{{% /alert %}}
    - 虚拟机：选择提供互联网服务的虚拟机。
    - 公网端口：进行端口转发的外部端口。
    - 私网端口：进行端口转发的内部端口
    - 协议类型：转发端口的协议类型。
5. 单击 **_"确定"_** 按钮，创建DNAT条目。