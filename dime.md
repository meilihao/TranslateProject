# DIME(Dark Internet Mail Environment) - 黑暗邮件联盟架构和规范
version: June 2018

ps:
- [darkmail offical site](https://darkmail.info/)
- [secure-email](https://github.com/OpenTechFund/secure-email)

## 概述
本文件将被划分为若干小节以分别向读者介绍Dark INternet Mail Environment(DIME)的术语, 架构, 安全, 数据格式以及协议规范.

### part 1: 摘要
为本文档提供简要说明.

### part 2: 术语
和其他工业标准组织一样, 定义了所有DIME规范的术语, 缩写以及贯穿全文的关键词.

### part 3: 系统架构
论述了DIME的设计目标, 并提供了完整地支持DIME邮件处理系统的各功能组件的入门插画.

### part 4: 管理记录
描述了用于启用DIME支持的DNS记录: 通知策略和提供一个加密且可信的组织域名标识.

### part 5: 水印的数据格式
描述了用于用户和组织的水印的数据格式

### part 6: 消息的数据格式
描述了用于加密消息(以及其携带数据)的格式

### part 7: Dark Mail 传递协议(DMTP)
DMTP详述了用于消息传递和水印查找的未经证实的协议规范.
它提供了连接标准, 命令语法以及证书要求.

### part 8: Dark Mail 许可协议(DMAP)
DMAP详述了用于DIME生态的可靠的许可协议.

### part 9: 全球总帐
详述了用于水印的分布式不可变的反射式账目的实现和使用.

### part 10: Dark Mail 联盟
详述了Dark Mail Alliance(DMA)的创建, 描述了它的作用, 监管职责(包括用于管理DIME内部项目的流程).

### part 11: 威胁
详述了针对DIME隐私功能的威胁, 以及仅涵盖DIME的安全问题的讨论.

### part 12: 攻击和缓和
详述了攻击情景, 并提供了可用于缓解这类攻击的DIME策略.

### part 13: 已知缺陷
详述了已发现的所有缺陷.

### part 14: 人员名单
提供了对本文档有极大帮助的人的名单.

### part 15: 引用
提供了用于本文档的详细参考目录.

## part 1: 摘要