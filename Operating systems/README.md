# Operating systems

这是一份关于操作系统的学习笔记，由于我主要使用MIT6.S081的课程进行操作系统的学习，该笔记会涉及大量关于RISC-V版本xv6系统的内容，但同时也会辅以其他材料进行笔记整理。

各章节主要内容如下：

**chapter1.操作系统概述：** 简单介绍了什么是操作系统，讨论了隔离性和防御性的内核设计思想，简单讨论了宏内核和微内核的不同。

**chapter2.虚拟内存：** 介绍了內存虚拟化的概念，讨论了分段与分页内存管理，以SV39的RISC-V三级页表为例介绍了页表。

**chapter3.系统调用：** 介绍了异常控制流与RISC-V的陷阱机制，以xv6的trap为例讨论陷入的过程。

## 参考资料

- [MIT6.S081](https://pdos.csail.mit.edu/6.S081/2020/)
- [rCore-Tutorial-Book-v3](https://rcore-os.github.io/rCore-Tutorial-Book-v3/)
- [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)

