# proj123-linux-slab-cpp

## linux-slab-cpp
Linux内核slab内存分配器对象化实现

### 【项目描述】
为了解决小块内存的分配，Linux内核基于Solaris 2.4中的slab分配算法实现了自己的slab分配器。除此之外，slab分配器另一个主要功能是作为一个高速缓存，它用来存储内核中那些经常分配并释放的对象。C++语言提供了面向对象的语言层面支持，使对象的管理更为清晰。本项目拟利用C++语言对Linux内核slab分配算法进行重新改写，实现面向对象的块内存分配与管理。


### 【所属赛道】
2022全国大学生操作系统比赛的“OS功能设计”赛道

### 【参赛要求】
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

### 【项目导师】
刘冬华
- github https://github.com/cliff-china
- email donghua.liu@ucas.com.cn

### 【难度】
中等

### 【License】
MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)  

## 【预期目标】
- 完成Linux内核slab内存分配器对象化实现
- 对象化改造后的系统稳定运行

### 【参考资源】
- C++语言相关书籍
- SLAB介绍(https://www.cnblogs.com/pengdonglin137/p/3878552.html) 
