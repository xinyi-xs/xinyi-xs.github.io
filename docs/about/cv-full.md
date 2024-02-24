<!--
这里是生成部分的简历
# <center>李宏建</center>
<center>💬 182 1865 6060 | 📮 xuesengxinyi@gmail.com | 🔗 https://xinyi-xs.github.io</center>
下面是主页部分的简历
-->

# 李宏建
📮 xuesengxinyi@gmail.com | 🔗 https://xinyi-xs.github.io


<!--

<div style="float: left;display: flex;flex-wrap: wrap;width: 75%;justify-content: space-between;">
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">姓名： 吴彦祖</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">毕业院校： 蓝翔</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">出生年月： 1988-8</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">电话： 13888888888</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">籍贯： 中国香港</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">邮箱： wuyanzu@qq.com</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">专业： 挖掘机</div>
    <div style="width: 45%;font-weight: 500;color: #4c4c4c;font-size: 14px;margin: 5px;">期望工作地： 成都</div>
</div>
<div>
    <div style="float: right;margin-right: 10px;">
        <img src="../main/main-page.png" width="120px" height="150px" style="box-shadow: 5px 5px 5px rgba(0,0,0,.5);">
    </div>
</div>
————————————————
-->

> 4 年软件开发经验, 主要从事 MQTT broker 相关开发。
## 🎓 教育经历

2017年9月 \- 2020年6月 \| 中国科学院 深圳先进技术研究院 \| 计算机技术专业 <br />
2011年9月 \- 2015年6月 \| 桂林理工大学 \| 自动化专业

## 💻 工作 / 项目经历
### 映云科技公司 （ 2020年6月 ~ 至今 ）
#### 2020.6 - 至今 [NanoMQ](https://github.com/nanomq/nanomq) 
- **优化主题消息匹配**。与开发团队合作，通过实现前缀树数据结构优化主题消息匹配，显著提升吞吐率，增强了 NanoMQ 的整体性能。
- **MQTTV5 相关特性支持**（共享订阅，主题别名，订阅标识符，桥接主题过滤器）。使 NanoMQ 能够满足更多复杂的通信需求，提高了系统的灵活性和扩展性。
- **设计并引入基于 SQL 语句的规则引擎模块**。使其能够实现物联网数据的提取、过滤、转换、存储和处理，支持与 MySQL、Sqlite 等数据库的灵活集成，以及数据转发到新的主题，以加速应用集成和业务创新。规则引擎模块为物联网数据处理提供了强大而灵活的解决方案，无需编写代码，实现了一站式的数据处理和集成，促进了业务创新。
- **开发 Hocon 配置文件解析功能**。使其能够解析具有类似 JSON 语法的配置文件，并支持合并、引用等功能，提高配置文件的灵活性和可控性。Hocon 配置文件解析功能增强了 NanoMQ 的配置灵活性和可维护性，简化了配置文件的编写和管理。使用 Hocon 配置解析后相比于原有的配置文件性能有了很大提升。
- **实现多协议网关，包括 DDS、ZMQ 和 SOME/IP**。以确保 NanoMQ 与不同通信标准的互操作性和兼容性。多协议网关的开发确保了 NanoMQ 与不同通信标准的兼容性，扩展了其应用范围。
- **消息队列落盘功能**。使用 parquet 格式进行数据落盘，以提升数据持久化能力和查询效率。具有增删改查功能的消息队列使用 parquet 格式进行数据落盘，提高了数据的持久化能力和查询效率。
- **参与 NanoMQ的CI/CD 实施**。使用 checkinstall 打包和 Python 集成测试，以确保软件的快速、可靠发布。
- **处理项目的CMAKE依赖和编译（交叉编译）问题**。确保项目的顺利构建，部署和交付。
#### 2023.2 - 至今 NanoLink
- **开发并实现 ACF/SomeIP/UDP 与 MQTT 双向转换功能**。使得 NanoLink 能够在这些通信协议之间进行数据的转换和交换，实现系统间的互操作性。
- **集成 Franca IDL 工具**。用于生成序列化和反序列化代码，简化开发流程。通过该工具，可以自动生成与通信协议相关的代码，减少手动编写的工作量，提高开发效率。

