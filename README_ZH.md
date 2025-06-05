 <h1 align="center">Kestra数据编排平台</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[Kestra](https://github.com/kestra-io/kestra) 是一个开源的，由事件驱动的编排平台，使计划驱动和事件驱动的工作流程变得容易。通过将基础架构作为代码最佳实践，为数据，流程和微服务编排，您可以在仅几行yaml中直接从UI构建可靠的工作流程。

**关键功能：**

**事件驱动和计划的工作流程：** 通过简单定义自动化计划和实时事件驱动的工作流程trigger。

**声明性YAML接口：** 使用内置代码编辑器中的简单配置定义工作流

**富插件生态系统：** 内置数百个插件，用于从任何数据库，云存储或API中提取数据，并以任何语言运行脚本。

**直观的UI和代码编辑器：** 通过语法突出显示，自动完成和实时语法验证直接从UI构建和可视化工作流。

**可扩展：** 旨在处理数百万个工作流，具有高可用性和容错性。

**版本控制友好：** 从内置代码编辑器中写下您的工作流程，然后直接从Kestra将其推到您喜欢的Git分支，从而使用CI/CD管道和版本控制系统实现最佳实践。

本项目提供的开源镜像商品 [**Kestra数据编排平台**](https://marketplace.huaweicloud.com/hidden/contents/f339961a-eb5a-4c3b-87f1-306496e6368c#productid=OFFI1121282090660507648) 已预先安装0.22.1版本的Kestra及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。



> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格 | 特性说明 | 备注 |
| --- | --- | --- |
| [Kestra-v0.22.1](https://github.com/HuaweiCloudDeveloper/kestra-image/tree/Kestra-v0.22.1) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/kestra-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md