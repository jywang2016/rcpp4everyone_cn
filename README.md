## 老少咸宜Rcpp

[Rcpp for everyone](https://teuder.github.io/rcpp4everyone_en/)对应的中文文档。

### 目的

原文档是一本非常好的Rcpp入门书籍，其主旨在于不以C++为阐述重点，而以R及Rcpp的角度来描述Rcpp的数据类型等基本概念以及使用。中文文档是希望进一步降低阅读与学习门槛，同时，也会在原文的基础上**丰富案例代码**。

### 相关

- [Rcpp for everyone](https://teuder.github.io/rcpp4everyone_en/) 由[Masaki E.Tsuda](https://github.com/teuder)所著，本文档对应的原始文档。
- [Advanced R](http://adv-r.had.co.nz/Rcpp.html) 由[Hadley Wickham](https://github.com/hadley)所著，链接地址为其中讲述Rcpp的内容。
- [Seamless R and C++ intergration with Rcpp](http://www.rcpp.org/) 由Rcpp作者，[Dirk Eddelbuettel](https://github.com/eddelbuettel)所著。中文译本为`Rcpp:R与C++的无缝整合`。

### 推荐学习路线(Rcpp)

```
Rcpp for everyone => Advanced R => Seamless R and C++ intergration with Rcpp
```

### 完成情况

- [x] Suitable situations to use Rcpp 适用Rcpp的情形
- [x] Installation 安装
- [x] Basic usage 基本用法
- [x] Embedding Rcpp code in your R code 将Rcpp代码嵌入R代码
- [x] C++11 启用C++11特性
- [x] Printing messages 打印信息
- [x] Data types 数据类型
- [x] Vector 向量类
- [x] Matrix 矩阵类
- [x] Vector operations 向量运算
- [x] Logical operations 逻辑运算
- [x] DataFrame 数据框
- [ ] List
- [ ] S3·S4 class
- [ ] String
- [ ] Date
- [ ] Datetime
- [ ] RObject
- [ ] Cautions in handling Rcpp objects
- [ ] Attributes
- [ ] R-like functions
- [ ] Probability distribution
- [ ] Using R functions
- [ ] NA NaN Inf NULL
- [ ] factor
- [ ] Error handling
- [ ] Cancel handling
- [ ] Iterator
- [ ] Environment
- [ ] R Math Library

### 补完计划

在项目的最后，我会尝试使用Rcpp集成一个C++库至R，所以文档可能会补充其它来源的相关知识。