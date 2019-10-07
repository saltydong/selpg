# selpg

##### 一、实验目的

请按文档使用 selpg 章节要求测试你的程序  
请使用 pflag 替代 goflag 以满足 Unix 命令行规范， 参考：Golang之使用Flag和Pflag  
golang 文件读写、读环境变量，请自己查 os 包  
“-dXXX” 实现，请自己查 os/exec 库，例如案例 Command，管理子进程的标准输入和输出通常使用 io.Pipe，具体案例见 Pipe

#### 二、实验过程

对于已经给出的selpg.c文件，先对其进行了阅读，结合资料进行理解

![1](https://github.com/saltydong/selpg/blob/master/pics/3.JPG)

对于理解后的代码，所要做的主要任务便是对其将c语言翻译成go语言，以用来符合golang的需求  

完成之后，就是对其的应用检测  

首先创立一个测试文件1.txt  

打印其第一页显示在屏幕上

![2](https://github.com/saltydong/selpg/blob/master/pics/1.JPG)

可以看到一共有20行test全被打印出来  

然后利用 -l的功能打印部分

![2](https://github.com/saltydong/selpg/blob/master/pics/2.JPG)

打印出来了前五行的

#### 三、实验结果

对于本此cli的作业，更多的对自己来说是熟悉go语言的使用和C的异同之处，更多的是对c的翻译成Go的过程，和对命令行程序的认识。其中参考了一些博客
才勉强完成，以后应多加对这些知识的熟悉和了解。
