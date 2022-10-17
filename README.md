> TiDB Hackathon 2022 RFC 模板，本文档提供了中英文格式，如下：

> \* 标为必填项

# *设计文档模板

- 团队名称：孤身走暗巷
- 作者：nil
- 项目进展：待开发

## 项目介绍

一个类似修仙模拟器的游戏，只做服务端的开发，目标是游戏世界自运行，游戏npc高智能，服务稳定后接入客户端。

## 背景&动机

当前游戏都是比拼美术和特效，在游戏创意和玩法上基本雷同。基于个人兴趣爱好，我想要开发一个以服务端为主的游戏世界。

## 项目设计

游戏会根据配置文件生成游戏地图，定时生成npc。设计npc的ai,每个npc都有独立行动的能力。使用tidb记录npc的行为日志和战斗日志这类不可变更的数据。动态变更的数据采用实时计算，借助内存数据库作为存储。

> \* indicates required

# *RFC template

- Team name: Team name in the registration form
- Authors: Names of all team members
- Project process: If you have sub-pull requests or sub-issues, list their links here.

## Project description

A brief introduction that helps readers understand your RFC

## Background & motivation

What's the background of your design? What's the problem you're trying to solve? What use cases does your project support?

This section doesn't need much detail, but you must introduce your project's motivation or background. You need to tell readers where your project's requirements come from and what problem your project solves.

## Project design

Give a detailed explanation of your design, including your application's architectural design and what problem you want to solve by using TiDB's feature. Explain how you'll implement your design, analyze cases using examples, and introduce how to use your feature.

You can write pseudocode of the important algorithms, API interfaces, UML diagrams, and components you'll modify.

# An RFC explanation video (optional)

You can record a short RFC explanation video to let judges have a better understanding of your project.
