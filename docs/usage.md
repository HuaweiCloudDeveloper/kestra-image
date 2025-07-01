# Kestra数据编排平台使用指南

# 一、商品链接

[Kestra数据编排平台](https://marketplace.huaweicloud.com/contents/f339961a-eb5a-4c3b-87f1-306496e6368c?ticket=ST-848229-b5DwtJkjX1mOf37SSKLkBOKc-sso#productid=OFFI1121282090660507648&locale=zh-cn)

# 二、商品说明

Kestra 是一款‌开源、事件驱动、声明式数据编排平台‌，专注于简化和自动化复杂业务流程及数据处理。本商品基于arm架构的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的Kestra。

# 三、商品购买

您可以在云商店搜索 **Kestra数据编排平台**。

其中，地域、规格、推荐配置使用默认，购买方式根据您的需求选择按需/按月/按年，短期使用推荐按需，长期使用推荐按月/按年，确认配置后点击“立即购买”。


## 3.1 使用 RFS 模板直接部署
![img.png](images/img1.png)
必填项填写后，点击 下一步
![img.png](images/img2.png)
![img.png](images/img3.png)
创建直接计划后，点击 确定

![img.png](images/img4.png)
![img.png](images/img5.png)
如下图“Apply required resource success. ”即为资源创建完成
![img.png](images/img6.png)
# 3.2ECS 控制台配置

### 准备工作

在使用ECS控制台配置前，需要您提前配置好 **安全组规则**。

> **安全组规则的配置如下：**
> - 入方向规则放通端口8080，源地址内必须包含您的客户端ip，否则无法访问
> - 入方向规则放通 CloudShell 连接实例使用的端口 `22`，以便在控制台登录调试
> - 出方向规则一键放通

### 创建ECS

前提工作准备好后，选择 ECS 控制台配置跳转到购买 ECS 页面，ECS 资源的配置如下图所示：
![img.png](images/img7.png)
![img_1.png](images/img8.png)
![img_2.png](images/img9.png)





> **值得注意的是：**
> - VPC 您可以自行创建
> - 安全组选择 [**准备工作**](#准备工作) 中配置的安全组；
> - 弹性公网IP选择现在购买，推荐选择“按流量计费”，带宽大小可设置为5Mbit/s；
> - 高级配置需要在高级选项支持注入自定义数据，所以登录凭证不能选择“密码”，选择创建后设置；
> - 其余默认或按规则填写即可。

# 商品使用

## Kestra数据编排平台使用

### 通过IP+8080端口访问UI页面
![img.png](images/img10.png)

### 参考文档

[Kestra参考文档](https://kestra.io/docs)
