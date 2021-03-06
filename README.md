## 系统简介

为了便于自我管理，我每个月会设置一定的目标，每个月大致会按设定的目标进行工作、学习、生活等，每个月末会对目标进行评估，以调整自我管理策略，希望通过这样的管理，提升自己各方面的能力。之前一直是使用有道云，以文本记录的方式，记录目标，月末记录完成的进度，操作起来相对复杂。

作为一个软件开发人员，就按自己的想法做一个简单的系统出来进行管理，提升效率，于是就有了这个个人目标记录管理工具，它是基于若依系统进行开发，对个人的记录管理包括目标、想法、热点、总结进行记录，对于目标，可以进行增删改查，调整进度，目标翻阅等功能，让目标记录及管理更方便。

## 功能

基于[若依系统](http://ruoyi.vip/) 进行开发，对于其原有的功能不进行修改，直接在原有功能基础上添加目标管理模块`ruoyi-goal`，并在其中实现视图层、控制层，映射层、实体层的代码，基础代码使用若依本身提供的代码生成出来再进行修改。当前已实现如下功能：

- 月目标模块显示及统计
- 月目标查看与条件过滤筛选
- 月目标添加、编辑、删除
- 月想法添加、编辑、删除
- 月总结添加、编辑、删除
- 月热点记录的添加、编辑、删除

## 截图

- 目标管理

![目标管理](https://raw.githubusercontent.com/mianshenglee/goal-manager/master/pic/goal.png)

- 想法

![想法](https://raw.githubusercontent.com/mianshenglee/goal-manager/master/pic/idea.png)

- 总结

![总结](https://raw.githubusercontent.com/mianshenglee/goal-manager/master/pic/summary.png)

- 热点

![热点](https://raw.githubusercontent.com/mianshenglee/goal-manager/master/pic/hotspot.png)



## 未来设想

- 添加年目标及分解到月目标功能
- 改造为前后端分离项目
- 改造为适合web端及移动端相适配的形式（H5?flutter?）
- 添加小程序
