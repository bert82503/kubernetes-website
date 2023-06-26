
---
title: 概念
main_menu: true
content_type: concept
weight: 40
---

<!-- ---
title: Concepts
main_menu: true
content_type: concept
weight: 40
--- -->

<!-- overview -->

<!--
The Concepts section helps you learn about the parts of the Kubernetes system and the abstractions Kubernetes uses to represent your {{< glossary_tooltip text="cluster" term_id="cluster" length="all" >}}, and helps you obtain a deeper understanding of how Kubernetes works.
-->
概念部分帮助你了解 Kubernetes 系统的各个部分以及
Kubernetes 用来表示{{<glossary_tooltip text="集群" term_id="cluster" length="all" >}}的抽象概念，
并帮助你**更深入地理解 Kubernetes 是如何工作的**。
Kubernetes 用来**表示集群的抽象概念**，

## 概述
Kubernetes 是一个**可移植、可扩展**的开源平台，用于**管理容器化的工作负载和服务**，方便进行**声明式配置和自动化**。
Kubernetes 拥有一个庞大且快速增长的生态系统，其服务、支持和工具的使用范围广泛。

## Kubernetes 架构
Kubernetes 背后的**架构概念**。

## 容器
**打包_应用及其运行依赖环境_的技术**。

## 工作负载
理解 Pods，Kubernetes 中**可部署的最小计算对象**，以及辅助它运行它们的**高层抽象对象**。

## 服务、负载均衡和联网
Kubernetes **网络背后的概念和资源**。

## 存储
为集群中的 Pods 提供长期和临时存储的方法。

## 配置
Kubernetes 为**配置 Pods 提供的资源**。

## 安全
确保**云原生工作负载安全的一组概念**。

## 策略
**通过_策略_管理安全性和最佳实践**。

## 调度、抢占和驱逐
在 Kubernetes 中，调度 (scheduling) 指的是确保 Pod 匹配到合适的节点，以便 kubelet 能够运行它们。
抢占 (Preemption) 指的是终止低优先级的 Pod 以便高优先级的 Pod 可以调度运行的过程。
驱逐 (Eviction) 是在资源匮乏的节点上，主动让一个或多个 Pod 失效的过程。

## 集群管理
关于创建和管理 Kubernetes **集群的底层细节**。

## Kubernetes 中的 Windows
Kubernetes 支持运行 Microsoft Windows 节点。

## 扩展 Kubernetes
改变你的 Kubernetes 集群的行为的若干方法。

<!-- body -->
