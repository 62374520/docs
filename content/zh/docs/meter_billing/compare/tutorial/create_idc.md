---
title: "添加本地IDC虚拟机到价格清单"
date: 2022-01-25T14:41:14+08:00
weight: 10
description: >
    将本地IDC的虚拟机加入到价格清单进行比价
---

1. 在左侧导航栏，选择 **_"费用/价格比对/价格清单"_** 菜单项，进入价格清单页面。
2. 在价格清单页面，选择顶部页签为“本地IDC”。
3. 配置以下参数：
    - 数量：选择虚拟机的数量。
    - 平台：支持{{<oem_name>}}平台和VMware平台。
    - CPU架构：目前支持x86和aarch64架构。仅{{<oem_name>}}平台支持aarch64架构，其他平台默认只支持x86架构。
    - 是否配置GPU：是否为虚拟机配置GPU卡，启用该项后，还需要选择具体GPU卡型号和块数。目前只有{{<oem_name>}}平台的宿主机上存在GPU卡才能启用该项。
    - CPU核数、内存：设置虚拟机的规格。并可以根据虚拟机规格等选择可用套餐。
    - 套餐：虚拟机套餐为虚拟机CPU、内存规格的组合搭配，不同套餐价格不同。
    - 系统盘：设置系统盘的类型和大小。
    - 数据盘：数据盘域系统盘类型相同，设置数据盘大小。
4. 查看选中配置的虚拟机的费用。
5. 如需将其与其它平台，不同配置的虚拟机做对比，需要单击 **_"加入清单"_** 按钮，加入到价格清单。