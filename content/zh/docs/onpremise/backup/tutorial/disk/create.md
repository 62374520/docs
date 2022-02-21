---
title: "新建硬盘备份"
date: 2022-02-17T15:35:46+08:00
weight: 10
description: >
    为硬盘文件创建备份
---

新建硬盘备份有两个入口，一是为虚拟机的某块磁盘创建备份，二是在硬盘列表中为某块硬盘创建备份。

### 为虚拟机硬盘创建备份

1. 在左侧导航栏，选择 **_"主机/主机/虚拟机"_** 菜单项，进入虚拟机页面。
2. 单击虚拟机右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"实例配置 - 创建备份"_** 菜单项，弹性创建备份对话框。
3. 配置以下参数：
    - 备份类型：选择备份类型为“硬盘备份”。
    - 选择磁盘：选择需要备份的磁盘。
    - 备份名称：设置硬盘备份的名称。
    - 备份存储：选择存储备份文件的备份存储。
4. 单击 **_"确定"_** 按钮，完成操作。

### 为硬盘创建备份

仅支持为已挂载到虚拟机上的硬盘进行备份。

1. 在左侧导航栏，选择 **_"主机/存储/硬盘"_** 菜单项，进入硬盘页面。
2. 单击虚拟机右侧操作列 **_"更多"_** 按钮，选择下拉菜单 **_"新建备份"_** 菜单项，弹性新建备份对话框。
3. 配置以下参数：
    - 备份名称：设置硬盘备份的名称。
    - 备份存储：选择存储备份文件的备份存储。
4. 单击 **_"确定"_** 按钮，完成操作。