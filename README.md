# Tintin OS

a little OS on RISC-V ISA

## 功能

- 只运行在机器模式，内存地址使用物理地址
- 提供Scheme的执行环境，Scheme程序必现为源代码或者另外设计的字节码，不支持直接运行机器码
- 提供一个Shell，交互如下：
  ```
  # 提示符
    (
  # 打印Hello World
    (print "Hello World!")
    => Hello World!
  ```