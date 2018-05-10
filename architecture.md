---
description: Architecture
---

# 架构

`AVGPlus` 总共分为两个部分。分别是 [`avg.engine`](https://github.com/AngryPowman/avg.engine) 和 [`avg.renderer`](https://github.com/AngryPowman/avg.renderer).

`avg.engine` 该部分主要实现了整个游戏引擎的数据以及状态管理功能。并且所有的游戏API接口原型都在这部分进行暴露。

`avg.renderer` 是一个对 `avg.engine` 的实现部分。它依赖`avg.engine`的类型定义以及数据管理，并负责了游戏的绘图、渲染、API详细实现。游戏的前端效果都在这部分进行。

