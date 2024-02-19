## scala入门

#### 面向过程

架构、结构简单，程序的执行效率高

#### 面向对象

功能分离、可维护性强、耦合度低

#### 特点

1. 更适合操作数据
2. scala 中可以使用符号定义变量、方法、等名称
3. 没有continue和break，分别采用循环守卫和抛出异常进行
4. 方法里面可以定义函数



## 变量和数据类型

#### 变量和常量

|      |      |
| ---- | ---- |
| var  | 变量 |
| val  | 常量 |
|      |      |

#### 字符串

模板字符串

三引号  多行字符串

#### 数据类型

![image-20231215120913163](images/scala/image-20231215120913163.png)

#### Unit、Null、Nothing

![image-20231215121158469](images/scala/image-20231215121158469.png)

## 运算符

#### 比较运算符

==在String判断时与Java中不同

==是判断内容与equals一样，eq判断地址

==为Java中的equals

#### 赋值运算符

scala中没有++、--

## 流程控制

#### if    else

允许有返回值

<img src="images/scala/image-20231215132403796.png" alt="image-20231215132403796" style="zoom: 80%;" />

<img src="images/scala/image-20231215132626521.png" alt="image-20231215132626521" style="zoom:80%;" />

#### for循环

包含10

![image-20231215135307365](images/scala/image-20231215135307365.png)

不包含10

![image-20231215140241615](images/scala/image-20231215140241615.png)

![image-20231215140357024](images/scala/image-20231215140357024.png)



Range相当于一个数组，所以也可以这么写

![image-20231215140849307](images/scala/image-20231215140849307.png)

#### 循环守卫

scala中没有continue

![image-20231215142120258](images/scala/image-20231215142120258.png)

步长

![image-20231215142614618](images/scala/image-20231215142614618.png)



![image-20231215142713968](images/scala/image-20231215142713968.png)



![image-20231215142947325](images/scala/image-20231215142947325.png)



![image-20231215143107161](images/scala/image-20231215143107161.png)



![image-20231215143527300](images/scala/image-20231215143527300.png)

嵌套循环

![image-20231215151322897](images/scala/image-20231215151322897.png)



![image-20231215151435341](images/scala/image-20231215151435341.png)

99乘法口诀

![image-20231215152048053](images/scala/image-20231215152048053.png)

循环引入变量

![image-20231215152559353](images/scala/image-20231215152559353.png)

![image-20231215152646371](images/scala/image-20231215152646371.png)

九层妖塔

![image-20231215153641506](images/scala/image-20231215153641506.png)

循环返回值

![image-20231215154551073](images/scala/image-20231215154551073.png)

#### while循环(不推荐使用)

#### 循环中断

![image-20231215161044024](images/scala/image-20231215161044024.png)

![image-20231215161304304](images/scala/image-20231215161304304.png)

## 函数式编程

y=f（x）；

#### 函数基本语法

![image-20231215163635786](images/scala/image-20231215163635786.png)

#### 函数参数

参数默认值



带名参数

![image-20231215170942705](images/scala/image-20231215170942705.png)

#### 函数至简原则

![image-20231215192243451](images/scala/image-20231215192243451.png)



![image-20231215175502754](images/scala/image-20231215175502754.png)



![image-20231215180438655](images/scala/image-20231215180438655.png)

#### 匿名函数

![image-20231215193009885](images/scala/image-20231215193009885.png)

![image-20231215193109555](images/scala/image-20231215193109555.png)

![image-20231215193215227](images/scala/image-20231215193215227.png)

![image-20231215193422804](images/scala/image-20231215193422804.png)

![image-20231215193448256](images/scala/image-20231215193448256.png)

![image-20231215193531117](images/scala/image-20231215193531117.png)

#### 高阶函数

函数可以作为值传递

![image-20231215203204413](images/scala/image-20231215203204413.png)

## 面向对象

### scala包

#### 包对象

![image-20231215214203543](images/scala/image-20231215214203543.png)

### 封装

#### 访问权限

![image-20231215215104758](images/scala/image-20231215215104758.png)