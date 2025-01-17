---
title: "组织架构"
weight: 2
description: var_oem_name平台支持新建组织架构，目前支持域和项目的组织架构。
---

{{<oem_name>}}平台支持新建组织架构，目前支持域和项目的组织架构，新建后可以增加多个层级分别维护不同层级的域或项目。

**入口**：在云管平台单击左上角![](../../../images/intro/nav.png)导航菜单，在弹出的左侧菜单栏中单击 **_"认证与安全/认证体系/组织架构"_** 菜单项，进入认证源页面。

  ![](../../../images/iam/org.png)

{{% alert title="说明" %}}
- 平台中目前只能存在一种组织架构，域/项目在新建组织架构时需要选择。
- 在域/项目列表中给对应的域/项目打上层级的标签，也可以将域/项目添加到组织架构中
{{% /alert %}}

## 新建组织架构

该功能用于新建组织架构。

1. 在组织架构页面，单击列表上方 **_"新建组织架构"_** 按钮，进入新建组织架构页面。
2. 配置以下参数：
    - 名称：组织架构的名称。
    - 组织架构类型：支持选择域或项目。
    - 备注：组织架构的备注。
3. 单击 **_"确定"_** 按钮，新建域组织架构或项目组织架构。

## 配置组织架构

该功能用于配置组织架构的层级、权重等。

**入口**：在域/项目组织架构页面单击左上角 ![](../../../images/iam/nav1.png) 操作菜单。

### 新建层级

该功能用于为组织架构新增层级。

1. 单击组织架构名称或其他层级后，单击 ![](../../../images/iam/nav1.png) 操作菜单，单击 **_"新建"_** 按钮，弹出新建对话框。
2. 配置一下参数：
    - 父组织：当前节点归属于哪个层级下，例如刚新建完成的组织架构，父组织只能选择新建完成的组织架构名称。
    - 层级描述：层级描述是对当前层级的说明，例如：层级描述是省市，名称是北京市；层级描述是区县，名称是朝阳区。
    - 名称：层级的名称。
    - 权重：展示组织架构时，同级别的节点按照权重大小排序。
    - 备注：当前层级的备注。
3. 单击 **_"确定"_** 按钮，完成操作。

### 修改层级

该功能用于修改组织架构的层级信息，根节点支持修改名称和备注，其它层级支持修改权重和备注。

1. 单击组织架构名称或其他层级后，单击 ![](../../../images/iam/nav1.png) 操作菜单，单击 **_"修改"_** 按钮，弹出修改对话框。
2. 修改相关信息后，单击 **_"确定"_** 按钮，完成操作。

### 启用组织架构

该功能用于启用组织架构，组织架构默认禁用。

1. 单击组织架构名称后，单击 ![](../../../images/iam/nav1.png) 操作菜单，单击 **_"启用"_** 按钮，弹出启用确认对话框。
2. 单击 **_"确定"_** 按钮，完成操作。

### 禁用组织架构

该功能用于禁用组织架构。

1. 单击组织架构名称后，单击 ![](../../../images/iam/nav1.png) 操作菜单，单击 **_"禁用"_** 按钮，弹出禁用确认对话框。
2. 单击 **_"确定"_** 按钮，完成操作。

### 删除组织架构

该功能用于删除组织架构。

1. 单击组织架构名称后，单击 ![](../../../images/iam/nav1.png) 操作菜单，单击 **_"删除"_** 按钮，弹出删除确认对话框。
2. 单击 **_"确定"_** 按钮，完成操作。

### 添加项目

该功能用于给组织架构各层级添加项目。

1. 单击任意层级，单击列表上方 **_"添加项目"_** 按钮，弹出添加域/项目对话框。
2. 选择需要添加到当前层级的域/项目，单击 **_"确定"_** 按钮，完成操作。

### 移除项目

该功能用于给组织架构各层级移除项目。

1. 单击任意层级，选择需要从当前层级移除的域/项目，单击 **_"移除项目"_** 按钮，弹出移除域/项目对话框。
2. 单击 **_"确定"_** 按钮，完成操作。