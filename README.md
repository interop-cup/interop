# README

## Overview/概述

为解决当前异构隐私计算平台互联互通问题，由北京金融科技产业联盟组织，中国银联牵头，联合主要金融机构、电信运营商、互联网公司、科技公司、检测机构、科研院所等 50 余家单位共同参与开展了隐私计算互联互通工作，形成了隐私计算互联互通统一框架，并制定了互联互通 API 接口规范。

在隐私计算产业联盟、开源社区等产业合作伙伴的大力支持下，现已完成本开源接口与各主流标准、开源路线的兼容对齐，并进一步与各主流隐私计算平台完成了跨平台多方互通验证。为帮助各隐私计算平台开发者更好开展互联互通改造，现将互联互通 API 接口规范、集成对接指引等文档进行开源发布。

## Interconnection Framework/互联互通统一框架

互联互通统一框架分为管理面与数据面两部分。管理面互通是对管理层所设计互联互通资源管理的统一抽象，数据面互通是指管理面下发到数据面的数据信息流转调度及相关计算存储操作。互通视角描述了异构隐私计算平台在实现互联互通（InterConn）相关功能时双方在东西向与南北向所需的基础信息交互；模块视角定了 InterConn 各层最小必要接口及其模块实现的功能要求。

**Interconnection View/互通视角**

![](static/NVyZbnwGno5E1sxZOphc517Gnfe.png)

**Module View/功能视角**

![](static/UMeobn0rwoQc6lxJ3vecnCqJnqc.png)

## Diretory Structure/目录结构

```
InterOp
├─ LICENSE
├─ README.md              # 互联互通统一框架，贡献单位，版权声明等                  
└─ 互联互通集成对接指引     # 存放对接指引，注意事项等相关内容
└─ 互联互通API接口规范
    └─ （模块名称）
        ├── README.md     # 模块简介，Contributor联系方式等                     
        ├── api.md        # 存放接口文件
        └── examples      # 接口使用示例（可选）
```

注：各子模块按照“管理层接口-控制层接口-算法组件层接口-传输层接口-开放算法协议-TEE 统一远程证明协议”的顺序进行文件夹排布。

## Contribution Institutions/参与单位

![](static/U3sZbakE2oeR0XxINsGcTeiWn0b.png)

## License/版权声明

**开源协议****：**

Apache License 2.0
