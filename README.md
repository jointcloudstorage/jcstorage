# 云际存储

## Introduction

- 2016年国家重点研发计划项目：软件定义的云际计算基础理论和方法
- 课题三：云际存储资源的聚合模型与协同机制
- 执行期限：2016年07月至2021年06月
- 课题目标描述：本课题是支撑软件定义的云际计算运行与管理的关键，针对大数据应用、计算框架等对资源动态个性化的需求，以云际计算环境跨地理位置分布的存储资源为主体，重点研究云际存储资源抽象聚合与评估、云际分布存储与数据管理、多源异构数据感知的应用部署与协同调度等，实现全局的效能优化与最小化多副本开销，降低云际不确定性对服务性能带来的影响，实现软件定义的云际大数据高效能存储管理，形成一系列云际计算环境下大数据资源分布式管理与处理的高效运行支撑理论、机制和关键技术等。

## ![云际存储原型系统-v1](https://github.com/jointcloud-buaa/jcsCloudfs)

### 背景及问题--确定数据存储模式和位置

- **云服务提供商锁定问题**：单个云存储供应商中断导致服务不可用，使用多个云存储供应商可避免供应商锁定问题
- **云存储提供商多样性**：访问延迟，定价策略，标准/低频存储等
- **需求**：提高云存储可靠性和成本效益，减少用户访问延迟

### 解决方案

- 统一的用户入口以及文件元信息管理
  - 为云际存储用户提供统一系统入口
  - 用户文件元信息在各个云存储服务商间同步管理
- 自适应的多云数据冗余存储机制
  - 纠删编码和复制两种机制
  - 改进纠删编码，减少数据恢复和迁移成本；消除重复数据，减少网络流量
- 根据数据对象的历史访问规律，动态调整数据存储模式

## 云际计算框架G-Spark原型系统-v1

## 云际时空数据索引原型系统-v1