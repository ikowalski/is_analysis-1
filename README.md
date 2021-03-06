﻿<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 《信息系统分析与设计》（第4版）

![book](book.jpg)

清华大学出版社 王晓敏 邝孔武 编著

主讲：成都大学信息科学与工程学院 赵卫东

## 搭建文档编写环境：
- 编辑器: IntelliJ IDEA
- IDEA插件: markdown 和 plantuml
- 单独安装: git 和 graphviz

> 实验1 业务流程建模

- 重新绘制Page107图6.1: 考试及成绩管理流程 
- 重新绘制Page108图6.2: 客户维修服务流程
- 重新绘制的两个流程图要汇总到REMADE.md文本文件中进行说明，说明文件用Markdown格式编写。

<b>注意事项</b>

- 图6.1按不同的使用者（用户类别）分成了4行，图6.2按不同的用户类别分成了4列，
  如何在建模中区分各功能的使用者？
- 图6.1中有同步功能“A、B试卷”和“打印审批表”等，图6.2也有同步功能“安排工人”和“安排材料”，如何在建模中绘制？
- 业务流程建模采用PlantUML的活动图(新语法)Activity Diagram (beta)标准绘制。

<b>实验提交</b>

- 实验提交到自己的gitHub的is_analysis/test1目录中，主要文件名是：README.md，再附上一些图片文件。
- 你的gitHub中的is_analysis/test1目录中可能有以下文件：

``` filelist
README.md
flow1.jpg
flow2.jpg
```
- 本次实验需要写到纸质实验报告中，纸质报告只需要写一个业务流程图。

- 你的实验内容提交成功后，可以直接访问https://github.com/<b>zhang</b>/is_analysis/tree/master/test1
查看你编写的实验文档。其中zhang是你的gitHub用户名。

- 请在2018-04-02之前提交，过时扣分。

<b>参考</b>

- 绘制方法参考[PlantUML标准](http://plantuml.com/activity-diagram-beta)文件的活动图(新语法)Activity Diagram (beta)
- Markdown格式参考：https://www.jianshu.com/p/b03a8d7b1719
- 老师的教学资源：https://github.com/zwdbox/is_analysis
- 老师以同学身份做的<b>伪实验1</b>教参：https://github.com/zwdbox/is_analysis/tree/master/test1
