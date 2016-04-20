# Java Collections Framework Internals
## Authors
| Weibo Id | Name |
|:-----------|:-------------|
|[@计算所的小鼠标](http://weibo.com/icttinymouse) | Hao Li |

## Introduction

关于*C++ Standard Template Library(STL)*的书籍和资料有很多，关于*Java Collections Framework(JCF)*的资料却很少，甚至很难找到一本专门介绍它的书籍，这给Java学习者们带来不小的麻烦。我深深的不解其中的原因。虽然JCF设计参考了STL，但其定位不是Java版的STL，而是要实现一个精简紧凑的容器框架，对STL的介绍自然不能替代对JCF的介绍。

## Contents

本系列文章主要从**数据结构和算法**层面分析JCF中List, Set, Map等典型容器，并不特意介绍Java的语言特性。具体内容如下：

1. Overview
2. ArrayList
3. LinkedList
4. Stack and Queue
5. TreeSet and TreeMap
6. HashSet and HashMap
7. LinkedHashSet and LinkedHashMap
