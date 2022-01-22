# Tool-Bioconductor

## **Introduction of Bioconductor** 
https://blog.csdn.net/shmilyringpull/article/details/8542607 设计理念


## **Basics of Bioconductor** 
http://www.bio-info-trainee.com/2922.html 合集
- S4 language 面向对象，类接口与方法分离
- 复习面向对象的程序设计（C++面向对象程序设计 谭浩强）
- Installation 
https://www.bioconductor.org/install/ 官方
https://blog.csdn.net/TianzhouFeng/article/details/113488282 一些可能的坑，按官方来应该不会遇到
- Data Structure
- Bioconductor Structure: Software, Experiments, Annotation, Workflows


## **Learn Bioconductor from often used packages** 从常用包开始熟悉
- GenomicRanges https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html
- 包自带的说明文档是非常好的学习入口和学习路径
- GenomicRanges是一种software包，这个包就是把基因组开始到结束的结构储存下来，包括的基础信息就是在染色体在基因组上**开始的位置，结束的位置，在正链还是负链，最主要的就是这4个信息**，它可以进行基因组的定位。这个包最大的优点就是可以做非常复杂的操作：去找overlap算coverage等等非常方便。这个包是我们现在做组学分析的基础，**基本上你只要做组学分析用Bioconductor就离不开这个包，很多包都是在这个基础上构建出来的**
