---
title: "功能特性"
description: 本小节主要介绍 RadonDB 功能特性。 
keywords: radondb 功能特性,
weight: 20
collapsible: false
draft: false
---

RadonDB 支持如下功能特性。

- 自动水平分表，一键即可开启智能化扩容，扩容过程业务不中断。

- 数据多副本，率先使用 GTID 并行复制和 Raft 一致性协议确保副本间数据强一致、零丢失。

- 主副本故障自动秒级切换，实现自动化运维，无需人工干预。

- 存储副本使用 MySQL(5.7.29) 存储，稳定可靠的存储能力与强大的计算能力并存。

- 提供分布式事务能力，保证跨节点操作的数据一致性。

- 同时支持 OLTP (高并发事务需求)和 OLAP (复杂分析需求)。

- 高度兼容 MySQL 语法，数据可快速导入、导出，简单易用。

- 多可用区部署，提供 SQL 审计和 IP 白名单功能，安全可靠。