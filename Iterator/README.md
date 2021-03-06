## 迭代器模式

### 概述
迭代器模式提供一种方法，使得可以顺序访问一个聚合对象中的各个元素，而又不暴露其内部的表示。

### 结构
![迭代器模式结构图](http://7u2eqw.com1.z0.glb.clouddn.com/迭代器模式结构图.jpg)

### 实现
使用商品列表作为聚合对象，迭代器实现获得当前元素，移动到下一个元素，判断当前元素是否有效，获得当前元素的下标以及重置到第一个元素的接口。

### 总结与分析
迭代器模式将便利的任务放在迭代器上，而不是聚合对象上。这样既简化了聚合对象的接口和实现，也让责任各得其所。