#### 2023.8-10 fidl-serial
- **设计并开发基于 Franca IDL 和 CommonAPI 的自动生成工具**。基于 pyfranca 的语法树。为 NanoLink 自动生成了包括 JSON 序列化、反序列化代码、动态订阅和发布主题等功能的 Application 代码。用于生成 SOME/IP 客户端和服务端的代码。减少了手动编写的工作量，提高了开发效率。这些生成的代码具备动态适应服务数量的能力，同时还包括多个独立的服务线程和测试service等功能。

#### 2023.1-至今 idl-serial
- **基于 flex/bison 技术设计并开发基于 OMG IDL 的自动生成工具**。完成了 idl-serial 的开发，该工具利用flex/bison 技术实现了基于 OMG IDL 的自动生成工具。自动生成工具能够解析不同 IDL 文件，生成相应的语法树，并自动生成序列化和反序列化代码，使得 NanoMQ 能够处理不同 IDL 的数据类型。通过使用自动生成工具，显著减少了手动编写代码的工作量，提高了开发效率。持续优化自动生成工具的性能和稳定性，确保其能够快速应对客户对于 DDS 不同 IDL 的新的开发工作量。

#### 2021.6-10 edge-agent
- **在边缘端和云端之间建立 HTTP 通道，以实现边缘端对云端的反向 HTTP 代理服务**。通过该代理服务，边缘端的组件服务可以与云端进行 HTTP 通信。
- **实现 SSH 客户端反向代理服务**。使得边缘设备可以通过 edge-agent 代理与云端的 SSH 服务器建立连接，并进行远程访问和管理。
- **基于 procfs 技术，实现了边缘端进程监控功能**。能够监控边缘设备上运行的进程，并提供相应的监控信息，增强了边缘端的管理能力。

#### 2021.1-8 fabric-sdk
- **设计并开发 Fabric SDK 设备影子和物模型 SDK**。提供与 Fabric 服务端的通信的能力，并实现设备影子和物模型相关的功能，如状态同步、属性更新等。
- **开发一个简单代码生成工具**。通过输入相关参数，生成 Demo 版本的展示性代码，以便用户能够快速了解和展示 SDK 的使用方式和功能。


### 深圳先进技术研究院 (2017年9月 ~ 2020年6月)
#### 2020 1-6 高并发在线字符识别服务器（独立）

* 基于 socket、http 协议实现服务器与客户端通信和 get/post 协议。
* 基于 epoll 和线程池实现服务器并发。
* 基于 Tesseract-ocr，实现通用字符及手写体识别。

#### 2019 8–10 VIORB算法优化（主导）

* 通过结合 Gamma 矫正和 CLAHE 算法，提升算法在低光照环境的鲁棒性。
* 通过对特征点法和光流法相结合，提升了算法在纹理较弱情况的鲁棒性。
* 基于线特征对特征点进行约束，实现了特征点的更优选择策略。

#### 2019 3–7 基于TX2多传感器机器人实验平台搭建（主导）

* IMU 和图像的 Topic 发布、分别标定、联合标定、同步、采包、测试。
* 对多种视觉（惯性紧耦合）SLAM 框架、雷达 SLAM 框架进行测试。
* ORB-SLAM 结合 PCL 库实现三维点云重建。

## 🔧 专业技能

* 熟悉 Unix/Linux 操作系统（熟悉 XV6 操作系统源码），了解 ucos 源码。
* 熟悉多线程/多进程程序开发，了解异步，并发技术，熟悉网络编程。
* 熟悉计算机网络，包括（TCP/IP，TLS, mqtt , quic 等等）。
* 熟悉常用消息中间件 （熟悉 Redis 源码， nanomsg, ZMQ， someip 和 dds）
* 熟练使用 c/cpp, python 编程语言, 熟悉 rust，shell 编程语言.
* 熟练使用 cmake，makefile，gdb，git，flex&bison 等工具。
* 熟悉常见数据库使用 sqlite, mysql 等。
* 熟悉 IDL。
* 熟悉常用数据结构和算法设计，了解编译原理。
* 可以流畅阅读文献以及英文技术文档。

## 科研成果

* 论文： LMVI-SLAM: Robust Low-Light MonocularVisual-Inertial Simultaneous Localization and Mapping，第一作者， ROBIO2019， 发表
* 论文： A Lifted Semi-direct Monocular Visual Odometry，第一作者， DSCI2019， 发表
* 论文： EIP-VIO: Edge-Induced Points based Monocular