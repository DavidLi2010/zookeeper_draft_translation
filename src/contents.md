#目录

##前言

##第一部分 ZooKeeper概念和基础

###1. 概述

####ZooKeeper的任务
      没有ZooKeeper的世界如何存活
      ZooKeeper不做什么
      Apache项目
      使用ZooKeeper构建分布式系统
####示例：Master-Worker应用程序
      Master故障
      Worker故障
      通信故障
      任务总结
####为什么分布式协调很难？
####ZooKeeper是成功的，以及告诫

###2. ZooKeeper入门
####Zookeeper基础
      API概览
      Znodes模型
      观察和通知
      版本
####ZooKeeper架构
      ZooKeeper Quorums
	  会话
####ZooKeeper初体验
      第一个ZooKeeper会话
	  会话的状态和生命周期
	  ZooKeeper with Quorums
      实现原语：基于ZooKeeper的锁
####Master-Worker示例实现
      Master角色
	  Worker，任务和分配
	  Worker角色
	  客户端角色
####总结
