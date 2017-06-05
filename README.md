# ZendApi
### 介绍
zendapi这个项目是对zend engine的C接口使用C++11进行而面向对象的封装，从而屏蔽了底层Zend Engine API的接口复杂性，加快开发PHP扩展的效率。

项目官网地址：www.zendapi.org

### 设计目标
让php扩展开发更有趣

### 特性
1. 完全面向对象，对Zend Engine API进行二次定义
2. 使用现代的C++11语法进行开发，便于维护
3. 最大化屏蔽PHP版本对扩展开发的影响，zendapi将对Zend Engine API不同版本带来的差异屏蔽掉
4. 高覆盖的单元测试，保证代码质量
5. 在封装的时候，尽最大能力保证性能

### 文档相关
用户手册: www.zendapi.org/documents
API手册: www.zendapi.org/api

### 说明
当前zendapi项目处于非常前期阶段，很多接口都不稳定，甚至会经常有大的变化，请不要用于实际项目，现阶段只适合学习用途。
### 特别感谢
Unicorn Team