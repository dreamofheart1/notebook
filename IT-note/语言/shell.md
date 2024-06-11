## shell脚本入门

字符串中输出$变量时，外面需要使用单引号

### 执行方式

1. sh 或 bash 执行脚本
2. 输入脚本的绝对路径或相对路径（需要具有文件的可执行权限+x)
3. source 或 . 执行  （该方式是在当前shell中执行，上面两种是开启一个新子shell中执行）

![image-20231218131838709](images/shell/image-20231218131838709.png)

## 变量（环境变量）

1. 系统变量
2. 自定义变量
3. 全局变量 export 变量名  将局部变量升级为全局变量（而且修改值只在局部有效）
4. 局部变量

### 自定义变量

![image-20231218133740618](images/shell/image-20231218133740618.png)

## 特殊变量

### $n

![image-20231218141100724](images/shell/image-20231218141100724.png)

### $#

![image-20231218141127978](images/shell/image-20231218141127978.png)

### $*  $@

![image-20231218141412928](images/shell/image-20231218141412928.png)

### $?

![image-20231218141739863](images/shell/image-20231218141739863.png)

## 运算符

![image-20231218141840516](images/shell/image-20231218141840516.png)

命令替换

![image-20231218142335950](images/shell/image-20231218142335950.png)

## 条件判断

![image-20231218142727114](images/shell/image-20231218142727114.png)

**注意** [] 中要有空格

![image-20231218144314237](images/shell/image-20231218144314237.png)

## 流程控制

### if判断

![image-20231218145638899](images/shell/image-20231218145638899.png)

**注意**上面分号的使用

![image-20231218154919817](images/shell/image-20231218154919817.png)

### case语句

![image-20231218160058207](images/shell/image-20231218160058207.png)

![image-20231218160356560](images/shell/image-20231218160356560.png)

### for 循环

![image-20231218160509583](images/shell/image-20231218160509583.png)

**注意**双小括号中就可以写一些数学的比较

![image-20231218161158224](images/shell/image-20231218161158224.png)

![image-20231218161310176](images/shell/image-20231218161310176.png)

![image-20231218161500287](images/shell/image-20231218161500287.png)

### while循环

![image-20231218162012832](images/shell/image-20231218162012832.png)

let的使用可以使高级语言的语法特性

![image-20231218162204523](images/shell/image-20231218162204523.png)

## 读取控制台输入

![image-20231218162452197](images/shell/image-20231218162452197.png)

## 函数

命令替换$() 就是系统函数调用

### 系统函数

![image-20231218164731331](images/shell/image-20231218164731331.png)

![image-20231218164902894](images/shell/image-20231218164902894.png)

### 自定义函数

![image-20231218165156081](images/shell/image-20231218165156081.png)

解决**return**

![image-20231218165928996](images/shell/image-20231218165928996.png)





## 其他笔记

https://blog.csdn.net/da_ge_de_nv_ren/article/details/128391575







