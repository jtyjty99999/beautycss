beautycss
=========

css verify&amp;beauty

css质量工具


设计：
 
有很多rule，这种rule有全局性的（比如ID不能重复，比如标签闭合，比如分行）
有特殊性的（比如颜色缩写或者拼写检查，css3前缀，不要使用important，不使用border：0 ,class不能与dpl的class类似）
区块性的 （ 属性应该按照推荐的顺序编写）


当然也提供css格式化工具－单行到多行
css区块注释及文档化
css压缩输出等。


流程

读入css－总体分析（提取id class及区块）－区块分析 －格式化css，打印分析报告
