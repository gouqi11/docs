---
title: "设置超售上限"
date: 2022-02-07T18:26:01+08:00
weight: 60
description: >
    设置宿主机的CPU、内存超售比等
---

该功能用于设置宿主机CPU和内存的超售比以及系统预留内存，超售即宿主机提供超过自身拥有的CPU或内存资源，宿主机实际可分配资源为实际资源*超售比。一般情况下CPU超售比可以远大于1，内存超售比建议为1。

**单个宿主机调整超售上限**

1. 在左侧导航栏，选择 **_"主机/基础资源/宿主机"_** 菜单项，进入宿主机页面。
2. 单击宿主机右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"调整超售比"_** 菜单项，弹出修改属性对话框。
3. 设置以下参数：
    - CPU超售比上限：设置宿主机CPU的超售比上限，宿主机可分配虚拟机CPU数量 = 宿主机的CPU数量 * 超售比。
    - 内存超售比上限：设置宿主机内存的超售比上限，宿主机可分配虚拟机内存 = （宿主机实际内存 - 系统预留内存 ）* 超售比。
    - 系统内存预留（GB）：设置宿主机的系统预留内存，最低为1GB。宿主机的预留内存将不会用于分配虚拟机使用。
4. 单击 **_"确定"_** 按钮。

**批量调整超售比**

1. 在左侧导航栏，选择 **_"主机/基础资源/宿主机"_** 菜单项，进入宿主机页面。
2. 在宿主机列表中勾选一个或多个宿主机，单击列表上方 **_"批量操作"_** 按钮，选择下拉菜单 **_"调整超售比"_** 菜单项，弹出修改属性对话框。
3. 设置以下参数：
    - CPU超售比上限：设置宿主机CPU的超售比上限，宿主机可分配虚拟机CPU数量 = 宿主机的CPU数量 * 超售比。
    - 内存超售比上限：设置宿主机内存的超售比上限，宿主机可分配虚拟机内存 = （宿主机实际内存 - 系统预留内存 ）* 超售比。
    - 系统内存预留（GB）：设置宿主机的系统预留内存，最低为1GB。宿主机的预留内存将不会用于分配虚拟机使用。
4. 单击 **_"确定"_** 按钮。