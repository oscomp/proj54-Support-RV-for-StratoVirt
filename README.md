# proj54-Support-RV-for-StratoVirt
### 项目名称
为StratoVirt在RISC-V平台上提供支持，基于Rust语言。

### 项目描述

**StratoVirt**是计算产业中面向云数据中心的企业级虚拟化平台，实现了一套架构统一支持虚拟机、容器、Serverless三种场景。StratoVirt在轻量低噪、软硬协同、Rust语言级安全等方面具备关键技术竞争优势。

当前项目实现源码：

 https://gitee.com/openeuler/stratovirt.git

StratoVirt目前已经对x86_64和arm64平台有了友好的支持，但对于RISC-V这个当前的明星开源指令架构目前还没有提供支持。本项目要求参赛者为StratoVirt在RISC-V的平台上提供支持。项目使用Rust语言构建。

### 所属赛道

2025全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

陈振东

* github
* email alex.chen@huawei.com

方应

- github fangying
- email fangying712@gmail.com



### 难度

高等



### 特征

* 需要熟悉kvm虚拟化
* 熟悉device tree
* RISC-V体系结构
* Rust语言



### License

* [木兰宽松许可证, 第2版](http://license.coscl.org.cn/MulanPSL2)



## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

* 在RISC-V平台上能够启动StratoVirt虚拟机
* StratoVirt 虚拟机可以正常运行initrd引导或rootfs系统
