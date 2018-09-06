# python学习记录

## 一、安装与了解
[python官网](https://www.python.org/)

1. python目前有两个版本，2.X和3.X,在mac上默认的是2.x的版本，我们可以能过官网下载3.x的版本，并安装其解释器；
2. 安装完后，可以启动IDLE这个解释器，这样就可以在上面敲python代码了；
3. 编辑器可以选择sublime\vs code\pycharm等都可以，我用的是vs code
4. 在IDLE里，可以直接输入即可得到运算结果，若在编辑器里，则可以通过print()函数将运算结果打印出来；

## 二、基础知识
### (一) 数据类型
1. 整型
    ```
    >>> 1+1
    2
    ```
2. 浮点型
    ```
    >>> 1.2+1.3
    2.5
    ```
3. 字符串,可以用双引号，或者单引号，可混合使用；
    ```
    >>> 'hello world'
    hello world
    ```
    混合使用时,要输出类似let\'s go!这样带引号的字符串，可以用转义符，如下：
    ```
    'let\'s go!'
    ```
### （二） 变量
1. 使用变量时，不需要先定义，可以直接赋值,而且使用先必须先赋值，不能定义一个空值，它没有默认值；例如：
   ```
   >>> a = 123;
   >>> a
   123
   ```

### （三） 函数
python有内置函数和自定义函数
1. 内置函数，如计算乘方(2的3次方)：
   ```
   >>> pow(2,3)
   8
   ```
2. 函数还可以通过引入模块来使用已有函数，如引入```math```模块，来使用```ceil```这个函数：
    ```
    >>> import math
    >>> math.ceil(32.9)
    33
    ```
3. 自定义函数：
    ```
    def add(a,b){
        return a+b
    }
    ```
### （四）保存程序
1. 将程序保存成```.py```文件，然后通过IDLE打开运行.
   