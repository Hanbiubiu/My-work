# -
词法分析器

一、实验名称
    简单的词法分析器设计
二、实验目的
    1. 掌握针对 C 语言的一个子集设计并实现一个简单的词法分析器的方法。
    2. 掌握利用状态转换图设计词法分析器的基本方法。 
    3. 通过词法分析程序的设计实例，进一步了解词法分析程序的构造细节。
三、实验内容和要求
    1. 以C语言小子集定义表（见表1）为例实现词法分析； 
                          表1 C语言小子集定义表


    2. 设计单词属性字，及各类表格（表示符表、常量表、单词符号及机内表示）；
    3. 画出总控流程图，确定各个子程序的功能并画出控制流程图；
    4. 编码实现词法分析程序
    采用标准输入和输出的方式。程序从键盘接收代码，遇到代码结束符“#”时结束，并将词法分析的结果输出到屏幕上。
    要求实现：
    （1）对正确源程序的识别；
    （2）对包含有注释//和/* */的源程序的识别；
    （3）对包含错误标识符的源程序的识别。（注意，行号的计算不包含空行，详见样例3）
    5. 设计3-5个测试实例，要求覆盖上述功能，并完成测试，测试样例见附录。
四、实验环境
1.操作系统：Windows10
2.开发工具：Microsoft Visual Studio 2019
3.开发语言：C语言
