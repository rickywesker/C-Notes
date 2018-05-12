#程序设计实习 学习笔记

***

## STL

	### STL的基本概念:

### ·容器(container)：用于存放数据的**类模板**。

### ·迭代器(iterator):用于存取容器中存放的元素的工具。

### ·算法(algorithm):用于操作容器中元素的**函数模板**。

***

### 顺序容器

·vector,deque,list.元素在容器中的位置与值无关，即容器不是排序的。

### 关联容器

·set,multiset,map,multimap.关联容器中的元素是排序的，查找时有较好性能。

### 容器适配器

·queue,priority-queue,stack

***

**所有容器都有 `int size()`和`bool empty()`两个成员函数。**

**顺序容器和关联容器还有以下成员函数**

·`begin()`,`end()`,`rbegin()`,`rend()`,`erase()`,`clear()`

**顺序容器还有以下常用成员函数**

·`front()`,`back()`,`push_back()`,`pop_back()`,`insert()`..

