# NEUBachelorThesis-NG

脱胎自东北大学软件学院提供的本科生毕业论文模板。

## 主要特性

- 格式与原论文无异
- 梳理并删除了无用的样式，只保留了论文中用到的
- 半自动奇偶、留白页
- 自动页眉页脚
- 自动主题编号
- 自动表格样式

# 注意事项

1. 正确使用模板中的标题、正文样式，不要手动调字体大小、编号。
2. 前言部分的留白页和页码已经调整好了，最终印出来都是单面有字。打印后需手动将英文摘要页正反面颠倒过来，技术原因，算是个bug。
3. 插入表格时， **先插入一个空行** 并修改样式为 `表格字体` ， **再** 在这个空行插入表格， **最后** 将表格样式修改为 `论文样式` 。否则表格字体无法正常居中对齐。
4. 关于怎么插入表头和表、图的交叉引用，请参阅模板中注解，并上网查。不要一个一个自己加文本框。否则一旦图表顺序更改后，你需要改整篇文章的图片编号。
5. 每章节末尾请插入一个 **奇数页分节符** 。方法自行百度。

如果需要使用 Git 管理论文版本，需要额外[安装 pandoc](https://pandoc.org/installing.html)  ，并在 git 目录中运行 [setup-git-hook.sh](/setup-git-hook.sh) （在 mac 下测试正常， Windows Git Bash 不保证）。以后每次 diff 和 commit 就能正常显示 docx 的变化了。


模板： [毕业设计（论文）排版样例.dotx](毕业设计（论文）排版样例.dotx)

## Fuck LaTeX

![LaTeX](LaTeX.gif)



# 论文大纲参考

总结自《软件学院毕业设计（软件开发类论文）撰写说明》，仅供参考。

根据要求，论文总长度在30～50页之间。大约会有一万字。

- 绪论 10% 3～5页
  - 课题研究背景
  - 课题研究意义
  - 国内外现状
  - 论文研究内容
- 相关技术（可选） 15% 5～8页
- 需求分析、系统分析 15%
  - 业务需求/用户需求/功能需求
  - 如果论文所研究的课题属于某个较大项目的子课题，则应该首先进行系统分析，对主课题的全貌加以介绍分析，说明本人的工作内容以及在整个课题中所起的作用和关系。然后重点对子课题进行较全面的需求分析。 
  - 最后写一段本章小结，最好不要少于3行。
- 系统设计 30%
  - 功能模块/数据流/输入输出
  - 最后写一段本章小结，最好不要少于3行。
- 系统实现 20%
  - 与设计呼应，一设计 => 一实现
  - 流程图/代码/界面
  - 最后写一段本章小结，最好不要少于3行。
- 系统测试 7%
  - 测试方案/用例/结果
  - 测试结论或评价。
- 总结及展望
  - 以整个研究工作为主体，进行阐述相关的问题
  - 课题研究内容进行总结，摘要是对论文本身进行概括 