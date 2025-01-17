---
title: "查看未恢复告警"
date: 2022-01-14T15:49:20+08:00
weight: 10
description: >
    查看所有未恢复告警的告警记录
---
### 查看未恢复告警

当告警策略发生告警时，用户可在界面右上角![](../../../images/alertpolicytip.png)查看到告警策略的数量等，单击查看按钮可跳转到未恢复告警页面。

1. 在左侧导航栏，选择 **_"监控/告警/告警历史"_** 菜单项，进入告警历史页面。
2. 查看所有未恢复告警的最新报警记录。
2. 支持查看以下信息：
    - 策略名称：触发告警的资源匹配的告警策略的名称。
    - 触发时间：发生告警的时间。
    - 状态：仅包括发生报警的状态。
    - 资源类型：告警策略的类型。
    - 策略详情：告警策略的具体规则信息。
    - 告警级别：显示当前告警记录的级别，包括普通、重要、致命。
    - 资源数量：匹配告警策略的告警资源的数量，支持点击展开查看资源的名称、IP、平台、触发告警的值等。
    - 消息状态：包括已发送、已收敛。当告警消息因为消息静默期未发送时，状态显示为已收敛。
    - 查看：查看告警记录详情，包含触发告警的资源的触发告警的值，以及资源上告警相关参数的标签。



### 查看致命告警

当除云账号类型外影响平台正常运行的默认策略发生告警时，将会弹出“发出致命告警”的弹框，此时平台不可操作，需要对告警进行处理。

仅在管理后台下支持查看致命告警的弹框提示。

1. 当平台发生致命告警并弹框时，弹框中默认展示告警信息，包括策略名称、触发时间、报警级别、触发条件、资源数量、资源名称等。
2. 需要管理员对告警进行处理。
    - 查看详情：单击 **_"查看详情"_** 按钮，关闭弹框并跳转到非恢复告警页面。查看告警信息并进行处理。
    - 稍后处理：单击 **_"稍后处理"_** 按钮，关闭弹框，后续刷新页面将会继续弹框提醒。

