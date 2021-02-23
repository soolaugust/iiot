# 工业互联网 （工业4.0）

> 工业互联网涉及到的行业知识非常丰富。对于想要从事工业互联网的开发者来说，如果来开始学习工业互联网是一个非常具有挑战的问题。
>
> 因为本人也是刚刚进入工业互联网，这个项目主要是学习和实践中的一些总结。所以有很多不完善的地方。有任何建议和意见都可以通过issue或者pull request来贡献。也可以直接发送邮件到soolaugust@gmail.com来进行讨论。

- [工业互联网 （工业4.0）](#工业互联网-工业40)
  - [基本概念](#基本概念)
    - [IT & OT](#it--ot)
    - [现场总线](#现场总线)
  - [协议和标准](#协议和标准)
    - [OSLC](#oslc)
    - [OPC UA](#opc-ua)
    - [TSN](#tsn)
    - [Modbus](#modbus)
    - [HART](#hart)
  - [边缘计算](#边缘计算)
  - [架构&设计](#架构设计)
    - [云端](#云端)
    - [边缘端](#边缘端)
    - [组合](#组合)
  - [文章](#文章)
  - [平台调研](#平台调研)
  - [大数据相关](#大数据相关)
  - [网站](#网站)
  - [其他](#其他)
    - [公众号](#公众号)

## 基本概念

### IT & OT

IT (Information Technology)，即信息技术，是用于管理和处理信息所采用的各种技术总称，主要是应用计算机科学和通信技术来设计、开发、安装和实施信息系统及应用软件。

OT (Operational Technology)，指操作技术，是工厂内的自动化控制系统操作专员为自动化控制系统提供支持，确保生产正常进行的专业技术。

IT/OT的融合是近几年的热点，其大致意思是通过打通制造执行系统与运营管理系统之间的数据链路，并将二者整合在一个统一的信息平台上，从而帮助企业提升在生产管理、运营决策与制造执行等各方面的综合效益。但知难行易，将OT与IT融合并不是一件容易的事情，制造企业除了需要面对跨界投入不稳定、不确定的风险以及设备、专业IT人力等成本的挑战外，IT与OT本身的特性也为二者融合设置了障碍。

![](resources/imgs/it_vs_ot.png)

### 现场总线

* [现场总线](docs/basic/field_bus.md)

## 协议和标准

### OSLC

* [OSLC官网](https://open-services.net/)

### OPC UA

* [OPC UA官网](https://opcfoundation.org/about/opc-technologies/opc-ua/)

* [OPC UA协议](docs/protocols/opc_ua_guide.md)

* [OPC UA TSN](docs/protocols/opc_ua_tsn.md)

### TSN

* [TSN时间敏感网络协议](docs/protocols/tsn.md)

### Modbus

* [Modbus协议](docs/protocols/modbus.md)

### HART

* [什么是HART协议](docs/protocols/hart.md)

## 边缘计算

* [边缘计算](docs/edge-computing/README.md)

## 架构&设计

### 云端

* [AWS IoT Core设计解析](docs/architectures/cloud/aws_iot_core.md)
* [AWS IoT Device Defender设计解析](docs/architectures/cloud/aws_iot_device_defender.md)
* [AWS IoT Device Management设计解析](docs/architectures/cloud/aws_iot_device_management.md)

### 边缘端

* [AWS IoT Greengrass设计解析](docs/architectures/edge/aws_iot_greengrass.md)

### 组合

* [AWS IoT SiteWise设计解析](docs/architectures/aggregation/aws_iot_sitewise.md)

## 文章

* [杂谈：一文了解工业4.0](docs/articles/iiot4.0_guide.md)
* [数据模型设计](docs/articles/ibm_iot.md)

## 平台调研

* [阿里云物联网平台](docs/platforms/aliyun_iot_platform)

## 大数据相关

* [工业大数据](docs/big-data/reference.md)

## 网站

* [数字孪生体 - 开源工业互联网平台](https://digitaltwin.openii.cn/)
* [Next Generation Data Integration Solutions (OSLC)](https://koneksys.com/)

## 其他

### 公众号

如果大家想要实时关注我更新的文章和其他的分享，可以关注我的公众号"yuye_suibi"。

![](resources/imgs/gongzhonghao.jpg)