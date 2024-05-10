- 网课（韩顺平）（共 910 集）：46
  - 跳过 递归部分：222 ~ 227
  - 333
  - 424
  - 436
  - 注解：作用不大，也了解不深
  - 455


# Java后端技术体系

## 第一部分：Java基础

### 第一阶段：建立编程思想

#### 1.Java概述

- 如何快速学习Java技术
- Java历史
- Java特点
- Sublime
- Java运行机制
- JDK
- 转义字符
- Java开发规范
- Java API

#### 2.变量

- 数据类型
- 变量基本使用
- 数据类型转换

#### 3.运算符

- 运算符介绍
- 算术运算符
- 关系运算符
- 逻辑运算符
- 赋值运算符
- 三元运算符
- 优先级
- 二进制
- 位运算符

#### 4.控制结构

- 顺序
- 分支（if else 、switch）
- 循环（for、while、do while）
- break
- continue
- return

#### 5.数组、排序和查找

- 数组
- 排序
- 查找

#### 6.面向对象编程基础

- 类与对象
- 成员方法
- 成员方法传参机制
- overload
- 可变参数
- 作用域
- 构造器
- this

#### 7.面向对象编程中级

- 包
- 访问修饰符
- 封装
- 继承
- 多态
- Super
- overwrite
- Object 类详解
- 断点测试

#### 8.项目

- 零钱通
- 房屋出租系统
- 迷宫问题
- 八皇后问题
- 汉诺塔问题

### 第二阶段：提升编程思想

#### 1.面向对象编程高级

- 类变量和类方法
- 理解main方法语法
- 代码块
- 单例设计模式
- final关键字
- 抽象类
- 接口
- 内部类

#### 2.枚举和注解

- 自定义类实现枚举
- enum 关键字实现枚举
- JDK内置的基本注解类型
- 元注解：对注释进行注解

#### 3.异常

- 异常（Exception）的概念
- 异常体系图
- 常见的异常
- 异常处理
- 异常处理分类
- 自定义异常
- throw 和 throws 的对比

#### 4.常用类

- 包装类
- String
- StringBuffer
- StringBuilding
- Math
- Date、Calender、LocalDate
- System
- Arrays
- BigInteger BigDecimal

#### 5.集合

- 集合框架体系
- Collection
  - List
    - ArrayList
    - LinkedList
    - Vector
  - Set
    - HashSet
    - LinkedHashSet
    - TreeSet
- Map
  - HashMap
  - Hashtable
  - LinkedHashMap
  - TreeMap
  - Properties
- Collections

#### 6.泛型

- 泛型语法
- 自定义泛型
  - 泛型类
  - 泛型接口
  - 泛型方法
- 泛型继承和通配符

#### 7.线程

- 线程介绍
- 线程使用
- 线程方法
- 线程生命周期
- Synchronized
- 互斥锁
- 死锁

#### 8.IO流

- 文件
  - 概念
  - 常用操作
- IO流原理及流的分类
- 节点流和处理流
- 输入流
  - InputStream
    - FileInputStream
    - BufferedInputStream
    - ObjectInputStream
  - Reader
    - FileReader
    - BufferedReader
    - InputStreamReader
- 输出流
  - OutputStream
    - FileOutputStream
    - BufferedOutputStream
    - ObjectOutputStream
  - Writer
    - FileWriter
    - BufferedWriter
    - InputStreamWriter
- Properties类

#### 9.项目

- 坦克大战

### 第三阶段：分析需求，代码实现能力

#### 1.网络编程

- 网络基础
- InetAddress
- Socket
- TCP编程
  - 字节流
  - 字符流
- UDP编程

#### 2.反射

- 反射机制
- Class类
- 类的加载
- 反射获取类的结构信息
  - Class
  - Field
  - Method
  - Constructor
  - 访问属性
  - 访问方法

#### 3.Mysql基础

- MySQL安装和配置
- 数据库
  - 创建
  - 查看、删除数据库
  - 备份恢复数据库
- 表
  - 创建
  - 删除
  - 修改
- MySQL数据类型
- CRUD
  - Insert
  - Update
  - Delete
  - Select
    - 单表
    - 多表
- 函数
- 内连接
- 外连接
- 约束
  - not null
  - primary key
  - unique
  - foreign key
  - check
  - 自增长
- 索引
  - 主键索引
  - 唯一索引（UNIQUE）
  - 普通索引（INDEX）
  - 全文索引
- 事务

#### 4.JDBC和连接池

- JDBC概述
- JDBC快速入门
- JDBC API
  - PreparedStatement
  - DriverManager
  - Statement
  - ResultSet
- JDBCUtils
- 事务
- 批处理
- 连接池
  - DataSource
  - DBCP
  - C3P0
  - Proxool
  - BoneCP
  - Druid
- Apache - DBUtils
- DAO增删改查 - BasicDao

#### 5.正则表达式

- 快速入门
- 正则表达式基本语法
- 三个常用类
  - Pattern
  - Matcher
  - PatternSyntaxException
- 分组、捕获、反向引用
- 元字符
  - 限定符
  - 选择匹配符
  - 分组组合和反向引用符
  - 特殊字符
  - 字符匹配符
  - 定位符
- 应用实例

#### 6.Java8、Java11新特性

- Java8新特性：
  - Lambda
  - 函数式接口
  - 接口静态方法
  - 接口默认方法
  - 方法引用
  - 构造器引用
  - stream API
  - 并行流
  - 串行流
  - Optional
  - 新时间日期 API
- Java11新特性（包含9、10）：
  - 代码层面：
    - JShell
    - 类型推断
    - 集合增强API
    - Stream 加强
    - 新增字符串处理方法
    - Optional加强
    - InputStream增强API
    - 标准Java异步HTTP客户
  - 其他新特性
    - 简化的编译运行
    - 支持Unicode10
    - Epsilon垃圾收集器
    - ZGC
    - JFR
    - 支持Linux容器
    - 支持G1上的并行完全垃圾收集
    - 增强加密算法，代替RC4
    - 最新HTTPS安全协议TLS 1.3
    - 移除和废弃的内容

#### 7.项目

- 骑士周游问题
- 满汉楼
- 多用户通信系统（推消息、私聊、发文件）

## 第二部分：Java高级

### （一）Java多线程 / 多并发

#### 1.并发基础

- 互斥同步
- 非阻塞同步
- 指令重排
- synchronized
- volatile

#### 2.线程

#### 3.锁

- 自旋锁
- 偏向锁
- 可重入锁

#### 4.线程池

#### 5.并发容器

#### 6.JUC

- executor
- collections
- locks
- atomic原子类
- tools（CountDownLatch、Exchanger、ThreadLocal、CyclicBarrier）

### （二）数据结构和算法

#### 数据结构

- 数组
- 队列
- 栈
- 链表
- 树
- 散列
- 堆
- 图

#### 算法

- 排序
- 查找
- 分治
- 动态规划
- 回溯
- 贪心算法
- KMP
- Prim
- kruskal
- floyd最短路径
- 缔结特斯拉最短路径

### （三）设计模式

### （四）JVM

- JVM体系
- 类加载过程、机制
- 双亲委派机制、沙箱安全机制
- JMM（java内存模式）
- 字节码执行过程、机制
- GC（垃圾回收算法）
- JVM性能监控
- JVM调优



## 第三部分：JavaWEB

### （一）前端基础

#### 1.HTML

#### 2.CSS

#### 3.JavaScript

#### 4.Ajax

#### 5.Jquery

### （二）前端框架

#### 1.VUE

#### 2.React

#### 3.Angular

#### 4.bootstarp

#### 5.Node.js

### （三）JavaWeb 后端

#### 1.Tomcat

#### 2.Servlet

#### 3.JSP

## 第四部分：主流框架和项目管理

### （一）Linux

### （二）Nginx（做反向代理的WEb服务器）

### （三）SSM

#### 1.Spring（轻量级的容器框架）

#### 2.SpringMVC（分层的web开发框架）

#### 3.MyBatis（持久化框架）

### （四）项目管理

#### 1.Maven

#### 2.git

#### 3.SVN

#### （五）数据库

#### 1.Redis

#### 2.Mysql

#### 3.Oracle

### （六）其他框架

#### 1.WebService

#### 2.Activiti（工作流框架）

#### 3.Shiro（安全框架）

#### 4.Spring Security（安全框架）

#### 5.JPA

#### 6.SpringData



# Java基础

## 一.第一阶段：建立编程思想

### （一）Java概述

#### 1.Java技术体系平台

- Java SE（Java Standard Edition）标准版：
  - 支持面向桌面级应用（如Windows下的应用程序的 Java 平台，提供了完整的 Java 核心 API，此版本以前称为J2SE
- Java EE（Java Enterprise Edition）企业版：
  - 是为开发企业环境下的应用程序提供的一套解决方案。该技术体系中包含的技术，如：Serclet、Jsp等，主要针对与 Web 应用程序开发。该版本以前称为 J2EE
- Java ME（Java Micro Edition）小型版：
  - 支持Java程序运行在移动终端（手机、PDA）上的平台，对Java API有所精简，并加入了针对移动终端的支持，此版本以前称为J2ME

#### 2.Java重要特点

1. Java语言是面向对象的（OOP）
2. Java语言是健壮的。Java的强类型机制、异常处理、垃圾的自动回收等是Java程序健壮性的重要保证
3. Java语言是跨平台性的。即：一个编译好的 .class 文件可以在多个系统下运行，这种特性称为跨平台
4. Java语言是解释型的
   - 解释性语言：Javascript、PHP、Java
   - 编译型语言：c/c++
   - 区别是：
     - 解释型语言，编译后的代码，不能直接被机器执行，需要解释器执行
     - 编译型语言，编译后的代码，可以直接被机器执行

#### 3.Java开发工具

- editplus、notepad++
- Sublime Text
  - 切换中英文：帮助、language
  - [Sublime Text3快捷键大全](https://www.cnblogs.com/rudong/p/7889114.html)
- IDEA
- eclipse

#### 4.Java运行机制及运行过程

- Java核心机制 - Java虚拟机（JVM java virtual machine）
- 基本介绍：
  - JVM是一个虚拟的计算机，具有指令集并使用不同的存储区域。负责执行指令，管理数据、内存、寄存器，包含在JDK中
  - 对于不同的平台，有不同的虚拟机
  - Java虚拟机机制屏蔽了底层运行平台的差别，实现了“一次编译，到处执行”

#### 5.什么是JDK、JRE

- JDK基本介绍
  - JDK（Java Development Kit ，Java开发工具包）
    - JDK = JRE + Java的开发工具集（java、javac、javadoc、javap等）
  - JDK是提供给开发人员使用的，其中包含了java的开发工具，也包含了JRE，所有安装了JDK就不用再单独安装JRE了
- JRE基本介绍
  - JRE（Java Runtime Environment，Java运行环境）
    - JRE = JVM + Java的核心类库
  - 包括Java虚拟机（JVM）和Java程序所需的核心类库等，如果仅仅想要运行一个开发好的Java程序，计算机中只需要安装JRE即可
- JDK、JRE和JVM的包含关系
  - JDK = JRE + Java的开发工具集（java、javac、javadoc、javap等）
  - JRE = JVM + Java SE标准类库
  - JDK = JVM + Java SE标准类库 + Java的开发工具集
  - 如果仅仅想要运行一个开发好的Java程序 .class 文件，计算机中只需要安装JRE即可

#### 6.下载安装JDK

- 官网：
  - https://www.oracle.com/java/technologies/javase-downloads.html
- 细节说明：
  - 安装路径不用有中文或特殊符号如空格
  - 当提示安装JRE时，建议安装
- 配置环境变量 path
  - 右键我的电脑、属性、高级系统设置、环境变量
  - 系统变量，新建JAVA_HOME，变量值为JDK安装目录
  - 编辑path环境变量，添加：`%JAVA_HOME%\bin`
    - 意思是：告诉Windows操作系统需要到JAVA_HOME指向的目录下的bin文件夹寻找
  - 在终端任意窗口输入javac，如果出现参数信息，则说明配置成功
- 环境变量配置说明：
  - 若配置在用户变量下，则只对这一个用户生效
  - 若配置在系统变量下，则对所有用户都生效

#### 7.Java快速入门

- 需求说明：

  - 要求开发一个`Hello.java`程序，可以输出"hello,world!"

- 开发步骤：

  1. 将Java代码编写到拓展名为`Hello.java`的文件中

     - ```java
       //Java快速入门，演示Java开发步骤
       
       //对代码的相关说明
       //1.public class Hello 表示Hello是一个类，是一个public的类
       //2.Hello{ }	表示一个类的开始和结束
       //3.public static void main(string[] args)	表示一个主方法，即程序的入口
       //4.main(){ }	表示方法的开始和结束
       //5.System.out.println("hello,world!");	表示输出"hello,world!"到屏幕
       
       public class Hello{
       
       	//编写一个主方法
       	public static void main(String[] args){
       		System.out.println("hello,world!");
       	}
       }
       ```

  2. 通过 javac 命令对该 java 文件进行编译，生成 .class 文件

     - 无法生成，因为文件有中文注释
     - 处理方法：文件、重新编码保存、选GBK
       - 无GBK时，切换回英文版，选Chinese
       - 原因：要与控制台保持一致（右键控制台上栏、属性、当前代码页GBK）

  3. 通过 java 命令对生成的 class 文件进行运行

#### 8.Java开发注意事项和细节说明

1. Java源文件以 .java 为拓展名。源文件的基本组成部分是类 class，如：上例中的Hello类
2. Java应用程序的执行入口是 main() 方法。它有固定的书写格式：
   - `public static void main(String[] args){...}`
3. Java语言严格区分大小写
4. Java方法由一条条语句构成，每个语句以`;`结束
5. 大括号都是成对出现的，缺一不可
6. 一个源文件中最多只能有一个 public 类。其他类的个数不限
   - 编译后，每个类都会对应一个 .class 文件
7. 如果源文件包含一个 public 类，则文件名必须按该类名命名
8. 一个源文件中最多只能有一个 public 类，其他类的个数不限，也可以将 main() 方法写在非 public 类中，然后指定运行非 public 类，这样入口就是非 public 的 main() 方法

#### 9.Java转义字符

- 转义字符：

  - `\t`：制表符
  - `\n`：换行符
  - `\\`：一个`\`
  - `\"`：一个`"`
  - `\'`：一个 '
  - `\r`：一个回车

- 补充：在控制台，输入Tab键，可以进行命令自动补全

- 示例：

  - ```java
    //转义字符
    
    public class ChangeChar{
    	public static void main(String[] args){
    		//	\t：制表符
    		System.out.println("aaa\tbbb\tccc\t");	//这里会自动换行
    
    		//	\n：换行符
    		System.out.println("第二行\n第三行\n第四行");
    
    		//	\\：一个 \
    		System.out.println("hello\\java");	//这里只想要输出一个\
    		System.out.println("C:\\Windows\\System32\\cmd.exe");	//这里要输出一个路径
    		System.out.println("\\\\");	//这里要输出连续两个\
    
    		//	\"：一个 "
    		System.out.println("aaa说:\"好好学习Java\"");		//这里要输出：aaa说:"好好学习Java"
    
    		//	\'：一个 '
    		System.out.println("aaa说:\'好好学习Java\'");		//这里要输出：aaa说:'好好学习Java'
    		
    		//	\r：一个回车
    		System.out.println("abcdefg\rbbb");	//解读：1.输出aaa	2.\r光标移到当前行的的第一格，bbb会替换掉abc
    		System.out.println("abcdefg\r\nbbb");	//这里就和没有\r时的输出一致
    	}
    }
    ```

#### 10.初学Java时易犯的错误

1. 找不到文件
   - 原因：源文件名不存在或写错、或当前路径错误
2. 主类名与文件名不一致
   - 解决方法：文件名应该与声明为 public 的主类一致
3. 缺少分号
4. 忘记大小写
5. 拼写错误
6. 括号、引号等左右不匹配
7. 中英文符号区别

#### 11.注释

- 注释(comment)种类：

  1. 单行注释：`//aaa`
  2. 多行注释：`/* aaa */`
  3. 文档注释：`/** aaa */`

- 关键点：文档注释

  - 文档注释，知识内容可以被 JDK 提供的工具 javadoc 所解析，生成一套以网页文件形式体现的该程序的说明文档，一般写在类

- 基本格式：

  - `javadoc -d 文件夹名 -xx -yy 文件名.java`

- 示例：

  - ```java
    //文档注释
    
    /**
     * 
     * @author zzx
     * @version 1.0
     */
    
    public class JavaDocComment{
    	public static void main(String[] args){
    		
    	}
    }
    ```

  - `javadoc -d E:\\temp -author -version JavaDocComment.java`

    - 出错：javadoc不是内部或外部命令
      - 解决办法：在PATH变量中添加jdk的bin文件夹所在路径

#### 12.Java代码规范（精简入门）

    1. 类、方法的注释需要以 javadoc 的方式来写
    2. 非 javadoc 的注释，往往是给代码的维护者来看的，着重告诉读者为什么这么写，如何修改，注意什么问题等
    3. 使用 Tab 操作，实现缩进，默认整体向右边移动，使用 Shift + Tab 整体左移
    4. 运算符和 = 两边习惯性各加一个空格
    5. 源文件使用 utf-8 编码
    6. 行宽度不要超过 80 字符
    7. 代码编写次行风格（大括号另起一行）和行尾风格（大括号在行尾）

#### 13.DOS命令

- DOS介绍：
  - DOS：Disk Operating System 磁盘操作系统
- 与Linux基础命令几乎一致

### （二）变量

#### 1.变量原理

- 变量是程序的基本组成单位
- 变量有三个基本要素：
  - 类型
  - 名称
  - 值

#### 2.变量入门

- 示例1：

  - ```java
    public class Var01 { 
    
    	public static void main(String[] args) {
    
    		//声明变量
    		int a;
    		a = 100;
    		System.out.println(a); 
    
    		//还可以这样使用
    		int b = 800;	//初始化
    		System.out.println(b); 
    	}
    }
    ```

- 示例2：

  - ```java
    public class Var02 { 
    
    	public static void main(String[] args) {
    		//记录人的信息
    		int age = 30;
    		double score = 88.9;
    		char gender = '男';
    		String name = "king";	//注意Java中的字符串String首字母是大写的
    		//输出信息, 快捷键
    		System.out.println("人的信息如下:");
    		System.out.println(name);
    		System.out.println(age);
    		System.out.println(score);
    		System.out.println(gender);		
    	}
    }
    ```

  - 注意：

    - Java中的字符串String首字母是大写的

#### 3.变量使用注意事项

1. 变量表示内存中的一个存储区域（不同的变量，类型不同，占用的空间大小不同）
2. 该区域有自己的名称（变量名）和类型（数据类型）
3. 变量必须先声明，后使用。有顺序
4. 该区域的数据可以在同一类型范围内不断变化
5. 变量在同一作用域内不能重名
6. 变量 = 变量名 + 值 + 数据类型。变量三要素

#### 4.程序中 + 的使用

1. 当左右两边都是数值型时，则作加法运算
2. 当左右两边有一方为字符串，则作拼接操作

- 示例：

  - ```java
    public class Plus { 
    
    	public static void main(String[] args) {
    		System.out.println(100 + 98); //198
    		System.out.println("100" + 98);	//10098
    
    		System.out.println(100 + 3 + "hello");	//103hello
    		System.out.println("hello" + 100 +3); //hello1003
    	}
    }
    ```

#### 5.数据类型

- 每一种数据都定义了明确的数据类型，在内存中分配了不同大小的内存空间（字节）
- Java数据类型：
  - 基本数据类型：
    - 数值型：
      - 整数类型（整型）：
        - byte：1字节
        - short：2字节
        - int：4字节
        - long：8字节
      - 浮点型：
        - float：4字节
        - double：8字节
    - 字符型：
      - char：2字节
    - 布尔型（boolean）：1字节
  - 引用数据类型：
    - 类 class
    - 接口 interface
    - 数组 [ ]
- 注：Java 与 C++ 数据类型区别对比：
  1. Java 的 long 占8个字节；而 C++ 中的 long 占4个字节，long long 类型占8个字节
  2. Java 的布尔类型为 boolean，只包含 true 和 false，没有其他值，不可使用1和0，也不可使用其他数字，因此Java中的布尔类型仅用于逻辑判断；而 C++ 中的布尔类型为  bool，可以使用数字1、0，也可使用其他数字
  3. Java的 char 类型占两个字节；C++ 中的 char 占1个字节
  4. String 在Java中不算数据类型，而是一个类

#### 6.整型类型

- 整型使用细节：
  1. Java 各整数类型有固定的范围和字段长度，不受具体OS的影响，以保证 java程序的可移植性
  2. Java的整型常量（具体值）默认为 int 型，声明 long 型常量后要加`l`或`L`
  3. Java程序中变量常声明为 int 型，除非不足以表示大数，才使用 long

#### 7.浮点类型

- 注意：

  - 关于浮点数在机器中存放形式的简单说明，浮点数 = 符号位 + 指数位 + 尾数位
  - 尾数部分可能丢失，造成精度损失（小数都是近似值）

- 浮点类型使用细节：

  1. 与整数类型类似，Java 各浮点类型也有固定的范围和字段长度，不受具体OS的影响，以保证 java程序的可移植性
  2. Java 的浮点型常量（具体值）默认为 double 型，声明 float 型常量，需要加`f`或`F`
  3. 浮点型常量有两种表示形式：
     1. 十进制数形式，如：`5.12    512.0f   .512`（小数点不能省略）
     2. 科学计数法形式，如：`5.12e2    5.12e-2`
  4. 通常情况下，应该使用 double 型，因为它更精确
  5. 浮点数使用陷阱：2.7 和 8.1/3

- 示例：

  - ```java
    public class FloatDetail { 
    
    	public static void main(String[] args) {
    
    		//Java 的浮点型常量(具体值)默认为double型，声明float型常量，须后加‘f’或‘F'
    		//float num1 = 1.1; //对不对?错误
    		float num2 = 1.1F; //对的
    		double num3 = 1.1; //对
    		double num4 = 1.1f; //对
    
    		//十进制数形式：如：5.12       512.0f        .512   (必须有小数点）
    		double num5 = .123; //等价 0.123
    		System.out.println(num5);
    		//科学计数法形式:如：5.12e2 [5.12 * 10的2次方 ]      5.12E-2   [] 
    		System.out.println(5.12e2);//512.0
    		System.out.println(5.12E-2);//0.0512
    
    		//通常情况下，应该使用double型，因为它比float型更精确。
    		//[举例说明]double num9 = 2.1234567851;	float num10 =  2.1234567851F;
    		double num9 =  2.1234567851;
    		float num10 =  2.1234567851F;
    		System.out.println(num9);
    		System.out.println(num10);
    
    		//浮点数使用陷阱: 2.7 和 8.1 / 3  比较
    		//看看一段代码
    		double num11 = 2.7;
    		double num12 = 8.1 / 3;	//8.1 / 3; //2.7
    		System.out.println(num11);	//2.7
    		System.out.println(num12);	//接近2.7的一个小数，而不是2.7
    		//得到一个重要的使用点: 当我们对运算结果是小数的进行相等判断时，要小心
    		//应该是以两个数的差值的绝对值，在某个精度范围类判断
    		if( num11 == num12) {
    			System.out.println("num11 == num12 相等");
    		}
    		//正确的写法 , ctrl + / 注释快捷键, 再次输入就取消注释
    		if(Math.abs(num11 - num12) < 0.000001 ) {
    			System.out.println("差值非常小，到我的规定精度，认为相等...");
    		}
    		// 可以通过java API  来看 下一个视频介绍如何使用API
    		System.out.println(Math.abs(num11 - num12));
    		//细节:如果是直接查询得的的小数或者直接赋值，是可以判断相等
    	}
    }
    ```

#### 8.补充：Java API文档

- API（Application Programming Interface，应用程序编程接口）是Java提供的基本编程接口（Java提供的类还有相关的方法）。
- 中文在线文档：https://www.matools.com
- 索引

#### 9.字符类型

- 基本介绍：
  - 字符类型可以表示单个字符,字符类型是 char，char 是两个字节（可以存放汉字），多个字符用字符串 String
  
- 注意：Java 中的 char 类型占两个字节，可以用来表示汉字；C++中的 char 占一个字节，不可以用来表示汉字；
  
- 基本使用示例：

  - ```java
    //演示char的基本使用
    public class Char01 { 
    
    	public static void main(String[] args) {
    		char c1 = 'a';
    		char c2 = '\t';
    		char c3 = '韩';
    		char c4 = 97; //说明: 字符类型可以直接存放一个数字
            
    		//修改快捷键 
    		//删除当前行的快捷键使用 ctrl+shif+k => ctrl+ k
            
    		System.out.println(c1);
    		System.out.println(c2);
    		System.out.println(c3);
    		System.out.println(c4);	//当输出c4时候，会输出97表示的字符 => 编码的概念
    	}
    }
    ```

- 字符型细节：

  1. 字符常量是用单引号 `` 括起来的单个字符。例如：
     - `char c1 = 'a';  char c2 = '中';  char c3 = '9';`
  2. Java 中还允许转义字符 `\`来将其后面的字符转变为特殊字符型常量
  3. 在 Java 中，char 的本质是一个整数，在输出时，是 unicode 码对应的字符。
     - https://tool.chinaz.com/Tools/Unicode.aspx
  4. 可以直接给 char 赋一个整数，如何输出时，会按照对应的 unicode 字符输出 [97]
  5. char 类型是可以进行运算的，相当于一个整数，因为它都对应有 Unicode 码

- 示例：

  - ```java
    public class CharDetail { 
    
    	public static void main(String[] args) {
    
    		//在java中，char的本质是一个整数，在默认输出时，是unicode码对应的字符
    		//要输出对应的数字，可以(int)字符
    		char c1 = 97;
    		System.out.println(c1); // a
    
    		char c2 = 'a'; 	//输出'a' 对应的 数字
    		System.out.println((int)c2);
    		char c3 = '韩';
    		System.out.println((int)c3);	//38889
    		char c4 = 38889;
    		System.out.println(c4);	//韩
    
    		//char类型是可以进行运算的，相当于一个整数，因为它都对应有Unicode码.
    		
    		System.out.println('a' + 10);//107
    		System.out.println((char)('a' + 10));//107
    
    		//课堂小测试
    		char c5 = 'b' + 1;	//98+1==> 99
    		System.out.println((int)c5); //99
    		System.out.println(c5); //99->对应的字符->编码表ASCII(规定好的)=>c
    	}
    }
    ```

- 字符类型本质：

  1. 字符型存储到计算机中，需要将字符对应的码值（整数）找出来。比如 a：
     - 存储：a → 码值97 → 二进制 → 存储
     - 读取：二进制 → 97 → a → 显示
  2. 字符和码值的对应关系是通过字符编码表决定的。字符编码表：
     - ASCII（一个字节表示，一共 128 个字符）
     - Unicode（固定大小的编码，使用两个字节来表示字符，字母和汉字都是占用两个字节，会浪费空间）
     - utf-8（大小可变的编码，字母使用一个字节，汉字使用3个字节）
     - GBK（可以表示汉字，且范围广，字母使用一个字节，汉字使用3个字节）
     - gb2312（可以表示汉字，gb2312 < GBK）
     - big5（繁体中文，台湾，香港）

#### 10.布尔类型

- 基本介绍：
  - 布尔类型也叫 boolean 类型，boolean 类型数据只允许取值 true 和 false，无 null
  - boolean 类型占一个字节
  - boolean 类型适用于逻辑运算，一般用于程序流程控制
    - if 条件控制语句
    - while 循环控制语句
    - do-while 循环控制语句
    - for 循环控制语句
- 使用关键细节：
  - Java 的 boolean 类型不可以用 0 或非 0 整数代替 true 和 flase

#### 11.基本数据类型转换

- 自动类型转换

  - 介绍：当 Java 程序在进行赋值或运算时，精度小的类型自动转换为精度大的数据类型
  - 数据类型按精度从小到大排序：
    - char、int、long、float、double
    - byte、short、int、long、float、double

- 示例：

  - ```java
    public class AutoConvert { 
    
    	public static void main(String[] args) {
    		//演示自动转换
    		int num = 'a';	// char -> int
    		double d1 = 80; // int -> double
    		System.out.println(num);	//97
    		System.out.println(d1);	//80.0
    
    	}
    }
    ```

- 自动类型转换注意和细节：

  1. 有多种类型的数据混合运算时，系统首先自动将所有数据转换成容量最大的那种数据类型，如何再进行计算
  2. 当我们把精度大的数据类型赋值给精度小的数据类型时，就会报错，反之就会自动类型转换
  3. （byte 和 short） 与 char 之间不会自动转换
  4. byte、short、char 三者可以计算，在计算时首先转换为 int 类型
  5. boolean 不参与转换
  6. 自动提升原则：表达式结果的类型自动提升为操作数中最大的类型

- 示例：

  - ```java
    //自动类型转换细节
    public class AutoConvertDetail { 
    
    	//编写一个main方法
    	public static void main(String[] args) {
    		//细节1： 有多种类型的数据混合运算时，
    		//系统首先自动将所有数据转换成容量最大的那种数据类型，然后再进行计算
    		int n1 = 10; //ok
    		//float d1 = n1 + 1.1;	//错误 因为1.1的数据类型是double，n1 + 1.1 => 结果类型是 double
    		//double d1 = n1 + 1.1;	//对 n1 + 1.1 => 结果类型是 double
    		float d1 = n1 + 1.1F;//对 n1 + 1.1 => 结果类型是 float
    
    		//细节2: 当我们把精度(容量)大 的数据类型赋值给精度(容量)小 的数据类型时，
    		//就会报错，反之就会进行自动类型转换。
    		//int n2 = 1.1;	//错误 double -> int 
    		
    		//细节3: (byte, short) 和 char之间不会相互自动转换
    		//当把具体数赋给 byte 时，(1)先判断该数是否在byte范围内，如果是就可以
    		byte b1 = 10; //对  这里是正确的, byte范围：-128-127
    		// int n2 = 1; //n2 是int 
    		// byte b2 = n2; //错误，原因： 如果是变量赋值，判断类型。不可以大转小
    		// char c1 = b1; //错误， 原因 byte 不能自动转成 char
    		
    		//细节4: byte，short，char  他们三者可以计算，在计算时首先转换为int类型	
    		byte b2 = 1;
    		byte b3 = 2;
    		short s1 = 1;
    		//short s2 = b2 + s1;	//错, b2 + s1 => int
    		int s2 = b2 + s1;	//对, b2 + s1 => int
    		//byte b4 = b2 + b3; //错误: b2 + b3 => int
    		
    		//boolean 不参与转换
    		boolean pass = true;
    		//int num100 = pass;	// boolean 不参与类型的自动转换
    
    		//自动提升原则： 表达式结果的类型自动提升为 操作数中最大的类型
    		//看一道题		
    		byte b4 = 1;
    		short s3 = 100;
    		int num200 = 1;
    		float num300 = 1.1F;
    
    		double num500 = b4 + s3 + num200 + num300; //等号右边最后是float，再转换float -> double
    	}
    }
    ```

- 强制类型转换：

  - 介绍：自动类型转换的逆过程，**将容量大的数据类型转换为容量小的数据类型**。使用时要加上强制转换符 ( )，但可能造成**精度降低或溢出**，格外要注意

  - 示例：

    - ```java
      public class ForceConvert { 
      
      	public static void main(String[] args) {
      		
      		//演示强制类型转换
      		int n1 = (int)1.9;	//强制将double转换为int
      		System.out.println("n1=" + n1);	//1, 造成精度损失
      
      		int n2 = 2000;
      		byte b1 = (byte)n2;
      		System.out.println("b1=" + b1);//造成 数据溢出 与二进制原反补有关系
      	}
      }
      ```

- 强制类型转换细节

  1. 当进行数据精度从大到小转换时，就需要用到强制类型转换
  2. 强转符号只针对最近的操作数有效，往往会使用小括号提升优先级
  3. char 类型可以保存 int 的常量值，但不能保存 int 的变量值，需要强转

- 示例：

  - ```java
    public class ForceConvertDetail { 
    
    	public static void main(String[] args) {
    		
    		//演示强制类型转换
    		//强转符号只针对于最近的操作数有效，往往会使用小括号提升优先级
    		//int x = (int)10*3.5+6*1.5;//编译错误： double -> int 
    		int x = (int)(10*3.5+6*1.5);// (int)44.0 -> 44
    		System.out.println(x);//44
    
    		char c1 = 100; //ok
    		int m = 100; //ok
    		//char c2 = m; //错误
    		char c3 = (char)m; //ok
    		System.out.println(c3);	//100对应的字符d		
    	}
    }
    ```

#### 12.基本数据类型和 String 类型的转换

- 介绍：

  - 在程序开发中，我们经常需要将基本数据类型转换成 String 类型，或者将 String 类型转成基本数据类型

- 基本数据类型转换 String 类型

  - 语法：将基本类型的值`+ ""`即可
    - `String s = 基本数据类型 + "";`

- String 类型转换为基本数据类型

  - 语法：通过基本类型的包装类调用 parseXX 方法即可

- 示例：

  - ```java
    public class StringToBasic { 
    
    	public static void main(String[] args) {
    		
    		//基本数据类型->String
    		int n1 = 100;
    		float f1 = 1.1F;
    		double d1 = 4.5;
    		boolean b1 = true;
    		String s1 = n1 + "";
    		String s2 = f1 + "";
    		String s3 = d1 + "";
    		String s4 = b1 + "";
    		System.out.println(s1 + " " + s2 + " " + s3 + " " + s4);
    
    		//String->对应的基本数据类型
    		String s5 = "123";
    		//会在OOP 讲对象和方法的时候详细讲
    		//使用 基本数据类型对应的包装类的相应方法，得到基本数据类型
    		int num1 = Integer.parseInt(s5);
    		double num2 = Double.parseDouble(s5);
    		float num3 = Float.parseFloat(s5);
    		long num4 = Long.parseLong(s5);
    		byte num5 = Byte.parseByte(s5);
    		short num6 = Short.parseShort(s5);
             boolean b = Boolean.parseBoolean("true");
    
    		System.out.println("===================");
    		System.out.println(num1);	//123
    		System.out.println(num2);	//123.0
    		System.out.println(num3);	//123.0
    		System.out.println(num4);	//123
    		System.out.println(num5);	//123
    		System.out.println(num6);	//123
    		System.out.println(b);	//true
    
    		//怎么把字符串转成字符char -> 含义是 得到字符串的第一个字符
    		//s5.charAt(0) 得到 s5字符串的第一个字符 '1'
    		System.out.println("第一个字符：" + s5.charAt(0));
             char n = s5.charAt(1);
             System.out.println("第二个字符：" + n);	
    	}
    }
    ```

- 注意事项：

  - 在将 String 类型转成 基本数据类型时，要确保 String 能够转成有效的数据类型。比如 我们可以把 "123" ，转成一个整数，但是不能把 "hello" 转成一个整数
  - 如果格式不正确，就会**抛出异常，程序就会终止**， 这个问题在异常处理章节中，会处理

- 示例：

  - ```java
    public class StringToBasicDetail { 
    
    	public static void main(String[] args) {
    		
    		String str = "hello";
    		//转成int
    		int n1 = Integer.parseInt(str);
    		System.out.println(n1);
    	}
    }
    ```

  - 编译不会出错，在执行时才会抛出异常

### （三）运算符

#### 1.运算符介绍

- 运算符是一种特殊的符号，用以表示数据的运算、赋值和比较等。
  1) 算术运算符
  2) 赋值运算符
  3) 关系运算符 [比较运算符]
  4) 逻辑运算符
  5) 位运算符 [需要二进制基础]
  6) 三元运算符

#### 2.算数运算符

- 算术运算符：

  - +
  - -
  - *
  - /
  - %
  - 前++
  - 后++
  - 前--
  - 后--
  - 字符串相加 +

- 示例：

  - ```java
    /**
     * 演示算术运算符的使用 
     */
    public class ArithmeticOperator { 
    
    	public static void main(String[] args) {
    		// /使用
    		System.out.println(10 / 4); //从数学来看是2.5, java中 2
    		System.out.println(10.0 / 4); //java是2.5
    		// 注释快捷键 ctrl + /, 再次输入 ctrl + / 取消注释
    		double d = 10 / 4;//java中10 / 4 = 2, 2=>2.0 
    		System.out.println(d);// 是2.0
    
    		// % 取模 ,取余
    		// 在 % 的本质 看一个公式!!!! a % b = a - a / b * b
    		// -10 % 3 => -10 - (-10) / 3 * 3 = -10 + 9 = -1
    		// 10 % -3 = 10 - 10 / (-3) * (-3) = 10 - 9 = 1
    		// -10 % -3 =  (-10) - (-10) / (-3) * (-3) = -10 + 9 = -1
    		System.out.println(10 % 3); //1
    
    		System.out.println(-10 % 3); // -1
    		System.out.println(10 % -3); //1
    		System.out.println(-10 % -3);//-1
    
    		//++的使用
    		//
    		int i = 10;
    		i++;//自增 等价于 i = i + 1; => i = 11
    		++i;//自增 等价于 i = i + 1; => i = 12
    		System.out.println("i=" + i);//12
    
    		/*
    		作为表达式使用
            前++：++i先自增后赋值
            后++：i++先赋值后自增
    		 */
    		int j = 8;
    		//int k = ++j; //等价 j=j+1;k=j; 
    		int k = j++; // 等价 k =j;j=j+1;
    		System.out.println("k=" + k + "j=" + j);//8 9
    	}
    }
    ```

- 练习：

  - ```java
    //练习
    public class ArithmeticOperatorExercise01 { 
    
    	public static void main(String[] args) {
    		
    		// int i = 1;	//i->1
    		// i = i++; //规则使用临时变量: (1) temp=i;(2) i=i+1;(3)i=temp;
    		// System.out.println(i); // 1
    
    		// int i=1;
    		// i=++i; //规则使用临时变量: (1) i=i+1;(2) temp=i;(3)i=temp;
    		// System.out.println(i); //2
    		// 
    		// 测试输出
    		int i1 = 10;
    	    int i2 = 20;
            int i = i1++;
            System.out.print("i="+i);//10
            System.out.println("i2="+i2);//20
            i = --i2; 
            System.out.print("i="+i);//19
            System.out.println("i2="+i2);//19
    	}
    }
    ```

  - ```java
    //课堂练习
    public class ArithmeticOperatorExercise02 { 
    
    	public static void main(String[] args) {
    
    		//1.需求:
    		//假如还有59天放假，问：合xx个星期零xx天
    		//2.思路分析
    		//(1) 使用int 变量 days 保存 天数
    		//(2) 一个星期是7天 星期数weeks： days / 7 零xx天leftDays days % 7
    		//(3) 输出
    
    		//3.走代码
    		int days = 25911;
    		int weeks = days / 7;
    		int leftDays = days % 7;
    		System.out.println(days + "天 合" + weeks + "星期零" 
    			+ leftDays + "天");
    
    		//1.需求
    		//定义一个变量保存华氏温度，华氏温度转换摄氏温度的公式为
    		//：5/9*(华氏温度-100),请求出华氏温度对应的摄氏温度
    		//
    		//2.思路分析
    		//(1) 先定义一个double huaShi 变量保存 华氏温度
    		//(2) 根据给出的公式，进行计算即可5/9*(华氏温度-100)
    		//    考虑数学公式和java语言的特性
    		//(3) 将得到的结果保存到double sheShi
    		//3走代码
    		double huaShi = 1234.6;
    		double sheShi = 5.0 / 9 * (huaShi - 100);	//这里5.0可以将结果转为double
    		System.out.println("华氏温度" + huaShi 
    			+ " 对应的摄氏温度=" + sheShi);
    	}
    }
    ```

#### 3.关系运算符

- 介绍：

  1) 关系运算符的结果都是 boolean 型，也就是要么是 true，要么是 false
  2) 关系表达式经常用在 if 结构的条件中或循环结构的条件中

- 关系运算符（relational operator）：

  - ==
  - !=
  - <
  - `>`
  - <=
  - `>=`
  - instanceof
    - 作用：检查是否是类的对象（在面向对象部分会讲解）

- 示例：

  - ```java
    //演示关系运算符的使用
    public class RelationalOperator { 
    
    	public static void main(String[] args) {
    
    		int a = 9;  //提示：开发中，不可以使用 a, b 。变量要尽量见名知意
    		int b = 8;
    		System.out.println(a > b); //T 
    		System.out.println(a >= b);  //T
    		System.out.println(a <= b); //F
    		System.out.println(a < b);//F
    		System.out.println(a == b); //F
    		System.out.println(a != b); //T
    		boolean flag = a > b; //T
    		System.out.println("flag=" + flag);
    	}
    }
    ```

- 关系运算符细节说明：

  1) 关系运算符的结果都是 boolean 型，也就是要么是 true，要么是 false。
  2) 关系运算符组成的表达式，我们称为关系表达式： a > b
  3) 重点！！！：比较运算符"=="不能误写成"="

#### 4.逻辑运算符

- 介绍：

  - 用于连接多个条件（多个关系表达式），最终的结果也是一个 boolean 值

- 逻辑运算符（logic operator）：

  - 短路与：&&
  - 短路或：||
  - 取反：！
  - 逻辑与：&
  - 逻辑或：|
  - 逻辑异或：^

- 逻辑运算规则：

  1) a&b : & 逻辑与
     - 规则：当 a 和 b 同时为 true ,则结果为 true, 否则为 false
  2) a&&b : && 短路与
     - 规则：当 a 和 b 同时为 true ,则结果为 true,否则为 false
  3) a|b : | 逻辑或
     - 规则：当 a 和 b ，有一个为 true ,则结果为 true,否则为 false
  4) a||b : || 短路或
     - 规则：当 a 和 b ，有一个为 true ,则结果为 true,否则为 false
  5) !a : 取反，或者非运算
     - 规则：当 a 为 true, 则结果为 false, 当 a 为 false 是，结果为 true
  6) a^b: 逻辑异或
     - 规则：当 a 和 b 不同时，则结果为 true, 否则为 false

- && 和 & 示例：

  - ```java
    //演示逻辑运算符的使用
    public class LogicOperator01 { 
    
    	public static void main(String[] args) {
    		//&&短路与  和 & 案例演示
    		int age = 50;
    		if(age > 20 && age < 90) {
    			System.out.println("ok100");
    		}
    
    		//&逻辑与使用
    		if(age > 20 & age < 90) {
    			System.out.println("ok200");
    		}
    
    		//区别：
    		//对于&&短路与而言，如果第一个条件为false ,后面的条件不再判断。效率高，开发中基本都用短路与&&
    		//对于&逻辑与而言，如果第一个条件为false ,后面的条件仍然会判断
             int a = 4;
    		int b = 9;
             if(a < 1 && ++b < 50) {	//前半部分不成立，后半部分不执行
    			System.out.println("ok300");
    		}
             System.out.println("a=" + a + " b=" + b);// 4 9
            
             a = 4;
             b = 9;
    		if(a < 1 & ++b < 50) {	//前半部分不成立，后半部分仍继续执行
    			System.out.println("ok400");
    		}
    		System.out.println("a=" + a + " b=" + b);// 4 10
    	}
    }
    ```

- || 和 | 示例：

  - ```java
    //演示| || 使用
    public class LogicOperator02 { 
    
    	public static void main(String[] args) {
    
    		//||短路或  和 |逻辑或 案例演示
    		//|| 规则: 两个条件中只要有一个成立，结果为true,否则为false
    		//| 规则: 两个条件中只要有一个成立，结果为true,否则为false
    		int age = 50;
    		if(age > 20 || age < 30) {
    			System.out.println("ok100");
    		}
    
    		//&逻辑与使用
    		if(age > 20 | age < 30) {
    			System.out.println("ok200");
    		}
    
    		//看看区别
    		//(1)||短路或：如果第一个条件为true，则第二个条件不会判断，最终结果为true，效率高
    		//(2)| 逻辑或：不管第一个条件是否为true，第二个条件都要判断，效率低
    		int a = 4;
    		int b = 9;
    		if( a > 1 || ++b > 4) { //第一个条件成立，第二个条件不执行
    			System.out.println("ok300");
    		}
    		System.out.println("a=" + a + " b=" + b); //4 9
            
            a = 4;
            b = 9;
            if( a > 1 | ++b > 4) { //第一个条件成立，第二个条件仍继续执行
    			System.out.println("ok400");
    		}
    		System.out.println("a=" + a + " b=" + b); //4 10
    	}
    }
    ```

- 取反 ! 和 逻辑异或 ^ 示例：

  - ```java
    //!和^案例演示
    public class InverseOperator { 
    
    	public static void main(String[] args) {
    
    		//! 操作是取反 T->F  , F -> T
    		System.out.println(60 > 20); //T
    		System.out.println(!(60 > 20)); //F
    
    		//a^b: 叫逻辑异或，当 a 和 b 不同时，则结果为true, 否则为false
    		boolean b = (10 > 1) ^ ( 3 > 5); //不同为真
    		System.out.println("b=" + b);	//T
    	}
    }
    ```

- 练习：

  - ```java
    public class Test { 
    
    	public static void main(String[] args) {
    
    		int x = 5;
    		int y = 5;
    		if(x++ == 6 & ++y == 6){ //逻辑与
    		x = 11;
    		}
    		System.out.println("x="+x+",y="+y);
    		// 6, 6
            
    		
    		if(x++==6 && ++y==6){
    		x = 11;
    		}
    		System.out.println("x="+x+",y="+y);
    		// 6, 5
            
    		x = 5;
             y = 5;
    		if(x++==5 | ++y==5){
    		 	x =11;
    		}
    		System.out.println("x="+x+",y="+y);
    		//11, 6
    		
             x = 5;
             y = 5;
    		if(x++==5 || ++y==5){
    			x =11;
    		}
    		System.out.println("x="+x+",y="+y);
    		//11, 5
    		
    		boolean x = true;
    		boolean y = false;
    		short z = 46;
    		if( (z++ == 46) && (y = true) )   z++;  //第一个条件成立，47；第二个条件是赋值,将true赋给y，再判断y是t，成立。48
    		if((x = false) || (++z == 49))  z++; //第一个条件是赋值，将flase赋给x，再判断x，不成立；第二个条件要执行，49。50
    		System.out.println("z="+z); //50 
    	}
    }
    ```

  - 注意：赋值语句不是一定为真，而是先进行赋值，再对赋值后的变量进行判断（！！！）

#### 5.赋值运算符

- 介绍：赋值运算符就是将某个运算后的值，赋给指定的变量

- 赋值运算符（assign operator）：

  - 基本赋值运算符：=
  - 复合赋值运算符：
    - += 
    - -= 
    - *= 
    -  /= 
    - %= 

- 赋值运算符特点：

  1. 运算顺序从右往左 
     - `int num = a + b + c;`
  2. 赋值运算符的左边 只能是变量,右边 可以是变量、表达式、常量值
     - `int num = 20; int num2= 78 * 34 - 10; int num3 = a;`
  3. 复合赋值运算符等价于下面的效果
     - 比如：`a+=3;等价于 a=a+3; 其他类推`
  4. 复合赋值运算符会进行类型转换。
     - `byte b = 2; b+=3; b++;`

- 示例：

  - ```java
    //演示赋值运算符的使用
    
    public class AssignOperator { 
    	public static void main(String[] args) {
    		int n1 = 10;
    		n1 += 4;// n1 = n1 + 4;
    		System.out.println(n1); // 14
    		n1 /= 3;// n1 = n1 / 3;	//4
    		System.out.println(n1); // 4
    
    		//复合赋值运算符会进行强制类型转换
    		byte b = 3;
    		b += 2; // 等价 b = (byte)(b + 2);
             //b = b + 2	//则不可以，会报错，相当于int转换为byte
    		b++; // b = (byte)(b+1);		
    	}
    }
    ```

#### 6.三元运算符

- 三元运算符（ternary operator）基本语法：

  - `条件表达式 ? 表达式 1: 表达式 2;`

- 运算规则：

  1. 如果条件表达式为 true，运算后的结果是表达式 1
  2. 如果条件表达式为 false，运算后的结果是表达式 2

- 示例：

  - ```java
    //三元运算符使用
    
    public class TernaryOperator { 
    
    	public static void main(String[] args) {
    
    		int a = 10;
    		int b = 99;
    		int result = a > b ? a++ : b--;
             // 解读：
    		// 1. a > b 为 false
    		// 2. 返回 b--, 先返回 b的值,然后在 b-1
    		// 3. 返回的结果是99 
    		System.out.println("result=" + result);	//99
    		System.out.println("a=" + a);	//10
    		System.out.println("b=" + b);	//98
    	}
    }
    ```

- 三元运算符细节：

  - 表达式 1 和表达式 2 要为可以赋给接收变量的类型（或可以自动转换）
  - 三元运算符可以转成 if--else 语句
  - 整体类型提升（？？？）

- 示例：

  - ```java
    //三元运算符细节
    public class TernaryOperatorDetail { 
    	public static void main(String[] args) {
    		//表达式1和表达式2要为可以赋给接收变量的类型
    		//(或可以自动转换/或者强制转换)
    		int a = 3;
    		int b = 8;
    		int c = a > b ? (int)1.1 : (int)3.4;//可以的
    		double d = a > b ? a : b + 3;//可以的，满足 int -> double
    	}
    }
    ```

- 练习：

  - ```java
    public class TernaryOperatorExercise { 
    	public static void main(String[] args) {
    		//案例：实现三个数的最大值
    		int n1 = 553;
    		int n2 = 33;
    		int n3 = 123;
    		//思路
    		//1. 先得到 n1 和 n2 中最大数 , 保存到 max1
    		//2. 然后再 求出 max1 和 n3中的最大数，保存到 max2
    		
    		int max1 = n1 > n2 ? n1 : n2;
    		int max2 = max1 > n3 ? max1 : n3;
    		System.out.println("最大数=" + max2);
    
    		//使用一条语句实现, 推荐使用上面方法
    		//老师提示: 后面我们可以使用更好方法,比如排序
    		// int max = (n1 > n2 ? n1 : n2) > n3 ? 
    		// 				(n1 > n2 ? n1 : n2) : n3;
    		// System.out.println("最大数=" + max);	
    	}
    }
    ```

#### 7.Java标识符命名规则和规范

- 标识符概念：

  1. Java 对各种变量、方法和类等命名时使用的字符序列称为标识符
  2. 凡是自己可以起名的地方都叫标识符

- 标识符命名规则：

  1. 由 26个英文字母的大小写、数字0~9、下划线_、& 组成
  2. 数字不可以开头
  3. 不可以使用关键字和保留字，但能包含关键字和保留字
  4. Java 中严格区分大小写，长度无限制
  5. 标识符不能包含空格

- 示例：

  - ```java
    int abcclass = 10;
    int n = 40;
    int N = 50;
    System.out.println("n = " + n);//40
    System.out.println("N = " + N);//50
    
    //? abc 和 aBc 是两个不同变量
    int abc = 100;
    int aBc = 200;
    
    //int a b = 300;	//不能包含空格
    //int a-b=10;	//不能包含-
    int goto1 = 10;
    ```

- 标识符命名规范：

  1. 包名（小写字母加.）：多单词组成时所有字母都小写：aaa.bbb.ccc 
     - 比如：com.hsp.crm
  2. 类名、接口名：多单词组成时，所有单词的首字母大写：XxxYyyZzz [大驼峰]
     - 比如： TankShotGame
  3. 变量名、方法名：多单词组成时，第一个单词首字母小写，第二个单词开始每个单词首字母大写：xxxYyyZzz [小驼峰， 简称 驼峰法]
     - 比如： tankShotGame
  4. 常量名：所有字母都大写。多单词时每个单词用下划线连接：XXX_YYY_ZZZ
     - 比如 ：定义一个所得税率 TAX_RATE
  5. 后面我们学习到 类，包，接口，等时，我们的命名规范要这样遵守，更加详细的看文档

#### 8.保留字

- Java 保留字：现有 Java 版本尚未使用，但以后版本可能会作为关键字使用。自己命名标识符时要避免使用这些保留字：
  -  byValue、cast、future、 generic、 inner、 operator、 outer、 rest、 var 、 goto 、const

#### 9.键盘输入

- 在编程中，需要接收用户输入的数据，就可以使用键盘输入语句来获取。Input.java，需要一个 扫描器（对象），就是 Scanner

- 步骤：

  1. 导入该类的所在包：`java.util.*`
  2. 创建该类对象（声明变量）
  3. 调用里面的功能

- 示例：

  - ```java
    //演示接受用户的输入
    //Scanner类 表示 简单文本扫描器，在java.util 包
    //步骤
    //1. 引入/导入 Scanner类所在的包
    import java.util.Scanner;	//表示把 包：java.util包 下的 类：Scanner类 导入 
    public class Input { 
    	public static void main(String[] args) {
    		/*2. 创建 Scanner 对象 , new 创建一个对象,体会
    			  myScanner 就是 Scanner类的对象*/
    		Scanner myScanner = new Scanner(System.in);
    		//3. 接收用户输入了， 使用 相关的方法，输入不同的数据类型时方法不一样
             //当程序执行到 next 方法时，会等待用户输入~~~
    		System.out.println("请输入名字");
             String name = myScanner.next();	//接收用户输入字符串
            
             System.out.println("请输入年龄");
             int age = myScanner.nextInt();	//接收用户输入int
            
             System.out.println("请输入薪水");
             double sal = myScanner.nextDouble();	//接收用户输入double
            
             System.out.println("人的信息如下:");	
    		System.out.println("名字=" + name + " 年龄=" + age + " 薪水=" + sal);
    	}
    }
    ```

#### 10.进制

- 介绍：
  - 二进制：0,1 ，满 2 进 1。以 0b 或 0B 开头
  - 十进制：0-9 ，满 10 进 1
  - 八进制：0-7 ，满 8 进 1。 以数字 0 开头表示
  - 十六进制：0-9 及 A(10)-F(15)，满 16 进 1。以 0x 或 **0X** 开头表示。此处的 A-F 不区分大小写
- 十进制转换成其他进制
  - 规则：将该数不断除以 进制数，直到商为 0 为止，然后将每步得到的余数倒过来，就是对应的进制

#### 11.原码、反码、补码：

- 对于有符号的而言：
  1. 二进制的最高位是符号位：0表示正数、1表示负数
  2. 正数的原、反、补都一样
  3. 负数的反码：原码符号位不变，其他位取反
  4. 负数的补码：反码 + 1。负数的反码 = 负数的补码 -1
  5. 0的反码、补码都是0
  6. Java 中 没有无符号数，都是有符号的
  7. 在计算机运算时，都是以补码来进行计算的
  8. 当我们看运算结果时，要看原码

#### 12.位运算符

- 位运算符：

  - 按位与 &：两位全为1，则结果为1，否则为0
  - 按位或 |：两位全为0，结果为0，否则为1
  - 按位异或 ^：两位不同为1，相同为0
  - 按位取反 ~：0变1，1变0
  - 算数右移 >> ：低位溢出，符号位不变，并用符号位补溢出的高位
  - 算数左移 << ：符号位不变，低位补0
  - 逻辑右移（无符号右移）：低位溢出，高位补0
  - 没有 <<< 

- 位运算示例：

  - ```java
    public class BitOperator { 
    	public static void main(String[] args) {
    
    		System.out.println(2&3);//2
            //看老师的推导过程
    		//1. 先得到 2的补码 => 2的原码 00000000 00000000 00000000 00000010
    		//   2的补码 00000000 00000000 00000000 00000010
    		//2. 3的补码 3的原码 00000000 00000000 00000000 00000011
    		//   3的补码 00000000 00000000 00000000 00000011
    		//3. 按位&
    		//   00000000 00000000 00000000 00000010
    		//   00000000 00000000 00000000 00000011 
    		//   00000000 00000000 00000000 00000010 & 运算后的补码
    		//   运算后的原码 也是  00000000 00000000 00000000 00000010
    		//   结果就是  2
    
    		System.out.println(~-2);//1
            //推导
    		//1. 先得到 -2的原码 10000000 00000000 00000000 00000010
    		//2. -2的 反码 	    11111111 11111111 11111111 11111101
    		//3. -2的 补码       11111111 11111111 11111111 11111110
    		//4. ~-2操作        00000000 00000000 00000000 00000001运算后的补码
    		//5. 运算后的原码 就是 00000000 00000000 00000000 00000001 => 1
    
    		System.out.println(~2); //-3
            //推导
    		//1. 得到2的补码 00000000 00000000 00000000 00000010
    		//2. ~2操作     11111111 11111111 11111111 11111101  运算后的补码
    		//3. 运算后的反码  11111111 11111111 11111111 11111100
    		//4. 运算后的原码  10000000 00000000 00000000 00000011=>-3
    	}
    }
    ```

  - ```java
    public class BitOperator02 { 
    	public static void main(String[] args) {
    		System.out.println(1 >> 2); //0
    		System.out.println(1 << 2); //4
    		System.out.println(4 << 3); // 4 * 2 * 2 * 2 = 32
    		System.out.println(15 >> 2); // 15 / 2 / 2 = 3
    
    		System.out.println(-10.4%3); // -1.4近似值
    
    		int i = 66;
    		System.out.println(++i+i); //134
    	}
    }
    ```

### （四）程序控制结构

#### 1.程序流程控制介绍

- 在程序中，程序运行的流程控制决定程序是如何执行的，是我们必须掌握的，主要有三大流程控制语句。
  1) 顺序控制
  2) 分支控制
  3) 循环控制

#### 2.顺序控制介绍

- 顺序控制：程序从上到下逐行执行，中间没有任何判断和跳转
- 注意事项：Java 中定义变量时采用合法的前向引用（先定义，再引用）

#### 3.分支控制（if-else）

- if-else

  - 单分支：if
  - 双分支：if-else
  - 多分支：if...else if...else if...else

- 单分支示例：

  - ```java
    //if的快速入门
    import java.util.Scanner;//导入
    public class If01 { 
    
    	public static void main(String[] args) {
    		//编写一个程序,可以输入人的年龄,如果该同志的年龄大于18岁,则输出 "你年龄大于18,要对自己的行为负责,送入监狱"
    		//思路分析
    		//1. 接收输入的年龄, 应该定义一个Scanner 对象
    		//2. 把年龄保存到一个变量 int age
    		//3. 使用 if 判断，输出对应信息
    		
    		//定义一个Scanner 对象
    		Scanner myScanner = new Scanner(System.in);
    		System.out.println("请输入年龄");
    		//把年龄保存到一个变量 int age
    		int age = myScanner.nextInt();
    		//使用 if 判断，输出对应信息
    		if(age > 18) {
    			System.out.println("你年龄大于18,要对自己的行为负责,送入监狱");
    		}
    
    		System.out.println("程序继续...");
    	}
    }
    ```

- 双分支示例：

  - ```java
    //if-else的快速入门
    import java.util.Scanner;//导入
    public class If02 { 
    
    	public static void main(String[] args) {
    		//编写一个程序,可以输入人的年龄,如果该同志的年龄大于18岁,
    		//则输出 "你年龄大于18,要对
    		//自己的行为负责, 送入监狱"。否则 ,输出"你的年龄不大这次放过你了."
    
    		//思路分析
    		//1. 接收输入的年龄, 应该定义一个Scanner 对象
    		//2. 把年龄保存到一个变量 int age
    		//3. 使用 if-else 判断，输出对应信息
    		
    		//应该定义一个Scanner 对象
    		Scanner myScanner = new Scanner(System.in);
    		System.out.println("请输入年龄");
    		//把年龄保存到一个变量 int age
    		int age = myScanner.nextInt();
    		//使用 if-else 判断，输出对应信息
    		if(age > 18) {
    			System.out.println("你年龄大于18,要对自己的行为负责,送入监狱");
    		} else {//双分支
    			System.out.println("你的年龄不大这次放过你了");
    		}
    
    		System.out.println("程序继续...");
    	}
    }
    ```

- 练习：

  - ```java
    //单分支和双分支的练习
    public class IfExercise01 { 
    	public static void main(String[] args) {
    		//编写程序，声明2个double型变量并赋值。
    		//判断第一个数大于10.0，且第2个数小于20.0，打印两数之和
    		
    		double d1 = 33.5;
    		double d2 = 2.6;
    		if(d1 > 10.0 && d2 < 20.0) {
    			System.out.println("两个数和=" + (d1 + d2));
    		}
    
    		//定义两个变量int，判断二者的和，是否能被3又能被5整除，打印提示信息
    		//思路分析:
    		//1. 定义两个变量int num1, num2
    		//2. 定义一个变量 int sum = num1 + num2;
    		//3. sum % 3 , 5 后 等于0 说明可以整除
    		//4. 使用 if - else 来提示对应信息
    		int num1 = 10;
    		int num2 = 1;
    		int sum = num1 + num2;
    		if(sum % 3 == 0 && sum % 5 == 0) {
    			System.out.println("和可以被3又能被5整除");
    		} else {
    			System.out.println("和不能被3和5整除..");
    		}
    
    		//判断一个年份是否是闰年，闰年的条件是符合下面二者之一：
    		//(1)年份能被4整除，但不能被100整除；(2)能被400整除
    		//思路分析:
    		//1. 定义 int year 保存年
    		//2. 年份能被4整除，但不能被100整除  => year % 4 == 0 && year % 100 != 0 
    		//3. 能被400整除 => year % 400 == 0
    		//4. 上面的 2 和  3 是 或的关系 
    		int year = 2028;
    		if( (year % 4 == 0 && year % 100 != 0) ||  year % 400 == 0 ) {
    			System.out.println(year + " 是 闰年");
    		} else {
    			System.out.println(year + " 不是 闰年");
    		}
    	}
    }
    ```

- 多分支示例：

  - ```java
    import java.util.Scanner;
    public class If03 { 
    
    	public static void main(String[] args) {
    		/*
    		输入保国同志的芝麻信用分：
    		如果：
    		信用分为100分时，输出 信用极好；
    		信用分为(80，99]时，输出 信用优秀；
    		信用分为[60,80]时，输出 信用一般；
    		其它情况 ，输出 信用 不及格 
    		请从键盘输入保国的芝麻信用分，并加以判断
    		假定信用分数为int
    		 */
    		
    		Scanner myScanner = new Scanner(System.in);
    		//提示接收用户输入
    		System.out.println("请输入信用分(1-100):");
    		//请思考：如果小伙伴输入的不是整数，而是hello..
    		//==>这里后面可以使用异常处理机制搞定
    		int grade = myScanner.nextInt();
    
    		//先对输入的信用分，进行一个范围的有效判断 1-100, 否则提示输入错误
    		if(grade >=1 && grade <= 100) {
    			//因为有4种情况，所以使用多分支
    			if(grade == 100) {
    				System.out.println("信用极好");
    			} else if (grade > 80 && grade <= 99) { //信用分为(80，99]时，输出 信用优秀；
    				System.out.println("信用优秀");
    			} else if (grade >= 60 && grade <= 80) {//信用分为[60,80]时，输出 信用一般
    				System.out.println("信用一般");
    			} else {//其它情况 ，输出 信用 不及格 
    				System.out.println("信用不及格");
    			}
    		} else {
    			System.out.println("信用分需要在1-100,请重新输入:)");
    		}
    	}
    }
    ```

- 嵌套分支示例：

  - ```java
    import java.util.Scanner;
    public class NestedIf { 
    	public static void main(String[] args) {
    		/*
    		参加歌手比赛，如果初赛成绩大于8.0进入决赛，否则提示淘汰。并且根据性别提示进入男子组或女子组。
    		输入成绩和性别，进行判断和输出信息
    
    		提示: double score; char gender; 
    		接收字符（关键新内容）: char gender = scanner.next().charAt(0)
    			为什么要这样，因为java没有之间键入char的方法，必须键入字符串，再从中取字符
    		 */
    		//思路分析
    		//1. 创建Scanner对象，接收用户输入
    		//2. 接收 成绩保存到 double score
    		//3. 使用 if-else 判断 如果初赛成绩大于8.0进入决赛，否则提示淘汰
    		//4. 如果进入到 决赛，再接收 char gender, 使用 if-else 输出信息
    		//代码实现 => 思路 --> java代码
    		
    		Scanner myScanner = new Scanner(System.in);
    		System.out.println("请输入该歌手的成绩");
    		double score = myScanner.nextDouble();
    		if( score > 8.0 ) {
    			System.out.println("进入决赛，请输入性别：");
    			char gender = myScanner.next().charAt(0); //先接受一个字符串，再取出第一个字符
    			if( gender == '男' ) {
    				System.out.println("进入男子组");
    			} else if(gender == '女') {
    				System.out.println("进入女子组");
    			} else {
    				System.out.println("你的性别有误，不能参加决赛~");
    			}
    		} else {
    			System.out.println("sorry ,你被淘汰了~");
    		}
    	}
    }
    ```

#### 4.分支控制（switch）

- 基本语法：

  - ```java
    switch(表达式){
        case 常量1:
            语句块1;
            break;
        case 常量2:
            语句块2;
            break;
        ...
        case 常量n:
            语句块n;
            break;
        default:
            default语句块;
            break;	//这里的break没有必要，可以省略
    }
    ```

- 示例：

  - ```java
    import java.util.Scanner;
    public class Switch01 { 
    	public static void main(String[] args) {
    		/*
    		案例：
                请编写一个程序，该程序可以接收一个字符，比如:a,b,c,d,e,f,g  
                a表示星期一，b表示星期二 …  
                根据用户的输入显示相应的信息.要求使用 switch 语句完成
    
    		思路分析：
    		1. 接收一个字符 , 创建Scanner对象
    		2. 使用switch 来完成匹配,并输出对应信息
    		 */
    		Scanner myScanner = new Scanner(System.in);
    		System.out.println("请输入一个字符(a-g)");
    		char c1 = myScanner.next().charAt(0);
    		//在java中，只要是有值返回，就是一个表达式
    		switch(c1) {
    			case 'a' : 
    				System.out.println("今天星期一,猴子穿新衣");
    				break;
    			case 'b' : 
    				System.out.println("今天星期二,猴子当小二");
    				break;
    			case 'c' : 
    				System.out.println("今天星期三,猴子爬雪山..");
    				break;
    			//.....
    			default:
    				System.out.println("你输入的字符不正确，没有匹配的");
    		}
    		System.out.println("退出了switch ,继续执行程序");
    	}
    }
    ```

- switch 注意事项和细节：

  1. 表达式数据类型，应该与 case 后的常量类型一致，或者是可以自动转换成可以比较的类型，比如输入的是字符，而常量是 int，可以自动转换，char 会自动转换为 int 然后继续比较。否则就会报错（不兼容的类型）
  2. switch(表达式)中表达式的返回值必须是：
     - byte、short、int、char、enum[枚举]、String
  3. case子句中的值必须是常量（1、'a'）或者是常量表达式，而不能是变量
  4. default 子句是可选的，当没有匹配的 case 时，执行 default 。如果没有default 子句，又没有匹配任何常量，则没有输出
  5. break 语句用来在执行完一个 case 分支后使程序跳出 switch 语句块；如果没有写 break，程序会顺序执行到 switch 结尾，除非执行到 break

- 细节示例：

  - ```java
    public class SwitchDetail { 
    	public static void main(String[] args) {
    		//细节1
    		//表达式数据类型，应和case 后的常量类型一致，
    		//或者是可以自动转成可以相互比较的类型。比如输入的是字符，而常量是 int
    		
    		//细节2
    		//switch(表达式)中表达式的返回值必须是：
    		//(byte,short,int,char,enum[枚举],String)
    
    		//细节3
    		//case子句中的值必须是常量(1,'a')或者是常量表达式,而不能是变量
    		
    		//细节4
    		//default子句是可选的，当没有匹配的case时，执行default
    		//如果没有default 子句，有没有匹配任何常量，则没有输出
    		
    		//细节5
    		//break语句用来在执行完一个case分支后使程序跳出switch语句块；
    		//如果没有写break，程序会顺序执行到switch结尾,除非执行到break
    		char c = 'b';
    		char c2 = 'c';
    		switch(c) {
    			case 'a' :
    				System.out.println("ok1");
    				break;
    			case 'b'  :
    				System.out.println("ok2");
    				break;
    			default :
    				System.out.println("ok3");
    		}
    
    		System.out.println("退出了switch,继续执行..");
    	}
    }
    ```

- 练习：

  - ```java
    import java.util.Scanner;
    public class SwitchExercise { 
    	public static void main(String[] args) {
    		/*	练习1：使用 switch 把小写类型的 
    			char型转为大写(键盘输入)。只转换 a->A, b->B, c, d, e. 
    			其它的输出 "other"。*/
    		/*
            //创建Scanner对象
            Scanner myScanner = new Scanner(System.in);
            System.out.println("请输入a-e");
            char c1 = myScanner.next().charAt(0);
            switch(c1) {
                case 'a' :
                    System.out.println("A");
                    break;
                case 'b' :
                    System.out.println("B");
                    break;
                case 'c' :
                    System.out.println("C");
                    break;
                case 'd' :
                    System.out.println("D");
                    break;
                case 'e' :
                    System.out.println("E");
                    break;
                default :
                    System.out.println("你的输入有误~"); */
    
            /*
            练习2：对学生成绩大于等于60分的，输出"合格"
            低于60分的，输出"不合格"。(注：输入的成绩不能大于100), 提示 成绩/60
            思路分析：
            	1. 这道题，可以使用 分支来完成， 但是要求使用switch
            	2. 这里我们需要进行一个转换, 编程思路 : 
            		如果成绩在 [60,100] , (int)(成绩/60) = 1 
           			如果成绩在 [0,60) , (int)(成绩/60) = 0 */	
    		
            /*
    		double score = 1.1;
    		//使用if-else 保证输入的成绩有有效的 0-100
    		if( score >= 0 && score <= 100) {
    			switch ((int)(score / 60)) {
    				case 0 :
    					System.out.println("不合格");
    					break;
    				case 1 :
    					System.out.println("合格");
    					break;
    				// default :
    				// 	System.out.println("输入有误");
    			}
    		} else {
    			System.out.println("输入的成绩在0-100");
    		}
    		*/
    		
            /*
            练习3：根据用于指定月份，打印该月份所属的季节。3,4,5 春季 6,7,8 夏季  9,10,11 秋季 12, 1, 2 冬季 
    
            思路分析：
            	1. 创建Scanner对象， 接收用户输入
            	2. 使用 int month 接收
            	3. 使用switch 来匹配 ,使用穿透来完成，比较简洁
            */
    		
    		Scanner myScanner = new Scanner(System.in);
    		System.out.println("输入月份");
    		int month = myScanner.nextInt();
    		switch(month) {
    			case 3:
    			case 4:
    			case 5: 
    				System.out.println("这是春季");
    				break;
    			case 6:
    			case 7:
    			case 8: 
    				System.out.println("这是夏季");
    				break;
    			case 9:
    			case 10:
    			case 11: 
    				System.out.println("这是秋季");
    				break;
    			case 1:
    			case 2:
    			case 12: 
    				System.out.println("这是冬季");
    				break;
    			default :
    				System.out.println("你输入的月份不对(1-12)");
    		}
    	}
    }
    ```

#### 5.for 循环控制

- 基本语法：

  - ```java
    for(循环变量初始化; 循环条件; 循环遍历迭代){
        循环操作;
    }
    ```

- for 循环注意事项和细节：

  1. 循环条件是返回一个布尔值的表达式

  2. `for(; 循环判断条件; ) `中的初始化和变量迭代可以写到其它地方，但是两边的分号不能省略。

  3. 循环初始值可以有多条初始化语句，但要求类型一样，并且中间用逗号隔开，循环变量迭代也可以有多条变量迭代

     语句，中间用逗号隔开

#### 6.while 循环控制

- 基本语法：

  - ```java
    循环遍历初始化;
    while(循环条件){
        循环体;
        循环遍历迭代;
    }
    ```

- while 循环注意事项和细节：

  1. 循环条件是返回一个布尔值的表达式
  2. while 循环是先判断再执行语句

- 示例：

  - ```java
    public class WhileExercise { 
    	public static void main(String[] args) {
    		// 打印1—100之间所有能被3整除的数 
    		int i = 1;
    		int endNum = 100;
    		while( i <= endNum) {
    			if( i % 3 == 0) {
    				System.out.println("i=" + i);
    			}
    
    			i++;//变量自增
    		}
    
    		// 打印40—200之间所有的偶数 
    		System.out.println("========");
    		int j = 40; //变量初始化
    		while ( j <= 200) {
    			//判断
    			if( j % 2 == 0) {
    				System.out.println("j=" + j);
    			}
    			j++;//循环变量的迭代
    		}
    	}
    }
    ```

#### 7.do...while 循环控制

- 基本语法：

  - ```java
    循环遍历初始化;
    do{
        循环体;
        循环变量迭代;
    }while(循环条件);
    ```

  - 注意：最后有一个分号

- 示例：

  - ```java
    public class DoWhile01 { 
    	public static void main(String[] args) {
    		//输出10句 你好,韩顺平教育
    		int i = 1; //循环变量初始化
    		do {
    			//循环执行语句
    			System.out.println("你好，韩顺平教育" + i);
    			//循环变量迭代
    			i++;
    		}while(i <= 10);
    
    		System.out.println("退出 do..while 继续执行.." + i);//11
    	}
    }
    ```

- 练习：

  - ```java
    public class DoWhileExercise01 { 
    	public static void main(String[] args) {
    		//要求：输出能被5整除但不能被3整除的数，统计满足条件的个数 int count = 0
    		int i = 1;
    		int count = 0; //统计满足条件的个数
    		do {
    			if( i % 5 == 0 && i % 3 != 0 ) {
    				System.out.println("i=" + i);
    				count++;
    			}
    			i++;
    		}while(i <= 200);
    
    		System.out.println("count=" + count);
    	}
    }
    ```

#### 8.多重循环

- 示例1：

  - ```java
    import java.util.Scanner;
    public class MulForExercise01 { 
    	public static void main(String[] args) {
    		/*
                统计3个班成绩情况，每个班有5名同学
                要求：
                	1.求出各个班的平均分 和 所有班级的平均分[学生的成绩从键盘输入]。
                	2.统计三个班及格人数，每个班有5名同学。	*/
    		/*
                思路分析:
                    (1) 先计算一个班 , 5个学生的成绩和平均分 , 使用for
                        1.1 创建 Scanner 对象然后，接收用户输入
                        1.2 得到该班级的平均分 , 定义一个 doubel sum 把该班级5个学生的成绩累积 
                    (2) 统计3个班(每个班5个学生) 平均分
                    (3) 所有班级的平均分
                        3.1 定义一个变量，double totalScore 累积所有学生的成绩
                        3.2 当多重循环结束后，totalScore / (3 * 5) 
                    (4) 统计三个班及格人数
                        4.1 定义变量 int passNum = 0; 当有一个学生成绩>=60, passNum++
                        4.2 如果 >= 60 passNum++
                    (5) 可以优化[效率，可读性, 结构]
    		*/
    		//创建 Scanner 对象
    		Scanner myScanner = new Scanner(System.in);
    		double totalScore = 0; //累积所有学生的成绩
    		int passNum = 0;	//累积所有及格人数
    		int classNum = 3;	 //班级个数
    		int stuNum = 5;	//学生个数
    		for( int i = 1; i <= classNum; i++) {//i 表示班级
    			double sum = 0; //一个班级的总分
    			for( int j = 1; j <= stuNum; j++) {//j 表示学生
    				System.out.println("请输入第" + i + "个班的第" + j + "个学生的成绩");
    				double score = myScanner.nextDouble();
    				//当有一个学生成绩>=60, passNum++
    				if(score >= 60) {
    					passNum++;
    				}
    				sum += score; //累积
    				System.out.println("成绩为" + score);
    			}
    			//因为sum 是 5个学生的总成绩
    			System.out.println("sum=" + sum + " 平均分=" + (sum / stuNum));
    			//把 sum 累积到 totalScore
    			totalScore += sum;
    		}
    		System.out.println("三个班总分="+ totalScore 
    			+ " 平均分=" + totalScore / (classNum*stuNum));
    		System.out.println("及格人数=" + passNum);
    	}
    }
    ```

- 练习，打印空心金字塔：

  - ```java
    public class Stars { 
    	public static void main(String[] args) {
    		/*
    		
    			   *
    			  *  *
    			 *    *
    			********
    		思路分析:
    		
    		1. 先打印一个矩形
    		*****
    		*****
    		*****
    		*****
    		*****
    		
    		2. 打印半个金字塔
    
    		*    	//第1层 有 1个*
    		**   	//第2层 有 2个*
    		***		//第3层 有 3个*
    		****    //第4层 有 4个*
    		*****   //第5层 有 5个*
    		
    		3. 打印整个金字塔
    		*       //第1层 有 1个*   2 * 1 -1   有4=(总层数-1)个空格
    	   ***      //第2层 有 3个*   2 * 2 -1   有3=(总层数-2)个空格
    	  *****     //第3层 有 5个*   2 * 3 -1   有2=(总层数-3)个空格
    	 *******    //第4层 有 7个*   2 * 4 -1   有1=(总层数-4)个空格
    	*********   //第5层 有 9个*   2 * 5 -1   有0=(总层数-5)个空格
    
    		4. 打印空心的金字塔 [最难的]
    	    *       //第1层 有 1个*   当前行的第一个位置是*,最后一个位置也是*
    	   * *      //第2层 有 2个*   当前行的第一个位置是*,最后一个位置也是*
    	  *   *     //第3层 有 2个*   当前行的第一个位置是*,最后一个位置也是*
    	 *     *    //第4层 有 2个*   当前行的第一个位置是*,最后一个位置也是*
    	*********   //第5层 有 9个*   全部输出*
    	
    		5 层数做成变量 int totalLevel = 5;
    		 */
    		int totalLevel = 20; //层数
    		for(int i = 1; i <= totalLevel; i++) { //i 表示层数
    
    			//在输出*之前，还有输出 对应空格 = 总层数-当前层
    			for(int k = 1; k <= totalLevel - i; k++ ) {
    				System.out.print(" ");
    			}
    
    			//控制打印每层的*个数
    			for(int j = 1; j <= 2 * i - 1; j++) {
    				//当前行的第一个位置是*,最后一个位置也是*, 最后一层全部 *
    				if(j == 1 || j == 2 * i - 1 || i == totalLevel) {
    					System.out.print("*");
    				} else { //其他情况输出空格
    					System.out.print(" ");
    				}
    			}
    			//每打印完一层的*后，就换行 println本身会换行
    			System.out.println("");
    		}
    	}
    }

#### 9.跳转控制语句 break

- break 语句用于终止某个语句块的执行，一般使用在 switch 或者循环（for 、while 、do-while）中

- 示例：

  - ```java
    public class Break01 { 
    	public static void main(String[] args) {
    
    		//测试代码
    		for( int i = 0; i < 10; i++) {
    			if( i == 3) {
    				break ;
    			}
    			System.out.println("i=" + i);
    		}
    
    		System.out.println("退出for循环, 继续执行..");
            //...
    	}
    }
    ```

- break 细节和注意事项：

  1. break 语句出现在多层嵌套的语句块中时，可以通过标签指明要终止的时那一层语句块

  2. 标签的基本使用：

     - ```
       label1:{
       	label2:{
       		label3:{
       			break label2;
       		}
       	}
       }
       ```

     - 解读：

       - break 语句可以指定退出哪层
       - label 是标签，名字由程序员指定
       - break 后指定到哪个 label 就退出到哪里
       - 在实际开发中，尽量不要使用标签
       - 如果没有指定 break ，默认退出最近的循环体

- 细节示例：

  - ```java
    public class BreakDetail { 
    	public static void main(String[] args) {
    
    		abc1:
    		for(int j = 0; j < 4; j++){//外层for
    		abc2:
    			for(int i = 0; i < 10; i++){//内层for
    				if(i == 2){
    					//break  ;//等价 break abc2
    					break abc1 ;
    				}
    				System.out.println("i = " + i);
    			}
    		}
    
    	}
    }
    ```

- 练习：

  - ```java
    public class BreakExercise { 
    	public static void main(String[] args) {
    		//1-100以内的数求和，求出 当和 第一次大于20的当前数 【for + break】
    
    		/*思路分析
                1. 循环 1-100, 求和 sum  
                2. 当 sum > 20 时，记录下当前数，然后break
                3. 在for循环外部，定义变量 n , 把当前i 赋给 n	*/
    		int sum = 0; //累积和	
    
    		//注意i 的作用范围在 for{}
    		int n = 0;
    		for(int i = 1; i <= 100; i++) {
    			sum += i;//累积
    			if(sum > 20) {
    				System.out.println("和>20时候 当前数i=" + i);
    				n = i;
    				break;
    			} 
    		}
    
    		System.out.println("当前数=" + n);
    	}
    }
    ```

  - ```java
    import java.util.Scanner;
    public class BreakExercise02 { 
    	public static void main(String[] args) {
    
    		/*
    		实现登录验证，有3次机会，如果用户名为"丁真" ,密码"666"提示登录成功，
    		否则提示还有几次机会，请使用for+break完成
    	
             思路分析
                 1. 创建Scanner对象接收用户输入  
                 2. 定义 String name ; String passwd; 保存用户名和密码
                 3. 最多循环3次[登录3次]，如果 满足条件就提前退出
                 4. 定义一般变量 int chance 记录还有几次登录机会	*/
    		
    		Scanner myScanner  = new Scanner(System.in);
    		String name = "";
    		String passwd = "";
    		int chance = 3; //登录一次 ，就减少一次
    		for( int i = 1; i <= 3; i++) {	//3次登录机会
    			System.out.println("请输入名字");
    			name = myScanner.next();
    			System.out.println("请输入密码");
    			passwd = myScanner.next();
    			//比较输入的名字和密码是否正确
    			//补充说明字符串 的内容 比较 使用的 方法 equals
    			if("丁真".equals(name) && "666".equals(passwd)) {
    				System.out.println("恭喜你，登录成功~");
    				break;
    			}
    
    			//登录的机会就减少一次
    			chance--;
    			System.out.println("你还有" + chance + "次登录机会");
    		}
    	}
    }
    ```

#### 10.跳转控制语句 continue

- 基本介绍：

  1) continue 语句用于结束本次循环**，**继续执行下一次循环
  2) continue 语句出现在多层嵌套的循环语句体中时，可以通过标签指明要跳过的是哪一层循环，和前面的标签的使用的规则一样

- 示例：

  - ```java
    public class Continue01 { 
    	public static void main(String[] args) {
    		
    		int i = 1;
    		while( i <= 4) {
    			i++;
    			if( i == 2) {
    				continue;
    			}
    			System.out.println("i=" + i);
    		}
    	}
    }
    ```

- 细节示例：

  - ```java
    public class ContinueDetail { 
    	public static void main(String[] args) {
    		label1:
    		for(int j = 0; j < 2; j++){
    			label2:
    			for(int i = 0; i < 10; i++){
    				if(i == 2){
    					//看看分别输出什么值，并分析
    					//continue ; //等价于 continue label2
    					//continue label2;//等价 continue;
    					continue label1; //输出 2次[0,1]
    				}
    				System.out.println("i = " + i);	//continue;时  输出2遍[0,1,3,4,5,6,7,8,9]
    	        }
    	     }
    
    	}
    }
    ```

#### 11.跳转控制语句 return

- return 使用在方法，表示跳出所在的方法，在讲解方法的时候，会详细的介绍，这里我们简单的提一下。

- 注意：如果 return 写在 main 方法，退出程序

- 示例：

  - ```java
    public class Return01 { 
    	public static void main(String[] args) {
    		for(int i = 1; i <= 5; i++){
    			if(i == 3) {
    		        System.out.println("韩顺平教育 "+i);
    				return; //当return用在方法时，表示跳出方法，如果使用在main,表示退出程序
                      //break;
                      //continue;
    			}
    			System.out.println("Hello World!");
    		}
    		System.out.println("go on..");
    	}
    }
    ```

#### 12.作业练习：

- 练习1：

  - ```java
    
    public class Homework01 { 
    
    	//编写一个main方法
    	public static void main(String[] args) {
    		/*
    		某人有100,000元,每经过一次路口，需要交费,规则如下:
                1) 当现金>50000时,每次交5%
                2) 当现金<=50000时,每次交1000
    		编程计算该人可以经过多少次路口, 要求: 使用 while + break方式完成
    
    		思路分析:
                1. 定义 double money 保存 100000
                2. 根据题的要求，我们分析出来有三种情况 
                    money > 50000 
                    money >=1000 && money <= 50000
                    money < 1000 
                3. 使用多分支 if-elseif-else 
                4. while+break[money < 1000], 同时使用一个变量count来保存通过路口
    		 */
    		double money = 100000;	//还有多少钱
    		int count = 0; //累积过的路口
    		while(true) { //无限循环
    			if(money > 50000) { //过路口
    				//money = money -  money * 0.05;
    				money *= 0.95; //过了这个路口后，还有这么多钱
    				count++;
    			} else if(money >=	1000) {
    				money -= 1000;
    				count++;
    			} else { //钱不够1000
    				break;
    			}
    		}
    		System.out.println("100000 可以过 " + count + " 路口..");
    	}
    }
    ```

- 练习2：

  - ```java
    public class Homework02 { 
    	public static void main(String[] args) {
    		/*
    		判断一个整数是否是水仙花数，所谓水仙花数是指一个3位数，其各个位上数字立方和等于其本身。
    		例如： 153 = 1*1*1 + 3*3*3 + 5*5*5
    		
    		思路分析:
                1. 比如 int n = 153; 
                2. 先得到 n的百位，十位 ，各位的数字, 使用 if 判断他们的立方和是否相等
                3. n的百位 = n / 100
                4. n的十位 = n % 100 / 10
                5. n的各位 = n % 10
                6. 判断即可
    		 */
    		int n = 154;
    		int n1 = n / 100;
    		int n2 = n % 100 / 10;
    		int n3 = n % 10;
    		if(n1 * n1 * n1 + n2 * n2 * n2 + n3 * n3 * n3 == n) {
    			System.out.println(n + "是水仙花数");
    		} else {
    			System.out.println(n + "不是水仙花数");
    		}
    	}
    }
    ```

- 练习3：

  - ```java
    public class Homework03 { 
    	public static void main(String[] args) {
    		/*
    		输出1-100之间的不能被5整除的数，每5个一行
    
    		思路分析:
                1. 先输出1-100的所有数
                2. 然后过滤输出 不能被5整除的数 i % 5 !=0
                3. 每5个一行, 我们使用 int count 统计输出的个数 当 count % 5 == 0 就说明
                    输出了5个，这时，我们输出 一个换行即可控制
    		 */
    		int count = 0; //统计输出的个数
    		for(int i = 1; i <= 100; i++) {
    			if(i % 5 != 0) {
    				count++;
    				System.out.print(i + "\t");
    
    				//判断, 每满5个，就输出一个换行..
    				if(count % 5 == 0) {
    					System.out.println();
    				}
    			}
    		}
    	}
    }
    ```

- 练习4：

  - ```java
    public class Homework04 { 
    	public static void main(String[] args) {
    		//输出小写的 a-z 以及大写的 Z-A
    		//考察对 a-z 编码和 for的综合使用
    		/*思路分析
    			1. 'b' = 'a' + 1 c = 'a' + 2
    			2. 使用for搞定	*/	
    		for(char c1 = 'a'; c1 <= 'z'; c1++) {
    			System.out.print(c1 +" ");
    		} 
    		System.out.println("============");
    		//灵活的使用，编程..
    		for(char c1 = 'Z'; c1 >= 'A'; c1--) {
    			System.out.print(c1 +" ");
    		}		
    	}
    }
    ```

- 练习5：

  - ```java
    public class Homework05 { 
    	public static void main(String[] args) {
    		/*
    		求出1-1/2+1/3-1/4…..1/100的和
    		
    		思路分析:
                1. 1-1/2+1/3-1/4…..1/100 = (1/1)-(1/2)+(1/3)-(1/4)...1/100
                2. 从上面的分析我们可以看到 
                    (1) 一共有100数 ， 分子为1 , 分母从1-100
                    (2) 还发现 当分母为奇数时，前面是 +, 当分母是偶数时，前面是-
                3. 我们可以使用 for + 判断即可完成
                4. 把结果存放到 double sum 
                5. 这里有一个隐藏的陷阱，要把 公式分子 1 写出1.0 才能得到精确的小数
    		 */
    		
    		double sum = 0;
    		for(int i = 1; i <= 100; i++) {
    			//判断是奇数还是偶数，然后做不同的处理
    			if( i % 2 != 0) {//分母为奇数
    				sum += 1.0/i;
    			} else { //分母我偶数
    				sum -= 1.0/i;
    			}
    		}
    		System.out.println("sum=" + sum);
    	}
    }
    ```

- 练习6：

  - ```java
    public class Homework09 { 
    	public static void main(String[] args) {
    		//求(1)+（1+2）+（1+2+3）+（1+2+3+4）+...+(1+2+3+..+100)的结果
    
    		/*思路分析
    			1. 一共有100项相加
    			2. 每一项的数字在逐渐增加
    			3. 很像一个双层循环
    				i 可以表示是第几项,同时也是当前项的最后一个数
    			4. 使用 sum 进行累计即可	*/
    		int sum = 0;
    		for(int i = 1; i <= 100; i++) {
    			for(int j = 1; j <= i; j++) {//内层对1-i进行循环
    				sum += j;
    			}
    		}
    		System.out.println("sum=" + sum);  
    	}
    }
    ```

### （五）数组、排序和查找

#### 1.数组介绍

- 数组可以存放多个同一类型的数据。数组也是一种数据类型，是引用类型。

  - 即：数（数据）组（一组）就是一组数据

- 引导示例：

  - ```java
    //数组的引出
    public class Array01 { 
    	public static void main(String[] args) {
    		/*
    		它们的体重分别是3kg,5kg,1kg,3.4kg,2kg,50kg 。
    		请问这六只鸡的总体重是多少?平均体重是多少?
    		思路分析
                1. 定义六个变量 double , 求和 得到总体重
                2. 平均体重 = 总体重 / 6
                3. 分析传统实现的方式问题. 6->600->566
                4. 引出新的技术 -> 使用数组来解决.
    		 */
    		
    		// double hen1 = 3;
    		// double hen2 = 5;
    		// double hen3 = 1;
    		// double hen4 = 3.4;
    		// double hen5 = 2;
    		// double hen6 = 50;
    
    		// double totalWeight = hen1 + hen2 + hen3 + hen4 + hen5 + hen6;
    		
    		// double avgWeight = totalWeight / 6;
    		// System.out.println("总体重=" + totalWeight 
    		// 	+ "平均体重=" + avgWeight);
    
    		//比如，我们可以用数组来解决上一个问题 => 体验
    		
    		//定义一个数组
    		//解读
    			//1. double[] 表示 是double类型的数组， 数组名 hens
    			//2. {3, 5, 1, 3.4, 2, 50} 表示数组的值/元素,依次表示数组的第几个元素
    		
    		double[] hens = {3, 5, 1, 3.4, 2, 50, 7.8, 88.8,1.1,5.6,100};
    
    		//遍历数组得到数组的所有元素的和， 使用for
    		//解读:
    			//1. 我们可以通过 hens[下标] 来访问数组的元素下标是从 0 开始编号的比如第一个元素就是 hens[0] 第2个元						素就是 hens[1]  , 依次类推 
    			//2. 通过for就可以循环的访问 数组的元素/值
    			//3. 使用一个变量 totalWeight 将各个元素累积
    		System.out.println("===使用数组解决===");
    		//提示： 可以通过 数组名.length 得到数组的大小/长度
    		//System.out.println("数组的长度=" + hens.length);
    		double totalWeight = 0;
    		for( int i = 0; i < hens.length; i++) {
    			//System.out.println("第" + (i+1) + "个元素的值=" + hens[i]);
    			totalWeight += hens[i];
    		}
    
    		System.out.println("总体重=" + totalWeight + "平均体重=" + (totalWeight / hens.length) );		
    	}
    }
    ```

#### 2.数组的使用

- 使用方法1：动态初始化

  - 数组的定义：`数据类型 数组名[] = new 数据类型[大小]`
    - 例：`int a[] = new int[5];`
  - 数组的使用：`数组名[下标]`

- 使用方法2：动态初始化

  - 先声明数组，语法：
    - `数组类型 数组名[];`
  - 后创建：
    - `数组名 = new 数据类型[大小];`

- 使用方法3：静态初始化

  - 初始化数组：`数据类型 数组名[] = {元素1, 元素2, ... , 元素n};`
  - 适用于一开始知道数组有多少元素和具体值

- 示例：

  - ```java
    import java.util.Scanner;
    public class Array02 { 
    	public static void main(String[] args) {
    		//演示 数据类型 数组名[]=new 数据类型[大小]
    		//循环输入5个成绩，保存到double数组,并输出
    		
    		//步骤
    		//1. 创建一个 double 数组，大小 5
    		
    		//(1) 第一种动态分配方式
    		//double scores[] = new double[5];
    		//(2) 第2种动态分配方式， 先声明数组，再 new 分配空间
    		double scores[] ; //声明数组， 这时 scores 是 null
    		scores = new double[5]; // 分配内存空间，可以存放数据
    
    		//2. 循环输入
    		//   scores.length 表示数组的大小/长度
    		Scanner myScanner = new Scanner(System.in);
    		for( int i = 0; i < scores.length; i++) {
    			System.out.println("请输入第"+ (i+1) +"个元素的值");
    			scores[i] = myScanner.nextDouble();
    		}
    
    		//输出，遍历数组
    		System.out.println("==数组的元素/值的情况如下:===");
    		for( int i = 0; i < scores.length; i++) {
    			System.out.println("第"+ (i+1) +"个元素的值=" + scores[i]);
    		}
    	}
    }
    ```

- 数组使用注意事项和细节：

  1) 数组是多个相同类型数据的组合，实现对这些数据的统一管理
  2) 数组中的元素可以是任何数据类型，包括基本类型和引用类型，但是不能混用。
  3) 数组创建后，如果没有赋值，有默认值
     - int：0
     - short：0
     - byte：0
     - long：0
     - float：0.0
     - double：0.0
     - char：\u0000
     - boolean：false
     - String：null

  4) 使用数组的步骤
     1) 声明数组并开辟空间
     2) 给数组各个元素赋值
     3) 使用数组
  5) 数组的**下标是从** **0** **开始的**。
  6) 数组下标必须在指定范围内使用，否则报：下标越界异常，比如
     - `int [] arr=new int[5]; //有效下标为 0-4`

  7) 数组属引用类型，数组型数据是对象（object）

- 细节示例：

  - ```java
    public class ArrayDetail { 
    	public static void main(String[] args) {
    		//1. 数组是多个相同类型数据的组合，实现对这些数据的统一管理
    
    		//int[] arr1 = {1, 2, 3, 60,"hello"};//String ->int
    		double[] arr2 = {1.1, 2.2, 3.3, 60.6, 100};//int ->double
    
    		//2. 数组中的元素可以是任何数据类型，包括基本类型和引用类型，但是不能混用
    		String[] arr3 = {"北京","jack","milan"};
    
    		//3. 数组创建后，如果没有赋值，有默认值
    		//int 	0，short 0, byte 0, long 0, 
    		//float 0.0,double 0.0，char \u0000，
    		//boolean false，String null
    		
    		short[] arr4 = new short[3];
    		System.out.println("=====数组arr4=====");
    		for(int i = 0; i < arr4.length; i++) {
    			System.out.println(arr4[i]);
    		}
    
    		//6. 数组下标必须在指定范围内使用，否则报：下标越界异常，比如 
    		//int [] arr=new int[5]; 则有效下标为 0-4 
    		//即数组的下标/索引 最小 0 最大 数组长度-1(4)
    		int [] arr = new int[5];
    		//System.out.println(arr[5]);//数组越界
    
    	}
    }
    ```

- 数组应用：

  - ```java
    public class ArrayExercise01 { 
    	public static void main(String[] args) {
    		/*
    		创建一个char类型的26个元素的数组，分别 放置'A'-'Z'。使用for循环访问所有元素并打印出来。
    		提示：char类型数据运算 'A'+1 -> 'B'  
    
    		思路分析:
                1. 定义一个 数组  char[] chars = new char[26]
                2. 因为 'A' + 1 = 'B' 类推，所以老师使用for来赋值
                3. 使用for循环访问所有元素
    		 */
    		char[] chars = new char[26];
    		for( int i = 0; i < chars.length; i++) {//循环26次
    			//chars 是 char[] ,字符数组变量
    			//chars[i] 是 char,字符变量
    			chars[i] = (char)('A' + i); //'A' + i 是int , 需要强制转换
    		}
    
    		//循环输出
    		System.out.println("===chars数组===");
    		for( int i = 0; i < chars.length; i++) {//循环26次
    			System.out.print(chars[i] + " ");
    		}
    		
    	}
    }
    ```

  - ```java
    public class ArrayExercise02 { 
    	public static void main(String[] args) {
    		//请求出一个数组int[]的最大值 {4,-1,9, 10,23}，并得到对应的下标
    		/*
    		老韩思路分析
                1. 定义一个int数组 int[] arr = {4,-1,9, 10,23};
                2. 假定 max = arr[0] 是最大值 , maxIndex=0;
                3. 从下标 1 开始遍历arr， 如果max < 当前元素，说明max 不是真正的
                   最大值, 我们就 max=当前元素; maxIndex=当前元素下标
                4. 当我们遍历这个数组arr后 , max就是真正的最大值，maxIndex最大值对应的下标	*/
    		
    		int[] arr = {4,-1,9,10,23};
    		int max = arr[0];//假定第一个元素就是最大值
    		int maxIndex = 0; //
    
    		for(int i = 1; i < arr.length; i++) {//从下标 1 开始遍历arr
    			if(max < arr[i]) {//如果max < 当前元素
    				max = arr[i]; //把max 设置成 当前元素
    				maxIndex = i; 
    			}
    		} 
    		//当我们遍历这个数组arr后 , max就是真正的最大值，maxIndex最大值下标
    		System.out.println("max=" + max + " maxIndex=" + maxIndex);
    	}
    }
    ```

#### 3.数组赋值

- 数组赋值机制

  1) 基本数据类型赋值，这个值就是具体的数据，而且相互不影响
     - `int n1 = 2; int n2 = n1;`

  2) 数组在默认情况下是引用传递，赋的值是地址

- 示例：

  - ```java
    public class ArrayAssign { 
    	public static void main(String[] args) {
    		//基本数据类型赋值, 赋值方式为值拷贝
    		//n2的变化，不会影响到n1的值
    		int n1 = 10;
    		int n2 = n1;
    
    		n2 = 80;
    		System.out.println("n1=" + n1);	//10
    		System.out.println("n2=" + n2);	//80
    
    		//数组在默认情况下是引用传递，赋的值是地址，赋值方式为引用赋值
    		//是一个地址 , arr2变化会影响到 arr1
    		int[] arr1 = {1, 2, 3};
    		int[] arr2 = arr1;//把 arr1赋给 arr2
    		arr2[0] = 10;
    
    		//看看arr1的值
    		System.out.println("====arr1的元素====");
    		for(int i = 0; i < arr1.length; i++) {
    			System.out.println(arr1[i]);	//10, 2, 3
    		}
    
    		System.out.println("====arr2的元素====");
    		for(int i = 0; i < arr2.length; i++) {
    			System.out.println(arr2[i]);	3//10, 2, 3
    		}
    
    	}
    }
    ```

#### 4.数组拷贝

- 示例：

  - ```java
    public class ArrayCopy { 
    	public static void main(String[] args) {
    		//将 int[] arr1 = {10,20,30}; 拷贝到 arr2数组, 
    		//要求数据空间是独立的.
    		
    		int[] arr1 = {10,20,30};
    		
    		//创建一个新的数组arr2,开辟新的数据空间（关键）
    		//大小 arr1.length;
    		int[] arr2 = new int[arr1.length];	//关键
    
    		//遍历 arr1 ，把每个元素拷贝到arr2对应的元素位置
    		for(int i = 0; i < arr1.length; i++) {
    			arr2[i] = arr1[i];
    		}
    
    		//修改 arr2， 不会对arr1有影响.
    		arr2[0] = 100;
    
    		//输出arr1 
    		System.out.println("====arr1的元素====");
    		for(int i = 0; i < arr1.length; i++) {
    			System.out.println(arr1[i]);//10,20,30
    		}
    
    		System.out.println("====arr2的元素====");
    		for(int i = 0; i < arr2.length; i++) {
    			System.out.println(arr2[i]);//
    		}
    
    	}
    }
    ```

#### 5.数组反转

- 方法一示例：

  - ```java
    public class ArrayReverse { 
    	public static void main(String[] args) {
    		//定义数组
    		int[] arr = {11, 22, 33, 44, 55, 66};
    		/*老韩思路:
                1. 把 arr[0] 和 arr[5] 进行交换 {66,22,33,44,55,11}
                2. 把 arr[1] 和 arr[4] 进行交换 {66,55,33,44,22,11}
                3. 把 arr[2] 和 arr[3] 进行交换 {66,55,44,33,22,11}
                4. 一共要交换 3 次 = arr.length / 2
                5. 每次交换时，对应的下标 是 arr[i] 和 arr[arr.length - 1 -i]	*/
    
    		int temp = 0;
    		int len = arr.length; //计算数组的长度
    		for( int i = 0; i < len / 2; i++) {
    			temp = arr[len - 1 - i];//保存
    			arr[len - 1 - i] = arr[i];
    			arr[i] = temp; 
    		}
    
    		System.out.println("===翻转后数组===");
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");//66,55,44,33,22,11
    		}
    	}
    }
    ```

- 方法2示例：

  - ```java
    public class ArrayReverse02 { 
    	public static void main(String[] args) {
    		//定义数组
    		int[] arr = {11, 22, 33, 44, 55, 66};
    		/*使用逆序赋值方式 
                1. 先创建一个新的数组 arr2 ,大小 arr.length
                2. 逆序遍历 arr ,将 每个元素拷贝到 arr2的元素中(顺序拷贝)
                3. 建议增加一个循环变量 j -> 0 -> 5	*/
    		int[] arr2 = new int[arr.length];
    		//逆序遍历 arr
    		for(int i = arr.length - 1, j = 0; i >= 0; i--, j++) {
    			arr2[j] = arr[i];
    		}
    		//4. 当for循环结束，arr2就是一个逆序的数组 {66, 55, 44,33, 22, 11} 
    		//5. 让 arr 指向 arr2数据空间, 此时 arr原来的数据空间就没有变量引用,会被当做垃圾，自动销毁（！！！）
    		arr = arr2;
    		System.out.println("====arr的元素情况=====");
    		//6. 输出 arr 看看
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    	}
    }
    ```

  - 注意：Java 中手动创建的空间不需要手动释放，JVM 会自动回收

#### 6.数组扩容

- 要求：实现动态的给数组添加元素效果，实现对数组扩容

  1) 原始数组使用静态分配 `int[] arr = {1,2,3};`
  2) 增加的元素 4，直接放在数组的最后 `arr = {1,2,3,4};`
  3) 用户可以通过如下方法来决定是否继续添加：`添加成功，是否继续？y/n`

- 部分示例：

  - ```java
    public class ArrayAdd { 
    	public static void main(String[] args) {
    		/*
    		要求：实现动态的给数组添加元素效果，实现对数组扩容。ArrayAdd.java
                1.原始数组使用静态分配 int[] arr = {1,2,3}
                2.增加的元素4，直接放在数组的最后 arr = {1,2,3,4}
                3.用户可以通过如下方法来决定是否继续添加，添加成功，是否继续？y/n
    		
    		思路分析:
                1. 定义初始数组 int[] arr = {1,2,3}//下标0-2
                2. 定义一个新的数组 int[] arrNew = new int[arr.length+1];
                3. 遍历 arr 数组，依次将arr的元素拷贝到 arrNew数组
                4. 将 4 赋给 arrNew[arrNew.length - 1] = 4;把4赋给arrNew最后一个元素
                5. 让 arr 指向 arrNew ;  arr = arrNew; 那么 原来arr数组就被销毁
    		 */
    		int[] arr = {1,2,3};
    		int[] arrNew = new int[arr.length + 1];
    		//遍历 arr 数组，依次将 arr 的元素拷贝到 arrNew 数组
    		for(int i = 0; i < arr.length; i++) {
    			arrNew[i] = arr[i];
    		}
    		//把 4 赋给arrNew最后一个元素
    		arrNew[arrNew.length - 1] = 4;
    		//让 arr 指向 arrNew, 
    		arr = arrNew;
    		System.out.println("====arr扩容后元素情况====");
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    	}
    }
    ```

- 补充：

  - ```java
    import java.util.Scanner;
    public class ArrayAdd02 { 
    	public static void main(String[] args) {
    		/*
    		要求：实现动态的给数组添加元素效果，实现对数组扩容。ArrayAdd.java
                1.原始数组使用静态分配 int[] arr = {1,2,3}
                2.增加的元素4，直接放在数组的最后 arr = {1,2,3,4}
                3.用户可以通过如下方法来决定是否继续添加，添加成功，是否继续？y/n
    		
    		思路分析
                1. 定义初始数组 int[] arr = {1,2,3}//下标0-2
                2. 定义一个新的数组 int[] arrNew = new int[arr.length+1];
                3. 遍历 arr 数组，依次将arr的元素拷贝到 arrNew数组
                4. 将 4 赋给 arrNew[arrNew.length - 1] = 4;把4赋给arrNew最后一个元素
                5. 让 arr 指向 arrNew ;  arr = arrNew; 那么 原来arr数组就被销毁
                6. 创建一个 Scanner可以接受用户输入
                7. 因为用户什么时候退出，不确定，老师使用 do-while + break来控制
    		 */
    		
    		Scanner myScanner = new Scanner(System.in);
    		//初始化数组
    		int[] arr = {1,2,3};
    
    		do {	//第一遍要执行
    			int[] arrNew = new int[arr.length + 1];
    			//遍历 arr 数组，依次将arr的元素拷贝到 arrNew数组
    			for(int i = 0; i < arr.length; i++) {
    				arrNew[i] = arr[i];
    			}
    			System.out.println("请输入你要添加的元素");
    			int addNum = myScanner.nextInt();
    			//把addNum赋给arrNew最后一个元素
    			arrNew[arrNew.length - 1] = addNum;
    			//让 arr 指向 arrNew, 
    			arr = arrNew;
    			//输出arr 看看效果
    			System.out.println("====arr扩容后元素情况====");
    			for(int i = 0; i < arr.length; i++) {
    				System.out.print(arr[i] + "\t");
    			}
    			//问用户是否继续
    			System.out.println("是否继续添加 y/n");
    			char key = myScanner.next().charAt(0);
    			if( key == 'n') { //如果输入n ,就结束
    				break;
    			}			
    		}while(true);
    
    		System.out.println("你退出了添加...");
    	}
    }
    
    ```

#### 7.排序

- 一种分类：

  - 内部排序:
    - 指将需要处理的所有数据都加载到内部存储器中进行排序。包括(交换式排序法、选择式排序法和插入式排序法)
  - 外部排序法：
    - 数据量过大，无法全部加载到内存中，需要借助外部存储进行排序。包括(合并排序法和直接合并排序法)

- 冒泡排序（Bubble Sorting）的基本思想是：通过对待排序序列从前往后，依次比较相邻元素的值，若发现逆序则交换，使值较大的元素逐渐从前移向后部，就象水底下的气泡一样逐渐向上冒

- 冒泡排序的特点：

  1. n 个元素需要 n-1 趟排序（外层循环）
  2. 每一轮排序可以确定一个最大值的位置，下一轮确定次大的数的位置
  3. 每轮比较的次数减一

- 冒泡排序代码实现：

  - ```java
    public class BubbleSort { 
    	public static void main(String[] args) {
    		/*
    			数组 [24,69,80,57,13]
    			第1轮排序: 目标把最大数放在最后
                    第1次比较[24,69,80,57,13]
                    第2次比较[24,69,80,57,13]
                    第3次比较[24,69,57,80,13]
                    第4次比较[24,69,57,13,80]
    		 */
    		int[] arr = {24, 69, 80, 57, 13, -1, 30, 200, -110};
    		int temp = 0; //用于辅助交换的变量
    
    		//将多轮排序使用外层循环包括起来即可
    		//arr.length - 1 轮外层循环
    		for( int i = 0; i < arr.length - 1; i++) {	//外层循环
    			for( int j = 0; j < arr.length - 1 - i; j++) {	//比较次数第一轮为 n-1，并每轮减一
    				//如果前面的数>后面的数，就交换
    				if(arr[j] > arr[j + 1]) {
    					temp = arr[j];
    					arr[j] = arr[j+1];
    					arr[j+1] = temp;  
    				}
    			}
    			System.out.println("\n==第" + (i+1) + "轮排序后==");
    			for(int j = 0; j < arr.length; j++) {
    				System.out.print(arr[j] + "\t");
    			}
    
    		}
    	}
    }
    ```

#### 8.查找

- 介绍：在 java 中，我们常用的查找有两种:

  1) 顺序查找
  2) 二分查找

- 顺序查找示例：

  - ```java
    import java.util.Scanner;
    public class SeqSearch { 
    	public static void main(String[] args) {
    		/*
    		有一个数列：白眉鹰王、金毛狮王、紫衫龙王、青翼蝠王猜数游戏：
    		从键盘中任意输入一个名称，判断数列中是否包含此名称【顺序查找】 
    		要求: 如果找到了，就提示找到，并给出下标值
    
    		思路分析
                1. 定义一个字符串数组
                2. 接收用户输入, 遍历数组，逐一比较，如果有，则提示信息，并退出
    		 */
    		
    		//定义一个字符串数组
    		String[] names = {"白眉鹰王", "金毛狮王", "紫衫龙王", "青翼蝠王"};
    		Scanner myScanner = new Scanner(System.in); 
    
    		System.out.println("请输入名字");
    		String findName = myScanner.next();
    
    		//遍历数组，逐一比较，如果有，则提示信息，并退出
    		int index = -1;
    		for(int i = 0; i < names.length; i++) {
    			//比较 字符串比较 equals, 如果要找到名字就是当前元素
    			if(findName.equals(names[i])) {
    				System.out.println("恭喜你找到 " + findName);
    				System.out.println("下标为= " + i);
    				//把i 保存到 index
    				index = i;
    				break;//退出 
    			} 
    		}
    
    		if(index == -1) { //没有找到
    			System.out.println("sorry ,没有找到 " + findName);
    		}
    
    	}
    }
    ```

#### 9.多维数组 - 二维数组

- 入门示例：

  - ```java
    public class TwoDimensionalArray01 { 
    	public static void main(String[] args) {
    		/*
    		请用二维数组输出如下图形
    			0 0 0 0 0 0
    			0 0 1 0 0 0	
    			0 2 0 3 0 0
    			0 0 0 0 0 0
    		 */
    		
    		//什么是二维数组： 
    		/*解读
    			1. 从定义形式上看 int[][]
    			2. 可以这样理解，原来的一维数组的每个元素是一维数组, 就构成二维数组	*/
    		int[][] arr = { {0, 0, 0, 0, 0, 0},
    						{0, 0, 1, 0, 0, 0}, 
    						{0,2,  0, 3, 0, 0}, 
    						{0, 0, 0, 0, 0, 0} };
    
    		//关于二维数组的关键概念
    		//(1)
    		System.out.println("二维数组的元素个数=" + arr.length);
    		//(2) 二维数组的每个元素是一维数组, 所以如果需要得到每个一维数组的值
    		//    还需要再次遍历
    		//(3) 如果我们要访问第 (i+1) 个一维数组的第 j+1 个值 arr[i][j];
    		//    举例:访问第3个一维数组的第4个值, arr[2][3]
    		System.out.println("第3个一维数组的第4个值=" + arr[2][3]); //3
    
    		//输出二维图形
    		for(int i = 0; i < arr.length; i++) {//遍历二维数组的每个元素
    			//遍历二维数组的每个元素(数组)
    			//解读
    				//1. arr[i] 表示 二维数组的第i+1个元素 比如arr[0]：二维数组的第一个元素
    				//2. arr[i].length 得到 对应的 每个一维数组的长度 
    			for(int j = 0; j < arr[i].length; j++) {
    				System.out.print(arr[i][j] + " "); //输出了一维数组
    			}
    			System.out.println();//换行
    		}
    	}
    }
    ```

- 使用方式1：动态初始化

  - 语法: `类型[][] 数组名=new 类型[大小][大小]`
    - 比如：`int a[][]=new int[2][3]`

- 使用方式 2：动态初始化

  - 先声明：`类型 数组名[][]; `
  - 再定义(开辟空间)：`数组名 = new 类型[大小][大小]`
  - 赋值（有默认值，比如 int 类型的就是 0）

- 示例：

  - ```java
    public class TwoDimensionalArray02 { 
    	public static void main(String[] args) {
    		
            //int arr[][] = new int[2][3];
    		
    		int arr[][]; //声明二维数组
    		arr = new int[2][3];//再开空间 
    		
    		arr[1][1] = 8;
    		//遍历arr数组
    		for(int i = 0; i < arr.length; i++) {
    			for(int j = 0; j < arr[i].length; j++) {	//对每个一维数组遍历
    				System.out.print(arr[i][j] +" ");
    			}
    			System.out.println();//换行
    		}
    	}
    }
    ```

- 使用方式3：列数不确定

  - 示例：

    - ```java
      public class TwoDimensionalArray03 { 
      	public static void main(String[] args) {
      
      		/*
      		看一个需求：动态创建下面二维数组，并输出
      		
      		 i = 0:	1		
      		 i = 1:	2	2	
      		 i = 2:	3	3	3
      
      		 有三个一维数组, 每个一维数组的元素是不一样的
      		 */
      		
      		//创建 二维数组，有3个一维数组，但是每个一维数组还没有开数据空间
      		int[][] arr = new int[3][]; 
      		
      		for(int i = 0; i < arr.length; i++) {//遍历arr每个一维数组
      			//给每个一维数组开空间 new
      			//如果没有给一维数组 new ,那么 arr[i]就是null
      			arr[i] = new int[i + 1]; 
      
      			//遍历一维数组，并给一维数组的每个元素赋值
      			for(int j = 0;  j < arr[i].length; j++) {
      				arr[i][j] = i + 1;//赋值
      			}
      		}
      
      		System.out.println("=====arr元素=====");
      		//遍历arr输出
      		for(int i = 0; i < arr.length; i++) {
      			//输出arr的每个一维数组
      			for(int j = 0; j < arr[i].length; j++) {
      				System.out.print(arr[i][j] + " ");
      			}
      			System.out.println();//换行
      		}
      	}
      }
      ```

- 使用方式 4: 静态初始化

  - 定义：`类型 数组名[][] = {{值 1,值 2..},{值 1,值 2..},{值 1,值 2..}}`

  - 使用即可 [ 固定方式访问 ]

    - 比如：`int[][] arr = {{1,1,1}, {8,8,9}, {100}};`
      - 解读
        1. 定义了一个二维数组 arr
        2. arr 有三个元素（每个元素都是一维数组）
        3. 第一个一维数组有 3 个元素 , 第二个一维数组有 3 个元素, 第三个一维数组有 1 个元素

  - 案例：

    - ```java
      public class TwoDimensionalArray04 { 
      	public static void main(String[] args) {
      		int[][] arr = {{1,1,1}, {8,8,9}, {100}};
      	}
      }
      ```

- 二维数组练习：

  - ```java
    public class TwoDimensionalArray05 { 
    	public static void main(String[] args) {
    		/*
    		int arr[][]={{4,6},{1,4,5,7},{-2}}; 遍历该二维数组，并得到和 
    		
    		思路
    			1. 遍历二维数组，并将各个值累计到 int sum
    		 */
    		int arr[][]= {{4,6},{1,4,5,7},{-2}};
    		int sum = 0;
    		for(int i = 0; i < arr.length; i++) {
    			//遍历每个一维数组
    			for(int j = 0; j < arr[i].length; j++) {
    				sum += arr[i][j];
    			}
    		}
    		System.out.println("sum=" + sum);
    	}
    }
    ```

- 二维数组应用案例：杨辉三角

  - ```java
    public class YangHui { 
    	public static void main(String[] args) {
    		/*
    		使用二维数组打印一个 10 行杨辉三角
    		1
    		1 1
    		1 2 1
    		1 3 3  1
    		1 4 6  4  1
    		1 5 10 10 5 1
    
    		规律
                 1.第一行有 1 个元素, 第 n 行有 n 个元素
                 2. 每一行的第一个元素和最后一个元素都是 1
                 3. 从第三行开始, 对于非第一个元素和最后一个元素的元素的值. arr[i][j] 
                  arr[i][j]  =  arr[i-1][j] + arr[i-1][j-1]; //必须找到这个规律
    
    		 */
    		int[][] yangHui = new int[12][];	//12行的杨辉三角
    		for(int i = 0; i < yangHui.length; i++) {//遍历yangHui的每个元素
    			//给每个一维数组(行) 开空间
    			yangHui[i] = new int[i+1];	//第一行有 1 个元素, 第 n 行有 n 个元素
    			//给每个一维数组(行) 赋值
    			for(int j = 0; j < yangHui[i].length; j++){
    				//每一行的第一个元素和最后一个元素都是1
    				if(j == 0 || j == yangHui[i].length - 1) {
    					yangHui[i][j] = 1;
    				} else {//中间的元素
    					yangHui[i][j]  =  yangHui[i-1][j] + yangHui[i-1][j-1];
    				}
    			}
    		}
    		//输出杨辉三角
    		for(int i = 0; i < yangHui.length; i++) {
    			for(int j = 0; j < yangHui[i].length; j++) {//遍历输出该行
    				System.out.print(yangHui[i][j] + "\t");
    			}
    			System.out.println();//换行.
    		}
    		
    	}
    }
    ```

- 二维数组使用细节和注意事项

  1) 一维数组的声明方式有：
     - `int[] x 或者 int x[]`

  2) 二维数组的声明方式有：
     - `int[][] y 或者 int[] y[] 或者 int y[][]`

  3) 二维数组实际上是由多个一维数组组成的，它的各个一维数组的长度可以相同，也可以不相同。比如： map[][] 是一个二维数组
     - `int map [][] = {{1,2},{3,4,5}}`
     -  map由 `map[0]` （是一个含有两个元素的一维数） 、`map[1] `（是一个含有三个元素的一维数组）构成，我们也称为列数不等的二维数组

#### 10.作业练习

- 练习1：

  - ```java
    public class Homework01 { 
    	public static void main(String[] args) {
    		/*
    		已知有个升序的数组，要求插入一个元素，该数组顺序依然是升序, 比如:  
    		[10， 12， 45， 90],  添加23 后, 数组为 [10， 12，23， 45， 90]
    
    		思路: 本质数组扩容 + 定位
    			1. 我们先确定 添加数应该插入到哪个索引
    			2. 然后扩容
    		 */
    		
    		//先定义原数组
    		int[] arr = {10, 12, 45, 90};
    		int insertNum = 111;
    		int index = -1; //index就是要插入的位置
    
    		//遍历 arr数组， 如果发现 insertNum <= arr[i], 说明 i 就是要插入的位置
    		//使用 index 保留 index = i;
    		//如果遍历完后，没有发现 insertNum<=arr[i]， 说明 index = arr.length
    		//即：添加到arr的最后
    		
    		for(int i = 0; i < arr.length; i++) {
    			if(insertNum <= arr[i]) {
    				index = i;
    				break; //找到位置后，就退出
    			}
    		}
    
    		//判断index 的值
    		if(index == -1) { //说明没有还没有找到位置
    			index = arr.length;
    		}
    
    		//扩容
    		//先创建一个新的数组，大小 arr.length + 1
    		int[] arrNew = new int[arr.length + 1];
    		//下面将arr的元素拷贝到 arrNew ,并且要跳过 index位置
    		/*
    		分析:
    		int[] arr = {10, 12, 45, 90};
    		arrNew = {              }
    		*/
    		//i 控制arrNew的下标  , j用来控制arr数组的下标
    		for(int i = 0, j = 0; i < arrNew.length; i++) {
    			if( i != index ) { //说明可以把 arr的元素拷贝到 arrNew
    				arrNew[i] = arr[j];
    				j++;
    			} else { //i这个位置就是要插入的数
    				arrNew[i] = insertNum;
    			}
    		}
    
    		//让arr 指向 arrNew , 原来的数组，就成为垃圾，被自动销毁
    		arr = arrNew;
    
    		System.out.println("======插入后，arr数组的元素情况======");
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    	}
    }
    ```

- 练习2：

  - ```java
    public class Homework02 { 
    	public static void main(String[] args) {	
    		/*
    		题目：
    			随机生成10个整数(1_100的范围)保存到数组，并倒序打印以及求平均值、求最大值和最大值的下标、
    			并查找里面是否有8
    		 */
    		
    		int[] arr = new int[10]; 
    		
            //Math.random()	生成的是0.0~1.0之间的随机小数
            //(int)(Math.random() * 100) + 1 生产 随机数 1-100	
    		for(int i = 0; i < arr.length; i++) {
    			arr[i] = (int)(Math.random() * 100) + 1;
    		}
    
    		System.out.println("====arr的元素情况=====");
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    
    		System.out.println("\n====arr的元素情况(倒序)=====");
    		for(int i = arr.length -1; i >= 0; i--) {
    			System.out.print(arr[i] + "\t");
    		}
    
    		//平均值、求最大值和最大值的下标
    		//我们这里将需要一起完成
    		//
    		double sum = arr[0];
    		int max = arr[0];
    		int maxIndex = 0;
    		for(int i = 1; i < arr.length; i++ ) {
    			sum += arr[i]; //累积和
    			if( max < arr[i]) {//说明max不是最大值，就变化
    				max = arr[i];
    				maxIndex = i;
    			}
    		}
    
    		System.out.println("\nmax=" + max + " maxIndex=" + maxIndex);
    		System.out.println("\n平均值=" + (sum / arr.length));
    
    		//查找数组中是否有8->使用顺序查找
    		int findNum = 8;
    		int index = -1; //如果找到，就把下标记录到 index
    		for(int i = 0; i < arr.length; i++) {
    			if(findNum == arr[i]) {
    				System.out.println("找到数" + findNum + " 下标为：" + i);
    				index = i;
    				break;
    			}
    		}
    
    		if(index == -1) {
    			System.out.println("没有找到数" + findNum );
    		}
    	}
    }
    ```

- 练习3：

  - ```java
    public class Homework03 { 
    	public static void main(String[] args) {
    		//冒泡排序
    		//要求从小到大
            
    		int[] arr = {20, -1, 89, 2, 890, 7};
    		int temp = 0; 	//用于辅助交换
    		for(int i = 0; i < arr.length -1 ; i++) {	//外层循环(轮)
    			for(int j = 0; j < arr.length - 1 - i; j++) {	//每轮的比较次数
    				//如果是从小到大，条件是 arr[j] > arr[j+1]
    				//如果是从大到小，条件是 arr[j] < arr[j+1]
    				if(arr[j] > arr[j+1]) {
    					temp = arr[j];
    					arr[j] = arr[j+1];
    					arr[j+1] = temp;
    				}
    			}
    		}
    
    		System.out.println("\n==== 排序后====");
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    	}
    }
    ```

### （六）面向对象编程基础

#### 1.类与对象

##### 问题引入：

- 张老太养了两只猫猫:一只名字叫小白、今年 3 岁、白色。还有一只叫小花、今年 100 岁、花色。请编写一个程序，当用户输入小猫的名字时，就显示该猫的名字、年龄、颜色。如果用户输入的小猫名错误，则显示 张老太没有这只猫猫

- Java 的面向对象思想与 C++面向对象思想类似或一致

  - C++认为万事万物都皆为对象，对象上有其属性和行为
    - 人可以作为对象
      - 属性：姓名、年龄、身高、体重...
      - 行为：走、跑、跳、吃饭、唱歌
    - 车可以作为对象
      - 属性：轮胎、方向盘、车灯...
      - 行为：载人、放音乐、用空调
  - 具有相同性质的对象，我们可以将其抽象为类，人属于人类、车属于车类

- 入门示例：

  - ```java
    public class Object01 { 
    	public static void main(String[] args) {
    
    		/*
    		问题描述：
                张老太养了两只猫猫:一只名字叫小白,今年3岁,白色。 
                还有一只叫小花,今年100岁,花色。请编写一个程序，当用户输入小猫的名字时，
                就显示该猫的名字，年龄，颜色。如果用户输入的小猫名错误，
                则显示 张老太没有这只猫猫。	 */
            
            //单独变量来解决 => 不利于数据的管理(你把一只猫的信息拆解)
            /*		
    		//第1只猫信息	
    		// String cat1Name = "小白";
    		// int cat1Age = 3;
    		// String cat1Color = "白色";
    
    		//第2只猫信息
    		// String cat2Name = "小花";
    		// int cat2Age = 100;
    		// String cat2Color = "花色";
    
    		//数组：
    			(1)数据类型体现不出来
    			(2) 只能通过[下标]获取信息，造成变量名字和内容的对应关系不明确
    			(3) 不能体现猫的行为
    		
    		// String[] cat1 = {"小白", "3", "白色"}; 
    		// String[] cat2 = {"小花", "100", "花色"};		*/
    
    		//使用OOP面向对象解决
    		//实例化一只猫[创建一只猫对象]
    		/*解读
                1. new Cat() 创建一只猫(猫对象)	
                2. Cat cat1 = new Cat(); 把创建的猫赋给 cat1 
                3. cat1 就是一个对象		*/
    		Cat cat1 = new Cat();	//注意：这里就已经与C++不同了，Java里没有指针，new 也不返回对象指针
    		cat1.name = "小白";
    		cat1.age = 3;
    		cat1.color = "白色";
    		//cat1.weight = 10;
            
    		//创建了第二只猫，并赋给 cat2
    		//cat2 也是一个对象(猫对象)
    		Cat cat2 = new Cat();
    		cat2.name = "小花";
    		cat2.age = 100;
    		cat2.color = "花色";
    		//cat2.weight = 20;
    
    		//怎么访问对象的属性呢
    		System.out.println("第1只猫信息：" + cat1.name + " " + cat1.age + " " + cat1.color);
    		System.out.println("第2只猫信息：" + cat2.name + " " + cat2.age + " " + cat2.color);
    	}
    }
    
    //使用面向对象的方式来解决养猫问题
    //定义一个猫类 Cat -> 自定义的数据类型
    class Cat {
    //属性/成员变量：
    	String name; //名字
    	int age; //年龄
    	String color; //颜色
    	//double weight; //体重
        //...
    
    //行为
    	//..
    }
    ```

##### 类和对象的区别和联系：

1) 类是抽象的，概念的，代表一类事物。比如人类、猫类...，即它是数据类型. 
2) 对象是具体的，实际的，代表一个具体事物，即是实例.
3) 类是对象的模板，对象是类的一个个体，对应一个实例

##### 补充（重要）（内存管理机制）：Java的内存分区与C++的内存分区的比较

- C++的内存分为以下几个区域：
  1. 栈区：用于存储局部变量、函数参数、返回地址等信息。栈区的内存由编译器自动分配和释放，不需要手动管理
  2. 堆区：用于动态分配内存，由程序员手动分配和释放。堆区的内存需要手动管理，避免内存泄漏和野指针等问题
  3. 全局/静态区：用于存储全局变量、静态变量和常量等信息。全局/静态区的内存在程序开始时分配，在程序结束时释放
  4. 常量区：用于存储程序中的字符串常量等信息。常量区的内存在程序开始时分配，在程序结束时释放
  5. 代码区：用于存储程序的可执行代码。代码区的内存在程序开始时分配，在程序结束时释放
- Java的内存分为以下几个区域：
  1. 程序计数器：用于指示当前线程执行的字节码的行号，它是线程私有的，线程之间互不影响
  2. Java虚拟机栈：用于存储局部变量、方法参数、返回值以及操作数栈等信息。每个线程都有自己的Java虚拟机栈，栈中的数据随着方法的调用和返回而压入和弹出
  3. 本地方法栈：与Java虚拟机栈的作用类似，但它为本地方法服务
  4. Java堆：是Java虚拟机所管理的内存中最大的一块。Java堆是被所有线程共享的，用于存储对象实例和数组等信息。Java堆的内存不足时，会触发垃圾回收
  5. 方法区：用于存储已被加载的类的信息、常量池、静态变量、即时编译器编译后的代码等数据。方法区也是被所有线程共享的。方法区的内存不足时，同样会触发垃圾回收
- Java和C++的内存分区有相同之处，也有不同之处
  - 相同之处：
    1. 都有栈区和堆区：Java和C++都将内存分为栈区和堆区，用于存储变量、对象等信息
    2. 都有全局区/静态区：Java和C++都有全局区/静态区，用于存储全局变量和静态变量等信息
    3. 都有常量区：Java和C++都有常量区，用于存储字符串常量等信息
  - 不同之处：
    1. Java有程序计数器和方法区，而C++没有
    2. Java中的堆区由Java虚拟机管理，内存回收机制由Java虚拟机自动处理；而C++中的堆区由程序员手动管理，需要手动分配和释放内存
    3. Java中的内存管理机制较为安全，可以避免内存泄漏和野指针等问题；而C++中的内存管理需要程序员自己负责，容易出现内存泄漏和野指针等问题
    4. Java中的常量区和字符串常量池是分离的，而C++中的常量区和字符串常量区是合并在一起的
- 虽然Java和C++都将内存分为栈区、堆区、全局区/静态区和常量区等，但是它们的具体实现和内存管理机制有很大的不同

##### 属性 / 成员变量 / 字段

- 基本介绍：

  1. 从概念或叫法上看： 成员变量 = 属性 = field（字段） （即 成员变量是用来表示属性的）

     - 示例：

       - ```java
         public class Object02 { 
         	public static void main(String[] args) {
         	}
         }
         
         class Car {
         	String name;	//属性, 成员变量, 字段 field
         	double price;
         	String color;
         	String[] master;	//属性可以是基本数据类型，也可以是引用类型(对象，数组)
         }
         ```

  2. 属性是类的一个组成部分，一般是基本数据类型，也可是引用类型（对象，数组）比如我们前面定义猫类 的 int age 就是属性

- 注意事项和细节说明：

  1. 属性的定义语法同变量，示例：`访问修饰符 属性类型 属性名;`
     - 访问修饰符： 控制属性的访问范围
     - 有四种访问修饰符 `public    proctected    默认   private `

  2) 属性的定义类型可以为任意类型，包含基本类型或引用类型
  3) 属性如果不赋值，有默认值，规则和数组一致

- 细节示例：

  - ```java
    public class PropertiesDetail {
    	public static void main(String[] args) {
            //创建 Person 对象
            //p1 是对象名(对象引用)
            //new Person() 创建的对象空间(数据) 才是真正的对象
    		Person p1 = new Person();
            
    		//对象的属性默认值，遵守数组规则:
    		//int 0, short 0, byte 0, long 0, float 0.0, double 0.0, char \u0000, boolean false, String null
    		System.out.println("\n 当前这个人的信息");
    		System.out.println("age=" + p1.age + " name=" + p1.name 
                               + " sal=" + p1.sal + " isPass=" + p1.isPass);	//全部为默认信息
    	}
    }
    
    class Person {
        //四个属性
        int age;	//年龄
        String name;	//姓名
        double sal;	//薪水
        boolean isPass;	//是否通过
    }
    ```

##### 创建对象

1. 先声明再创建
   - `Cat cat ; //声明对象cat	在栈区开辟一个cat，cat此时为空`
   - `cat = new Cat(); //创建  在堆区开辟一个空间，将空间的地址返回到cat`
2. 直接创建
   - `Cat cat = new Cat();`

- 这里要注意与 C++ 的区别：
  - C++ C++ 中 new 操作符在堆区开辟空间，利用 new 创建的数据，会返回该数据对应的类型的指针
  - 而 Java 没有指针（这里后面还有多注意与 C++ 的区别）

##### 如何访问属性

- 基本语法：

  - `对象名.属性名;`

##### 类和对象的内存分配机制

- 类和对象的内存分配机制，示例：

  - ```java
    public class Object03 { 
    	public static void main(String[] args) {
    		Person p1 = new Person();
    		p1.age=10;
    		p1.name="小明";
    		Person p2 = p1; //把p1赋给了p2 ,或称 让p2指向p1 //指向的为同一块内存空间，没有创建新对象
             //注意：这里p2指向堆区，改变p2的指向不会影响p1的指向
             //可能类似 C++ 中的引用，但C++中的引用是指针常量，不允许改变指向，而Java这里可以改变指向
            
            //p1.age = 20;
    		System.out.println(p2.age); // 10
    	}
    }
    
    class Person {
    	String name;
    	int age; 
    }
    ```

- Java 内存的结构分析：

  1) 栈： 一般存放基本数据类型（局部变量）
  2) 堆： 存放对象（Cat cat，数组等）
  3) 方法区：常量池（常量，比如字符串）， 类加载信息

- Java 创建对象的流程简单分析：

  - ```java
    Person p = new Person();
    p.name = “jack”;
    p.age = 10;
    ```

    1) 先加载 Person 类信息（属性和方法信息，只会加载一次），加载 `Person.class` 文件进内存。
    2) 在栈内存为 p 开辟空间
    3) new 会在堆中为 Person对象 分配空间，进行默认初始化（int 0、String null 、...）
    4) 把创建在堆区中的地址赋给 p，p 就指向 new 出来的对象
    5) 进行指定初始化， 比如： `p.name ="jack"   p.age = 10 `

#### 2.成员方法

- 基本介绍：

  - 在某些情况下，我们要需要定义成员方法（简称方法）。比如人类：除了有一些属性外（年龄，姓名...），我们人类还有一些行为。比如：可以说话、跑步...，通过学习，还可以做算术题等

- 快速入门示例：

  - ```java
    public class Method01 { 
    	public static void main(String[] args) {
    		/*方法使用:
                1. 方法写好后，如果不去调用(使用)，则不会输出
                2. 先创建对象 ,然后调用方法即可	*/
    		Person p1 = new Person();
    		p1.speak(); //调用方法speak
    		p1.cal01(); //调用cal01方法
    		p1.cal02(5); //调用cal02方法，同时给n = 5
    		p1.cal02(10); //调用cal02方法，同时给n = 10
    		
    		//调用getSum方法，同时num1=10, num2=20
    		//把方法 getSum 返回的值，赋给 变量 returnRes
    		int returnRes = p1.getSum(10, 20); 
    		System.out.println("getSum方法返回的值=" + returnRes);
    	}
    }
    
    class Person {
    	String name;
    	int age;
        
    	//方法(成员方法)
    	//方法1：添加speak 成员方法：输出 “我是一个好人”
    	/*解读：
            1. public 表示方法是公开
            2. void ： 表示方法没有返回值
            3. speak() : speak是方法名， () 形参列表
            4. {} 方法体，可以写我们要执行的代码
            5. System.out.println("我是一个好人"); 表示我们的方法就是输出一句话	*/	
    	public void speak() {
    		System.out.println("我是一个好人");
    	}
    
    	//方法2：添加cal01 成员方法：可以计算从 1+..+1000的结果
    	public void cal01() {
    		int res = 0;
    		for(int i = 1; i <= 1000; i++) {
    			res += i;
    		}
    		System.out.println("cal01方法 计算结果=" + res);
    	}
        
    	//方法3：添加cal02 成员方法：该方法可以接收一个数n，计算从 1+..+n 的结果
    	//解读：1. (int n) 形参列表， 表示当前有一个形参 n, 可以接收用户输入
    	public void cal02(int n) {
    		//循环完成
    		int res = 0;
    		for(int i = 1; i <= n; i++) {
    			res += i;
    		}
    		System.out.println("cal02方法 计算结果=" + res);
    	}
    
    	//方法4：添加getSum成员方法,可以计算两个数的和
    	/*解读：
            1. public 表示方法是公开的
            2. int :表示方法执行后，返回一个 int 值
            3. getSum 方法名
            4. (int num1, int num2) 形参列表，2个形参，可以接收用户传入的两个数
            5. return res; 表示把 res 的值， 返回		*/
    	public int getSum(int num1, int num2) {
    		int res = num1 + num2;
    		return res;
    	}
    }
    ```

##### 方法调用机制

1. 当程序执行到方法时，就会开辟一个独立的空间（栈空间）
2. 当方法执行完毕，或者执行到 return 语句时，就会返回
3. 返回到调用方法的地方
4. 返回后，继续执行方面后面的代码
5. 当 main 主方法执行完毕，整个程序退出

##### 为什么要用成员方法

- 需求：

  - 请遍历一个数组 , 输出数组的各个元素值

- 思路：

  - 方法1：传统的方法，就是使用单个 for 循环，将数组输出
  - 方法2：定义一个类 MyTools，然后写一个成员方法，调用方法实现

- 示例：

  - ```java
    public class Method02 { 
    	public static void main(String[] args) {
    		//请遍历一个数组 , 输出数组的各个元素值
    		int [][] map =  {{0,0,1},{1,1,1},{1,1,3}};
    
             //方法1：传统的解决方式就是直接遍历
    		/*
    		for(int i = 0; i < map.length; i++) {
    		 	for(int j = 0; j < map[i].length; j++) {
    		 		System.out.print(map[i][j] + "\t");
    		 	}
    		 	System.out.println();
    		}		
    		
    		//若要求再次遍历map数组
    		for(int i = 0; i < map.length; i++) {
    		 	for(int j = 0; j < map[i].length; j++) {
    		 		System.out.print(map[i][j] + "\t");
    		 	}
    		 	System.out.println();
    		}		
    		*/    
             
    		//方法2：使用方法完成输出, 创建MyTools对象 
    		MyTools tool = new MyTools();
    		//使用方法
    		tool.printArr(map);
            
    		//若要求再次遍历map数组
    		tool.printArr(map);
        }
    }
    
    //把输出的功能，写到一个类的方法中,然后调用该方法即可
    class MyTools {
    	
        //方法，接收一个二维数组
    	public void printArr(int[][] map) {
    		System.out.println("=======");	//添加需求时也很方便，只需要修改一次成员方法，而不是所有的普通遍历
    		//对传入的map数组进行遍历输出
    		for(int i = 0; i < map.length; i++) {
    			for(int j = 0; j < map[i].length; j++) {
    				System.out.print(map[i][j] + "_");
    			}
    			System.out.println();
    		}
    	}
    }
    ```

- 总结：成员方法的好处：

  1) 提高代码的复用性
  2) 可以将实现的细节封装起来，然后供其他用户来调用即可

##### 成员方法的定义

- 语法：

  - ```java
    访问修饰符 返回数据类型 方法名(形参列表...) {
        //方法体语句；
    	return 返回值;
    }
    ```

    1. 形参列表：表示成员方法输入

    2) 返回数据类型：表示成员方法输出，void 表示没有返回值
    3) 方法主体：表示为了实现某一功能代码块
    4) return 语句不是必须的

##### 成员方法注意事项和细节

- 注意事项和细节：

  - 访问修饰符（作用是控制 方法使用的范围）：

    - 如果不写，则为默认访问
    - 一共有四种：public、protected、默认、private

  - 返回值数据类型：

    - 一个方法最多有一个返回值（思考如何返回多个结果？返回数组）
    - 返回类型可以为任意类型，包含基本类型或引用类型(数组，对象)
    - 如果方法要求有返回数据类型，则方法体中最后的执行语句必须为 return 值；而且要求返回值类型必须和 return 的值类型一致或兼容（兼容，指可以进行自动类型转换）

    4) 如果方法是 void，则方法体中可以没有 return 语句，或者 只写 return

  - 方法名：

    - 遵循驼峰命名法，最好见名知义，表达出该功能的意思即可。比如：得到两个数的和 getSum，开发中按照具体规范

  - 形参列表：

    1. 一个方法可以有 0 个参数，也可以有多个参数，中间用逗号隔开
    2. 参数类型可以为任意类型，包括基本类型和引用类型
    3. 调用带参数的方法时，一定对应着参数列表传入相同类型或兼容（可以进行自动类型转换）类型的参数
    4. 方法定义时的参数称为形式参数，简称形参；方法调用时的参数称为实际参数，简称实参。实参和形参的类型要一致或兼容、个数、顺序必须一致

  - 方法体：

    - 里面写完成功能的具体语句，可以为输入、输出、变量、运算、分支、循环、方法调用，但里面不能再定义方法（即，方法不能嵌套定义）

  - 方法调用细节：

    1. 同一个类中的方法调用：直接调用即可
    2. 跨类中的方法调用：A类调用B类方法，需要通过对象名调用
    3. 跨类的方法调用还与方法的访问修饰符有关，之后才会详细介绍

- 细节示例：

  - ```java
    public class MethodDetail { 
    	public static void main(String[] args) {
    
    		AA a = new AA();
    		int[] res = a.getSumAndSub(1, 4);	//返回值为int数组，用int数组接收
    		System.out.println("和 =" + res[0]);
    		System.out.println("差 =" + res[1]);
    
    		//细节: 调用带参数的方法时，一定对应着参数列表传入相同类型或兼容类型 的参数
    		byte b1 = 1;
    		byte b2 = 2;
    		a.getSumAndSub(b1, b2);	//byte -> int ，可以自动转换，没问题
    		
    		//细节: 实参和形参的类型要一致或兼容、个数、顺序必须一致
    		//a.getSumAndSub(1.1, 1.8);	//double ->int(×)	形式不一致
    		//a.getSumAndSub(100);//× 个数不一致
    		a.f3("tom", 10); //ok
    		//a.f3(100, "jack"); // 顺序不一致
    		
    	}
    }
    
    class AA {
    	//1. 一个方法最多有一个返回值  [思考，如何返回多个结果 返回数组 ]
    	public int[] getSumAndSub(int n1, int n2) {
    		int[] resArr = new int[2]; //
    		resArr[0] = n1 + n2;
    		resArr[1] = n1 - n2;
    		return resArr;
    	}
    	//2. 返回类型可以为任意类型，包含基本类型或引用类型(数组，对象)，例如细节1中的 getSumAndSub方法
    	
    	//3. 如果方法要求有返回数据类型，则方法体中最后的执行语句必须为 return 值; 
    	//   而且要求返回值类型必须和return的值类型一致或兼容
    	public double f1() {
    
    		double d1 = 1.1 * 3;
    		int n = 100;
    		return n; // int ->double 
    		//return d1; // 若返回值为int ，则这里不可以。double -> int 需要强制转换 
    	}
    
    	//如果方法是void，则方法体中可以没有return语句，或者 只写 return ; 
    	public void f2() {
    		System.out.println("hello1");
    		System.out.println("hello1");
    		System.out.println("hello1");
    		int n = 10;
    		//return ;
    	}
        
        //提示：在实际工作中，我们的方法都是为了完成某个功能，所以方法名要有一定含义最好是见名知意
    
    	public void f3(String str, int n) {
    
    	}  
        
        //细节: 方法不能嵌套定义
    	public void f4() {
    		//错误
    		// public void f5() {
    
    		// }
    	}
    }
    ```

  - ```java
    public class MethodDetail02 { 
    	public static void main(String[] args) {
    		A a = new A();
    		a.sayOk();
    		a.m1(); 
    	}
    }
    
    class A {
    	//同一个类中的方法调用：直接调用即可
    	public void print(int n) {
    		System.out.println("print()方法被调用 n=" + n);
    	}
    
    	public void sayOk() { 
    		print(10);	//sayOk调用 print(直接调用即可)
    		System.out.println("继续执行sayOK()~~~");
    	}
    
    	//跨类中的方法A类调用B类方法：需要通过对象名调用
    	public void m1() {
    		System.out.println("m1() 方法被调用");
             //创建B对象, 然后在调用方法即可
    		B b = new B();
    		b.hi();
    		System.out.println("m1() 继续执行:)");
    	}
    }
    
    class B {
    	public void hi() {
    		System.out.println("B类中的 hi()被执行");
    	}
    }
    ```

- 练习：

  - ```java
    public class MethodExercise01 { 
    	public static void main(String[] args) {
    
    		AA a = new AA();
             if(a.isOdd(2)) {
    		 	System.out.println("是奇数");
    		 } else {
    			System.out.println("是偶数");
    		 }	
    		
    		// 使用print方法
    		a.print(4, 4, '#');		
    	}
    }
    
    //练习1：编写类AA ，有一个方法：判断一个数是奇数odd(奇数英文是 odd nummer)还是偶数, 返回boolean
    class AA {
    	/*思路：
            1. 方法的返回类型 boolean
            2. 方法的名字 isOdd
            3. 方法的形参 (int num)
            4. 方法体 , 判断		*/
        
    	public boolean isOdd(int num) {
    		// 
            if(num % 2 != 0) {
             //第一种写法
    		/*	return true;
    		 } else {
    		 	return false;
    		 }	*/
    
    		//第二种写法
             //return num % 2 != 0 ? true; false;
                
    		//第三种写法
    		return num % 2 != 0;
    	}
    
    	//练习2：根据 行、列、字符 打印对应行数和列数的字符，
    	//比如：行：4，列：4，字符#,则打印相应的效果
    	/*
    		####
    		####
    		####
    		####
    	 */
    	//思路
    	//1. 方法的返回类型 void
    	//2. 方法的名字 print
    	//3. 方法的形参 (int row, int col, char c)
    	//4. 方法体 , 循环
    	public void print(int row, int col, char c) {
    		for(int i = 0; i < row; i++) {
    			for(int j = 0; j < col; j++) {//输出每一行
    				System.out.print(c);
    			}
    			System.out.println(); //换行
    		}
    	}
    }
    ```

#### 3.成员方法传参机制

- 补充：参数（parameter）

- 基本数据类型传参示例：

  - ```java
    public class MethodParameter01 { 
    	public static void main(String[] args) {
    		int a = 10;
    		int b = 20;
    		//创建AA对象 名字 obj
    		AA obj = new AA();
    		obj.swap(a, b); //调用swap
    		System.out.println("main方法 a = " + a + " b = " + b);//a=10 b=20
    	}
    }
    
    class AA {
    	public void swap(int a,int b){	//值传递
    		System.out.println("\na和b交换前的值\na=" + a + "\tb=" + b);//a=10 b=20
    		//完成了 a 和 b的交换
    		int tmp = a;
    		a = b;
    		b = tmp;
    		System.out.println("\na和b交换后的值\na=" + a + "\tb=" + b);//a=20 b=10
    	}
    }
    ```

  - 结论：基本数据类型，传递的是值，形参的任何改变不影响实参

- 引用数据类型传参示例：

  - ```java
    public class MethodParameter02 { 
    	public static void main(String[] args) {
    		
    		B b = new B();
    		int[] arr = {1, 2, 3};
    		b.test100(arr);//调用方法
    		System.out.println(" main的 arr数组 ");
    		//遍历数组
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    		System.out.println();		
    
    		//测试
    		Person p = new Person();
    		p.name = "jack";
    		p.age = 10;
    		b.test200(p);
            
    		//测试1, 如果 test200 执行的是 p = null ,下面的结果是 10
    		//测试2, 如果 test200 执行的是 p = new Person();..., 下面输出的是10
    		System.out.println("main 的p.age=" + p.age);	//10000 
    	}
    }
    
    class Person {
    	String name;
    	int age; 
    }
    
    class B {
    	//B类中编写一个方法test100，可以接收一个数组，在方法中修改该数组，看看原来的数组是否变化
    	public void test100(int[] arr) {
    		arr[0] = 200;//修改元素
    		//遍历数组
    		System.out.println(" test100的 arr数组: ");
    		for(int i = 0; i < arr.length; i++) {
    			System.out.print(arr[i] + "\t");
    		}
    		System.out.println();
    	}
        
        public void test200(Person p) {
    		//p.age = 10000; //修改对象属性
            
    		//思考
    		p = new Person();	//这里是在堆区新建了一个对象，并改变了方法栈中p的指向，与main中的p将毫无关系
             //这个对象没有用，在这个方法指向完之后将作为垃圾释放（若作返回值返回给了主方法中的p，则这个对象不会被释放）
    		p.name = "tom";
    		p.age = 99;
            
    		//思考
    		//p = null; 	//这里改变的是方法栈中的p的指向，main 方法中的p的指向不会改变
    	}
    }
    ```
  
  - 结论：引用类型传递的是地址（指向堆区中同一个对象）（其实传递还是值，但是这里的值是一个 地址，通过地址找到堆区中的同一份内容），可以通过形参影响实参
  
- 引用类型应用实例：编写一个方法 copyPerson，可以复制一个 Person 对象，返回复制的对象。克隆对象， 注意要求得到新对象和   原来的对象是两个独立的对象，只是他们的属性相同

  - ```java
    public class MethodExercise02 { 
    	public static void main(String[] args) {	
    		Person p = new Person();
    		p.name = "milan";
    		p.age = 100;
            
    		//创建tools
    		MyTools tools = new MyTools();
    		Person p2 = tools.copyPerson(p);
    
    		//到此 p 和 p2是Person对象，但是是两个独立的对象，属性相同
    		System.out.println("p的属性 age=" + p.age  + " 名字=" + p.name);
    		System.out.println("p2的属性 age=" + p2.age  + " 名字=" + p2.name);
            
    		//如何判断是否是同一个对象：直接对象比较
             //支持输出对象名，输出的时输出什么（？？？）
    		System.out.println(p == p2);//false
    	}
    }
    
    class Person {
    	String name;
    	int age;
    }
    
    class MyTools {
    	/*编写一个方法copyPerson，可以复制一个Person对象，返回复制的对象。克隆对象， 
    		注意要求得到新对象和原来的对象是两个独立的对象，只是他们的属性相同		*/
    	/*编写方法的思路：
            1. 方法的返回类型 Person
            2. 方法的名字 copyPerson
            3. 方法的形参 (Person p)
            4. 方法体, 创建一个新对象，并复制属性，返回即可	*/
    	
    	public Person copyPerson(Person p) {
    		//创建一个新的对象
    		Person p2 = new Person();
    		p2.name = p.name;	//把原来对象的名字赋给p2.name
    		p2.age = p.age;	//把原来对象的年龄赋给p2.age
    		return p2;
    	}
    }
    ```

#### 4.方法递归调用

##### 基本介绍

- 简单的说：递归（recursion）就是方法自己调用自己，每次调用时传入不同的变量。递归有助于编程者解决复杂问题,同时可以让代码变得简洁

##### 递归能解决的问题

- 各种数学问题：八皇后问题、汉诺塔问题、阶乘问题、迷宫问题、球和篮子的问题
- 各种算法中：快速排序、归并排序、二分查找、分治算法
- 用栈解决的问题

##### 递归入门案例

- 示例：

  - ```java
    public class Recursion01 { 
    	public static void main(String[] args) {
    		T t1 = new T();
    		t1.test(4);//输出什么？ n=2 n=3 n=4
            
    		int res = t1.factorial(5); 
    		System.out.println("5的阶乘 res =" + res);
    	}
    }
    
    class T {
    	//打印问题
    	public void test(int n) {
    		if (n > 2) {
    			test(n - 1);
    		} 
    		System.out.println("n=" + n);
    	}
    
    	//factorial 阶乘问题
    	public int factorial(int n) {
    		if (n == 1) {
    			return 1;
    		} else {
    			return factorial(n - 1) * n;
    		}
    	}
    }
    ```

##### 递归重要规则

1. 执行一个方法时，就创建一个新的受保护的独立空间（栈空间）
2. 方法的局部变量是独立的，不会互相影响
3. 如果方法中使用的是引用数据类型，就会共享该引用数据类型的数据
4. 递归必须向退出递归的条件逼近，否则就会无限递归，出现 StackOverFlow
5. 当一个方法执行完毕后，或遇到 return，就会返回，遵守谁调用，就将结果返回给谁，同时当方法执行执行完毕或返回，该方法就执行完毕

##### 递归练习案例

- 案例1：请使用递归的方式求出斐波那契（fibonacci）数列 1、1、2、3、5、8、13、...。给你一个整数 n，求出它的值

- 案例2：猴子吃桃子问题：有一堆桃子，猴子第一天吃了其中的一半，并再多吃了一个！以后每天猴子都吃其中的一半，然后再多吃一个。当到第10天时，想再吃时（即还没吃），发现只有1个桃子了。问题：最初共多少个桃子？

  - ```java
    public class RecursionExercise01 { 
    	public static void main(String[] args) {
    		//斐波那契
             /*T t1 = new T();
    		 int n = 7;
    		 int res = t1.fibonacci(n);
    		 if(res != -1) {
    		 	System.out.println("当n="+ n +" 对应的斐波那契数=" + res);
    		 } 		*/
            
    		//桃子问题
    		int day = 0;
    		int peachNum = t1.peach(day);
    		if(peachNum != -1) {
    			System.out.println("第 " + day + "天有" + peachNum + "个桃子");
    		}
    	}
    }
    
    class T {
    		/*
    		题目：请使用递归的方式求出斐波那契数1,1,2,3,5,8,13...给你一个整数n，求出它的值是多
    		
    		思路分析：
                1. 当n = 1 斐波那契数 是1
                2. 当n = 2 斐波那契数 是1
                3. 当n >= 3  斐波那契数 是前两个数的和
    		 */
    	
    		public int fibonacci(int n) {
    			if( n >= 1) {
    				if( n == 1 || n == 2) {
    					return 1;
    				} else {
    					return fibonacci(n-1) + fibonacci(n-2);
    				}
    			} else {
    				System.out.println("要求输入 n >= 1 的整数");
    				return -1;
    			}
    		}
    
    		/*
    		题目：猴子吃桃子问题：有一堆桃子，猴子第一天吃了其中的一半，并再多吃了一个！
    		以后每天猴子都吃其中的一半，然后再多吃一个。当到第10天时，
    		想再吃时（即还没吃），发现只有1个桃子了。问题：最初共多少个桃子？
    		
    		思路分析 逆推：
                1. day = 10 时 有 1个桃子
                2. day = 9 时  有 (day10 + 1) * 2 = 4
                3. day = 8 时  有 (day9 + 1) * 2 = 10
                4. 规律就是  前一天的桃子 = (后一天的桃子 + 1) *2//就是我们的能力
                5. 递归
    		 */
    		public int peach(int day) { 
    			if(day == 10) {//第10天，只有1个桃
    				return 1; 
    			} else if ( day >= 1 && day <=9 ) {
    				return (peach(day + 1) + 1) * 2;//规则，自己要想
    			} else {
    				System.out.println("day 在 1-10");
    				return -1;
    			}
    		}
    	
    }
    ```

##### 递归应用案例（迷宫问题）

- 问题描述：

- 示例：

  - ```java
    public class MiGong { 
    	public static void main(String[] args) {
    		/*思路:
                1. 先创建迷宫，用二维数组表示 int[][] map = new int[8][7];
                2. 先规定 map 数组的元素值: 0 表示可以走、 1 表示障碍物 	
                ...		*/
    		
    		int[][] map = new int[8][7];
    		//3. 设置障碍：将最上面的一行和最下面的一行，全部设置为1
    		for(int i = 0; i < 7; i++) {
    			map[0][i] = 1;	//第1行
    			map[7][i] = 1;	//第8行
    		}
    		//4.将最右面的一列和最左面的一列，全部设置为1
    		for(int i = 0; i < 8; i++) {
    			map[i][0] = 1;	//第1列
    			map[i][6] = 1;	//第7列
    		}
    		map[3][1] = 1;
    		map[3][2] = 1;
    		map[2][2] = 1; //测试回溯 
    		// map[2][1] = 1;
    		// map[2][2] = 1;
    		// map[1][2] = 1;
    
    		//输出当前的地图
    		System.out.println("=====当前地图情况======");
    		for(int i = 0; i < map.length; i++) {	//遍历行
    			for(int j = 0; j < map[i].length; j++) {	//遍历列
    				System.out.print(map[i][j] + " ");//输出一行
    			}
    			System.out.println();
    		}
    
    		//使用findWay给老鼠找路
    		T t1 = new T();
    		//下右上左
    		t1.findWay(map, 1, 1);	//（1，1）表示初始位置
    
    		System.out.println("\n====找路的情况如下=====");
    
    		for(int i = 0; i < map.length; i++) {
    			for(int j = 0; j < map[i].length; j++) {
    				System.out.print(map[i][j] + " ");//输出一行
    			}
    			System.out.println();
    		}
    	}
    }
    
    class T  {
    
    	//使用递归回溯的思想来解决老鼠出迷宫
    	/*思路解读：
            1. findWay 方法就是专门来找出迷宫的路径
            2. 如果找到，就返回 true ,否则返回false
            3. map 就是二维数组，即表示迷宫
            4. i,j 就是老鼠的位置，初始化的位置为(1,1)
            5. 因为我们是递归的找路，所以我先规定 map数组的各个值的含义
               0 表示没有走过的路可以走、1 表示障碍物、2 表示已经走过的可以走的路、3 表示走过，但是走不通是死路
            6. 当map[6][5] =2 就说明找到通路,就可以结束，否则就继续找.
            7. 先确定老鼠找路策略 下->右->上->左		*/	
    	public boolean findWay(int[][] map , int i, int j) {
    		if(map[6][5] == 2) {	//结束条件说明已经找到
    			return true;
    		} else {
    			if(map[i][j] == 0) {//当前这个位置0,说明表示可以走
    				//我们假定可以走通
    				map[i][j] = 2;
    				//使用一种找路策略，来确定该位置是否真的可以走通
    				//下->右->上->左
    				if(findWay(map, i + 1, j)) {	//先走下
    					return true;
    				} else if(findWay(map, i, j + 1)){	//右
    					return true;
    				} else if(findWay(map, i-1, j)) {	//上
    					return true;
    				} else if(findWay(map, i, j-1)){	//左
    					return true;
    				} else {
    					map[i][j] = 3;	//将这一格修改为3，表示不可走
    					return false;
    				}
    			} else { //map[i][j] = 1 , 2, 3
    				return false; 
    			}
    		}
    	}
    
    	//修改找路策略，看看路径是否有变化
    	//下->右->上->左 ==> 上->右->下->左
    	public boolean findWay2(int[][] map , int i, int j) {
    		if(map[6][5] == 2) {//说明已经找到
    			return true;
    		} else {
    			if(map[i][j] == 0) {//当前这个位置0,说明表示可以走
    				//我们假定可以走通
    				map[i][j] = 2;
    				//使用找路策略，来确定该位置是否真的可以走通
    				//上->右->下->左
    				if(findWay2(map, i - 1, j)) {//先走上
    					return true;
    				} else if(findWay2(map, i, j + 1)){//右
    					return true;
    				} else if(findWay2(map, i+1, j)) {//下
    					return true;
    				} else if(findWay2(map, i, j-1)){//左
    					return true;
    				} else {
    					map[i][j] = 3;
    					return false;
    				}
    			} else { //map[i][j] = 1 , 2, 3
    				return false; 
    			}
    		}
    	}
    }
    
    
    
    ```

#### 5.方法重载

##### 基本介绍：

- java 中允许同一个类中，多个同名方法的存在，但要求 形参列表不一致！

##### 重载的好处

1) 减轻了起名的麻烦
2) 减轻了记名的麻烦

##### 方法重载注意事项和细节

1. 方法名：必须相同
2. 形参列表：必须不同（参数类型、或个数、或顺序，至少有一样不同，参数名无要求）
3. 返回类型：无要求

##### 快速入门案例

- 示例：

  - ```java
    public class OverLoad01 { 
    	public static void main(String[] args) {
    
    		/* System.out.println(100);
    		   System.out.println("hello,world");
    		   System.out.println('h');
    		   System.out.println(1.1);
    		   System.out.println(true);	*/
    		 
    		MyCalculator mc = new MyCalculator();
    		System.out.println(mc.calculate(1, 2));
    		System.out.println(mc.calculate(1.1, 2));
    		System.out.println(mc.calculate(1, 2.1));
    	}
    }
    
    class MyCalculator  {
    
    	//下面的四个 calculate方法构成了重载
    	//1.两个整数的和
    	public int calculate(int n1, int n2)  {
    		System.out.println("calculate(int n1, int n2) 被调用");
    		return n1 + n2;
    	}
    	
        //仅仅返回值类型不同，没有构成方法重载, 仍然是错误的，因为是方法的重复定义
        /*
    	public void calculate(int n1, int n2)  {
    	 	System.out.println("calculate(int n1, int n2) 被调用");
    	 	int res =  n1 + n2;
    	} 	*/
    	
        //看看下面是否构成重载, 没有构成，而是方法的重复定义,就错了
        /*
    	public int calculate(int a1, int a2)  {
    	 	System.out.println("calculate(int n1, int n2) 被调用");
    	 	return a1 + a2;
    	} 	*/
    
    	//2.一个整数，一个double的和
    	public double calculate(int n1, double n2) {
    		return n1 + n2;
    	}
    	//3.一个double ,一个Int和 
    	public double calculate(double n1, int n2) {
    		System.out.println("calculate(double n1, int n2) 被调用..");
    		return n1 + n2;
    	}
    	//4.三个int的和
    	public int calculate(int n1, int n2,int n3) {
    		return n1 + n2 + n2;
    	}
    
    }
    ```

##### 练习

- 练习示例：

  - ```java
    public class OverLoadExercise { 
    	public static void main(String[] args) {
    
    		//在主类的main ()方法中分别用参数区别调用三个方法
    		Methods method = new Methods();
    		method.m(10);	//100
    		method.m(10, 20);	//200
    		method.m("韩顺平教育 hello");	//字符串信息
    
    		//测试
    		System.out.println(method.max(10, 24)); // 24
    		System.out.println(method.max(10.0, 21.4)); // 21.4
    		System.out.println(method.max(10.0, 1.4, 30.0)); // 30.0
    	}
    }
    
    /*
    练习1题目要求：编写程序，类Methods中定义三个重载方法并调用。方法名为m。
    三个方法分别接收一个int参数、两个int参数、一个字符串参数。
    分别执行平方运算并输出结果，相乘并输出结果，输出字符串信息。
    在主类的main()方法中分别用参数区别调用三个方法		*/
    
    /*
    练习2题目要求：定义三个重载方法max()，第一个方法，返回两个int值中的最大值，
    第二个方法，返回两个double值中的最大值，第三个方法，
    返回三个double值中的最大值，并分别调用三个方法		*/
    class Methods {
    	
        //练习1：
        /*分析：
            1.方法名 m
            2.形参 (int) 
            3.void		*/
    	public void m(int n) {
    		System.out.println("平方=" + (n * n));
    	} 
    
        /*分析：
            1.方法名 m
            2.形参 (int,int) 
            3.void		*/
    	public void m(int n1, int n2) {
    		System.out.println("相乘=" + (n1 * n2));
    	}
    
        /*分析：
            1.方法名 m
            2.形参 (String) 
            3.void		*/
    	public void m(String str) {
    		System.out.println("传入的str=" + str);
        }
        
        //练习2：
    	/*分析：
            1.方法名 max
            2.形参 (int,int) 
            3.int		*/
    	public int max(int n1, int n2) {
    		return n1 > n2 ? n1 : n2;
    	}
    
    	/*分析
            1.方法名 max
            2.形参 (double,double) 
            3.double		*/
    	public double max(double n1, double n2) {
    		return n1 > n2 ? n1 : n2;
    	}
    
    	//分析
    	//1 方法名 max
    	//2 形参 (double,double,double) 
    	//3.double
    	public double max(double n1, double n2, double n3) {
    		
    		System.out.println("max(double n1, double n2, double n3)");
    		//求出n1 和  n2的最大值
    		double max1 = n1 > n2 ? n1 : n2;
    		return max1 > n3 ? max1 : n3;
    	}
    
        //补充，也可以构成重载，若第三个参数传的是整型，则优先调用这个重载，因为这里不需要自动类型转换
    	public double max(double n1, double n2, int n3) {	
    		System.out.println("max(double n1, double n2, int n3)");
    		//求出n1 和  n2的最大值
    		double max1 = n1 > n2 ? n1 : n2;
    		return max1 > n3 ? max1 : n3;
    	}
    }
    ```

#### 6.可变参数

##### 基本概念

- java 允许将同一个类中多个同名同功能但参数个数不同的方法，封装成一个方法。可以通过可变参数实现

##### 基本语法

- ```java
  访问修饰符 返回类型 方法名(数据类型... 形参名) {
  
  }
  ```

##### 快速入门案例

- 示例：

  - ```java
    public class VarParameter01 { 
    	public static void main(String[] args) {
    
    		HspMethod m = new HspMethod();
    		System.out.println(m.sum(1, 5, 100)); //106
    		System.out.println(m.sum(1,19)); //20
    	}
    }
    
    class HspMethod {
    	//可以计算 2个数的和，3个数的和 ... 4个、5个...
        
    	/*可以使用方法重载
    	public int sum(int n1, int n2) {//2个数的和
    	 	return n1 + n2;
    	}
    	
    	public int sum(int n1, int n2, int n3) {//3个数的和
    	 	return n1 + n2 + n3;
    	}
    	
    	public int sum(int n1, int n2, int n3, int n4) {//4个数的和
    	 	return n1 + n2 + n3 + n4;
    	}		
    	.....		*/
        
    	//上面的三个方法名称相同，功能相同, 参数个数不同 -> 使用可变参数优化
    	/*解读：
            1. int... 表示接受的是可变参数，类型是int，即可以接收多个int（也可以是0个） 
            2. 使用可变参数时，可以当做数组来使用，即 nums 可以当做数组
            3. 遍历 nums 求和即可		*/
    	public int sum(int... nums) {
    		//System.out.println("接收的参数个数=" + nums.length);
    		int res = 0;
    		for(int i = 0; i < nums.length; i++) {
    			res += nums[i];
    		}
    		return res;
    	}
    }
    ```

##### 可变参数注意事项和细节

1. 可变参数的个数可以是 0 个或任意多个
2. 可变参数的实参可以为数组
3. 可变参数的本质就是数组
4. 可变参数可以和普通类型的参数一起放在形参列表，但必须保证可变参数在最后
5. 一个形参列表中只能出现一个可变参数

- 细节示例：

  - ```java
    public class VarParameterDetail { 
    	public static void main(String[] args) {
    		
            //细节: 可变参数的实参可以为数组
    		int[] arr = {1, 2, 3};
    		T t1 = new T();
    		t1.f1(arr);
    	}
    }
    
    class T {
    
    	public void f1(int... nums) {
    		System.out.println("长度=" + nums.length);
    	}
    
    	//细节: 可变参数可以和普通类型的参数一起放在形参列表，但必须保证可变参数在最后
    	public void f2(String str, double... nums) {
    
    	}
    	//细节: 一个形参列表中只能出现一个可变参数
    	//下面的写法是错的.
    	// public void f3(int... nums1, double... nums2) {
    
    	// }
    }
    ```

##### 可变参数练习

- 示例：

  - ```java
    public class VarParameterExercise { 
    	public static void main(String[] args) {
    		HspMethod hm = new HspMethod();
    		System.out.println(hm.showScore("milan" , 90.1, 80.0 ));
    		System.out.println(hm.showScore("terry" , 90.1, 80.0,10,30.5,70 ));
    	}
    }
    
    class HspMethod  {
    	/*问题描述：
    		有三个方法，分别实现返回姓名和两门课成绩(总分)，
    		返回姓名和三门课成绩(总分)，返回姓名和五门课成绩（总分）。封装成一个可变参数的方法		 */
    	
    	/*分析:
    		1. 方法名 	showScore  
    		2. 形参列表		(String ,double... ) 
    		3. 返回	String		*/
    	public String showScore(String name, double... scores) {
    		double totalScore = 0;
    		for(int i = 0; i < scores.length; i++) {
    			totalScore += scores[i];
    		}
    		return name + " 有 " +scores.length + " 门课的成绩总分为：" + totalScore;
    	}
     }
    ```

#### 7.作用域

##### 作用域（scope）基本使用

1. 在 Java 编程中，主要的变量就是属性（成员变量）和局部变量
2. 我们所说的局部变量一般是指在成员方法中定义的变量
3. Java 中作用域的分类：
   - 全局变量：也就是属性，作用域为整个类体
   - 局部变量：除了属性之外的其他变量，作用域为定义它的代码块中
4. 全局变量（属性）可以不赋值，直接使用，因为有默认值；局部变量必须赋值后，才能使用，因为没有默认值

- 示例：

  - ```java
    public class VarScope { 
    	public static void main(String[] args) {
    	}
    }
    
    class Cat {
    	//全局变量：也就是属性，作用域为整个类体 Cat类
    	//属性在定义时，可以直接赋值
    	int age = 10;	//指定的值是 10
    
    	//全局变量(属性)可以不赋值，直接使用，因为有默认值，
    	double weight; 	//默认值是0.0
    
    	public void hi() {
    		//局部变量必须赋值后，才能使用，因为没有默认值
    		int num = 1;
    		String address = "北京的猫";
    		System.out.println("num=" + num);
    		System.out.println("address=" + address);
    		System.out.println("weight=" + weight);//属性
    	}
    	
    	public void cry() {
    		//1. 局部变量一般是指在成员方法中定义的变量
    		//2. n 和 name 就是局部变量
    		//3. n 和 name 的作用域在 cry 方法中
    		int n = 10;
    		String name = "jack";
    		System.out.println("在cry中使用属性 age=" + age);
    	}
    
    	public void eat() {
    		System.out.println("在eat中使用属性 age=" + age);
    		//System.out.println("在eat中使用 cry的变量 name=" + name);//错误
    	}
    }
    ```

##### 作用域注意事项和细节

1. 属性和局部变量可以重名，访问时遵循就近原则
2. 同一个作用域中，比如在同一个成员方法中，两个局部变量，不能重名
3. 属性生命周期较长，伴随着对象的创建而创建，伴随着对象的销毁而销毁。局部变量，生命周期较短，伴随着它的代码块的执行而创建，伴随着代码块的结束而销毁。即在一次方法调用过程中
4. 作用域范围不同：
   - 全局变量（属性）：可以被本类使用，或其他类使用（通过对象调用）
   - 局部变量：只能在本类中对应的方法中使用
5. 修饰符：
   - 全局变量（属性）可以加修饰符
   - 局部变量不能加修饰符

- 细节示例：

  - ```java
    public class VarScopeDetail { 
    	public static void main(String[] args) {
    		Person p1 = new Person();
    		/*
    		属性生命周期较长，伴随着对象的创建而创建，伴随着对象的销毁而销毁。
    		局部变量，生命周期较短，伴随着它的代码块的执行而创建，
    		伴随着代码块的结束而销毁。即在一次方法调用过程中		*/
    		//p1.say();//当执行say方法时，say方法的局部变量比如name会创建，
            		   //当say执行完毕后name局部变量就销毁，但是属性(全局变量)仍然可以使用
    		
    		T t1 = new T();
    		t1.test(); //第1种跨类访问对象属性的方式
    
    		t1.test2(p1);//第2种跨类访问对象属性的方式
    
    	}
    }
    
    class T {
    
    	//全局变量/属性：可以被本类使用，或其他类使用（通过对象调用)
    	public void test() {
    		Person p1 = new Person();
    		System.out.println(p1.name);	//jack
    	}
    
    	public void test2(Person p) {
    		System.out.println(p.name);	//jack
    	}
    }
    
    class Person {
    	//细节: 全局变量/属性可以加修饰符(public、protected、private..)
    	//      局部变量不能加修饰符
    	public int age = 20;
    
    	String name = "jack";
    	public void say() {
    		//细节1.：属性和局部变量可以重名，访问时遵循就近原则
    		String name = "king";	//重名
    		System.out.println("say() name=" + name);
    	}
    
    	public void hi() {
    		String address = "北京";
    		//String address = "上海";	//错误,重复定义变量
    		String name = "hsp";//可以
    	}
    }
    ```

#### 8.构造方法 / 构造器

##### 需求引入

- 我们来看一个需求：前面我们在创建人类的对象时，是先把一个对象创建好后，再给他的年龄和姓名属性赋值，如果现在我要求，在创建人类的对象时，就直接指定这个对象的年龄和姓名，该怎么做? 这时就可以使用构造器

##### 构造方法 / 构造器基本语法

- ```java
  [修饰符] 方法名(形参列表){
  	方法体;
  }
  ```

- 解读：

  1) 构造器的修饰符可以默认， 也可以是：public、protected、private
  2) 构造器没有返回值
  3) 方法名和类名必须一样
  4) 参数列表和成员方法的参数列表规则一样
  5) 构造器的调用, 由系统完成

- （类似于 C++ 中的构造函数）

##### 基本介绍

- 构造方法又叫构造器（constructor），是类的一种特殊的方法，它的主要作用是完成对新对象的初始化
- 它有几个特点：
  1) 方法名和类名相同
  2) 没有返回值
  3) 在创建对象时，系统会自动的调用该类的构造器完成对象的初始化

##### 入门案例

- 示例：

  - ```java
    public class Constructor01 { 
    	public static void main(String[] args) {
    		//当我们new 一个对象时，直接通过构造器指定名字和年龄
    		Person p1 = new Person("smith", 80);
    		System.out.println("p1的信息如下");
    		System.out.println("p1对象name=" + p1.name);//smith
    		System.out.println("p1对象age=" + p1.age);//80
    	}
    }
    
    //在创建人类的对象时，就直接指定这个对象的年龄和姓名
    class Person {
    	String name;
    	int age;
    	/*构造器:
            1. 构造器没有返回值, 也不能写void
            2. 构造器的名称和类 Person 一样
            3. (String p_Name, int p_Age) 是构造器形参列表，规则和成员方法一样	*/
    	public Person(String p_Name, int p_Age) {
    		System.out.println("构造器被调用~~ 完成对象的属性初始化");
    		name = p_Name;
    		age = p_Age;
    	}
    }
    ```

##### 构造器注意事项和注意细节

1. 一个类可以定义多个不同的构造器，即构造器的重载
2. 构造器名要和类名一致
3. 构造器没有返回值
4. 构造器是完成对象的初始化，不是创建对象
5. 在创建对象时，系统自动调用该类的构造器
6. 如果程序员没有定义构造器，系统会自动给类生成一个默认无参构造器（也叫默认构造器）
7. 一旦定义了自己的构造器，默认的构造器就覆盖了，就不能再使用默认的无参构造，除非自己再进行显式定义一个默认构造器

- 细节示例：

  - ```java
    public class ConstructorDetail { 
    	public static void main(String[] args) {	
            Person p1 = new Person("king", 40);	//第1个构造器
    		Person p2 = new Person("tom");	//第2个构造器
    
    		Dog dog1 = new Dog();	//使用的是默认的无参构造器
    	}
    }
    class Dog {
    	//如果程序员没有定义构造器，系统会自动给类生成一个默认无参构造器(也叫默认构造器)（类似C++的默认构造函数）
    	//使用javap指令 反编译看看
    	/*
        默认构造器
        Dog() {
    
        }	*/
    	//一旦定义了自己的构造器,默认的构造器就覆盖了，就不能再使用默认的无参构造器，
    	//除非显式的定义一下,即:  Dog(){}  写 (这点很重要)
    	//
    	public Dog(String dName) {
    		//...
    	}
    	Dog() { //显式的定义一下 无参构造器
    
    	}
    }
    
    class Person {
    	String name;
    	int age;	//默认0
    	//第1个构造器
    	public Person(String pName, int pAge) {
    		name = pName;
    		age = pAge;
    	}
    	//第2个构造器, 只指定人名，不需要指定年龄
    	public Person(String pName) {
    		name = pName;
    	}
    }
    ```

##### 构造方法练习：

- 示例：

  - ```java
    public class ConstructorExercise { 
    	public static void main(String[] args) {
    		
            Person p1 = new Person();	//无参构造器
    		//下面输出 name = null, age = 18
    		System.out.println("p1的信息 name=" + p1.name + " age=" + p1.age);
    
    		Person p2 = new Person("scott", 50);
    		//下面输出 name = scott, age = 50
    		System.out.println("p2的信息 name=" + p2.name + " age=" + p2.age);
    	}
    }
    
    /*
        在前面定义的Person类中添加两个构造器:
        第一个无参构造器：利用构造器设置所有人的age属性初始值都为18
        第二个带pName和pAge两个参数的构造器：
        使得每次创建Person对象的同时初始化对象的age属性值和name属性值。
        分别使用不同的构造器，创建对象.		*/
    
    class Person {
    	String name;//默认值 null
    	int age;//默认 0
    	//第一个无参构造器：利用构造器设置所有人的age属性初始值都为18
    	public Person() {
    		age = 18;//
    	}
    	//第二个带pName和pAge两个参数的构造器
    	public Person(String pName, int pAge) {
    		name = pName;
    		age = pAge;
    	}
    }
    ```

#### 9.this 关键字

##### 入门示例：

- 示例：

  - ```java
    public class This01 { 
    	public static void main(String[] args) {
    
    		Dog dog1 = new Dog("大壮", 3);
    		System.out.println("dog1的hashcode = " + dog1.hashCode());
    		//dog1调用了 info()方法
    		dog1.info(); 
    
    		System.out.println("============");
    		Dog dog2 = new Dog("大黄", 2);
    		System.out.println("dog2的hashcode = " + dog2.hashCode());
    		dog2.info();
    	}
    }
    
    class Dog{ //类
    
    	String name;
    	int age;
    	/*public Dog(String dName, int  dAge){	//构造器
    		name = dName;
    		age = dAge;
    	}		
    	//如果我们构造器的形参，能够直接写成属性名，就更好了但是出现了一个问题，根据变量的作用域原则:
    	//	构造器的name 是局部变量，而不是属性
    	//	构造器的age  是局部变量，而不是属性	==> 引出this关键字来解决	*/
    	public Dog(String name, int  age){//构造器
    		//this.name 就是当前对象的属性name
    		this.name = name;
    		//this.age 就是当前对象的属性age
    		this.age = age;
    		System.out.println("this.hashCode=" + this.hashCode());
    	}
    
    	public void info(){//成员方法,输出属性x信息
    		System.out.println("this.hashCode=" + this.hashCode());
    		System.out.println(name + "\t" + age + "\t");
    	}
    }
    
    ```

##### 什么是 this

- Java 虚拟机会给每个对象分配 this，表示当前对象（类似 C++ 中的this，理念解决）
- 简单来说，哪个对象调用，this 就代表哪个对象

##### this 的注意事项和使用细节

1) this 关键字可以用来访问本类的属性、方法、构造器
2) this 用于区分当前类的属性和局部变量
3) 访问成员方法的语法：`this.方法名(参数列表)`
4) 访问构造器语法：`this(参数列表);` 。注意只能在构造器中使用（即只能在构造器中访问另外一个构造器，必须放在第一条语句）。因此只能调用一个其他构造器，不允许调用两个或多个
5) this 不能在类定义的外部使用，只能在类定义的方法中使用

- 示例：

  - ```java
    public class ThisDetail { 
    	public static void main(String[] args) {
    		T t1 = new T();
    		t1.f2();
            
    		T t2 = new T();
    		t2.f3();
    	}
    }
    
    class T {
    	String name = "jack";
    	int num = 100;
    
    	/*
    	细节: 访问构造器语法：this(参数列表); 注意只能在构造器中使用(即只能在构造器中访问另外一个构造器)
    
    	注意： 访问构造器语法：this(参数列表); 必须放置第一条语句 	 */
    	
    	public T() {
    		//这里去访问 T(String name, int age) 构造器
    		this("jack", 100);
    		System.out.println("T() 构造器");
    		
    	}
    
    	public T(String name, int age) {
    
    		System.out.println("T(String name, int age) 构造器");
    	}
    
    	//this 关键字可以用来访问本类的属性
    	public void f3() {
    		String name = "smith";
    		//传统方式
    		System.out.println("name = " + name + " num = " + num);//smith  100
    		//也可以使用this访问属性
    		System.out.println("name = " + this.name + " num = " + this.num);//jack 100
    	}
    	//细节: 访问成员方法的语法：this.方法名(参数列表);
    	public void f1() {
    		System.out.println("f1() 方法..");
    	}
    
    	public void f2() {
    		System.out.println("f2() 方法..");
    		//调用本类的 f1,有两种方式
    		//第一种方式
    		f1();
    		//第二种方式
    		this.f1();
    	}
    	
    }
    ```

##### this 练习：

- 示例：

  - ```java
    public class TestPerson { 
    	public static void main(String[] args) {
    
    		Person p1 = new Person("mary", 20);
    		Person p2 = new Person("mary", 20);
    
    		System.out.println("p1和p2比较的结果=" + p1.compareTo(p2));
    	}
    }
    
    /*题目描述：
        定义Person类，里面有name、age属性，并提供compareTo比较方法，
        用于判断是否和另一个人相等，提供测试类TestPerson用于测试, 
        名字和年龄完全一样，就返回true, 否则返回false	 */
    class Person {
    	String name;
    	int age;
    	//构造器
    	public Person(String name, int age) {
    		this.name = name;
    		this.age = age;
    	}
    	//compareTo比较方法
    	public boolean compareTo(Person p) {
    		//名字和年龄完全一样
    		/* if(this.name.equals(p.name) && this.age == p.age) {
    		 		return true;
    		 	} else {
    		 		return false;
    		 	}	*/
    		return this.name.equals(p.name) && this.age == p.age;
    	}
    }
    ```

#### 10.作业练习

- 练习1：

  - ```java
    public class Homework01 { 
    	public static void main(String[] args) {
    		A01 a01 = new A01();
    		double[] arr = {1, 1.4, -1.3, 89.8, 123.8 , 66}; //;{};
    		Double res = a01.max(arr);
    		if(res != null) {
    			System.out.println("arr的最大值 = " + res);
    		} else {
    			System.out.println("arr的输入有误, 数组不能为null, 或者{}");
    		}
    	}
    }
    /*题目描述：
    	编写类A01，定义方法max，实现求某个double数组的最大值，并返回	*/
    /*思路分析：
        1. 类名 A01
        2. 方法名 max
        3. 形参 (double[])
        4. 返回值 double
    
        先完成正常业务，然后再考虑代码健壮性	 */
    class A01 {
    	public Double max(double[] arr) {
    		//先判断arr是否为null,然后再判断 length 是否>0
    		if( arr != null && arr.length > 0 ) {	//这里如果只判断长度大于0，则数组赋为空时会出错(arr.length无法执行)，但是数组元素为0时（arr.length = 0）可以正常执行else
    			//保证arr至少有一个元素 
    			double max = arr[0];	//假定第一个元素就是最大值
    			for(int i = 1; i < arr.length; i++) {
    				if(max < arr[i]) {
    					max = arr[i];
    				}
    			}
    			return max;	//double
    		} else {
    			return null;	//这里由于没有合适的 double 类型可以返回，只好返回一个 null
    		}
    	}
    }
    ```

  - Double，double的包装类（？？？是什么）：在方法的返回值类型为 `Double` 时，你可以返回 `Double` 对象、null、基本类型的值或 `Double` 类型的子类对象。

  - 数组为空，与数组长度为0，是不同的概念：

    - 数组为空：指的是数组引用没有指向任何有效的数组对象，即数组变量指向了 `null`。这种情况下，数组被认为是空的，因为它不包含任何有效的元素
    - 数组长度为 0：指的是数组被创建但没有包含任何元素，数组的长度为 0
    - 虽然在两种情况下都可以说数组是空的，但是数组为空意味着数组引用为 null，而数组长度为 0 意味着数组已经被创建，但没有包含任何元素
    - chargpt：在 Java 中，当数组引用被赋为 `null` 时，尝试使用 `arr.length` 会导致 `NullPointerException` 异常。因为此时数组引用指向了 null，而不指向任何有效的数组对象，因此无法获取数组的长度

- 练习2：

  - ```java
    public class Homework02 { 
    	public static void main(String[] args) {
    		String[] strs = {"jack", "tom", "mary","milan"};	//字符串数组
    		A02 a02 = new A02();
    		int index = a02.find("milan", strs);
    		System.out.println("查找的index=" + index);
    	}
    }
    
    /*问题描述：
    	编写类A02，定义方法find，实现查找某字符串是否在字符串数组中，并返回索引，如果找不到，返回-1	*/
    /*分析：
        1. 类名 A02
        2. 方法名 find
        3. 返回值 int
        4. 形参 (String , String[])
    
        //自己补充代码健壮性		*/
    class A02 {
    	public int find(String findStr, String[] strs) {
    		if(strs != null)	//字符串数组不为null，.length语句才能正常执行。
            {
                //直接遍历字符串数组，如果找到，则返回索引
    			for(int i = 0; i < strs.length; i++) {
    				if(findStr.equals(strs[i])) {
    					return i;
    				}
    			}
            }
    		//如果字符串数组为null、或没有找到，返回-1
    		return -1;
    	}
    }
    ```

  - 在 Java 中，当字符串数组的引用被置为空时，尝试使用 `.length` 也会导致 `NullPointerException` 异常，与数组的情况类似。因为此时字符串数组的引用指向了 null，而不指向任何有效的字符串数组对象，因此无法获取数组的长度。

  - 如果字符串数组的只是长度为 0，而不是被置为 null，那么可以安全地使用 `.length` 来获取数组的长度。在这种情况下，`.length` 返回的值将是数组的长度，即 0

- 练习3：

  - ```java
    public class Homework03 { 
    	public static void main(String[] args) {
    		//测试
    		Book book = new Book("笑傲江湖", 300);
    		book.info();
    		book.updatePrice();//更新价格
    		book.info();
    	}
    }
    /*问题描述：
        编写类Book,  定义方法updatePrice，实现更改某本书的价格，
        具体：如果价格>150,则更改为150，如果价格>100,更改为100，否则不变	*/
    
    /*分析：
        1. 类名 Book
        2. 属性 price, name
        3. 方法名 updatePrice
        4. 形参 ()
        5. 返回值 void
        6. 提供一个构造器	 */
    
    class Book {
    	String name;
    	double price;
    	public Book(String name, double price) {
    		this.name = name;
    		this.price = price;
    	}
    	public void updatePrice() {
    		//如果方法中，没有 price 局部变量, this.price 等价 price
    		if(price > 150) {
    			price = 150;
    		} else if(price > 100 ) {
    			price = 100;
    		} 
    	}
    
    	//显示书籍情况
    	public void info() {
    		System.out.println("书名 = " + this.name + " 价格 = " + this.price);
    	}
    }
    ```

- 练习4：

  - ```java
    public class Homework04 { 
    	public static void main(String[] args) {
    		int[] oldArr = {10, 30, 50};
    		A03 a03 = new A03();
    		int[] newArr = a03.copyArr(oldArr);
            
    		//遍历newArr,验证
    		System.out.println("==返回的newArr元素情况==");
    		for(int i = 0; i < newArr.length; i++) {
    			System.out.print(newArr[i] + "\t");
    		}
    	}
    }
    
    /*问题描述：
    	编写类A03, 实现数组的复制功能copyArr，输入旧数组，返回一个新数组，元素和旧数组一样	 */
    class A03 {
    	public int[] copyArr(int[] oldArr) {	//返回值为数组
    		//在堆中，创建一个长度为 oldArr.length 数组
    		int[] newArr = new int[oldArr.length];
    		//遍历 oldArr,将元素拷贝到 newArr
    		for(int i = 0; i < oldArr.length; i++) {
    			newArr[i] = oldArr[i];
    		}
    		return newArr;
    	}
    }
    ```

- 练习5：

  - ```java
    public class Homework05 { 
    	public static void main(String[] args) {
    		Circle circle = new Circle(3);
    		System.out.println("面积=" + circle.area());
    		System.out.println("周长=" + circle.len());
    	}
    }
    /*问题描述：
    	定义一个圆类Circle, 定义属性：半径，提供显示圆周长功能的方法， 提供显示圆面积的方法	*/
    class Circle {
    	double radius;
    
    	public Circle(double radius) {	//有参构造器
    		this.radius = radius;
    	}
    
    	public double area() { //面积
    		return Math.PI * radius * radius;
    	}
    
    	public double len() { //周长
    		return 2 * Math.PI * radius;
    	}
    }
    ```

- 练习6：

  - ```java
    public class Homework06 { 
    	public static void main(String[] args) {
    		Cale cale = new Cale(2, 10);
    		System.out.println("和=" + cale.sum());
    		System.out.println("差=" + cale.minus());
    		System.out.println("乘=" + cale.mul());
    		Double divRes = cale.div();
    		if(divRes != null) {
    			System.out.println("除=" + divRes);
    		} 
    	}
    }
    
    /*问题描述：
         编程创建一个Cale计算类，在其中定义2个变量表示两个操作数，
         定义四个方法实现求和、差、乘、商(要求除数为0的话，要提示) 并创建两个对象，分别测试 	*/
    
    class Cale {
    	double num1;
    	double num2;
        
    	public Cale(double num1, double num2) {
    		this.num1 = num1;
    		this.num2 = num2;
    	}
        
    	//和
    	public double sum() {
    		return num1 + num2;
    	}
        
    	//差
    	public double minus() {
    		return num1 - num2;
    	}
        
    	//乘积
    	public double mul() {
    		return num1 * num2;
    	}
        
    	//除法
    	public Double div() {
    		//判断
    		if(num2 == 0) {
    			System.out.println("除数 num2 不能为0");
    			return null;	//这里没有合适的数字可以返回，只好返回null，用包装类作返回值
    		} else {
    			return num1 / num2;
    		}
    	}
    }
    ```

- 练习7：

  - ```java
    public class Test {   //公有类
        int count = 9; //属性
        public void count1() { 	//Test类的成员方法
     			count = 10;//这个count就是属性  改成 10
            	System.out.println("count1 = " + count); //10  
        }
        public void count2() {  //Test类的成员方法
            System.out.println("count1 = " + count++);
        } 
       
       	//这是Test类的main方法, 任何一个类，都可有main
        public static void main(String args[]) {
           /*解读:
               1.  new Test()	是匿名对象， 匿名对象使用后，就不能使用
               2.  new Test().count1() 创建好匿名对象后, 就调用count1()	*/
           new Test().count1(); 	//10
          
           Test t1 = new Test();
           t1.count2();	//9
           t1.count2();	//10
        }
    }
    ```

- 练习8：

  - ```java
    public class Homework08 { 
    	public static void main(String[] args) {
    		Music music = new Music("笑傲江湖", 300);
    		music.play();
    		System.out.println(music.getInfo());
    	}
    }
    /*题目描述：
    	定义Music类，里面有音乐名name、音乐时长times属性，并有播放play功能和返回本身属性信息的功能方法getInfo		*/
    class Music {
    	String name;
    	int times;
    	public Music(String name, int times) {
    		this.name = name;
    		this.times = times;
    	}
    	//播放play功能
    	public void play() {
    		System.out.println("音乐 " + name + " 正在播放中.... ，时长为 " + times + " 秒");
    	}
    	//返回本身属性信息的功能方法getInfo
    	public String getInfo() {	//返回的是字符串
    		return "音乐 " + name + " 播放时间为 " + times;
    	}
    
    }
    ```

- 练习9：

  - ```java
    public class Homework09{ 
    	public static void main(String[] args) {
    	}
    }
    
    class Demo{
    	int i = 100;
    	public void m(){
    		int j = i++; 
    		System.out.println("i = " + i);	//101
    		System.out.println("j = " + j);	//100
    	}
    }
    class Test{
    	public static void main(String[] args){	//运行它
    		Demo d1 = new Demo();
    		Demo d2 = d1;
    		d2.m();
    		System.out.println(d1.i);
    		System.out.println(d2.i);	
    	}
    }
    
    ```

- 练习10：

  - ```java
    public class Homework10 { 
    	public static void main(String[] args) {
    	}
    }
    /*题目描述：
        创建一个Employee类，属性有(名字，性别，年龄，职位，薪水)， 提供3个构造方法，可以初始化  
        (1) (名字，性别，年龄，职位，薪水), 
        (2) (名字，性别，年龄) 
        (3) (职位，薪水), 要求充分复用构造器  	 */
    class Employee {
    	//名字，性别，年龄，职位，薪水
    	String name;
    	char gender;
    	int age;
    	String job;
    	double sal;
    	//因为要求可以复用构造器，因此先写属性少的构造器
    	//职位，薪水
    	public Employee(String job, double sal) {
    		this.job = job;
    		this.sal = sal;
    	}
    	//名字，性别，年龄
    	public Employee(String name, char gender, int age) {
    		this.name = name;
    		this.gender = gender;
    		this.age = age;
    	}
    	//名字，性别，年龄，职位，薪水
    	public Employee(String job, double sal, String name, char gender, int age) {
    		this(name, gender, age);//使用到 前面的 构造器
    		this.job = job;
    		this.sal = sal;
    	}
    	
    
    }
    ```

  - 注意：在Java中，一个构造器可以调用同一个类中的其他构造器，但是一次只能调用一个构造器。Java语言规范不支持在一个构造器调用语句中同时调用多个构造器

- 练习11：

  - ```java
    public class Homework13 { 
    	public static void main(String[] args) {
    		Circle c = new Circle();
    		PassObject po = new PassObject();
    		po.printAreas(c, 5);
    	}
    }
    
    /*题目要求：
        (1) 定义一个Circle类，包含一个double型的radius属性代表圆的半径，findArea()方法返回圆的面积。
        (2) 定义一个类PassObject，在类中定义一个方法printAreas()，该方法的定义如下：
             public void printAreas(Circle c, int times) 	//方法签名/声明
        (3) 在printAreas方法中打印输出1到times之间的每个整数半径值，以及对应的面积。例如，times为5，则输出半径1，2，		3，4，5，以及对应的圆面积。
        (4) 在main方法中调用printAreas()方法，调用完毕后输出当前半径值。程序运行结果如图所示	 */
    class Circle { //类
    	double radius;//半径
    	public Circle() { //无参构造器
    
    	}
    	public Circle(double radius) {	//有参构造器
    		this.radius = radius;
    	}
    	public double findArea() {//返回面积
    		return Math.PI * radius * radius;
    	}
    	//添加方法setRadius, 修改对象的半径值
    	public void setRadius(double radius) {
    		this.radius = radius;
    	}
    }
    class PassObject {
    	public void printAreas(Circle c, int times) {
    		System.out.println("radius\tarea");
    		for(int i = 1; i <= times; i++) {//输出1到times之间的每个整数半径值
    			c.setRadius(i) ; //修改c 对象的半径值	//为了多次复用同一个Circle对象，而不是每次都创建一个新的
    			System.out.println((double)i + "\t" + c.findArea());
    		}
    	}
    }
    ```

- 练习12：

  - ```java
    import java.util.Random;                                                                              
    import java.util.Scanner;                                                                             
                                                                                                          
    /*题目描述：                                                                                                 
    请编写一个猜拳的游戏，有个人 Tom，设计他的成员变量. 成员方法, 可以电脑猜拳. 电脑每次都会随机生成 0, 1, 2            0 表示 石头 1 表示剪刀 2 表示 布                                                                             并要可以显示 Tom的输赢次数（清单）, 假定 玩三次.      */ 
     // 测试类,主类
    public class MoraGame {                                                                                             public static void main(String[] args) {                                                          
            // 创建一个玩家对象                                                                                   
            Tom t = new Tom(); 
        
            // 用来记录最后输赢的次数                                                                             
            int isWinCount = 0;                                                                           
                                                                                                          
            // 创建一个二维数组，用来接收局数、Tom出拳情况、电脑出拳情况                
            int[][] arr1 = new int[3][3];                                                                 
            int j = 0;                                                                                    
                                                                                                          
            // 创建一个一维数组，用来接收输赢情况                                                              
            String[] arr2 = new String[3];                                                                
                                                                                                          
            Scanner scanner = new Scanner(System.in);                                                     
            for (int i = 0; i < 3; i++) {   //比赛3次                                                              
                // 获取玩家出的拳                                                                                
                System.out.println("请输入你要出的拳（0-拳头，1-剪刀，2-布）：");                                           
                int num = scanner.nextInt();                                                              
                t.setTomGuessNum(num);   //设置玩家选择                                                                 
                int tomGuess = t.getTomGuessNum();                                                        
                arr1[i][j + 1] = tomGuess;                                                                
                                                                                                          
                // 获取电脑出的拳                                                                                
                int comGuess = t.computerNum();                                                           
                arr1[i][j + 2] = comGuess;                                                                
                                                                                                          
                // 将玩家猜的拳与电脑做比较                                                                           
                String isWin = t.vsComputer();                                                            
                arr2[i] = isWin;                                                                          
                arr1[i][j] = t.count;                                                                     
                                                                                                          
                // 对每一局的情况进行输出                                                                            
               System.out.println("=========================================");                           
                System.out.println("局数\t玩家的出拳\t电脑的出拳\t输赢情况");                                             
                System.out.println(t.count + "\t" + tomGuess + "\t\t" + comGuess + "\t\t" + t.vsComputer());
                System.out.println("=========================================");                          
                System.out.println("\n\n");                                                               
                isWinCount = t.winCount(isWin);                                                           
            }                                                                                             
                                                                                                          
            // 对游戏的最终结果进行输出                                                                     
        	System.out.println("局数\t玩家的出拳\t电脑的出拳\t\t输赢情况");                                               
            for (int a = 0; a < arr1.length; a++) {                                                       
                for (int b = 0; b < arr1[a].length; b++) {                                                
                    System.out.print(arr1[a][b] + "\t\t\t");                                              
                }                                                                                         
                                                                                                          
                System.out.print(arr2[a]);                                                                
                System.out.println();                                                                     
            }                                                                                             
            System.out.println("你赢了" + isWinCount + "次");                                                 
        }                                                                                                 
                                                                                                          
    }                                                                                                     
    
    // Tom类
    class Tom {     // 核心代码  
    	// 玩家出拳的类型 
        int tomGuessNum; //0,1,2
    	// 电脑出拳的类型
        int comGuessNum; //0,1,2
    	// 玩家赢的次数
        int winCountNum;  
    	// 比赛的次数
        int count = 1;   //一共比赛3次     
    	
    	public void showInfo() {
    		//....
    	}
    	
        //电脑随机生成猜拳的数字的方法              
        public int computerNum() {                                                                        
            Random r = new Random();                                                                      
            comGuessNum = r.nextInt(3);      // 方法 返回 0-2的随机数                                                             
            // System.out.println(comGuessNum);                                                           
            return comGuessNum;                                                                           
        }                                                                                                 
                                                                                                          
        //设置玩家猜拳的数字的方法                                                                       
        public void setTomGuessNum(int tomGuessNum) {                                                     
            if (tomGuessNum > 2 || tomGuessNum < 0) { 
    			//抛出一个异常, 李同学会写，没有处理
                throw new IllegalArgumentException("数字输入错误");                                             
            }                                                                                             
            this.tomGuessNum = tomGuessNum;                                                               
        }                                                                                                 
                                                                                                          
        public int getTomGuessNum() {                                                                     
            return tomGuessNum;                                                                           
        }                                                                                                 
                                                                                                          
        //比较猜拳的结果   
        public String vsComputer() { 
    		 //比较巧
            if (tomGuessNum == 0 && comGuessNum == 1) {	//0表示石头、1表示剪刀、2表示布                      
                return "你赢了";                                                                             
            } else if (tomGuessNum == 1 && comGuessNum == 2) {                                            
                return "你赢了";                                                                             
            } else if (tomGuessNum == 2 && comGuessNum == 0) {                                            
                return "你赢了";                                                                             
            } else if (tomGuessNum == comGuessNum){                                                       
                return "平手";                                                                              
            } else {                                                                                      
                return "你输了";                                                                             
            }                                                                                             
        }                                                                                                 
                                                                                                          
       // 记录玩家赢的次数                                                                                       
       public int winCount(String s) {                                                                   
            count++;    //控制玩的次数
            if (s.equals("你赢了")) {     //统计赢的次数
                winCountNum++;                                                                            
            }                                                                                             
            return winCountNum;                                                                           
        }                                                                                                      
    }                                                                                                      
    ```

### （七）面向对象编程中级

#### 1.IDE- IDEA

- IDEA（集成开发环境） 介绍
  1) IDEA 全称 IntelliJ IDEA
  2) 在业界被公认为最好的Java开发工具
  3) IDEA 是 JetBrains 公司的产品，总部位于捷克的首都布拉格
  4) 除了支持 Java 开发，还支持 HTML，CSS，PHP，MySQL，Python 等

#### 2.IDE-Eclipse

- Eclipse 介绍
  1) Eclipse 是一个开放源代码的、基于 Java 的可扩展开发平台
  2) 最初是由 IBM 公司耗资 3000 万美金开发的下一代 IDE 开发环境
  3) 2001 年 11 月贡献给开源社区
  4) Eclipse 是目前最优秀的 Java 开发 IDE 之一

#### 3.IDE-IDEA 的使用

- IDEA 的安装：
  - 官网: https://www.jetbrains.com/
- 注：IDEA 2020.1.2 最高只支持 JDK14，无法支持 JDK17，必须下载 JDK8，并更改相关IDEA的JDK相关设置

##### IDEA使用技巧

- 设置字体：
  - 菜单大小：File、Settings、Appearance & Behavior、Appearance、Size...
  - 代码大小：File、Settings、Editor、Font、Size
- ...（都可以百度）
- 字符编码：
  - File、Editor、File Encodeings、（默认：UTF-8）

##### 练习项目、以及常用快捷键

- 使用 IDEA 开发一个 java 项目 testpro01，创建一个类 MyTools, 编写一个方法，可以完成对 int 数组冒泡排序的功能， 使用快捷键的开发项目

- 示例：

  - ```java
    public class ArrayTest {
        //使用模板：main+回车 可以直接完成
        public static void main(String[] args) {
            MyTools mt = new MyTools();
            int[] arr = {10, -5, 8, 9, 25};
            mt.bubble(arr); //引用传递
            //输出排序后的arr
            System.out.println("排序后的arr:"); //快捷键：sout+回车
            for(int i = 0; i < arr.length; i++) {
                System.out.print(arr[i] + "\t");
            }
            //注意：在IDEA中，run一个文件时，会先自动编译成 .class 文件，再运行
        }
    }
    
    //创建一个类MyTools，编写一个方法，可以完成对int数组冒泡排序的功能
    //要求从小到大
    class MyTools{
        public void bubble(int[] arr){
            //冒泡排序
            int temp = 0;
            for(int i = 0; i < arr.length - 1; i++){
                for(int j = 0; j < arr.length - 1 -i; j++){
                    if(arr[j] > arr[j + 1]){
                        temp = arr[j];
                        arr[j] = arr[j + 1];
                        arr[j + 1] = temp;
                    }
                }
            }
        }
    }
    ```

- IDEA的项目的文件夹中：

  - src 文件夹存放源码
  - out 文件夹存放编译过后的 .class 文件

- IDEA常用快捷键：

  1. 删除当前行：修改为 ctrl + d （原默认为：ctrl + Y）

  2. 复制当前行：修改为 ctrl + alt + 下

  3. 补全代码：alt + /

  4. 添加注释和取消注释：ctrl + / 

     - 第一次是添加注释，第二次是取消注释

  5. 导入该行需要的类：

     - 先配置，auto import：File、Editor、General、Auto Inport、勾选两个选项

     - 然后使用：alt+enter 即可

  6. 快速格式化代码：ctrl + alt + L

  7. 快速运行程序：自定义为：alt + R

  8. 生成构造器等：alt + insert

     - ctrl 加点击，选择其他构造器选项

  9. 查看一个类的层级关系（继承时使用）：ctrl + H

  10. 定位到方法：将光标放在一个方法，输入：ctrl + B

  11. 自动的分配变量名 , 通过在后面加 `.var` 

  12. 全部展开：`ctrl + shift + "+"`

  13. 全部折叠：`ctrl + shift + "-"`

  14. 打开 structure 窗口：alt + 上方数字7

- 设置快捷键：

  - File、Settings、Keymap ... （搜索）

##### 模板

- 模板（template）
- 查看模板：
  - File、Settings、editor、Live templates
- 常用模板：
  - sout：`System.out.println();`
  - fori：生成基本 for 循环框架
  - main：生成主输出模板

#### 4.包

##### 包的作用

1. 区分相同的名字的类
2. 当类很多时，可以很好的管理类
3. 控制访问范围

##### 包的基本语法

- `package com.zzxedu`
- 说明：
  - package：关键字，表示打包
  - com.zzxedu：表示包名

##### 包的本质

- 包的本质就是创建不同的文件夹 / 目录来保存类文件

##### 包的命名

- 包的命名规则：
  - 只能包含数字、字母、下划线，但不能用数字开头，只能是关键字或保留字
- 包的命名规范：
  - 一般是小写字母 + 小圆点
  - 一般是：`com.公司名.项目名.业务模块名`
  - 例如：
    - `com.sina.crm.user	//sina公司、crm项目、user模块`

##### 常用的包

- `java.lang.*`
  - lang 包是基本包，默认引入，不需要再引入. 
- `java.util.*`
  - util 包，系统提供的工具包，工具类，使用 Scanner
- `java.net.*`
  - 网络包，网络开发
- `java.awt.*`
  - 是做 java 的界面开发，GUI

##### 如何引入包

- 语法：

  - `import 包;`

- 引入一个包的目的是：使用该包下的类。例如：

  - `import java.util.Scanner`：就只是引入 java.util 包下的一个类 Scanner
    - 推荐使用，需要使用哪个类，就导入哪个类
  - `import java.util.*`：就是将 java.util 包全部引入

- 示例：

  - ```java
    package com.zzxedu.pkg;
    
    //练习如何引入包
    //import java.util.Scanner;   //就只是引入 java.util 包下的一个类 Scanner
    //import java.util.*; //就是将 java.util 包全部引入（导入）
    
    import java.util.Arrays;    //自动引入
    
    public class Inport01 {
        public static void main(String[] args) {
            //使用系统提供的 Arrays 完成数组排序
            int[] arr = {-1, 2, 13, 25, 4};
            //可以自己编写排序
            //也可以使用系统提供的相关类 Arrays
            Arrays.sort(arr);
            for (int i = 0; i < arr.length; i++) {
                System.out.print(arr[i] + "\t");
            }
        }
    }
    ```

##### 包的注意实现和细节

1. package 的作用是声明当前类所在的包，需要放在类的最上面，一个类中最大只有一句 package
2. import 指令放在 package 下面，在类定义的前面，可以有多条且没有顺序要求

- 示例：

  - ```java
    //package 的作用是声明当前类所在的包，需要放在类的最上面，一个类中最大只有一句 package
    package com.zzxedu.pkg;
    
    //import 指令放在 package 下面，在类定义的前面，可以有多条且没有顺序要求
    import java.util.Arrays;
    import java.util.Scanner;
    
    public class PackageDetail {
        public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);
            int[] arr = {1, 2, 3};
            Arrays.sort(arr);
        }
    }
    ```

#### 5.访问修饰符（？？？存疑）

##### 基本介绍

- java 提供四种访问控制修饰符号，用于控制方法和属性（成员变量）的访问权限（范围）:

  1) public：公开级别，对外公开
  2) protected：受保护级别，对子类和同一个包中的类公开
  3) 没有修饰符号：默认级别，向同一个包的类公开（同一个包的子类可以访问，而其他包中的类和子类不可访问）
  4) private：私有级别，只有类本身可以访问，不对外公开

- 4 种访问修饰符的访问范围：

  - | 访问级别 | 访问修饰符 | 同类 | 同包 | 不同包的子类 | 不同包的非子类 |
    | -------- | ---------- | ---- | ---- | ------------ | -------------- |
    | 公开     | public     | √    | √    | √            | √              |
    | 受保护   | protected  | √    | √    | √            | ×              |
    | 默认     | 无         | √    | √    | ×            | ×              |
    | 私有     | private    | √    | ×    | ×            | ×              |

##### 访问修饰符的注意事项

1. 修饰符可以用来修饰类中的属性，成员方法以及类
2. 只有默认的和 public 才能修饰类，并且遵循上述访问权限的特点
3. 关于子类的访问权限 ...，在学习子类之后再详细展开
4. 成员方法的访问规则和属性完全一样

- 示例：

  - ```java
    package com.zzxedu.modifier;
    
    public class A {
        //四个属性
        public int n1 = 100;
        protected int n2 = 200;
        int n3 = 300;
        private int n4 = 400;
        public void m1(){
            //该方法可以访问四个属性（在同一个类中，四种属性都可以访问）
            System.out.println("n1 = " + n1 + " n2 = " + n2 + " n3 = " + n3 + " n4 = " + n4);
        }
    }
    ```

  - ```java
    package com.zzxedu.modifier;
    
    //与A在同一个包,不是同一个类，可以访问 public、protected、默认，不能访问 private
    public class B {
        public void say(){
            A a = new A();
            //这里 n4 会有红色提示
            System.out.println("n1 = " + a.n1 + " n2 = " + a.n2 + " n3 = " + a.n3);
        }
    }
    ```

  - ```java
    package com.zzxedu.modifier;
    
    public class Test {
        public static void main(String[] args) {
            A a = new A();
            a.m1();
            B b = new B();
            b.say();
        }
    }
    ```

  - ```java
    package com.zzxedu.pkg;
    
    import com.zzxedu.modifier.A;
    
    public class Test { //与A类不同类不同包
        public static void main(String[] args) {
            A a = new A();
            System.out.println(a.n1);   //在不同包下，只能访问到public修饰的属性或方法
        }
    }
    ```

#### 6.面向对象编程三大特征

##### 基本介绍

- 面向对象编程有三大特征：封装、继承和多态

##### 封装的介绍

- 封装（encapsulaton）：就是把抽象出的数据（属性）和对数据的操作（方法）封装在一起，数据被保护在内部，程序的其他部分只有通过被授权的操作（方法），才能对数据进行操作

##### 封装的好处

1. 隐藏实现细节
2. 可以对数据进行验证，保证安全合理

##### 封装实现的步骤

1. 将属性进行私有化 private（不能直接修改属性）

2. 提供一个公共的（public） set() 方法，用于对属性判断并赋值

   - ```java
     public void setXxx(类型 参数名){
         //加入数据验证的业务逻辑
         属性 = 参数名;
     }
     ```

3. 提供一个公共的 get() 方法，用于获取属性的值

   - ```java
     public Xx getXxx(){	//权限判断
         return Xx;
     }
     ```

##### 快速入门案例

- 要求：

  - 实现一个小程序，不能随便查看人的年龄、工资等隐私，并对设置的年龄进行合理的验证。年龄合理就设置，否则给默认
  - 年龄：必须在 1~120
  - 年龄、工资，不能直接查看
  - name 的长度在 2~6 字符
  - 补充：将 构造器 和 set 相结合

- 示例：

  - ```java
    package com.hspedu.encap;
    
    public class Encapsulation01 {
        public static void main(String[] args) {
            //如果要使用快捷键alt+r, 需要先配置主类
            //第一次，我们使用鼠标点击形式运算程序，后面就可以用
            Person person = new Person();
            person.setName("韩顺平");
            person.setAge(30);
            person.setSalary(30000);
            System.out.println(person.info());
            System.out.println(person.getSalary());
    
            //如果我们自己使用构造器指定属性
            Person smith = new Person("smith", 80, 50000);	//若需要去掉提示，也有方法可以去掉
            System.out.println("smith的信息：");
            System.out.println(smith.info());
        }
    }
    /*题目要求：
        实现小程序，不能随便查看人的年龄,工资等隐私，并对设置的年龄进行合理的验证。
        年龄合理1-120就设置，否则给默认
        年龄、工资不能直接查看
        name的长度在 2-6字符 之间 */
    
    class Person {
        public  String name; //名字公开
        private int age; //age 私有化
        private double salary; //..
    
        public void say(int n,String name) {
    
        }
    
        //无参构造器 alt+insert
        public Person() {
        }
    
        //有三个属性的构造器
        public Person(String name, int age, double salary) {
            //this.name = name;
            //this.age = age;
            //this.salary = salary;
            //我们可以将set方法写在构造器中，这样仍然可以验证
            setName(name);
            setAge(age);
            setSalary(salary);
        }
    
        //自己写setXxx 和 getXxx 太慢。
        // 使用快捷键：Alt + Insert, 选 Getter And Setter
        //如何再根据要求进行进一步补全
    
        //姓名
        //注意：数组的length是属性，使用时不加小括号；字符串的length是方法，使用时要加小括号
        public String getName() {
            return name;
        }
        public void setName(String name) {
            //加入对数据的校验,相当于增加了业务逻辑
            if(name.length() >= 2 && name.length() <=6 ) {
                this.name = name;
            }else {
                System.out.println("名字的长度不对，需要(2-6)个字符，默认名字");
                this.name = "无名";
            }
        }
    
        //年龄
        public int getAge() { return age; }
        public void setAge(int age) {
            //判断
            if(age >= 1 && age <= 120) {//如果是合理范围
                this.age = age;
            } else {
                System.out.println("你设置年龄不对，需要在 (1~120), 自动设为默认年龄18 ");
                this.age = 18;//给一个默认年龄
            }
        }
    
        //薪水
        public double getSalary() {
            //可以这里增加对当前对象的权限判断
            return salary;
        }
    
        public void setSalary(double salary) {
            this.salary = salary;
        }
    
        //写一个方法，返回属性信息
        public String info() {
            return "信息为：name = " + name  + " age = " + age + " 薪水 = " + salary;
        }
    }
    
    ```

##### 封装练习

- 题目要求：

  - 创建程序，在其中定义两个类：Account 和 AccountTest 类
    * Account 类要求具有属性：
      * 姓名：长度为 2位、3位 或 4位
      * 余额：必须 > 20
      * 密码：必须是六位，如果不满足，则给出提示信息，并给默认值（程序员自己定）
  - 通过 setXxx 的方法给 Account 的属性赋值
  - 在AccountTest中测试

- 示例：

  - `Account.java`

    - ```java
      package com.hspedu.encap;
      
      /*题目要求：
          创建程序,在其中定义两个类：Account和AccountTest类体会Java的封装性。
              Account类要求具有属性：
                  姓名（长度为2位3位或4位）、
                  余额(必须>20)、
                  密码（必须是六位）, 如果不满足，则给出提示信息，并给默认值(程序员自己定)
          通过setXxx的方法给Account 的属性赋值。
          在AccountTest中测试       */
      public class Account {
          //为了封装，将3个属性设置为private
          private String name;
          private double balance;
          private String pwd;
      
          //提供两个构造器
          public Account() {
          }
      
          public Account(String name, double balance, String pwd) {
              this.setName(name);
              this.setBalance(balance);
              this.setPwd(pwd);
          }
      
          //姓名（长度为2位3位或4位）
          public String getName() {
              return name;
          }
          public void setName(String name) {
              if (name.length() >= 2 && name.length() <= 4) {
                  this.name = name;
              } else {
                  System.out.println("姓名要求（长度为2位3位或4位），默认值：无名");
                  this.name = "无名";
              }
          }
      
          //余额(必须>20)
          public double getBalance() {
              return balance;
          }
          public void setBalance(double balance) {
              if (balance > 20) {
                  this.balance = balance;
              } else {
                  System.out.println("余额(必须 > 20)，默认为0");
              }
          }
      
          //密码（必须是六位）
          public String getPwd() {
              return pwd;
          }
          public void setPwd(String pwd) {
              if (pwd.length() == 6) {
                  this.pwd = pwd;
              } else {
                  System.out.println("密码（必须是六位），默认密码为 000000");
                  this.pwd = "000000";
              }
          }
      
          //显示账号信息
          public void showInfo() {
              //可以增加权限的校验
              System.out.println("账号信息 name：" + name + " 余额：" + balance + " 密码：" + pwd);
      //        if() {
      //            System.out.println("账号信息 name：" + name + " 余额：" + balance + " 密码：" + pwd);
      //        }else{
      //            System.out.println("你无权查看...");
      //        }
          }
      }
      
      ```

  - `AccountText.java`

    - ```java
      package com.hspedu.encap;
      
      public class TestAccount {
          public static void main(String[] args) {
              //创建Account
              Account account = new Account();
              account.setName("jack");
              account.setBalance(60);
              account.setPwd("123456");
              account.showInfo();
      		
              //有参构造，创建account2
              Account account2 = new Account("Tom", 500, "666666");
              account2.showInfo();
          }
      }
      ```

#### 7.继承

##### 为什么需要继承

- 方面：
  - 提高代码复用性
  - 可拓展性
  - 维护性
  - 多态性
  - 抽象和封装

##### 继承基本介绍

- 继承可以解决代码复用，让我们的编程更加靠近人类思维。当多个类存在相同的属性（变量）和方法时，可以从这些类中抽象出父类（基类、超类），在父类中定义这些相同的属性和方法，所有的子类（派生类）不需要重新定义这些属性和方法，只需要通过 extends 来声明继承父类即可

##### 继承的基本语法

- ```java
  class 子类 extends 父类{
      
  }
  ```

  - 子类会拥有父类定义的属性和方法

##### 继承的快速入门案例

- 示例：

  - `Student.java`

    - ```java
      package com.hspedu.extend_.improve_;
      
      //父类,是Pupil 和 Graduate的父类
      public class Student {
          //共有属性
          public String name;
          public int age;
          private double score;   //成绩
      
          //共有的方法
          public void setScore(double score) {
              this.score = score;
          }
          public void showInfo() {
              System.out.println("学生名：" + name + " 年龄：" + age + " 成绩：" + score);
          }
      }
      ```

  - `Pupil.java`

    - ```java
      package com.hspedu.extend_.improve_;
      
      //让Pupil 继承 Student类
      public class Pupil extends Student {
          public void testing() {
              System.out.println("小学生 " + name + "  正在考小学数学..");
          }
      }
      ```

  - `Graduate.java`

    - ```java
      package com.hspedu.extend_.improve_;
      
      public class Graduate extends Student {
          public void testing() { //和Pupil不一样
              System.out.println("大学生 " + name + " 正在考大学数学...");
          }
      }
      ```

  - `Extends01.java`

    - ```java
      package com.hspedu.extend_.improve_;
      
      public class Extends01 {
          public static void main(String[] args) {
              Pupil pupil = new Pupil();
              pupil.name = "银角大王~";
              pupil.age = 11;
              pupil.testing();
              pupil.setScore(50);
              pupil.showInfo();
      
              System.out.println("=======");
              Graduate graduate = new Graduate();
              graduate.name = "金角大王~";
              graduate.age = 23;
              graduate.testing();
              graduate.setScore(80);
              graduate.showInfo();
          }
      }
      
      ```

- 同级包下的类不需要引入

##### 继承使用的细节

1. 子类继承了所有的属性和方法，但是其中只有非私有的属性和方法可以在子类直接访问、私有属性和方法不能在子类直接访问，要通过父类提供公共的方法去访问
2. 子类必须调用父类的构造器， 完成父类的初始化
3. 当创建子类对象时，不管使用子类的哪个构造器，默认情况下总会去调用父类的无参构造器，如果父类没有提供无参构造器，则必须在子类的构造器中用 super 去指定使用父类的哪个构造器完成对父类的初始化工作，否则，编译不会通过
4. 如果希望指定去调用父类的某个构造器，则显式的调用一下 : `super(参数列表)`
5. super 在使用时，必须放在构造器第一行（super 只能在构造器中使用）
6. `super()` 和 `this()` 都只能放在构造器第一行，因此这两个构造方法不能共存在一个构造器
7. java 所有类都是 Object 类的子类, Object 是所有类的基类
8. 父类构造器的调用不限于直接父类！将一直往上追溯直到 Object 类（顶级父类）
9. 子类最多只能继承一个父类（指直接继承），即 java 中是单继承机制
   - 思考：如何让 A 类继承 B 类 和 C 类？ 
     - A 继承 B， B 继承 C
10. 不能滥用继承，子类和父类之间必须满足 is-a 的逻辑关系
    - 子类是父类的一个或一种

- 示例：

  - `TopBase.java`

    - ```java
      package com.hspedu.extend_;
      
      public class TopBase { //父类是Object
      
          public TopBase() {
              //super(); Object的无参构造器
              System.out.println("构造器TopBase() 被调用...");//1
          }
      }
      
      ```

  - `Base.java`

    - ```java
      package com.hspedu.extend_;
      
      public class Base extends TopBase { //父类
          //4个属性
          public int n1 = 100;
          protected int n2 = 200;
          int n3 = 300;
          private int n4 = 400;
      
          public Base() { //无参构造器
              System.out.println("父类Base()构造器被调用....");
          }
          public Base(String name) {  //有参构造器，一个参数
              System.out.println("父类Base(String name)构造器被调用....");
          }
          public Base(String name, int age) { //有参构造器，两个参数
              //默认super()
              System.out.println("父类Base(String name, int age)构造器被调用....");
          }
          //父类提供一个public的方法,返回了n4
          public int getN4() {
              return n4;
          }
          public void test100() {
              System.out.println("test100");
          }
          protected void test200() {
              System.out.println("test200");
          }
          void test300() {
              System.out.println("test300");
          }
          private void test400() {
              System.out.println("test400");
          }
          //call
          public void callTest400() {
              test400();
          }
      }
      ```

  - `Sub.java`

    - ```java
      package com.hspedu.extend_;
      
      import java.util.Arrays;
      
      //输入ctrl + H 可以看到类的继承关系
      public class Sub extends Base { //子类
      
          public Sub() {//无参构造器
              //super(); //默认调用父类的无参构造器
              super("smith", 10);
              System.out.println("子类Sub()构造器被调用....");
          }
          //当创建子类对象时，不管使用子类的哪个构造器，默认情况下总会去调用父类的无参构造器
          public Sub(String name) {
              super("tom", 30);
              //do nothing...
              System.out.println("子类Sub(String name)构造器被调用....");
          }
      
          public Sub(String name, int age) {
              //1. 要调用父类的无参构造器, 如下或者 什么都不写,默认就是调用super()
              //super();//父类的无参构造器
              //2. 要调用父类的 Base(String name) 构造器
              //super("hsp");
              //3. 要调用父类的 Base(String name, int age) 构造器
              super("king", 20);
      
              //细节： super在使用时，必须放在构造器第一行
              //细节: super() 和 this() 都只能放在构造器第一行，因此这两个方法不能共存在一个构造器
              //this() 不能再使用了
              System.out.println("子类Sub(String name, int age)构造器被调用....");
          }
      
          public void sayOk() {//子类方法
              //非私有的属性和方法可以在子类直接访问
              //但是私有属性和方法不能在子类直接访问
              System.out.println(n1 + " " + n2 + " " + n3);
              test100();
              test200();
              test300();
              //test400();    //错误，不能访问私有方法
              //要通过父类提供公共的方法去访问
              System.out.println("n4=" + getN4());    //通过父类提供的公共方法
              callTest400();//
          }
      }
      ```

  - `ExtendsDetail.java`

    - ```java
      package com.hspedu.extend_;
      
      public class ExtendsDetail {
          public static void main(String[] args) {
              System.out.println("===第1个对象====");
              Sub sub = new Sub(); //创建了子类对象 sub
              sub.sayOk();
      
              System.out.println("===第2个对象====");
              Sub sub2 = new Sub("jack"); //创建了子类对象 sub2
      
              System.out.println("===第3对象====");
              Sub sub3 = new Sub("king", 10); //创建了子类对象 sub2
          }
      }
      ```

##### 继承的本质

- 示例：

  - ```java
    package com.hspedu.extend_;
    /**
     * 讲解继承的本质
     */
    public class ExtendsTheory {
        public static void main(String[] args) {
            Son son = new Son();    //内存的布局
            /*要按照查找关系来返回信息：
                (1) 首先看子类是否有该属性
                (2) 如果子类有这个属性，并且可以访问，则返回信息
                (3) 如果子类没有这个属性，就看父类有没有这个属性(如果父类有该属性，并且可以访问，就返回信息..)
                (4) 如果父类没有就按照(3)的规则，继续找上级父类，直到Object...   */
            System.out.println(son.name);   //Son类中有name，返回就是大头儿子
            //System.out.println(son.age);//Son类中没有，Father类中有默认访问权限的age，返回的就是39
            System.out.println(son.getAge());   //Son类中没有，Father类中有，返回的就是39
            System.out.println(son.hobby);  //子类中没有，父类中没有，爷类中有，且访问类型为默认，返回的就是旅游
            //注意：java中不可以像C++中那样通过子类对象加作用域的方式访问父类同名成员
        }
    }
    
    class GrandPa { //爷类
        String name = "爷爷";
        String hobby = "旅游";
    }
    
    class Father extends GrandPa {  //父类
        String name = "爸爸";
        private int age = 39;
    
        public int getAge() {
            return age;
        }
    }
    
    class Son extends Father { //子类
        String name = "儿子";
    }
    ```

##### 继承练习

- 练习1：

  - ```java
    package com.hspedu.extend_.exercise;
    
    public class ExtendsExercise01 {
        public static void main(String[] args) {
            B b = new B();	//a , b name, b
        }
    }
    
    class A {
        A() {
            System.out.println("a");
        }
    
        A(String name) {
            System.out.println("a name");
        }
    }
    
    class B extends A {
        B() {
            this("abc");	//这里有了this，将不需要也不能再提供super
            System.out.println("b");
        }
    
        B(String name) {
            //默认有 super();  //这里调用A的无参构造
            System.out.println("b name");
        }
    }
    ```

- 练习2：

  - ```java
    package com.hspedu.extend_.exercise;
    
    //main方法中： C c = new C(); 输出内容?
    public class ExtendsExercise02 {
        public static void main(String[] args) {
            C c = new C();
            //A、B有参、C有参、C无参
        }
    }
    
    class A {	//A类
        public A() {
            System.out.println("我是A类");
        }
    }
    
    class B extends A { //B类,继承A类
        public B() {
            System.out.println("我是B类的无参构造");
        }
    
        public B(String name) {
            System.out.println(name + "我是B类的有参构造");
        }
    }
    
    class C extends B {   //C类，继承 B类
        public C() {
            this("hello");
            System.out.println("我是c类的无参构造");
        }
    
        public C(String name) {
            super("hahah");
            System.out.println("我是c类的有参构造");
        }
    }
    ```

- 练习3：

  - `ExtendsEcercise03.java`

    - ```java
      package com.hspedu.extend_.exercise;
      
      public class ExtendsExercise03 {
          public static void main(String[] args) {
              PC pc = new PC("intel", 16, 500, "IBM");
              pc.printInfo();
      
              NotePad notePad = new NotePad("HUAWEI", 8, 128, "black");
              notePad.printInfo();
      
          }
      }
      /*题目要求：
          编写Computer类，包含CPU、内存、硬盘等属性，getDetails方法用于返回Computer的详细信息
          编写PC子类，继承Computer类，添加特有属性【品牌brand】
          编写NotePad子类，继承Computer类，添加特有属性【color】//同学们自己写。
          编写Test类，在main方法中创建PC和NotePad对象，分别给对象中特有的属性赋值，
          以及从Computer类继承的属性赋值，并使用方法并打印输出信息        */
      ```

  - `Computer.java`

    - ```java
      package com.hspedu.extend_.exercise;
      
      //编写Computer类，包含CPU、内存、硬盘等属性，getDetails方法用于返回Computer的详细信息
      public class Computer {
          private String cpu;
          private int memory;
          private int disk;
          
          public Computer(String cpu, int memory, int disk) { //Conputer的有参构造
              this.cpu = cpu;
              this.memory = memory;
              this.disk = disk;
          }
          
          //返回Computer信息
          public String getDetails() {
              return "cpu: " + cpu + " memory: " + memory + " disk: " + disk;
          }
      	
          //3组getter、setter
          public String getCpu() {
              return cpu;
          }
      
          public void setCpu(String cpu) {
              this.cpu = cpu;
          }
      
          public int getMemory() {
              return memory;
          }
      
          public void setMemory(int memory) {
              this.memory = memory;
          }
      
          public int getDisk() {
              return disk;
          }
      
          public void setDisk(int disk) {
              this.disk = disk;
          }
      }
      ```

  - `PC.java`

    - ```java
      package com.hspedu.extend_.exercise;
      
      //编写PC子类，继承Computer类，添加特有属性【品牌brand】
      
      public class PC extends Computer{
      
          private String brand;
          //这里IDEA 根据继承的规则，自动把构造器的调用写好
          //这里也体现,继承设计的基本思想:
          //父类的构造器完成父类属性初始化
          //子类的构造器完成子类属性初始化
          public PC(String cpu, int memory, int disk, String brand) {
              super(cpu, memory, disk);   //父类没有无参构造器，则必须手动指定有参构造器
              this.brand = brand;
          }
          public String getBrand() {
              return brand;
          }
          public void setBrand(String brand) {
              this.brand = brand;
          }
          public void printInfo() {
              System.out.println("PC信息：");
              //第一种方法：System.out.println(getCpu() + getMemory() + getDisk());
              //第二种方法：也可以调用父类的getDetails方法，得到相关属性信息..
              System.out.println(getDetails() + " brand:" + brand);
          }
      }
      ```

  - `NotePad.java`

    - ```java
      package com.hspedu.extend_.exercise;
      
      public class NotePad extends Computer {
          private String color;
      
          public NotePad(String cpu, int memory, int disk, String color) {
              super(cpu, memory, disk);
              this.color = color;
          }
      
          public String getColor() {
              return color;
          }
      
          public void setColor(String color) {
              this.color = color;
          }
      
          public void printInfo() {
              System.out.println("NotePad信息：");
              //System.out.println(getCpu() + getMemory() + getDisk());
              //调用父类的getDetails方法，得到相关属性信息..
              System.out.println(getDetails() + " color:" + color);
          }
      }
      ```

#### 8.super 关键字

##### 基本介绍

- super 代表父类的引用，用于访问父类的 属性、方法、构造器

##### 基本语法

1. 访问父类的属性，但不能直接访问父类的 private 属性
   - `super.父类属性名`
2. 访问父类的方法，但不能访问父类的 private 方法
   - `super.父类方法名(参数列表)`
3. 访问父类的构造器
   - `super(参数列表);	//只能放在构造器第一句，只能出现一句`

##### 细节演示

- super 给编程带来的遍历，以及它的细节：

  1. 调用父类构造器的好处：分工明确，父类属性由父类初始化，子类属性由子类初始化
  2. 当子类中有和父类中的成员（属性和方法）重名时，为了访问父类的成员，必须通过super。如果没有重名，使用 super、this、直接访问 是一样的效果
  3. super 的访问不限于直接父类，如果爷爷类和本类，也可以使用 super 去访问爷爷类中的成员；如果多个上级类中有同名成员，采用就近原则

- 示例：

  - `Base.java`
  
    - ```java
      package com.hspedu.super_;
      
      public class Base { //父类是Object
      
          public int n1 = 999;
          public int age = 111;
          public void cal() {
              System.out.println("Base类的cal() 方法...");
          }
          public void eat() {
              System.out.println("Base类的eat().....");
          }
      }
      ```
  
  - `A.java`
  
    - ```java
      package com.hspedu.super_;
      
      public class A extends Base{
          //4个属性
          public int n1 = 100;
          protected int n2 = 200;
          int n3 = 300;
          private int n4 = 400;
      
          public A() {}   //无参
          public A(String name) {}    //有参，一个
          public A(String name, int age) {}   //有参，两个
      
          public void test100() {
          }
      
          protected void test200() {
          }
      
          void test300() {
          }
      
          private void test400() {
          }
      
          public void cal() {
              System.out.println("A类的cal() 方法...");
          }
      }
      ```
  
  - `B.java`
  
    - ```java
      package com.hspedu.super_;
      
      public class B extends A {
      
          public int n1 = 888;
      
          //访问父类的属性 , 但不能访问父类的 private 属性
          //super.属性名
          public void hi() {
              System.out.println(super.n1 + " " + super.n2 + " " + super.n3 );
          }
      
          //访问父类的方法，不能访问父类的 private 方法
          //super.方法名(参数列表);
          public void ok() {
              super.test100();
              super.test200();
              super.test300();
              //super.test400();//不能访问父类private方法
          }
      
          //访问父类的构造器(这点前面用过)：super(参数列表)
          //只能放在构造器的第一句，只能出现一句！
          public  B() {
              //super();
              //super("jack", 10);
              super("jack");
          }
      
          public void cal() {
              System.out.println("B类的cal() 方法...");
          }
      
          public void sum() {
              System.out.println("B类的sum()");
              //希望调用父类A 的cal方法
              //这时，如果子类B没有cal方法，可以使用下面三种方式
      
              //方式一：cal()   或    this.cal()
              /*寻找顺序是:
                   (1)先找本类，如果有，则调用
                   (2)如果没有，则找父类(如果有，并可以调用，则调用)
                   (3)如果父类没有，则继续找父类的父类,整个规则，就是一样的,直到 Object类    */
              /* 提示：如果查找方法的过程中，找到了，但是不能访问， 则报错, cannot access
                     如果查找方法的过程中，没有找到，则提示方法不存在        */
              cal();
              this.cal(); //等价 cal
      
              //找cal方法(super.call()) 的顺序是直接查找父类，其他的规则一样
              super.cal();
      
              //演示访问属性的规则
              /*n1 和 this.n1 查找的规则是：
                  (1) 先找本类，如果有，则调用
                  (2) 如果没有，则找父类(如果有，并可以调用，则调用)
                  (3) 如果父类没有，则继续找父类的父类,整个规则，就是一样的,直到 Object类
                   提示：如果查找属性的过程中，找到了，但是不能访问， 则报错, cannot access
                        如果查找属性的过程中，没有找到，则提示属性不存在        */
              System.out.println(n1);
              System.out.println(this.n1);
      
              //找n1 (super.n1) 的顺序是直接查找父类属性，其他的规则一样
              System.out.println(super.n1);
          }
      
          //编写测试方法
          public void test() {
              //细节3：super的访问不限于直接父类，如果爷爷类和本类中有同名的成员，也可以使用super去访问爷爷类的成员；
              //      如果多个基类(上级类)中都有同名的成员，使用super访问遵循就近原则。A->B->C
      
              System.out.println("super.n1=" + super.n1);
              super.cal();
              super.eat();
          }
      }
      ```
  
  - `Super01.java`
  
    - ```java
      package com.hspedu.super_;
      
      public class Super01 {
          public static void main(String[] args) {
              B b = new B();//子类对象
              b.sum();
              b.test();
          }
      }
      ```

#### 9.方法重写 / 覆盖

##### 方法重写基本介绍

- 简单的说，方法重写就是子类有一个方法，和父类的某个方法的名称、返回类型、参数一样，那么我们就说子类的这个方法重写了父类的方法

##### 方法重写的注意事项和细节

1. 子类的方法的形参列表、方法名称，要和父类方法的形参列表、方法名称完全一样
2. 子类方法的返回类型和父类方法返回类型一样，或者是父类返回类型的子类
3. 子类方法不能缩小父类方法的访问权限

##### 快速入门

- 示例：

  - `Override01.java`

    - ```java
      package com.hspedu.override_;
      
      public class Override01 {
          public static void main(String[] args) {
              //演示方法重写的情况
              Dog dog = new Dog();
              dog.cry();  //ctrl+b
          }
      }
      ```

  - `Animal.java`

    - ```java
      package com.hspedu.override_;
      
      public class Animal {
          public void cry() {
              System.out.println("动物叫唤..");
          }
      
          public Object m1() {
              return null;
          }
      
          public String m2() {
              return null;
          }
      
          public AAA m3() {
              return null;
          }
          protected void eat() {
      
          }
      }
      ```

  - `Dog.java`

    - ```java
      package com.hspedu.override_;
      
      public class Dog extends Animal{
          /*解读:
              1. 因为 Dog 是 Animal 子类
              2. Dog 的 cry 方法和 Animal 的 cry 定义形式一样(名称、返回类型、参数)
              3. 这时我们就说 Dog 的 cry 方法，重写了 Animal 的 cry 方法       */
          public void cry() {
              System.out.println("小狗汪汪叫..");
          }
      
          //细节2: 子类方法的返回类型和父类方法返回类型一样，或者是父类返回类型的子类
          //	比如：父类 返回类型是 Object，子类方法返回类型是 String
          public String m1() {
              return null;
          }
          //这里 Object 不是 String 的子类，因此编译错误
      //    public Object m2() {
      //        return null;
      //    }
      
      //    public BBB m3() {
      //        return null;
      //    }
          //细节3: 子类方法不能缩小父类方法的访问权限，但可以放大
          //public > protected > 默认 > private
          public void eat() {
      
          }
      }
      
      class AAA {
      
      }
      
      class BBB extends AAA  {
      
      }
      ```

##### 练习

- 题目要求：

  - 编写一个 Person 类，包括属性（private）（name、age）、构造器、方法 say（返回自我介绍的字符串）
  - 编写一个 Student 类，继承 Person 类，增加属性（ private）（id、score），以及构造器，定义 say 方法返回自我介绍的信息
  - 在 main 中，分别创建 Person 和 Student 对象，调用 say 方法输出自我介绍

- 示例：

  - `Person.java`

    - ```java
      package com.hspedu.override_;
      
      //编写一个Person类，包括属性/private（name、age），构造器、方法say(返回自我介绍的字符串）
      public class Person {
          private String name;
          private int age;
          public Person(String name, int age) {
              this.name = name;
              this.age = age;
          }
          public String say() {
              return "name = " + name + " age = " + age;
          }
          
          public String getName() {
              return name;
          }
          public void setName(String name) {
              this.name = name;
          }
      
          public int getAge() {
              return age;
          }
          public void setAge(int age) {
              this.age = age;
          }
      }
      ```

  - `Student.java`

    - ```java
      package com.hspedu.override_;
      
      //编写一个Student类，继承Person类，增加id、score属性/private，以及构造器，定义say方法(返回自我介绍的信息)。
      public class Student extends Person{
          private int id;
          private double score;
      
          public Student(String name, int age, int id, double score) {
              super(name, age);//这里会调用父类构造器
              this.id = id;
              this.score = score;
          }
          
          //say
          public String say() { //这里体现super的一个好处，代码复用.
              return super.say() + " id = " + id + " score = " + score;
          }
          
          public int getId() {
              return id;
          }
          public void setId(int id) {
              this.id = id;
          }
      
          public double getScore() {
              return score;
          }
          public void setScore(double score) {
              this.score = score;
          }
      }
      ```

#### 10.多态

##### 多态（polymorphic）基本介绍

- 方法或对象具有多种形态。是面向对象的第三大特征，多态是建立在封装和继承基础之上的

##### 多态的具体体现

###### 方法的多态

-  重写 和 重载 就体现多态

- 示例：

  - ```java
    package com.hspedu.poly_;
    
    public class PloyMethod {
        public static void main(String[] args) {
            //方法重载体现多态
            A a = new A();
            //这里我们传入不同的参数，就会调用不同sum方法，就体现多态
            System.out.println(a.sum(10, 20));
            System.out.println(a.sum(10, 20, 30));
    
            //方法重写体现多态
            B b = new B();
            a.say();
            b.say();
        }
    }
    class B { //父类
        public void say() {
            System.out.println("B say() 方法被调用...");
        }
    }
    class A extends B {	//子类
        public int sum(int n1, int n2){	//和下面sum 构成重载
            return n1 + n2;
        }
        public int sum(int n1, int n2, int n3){
            return n1 + n2 + n3;
        }
    
    
        public void say() {
            System.out.println("A say() 方法被调用...");
        }
    }
    ```

###### 对象的多态

- 重点：

  1. 一个对象的编译类型和运行类型可以不一致
  2. 编译类型在定义对象是，就确定了，不能改变
  3. 运行类型是可以变化的
  4. 编译类型看定义时 = 的左边，运行类型看 = 的右边

- 示例：

  - ```java
    package com.hspedu.poly_.objectpoly_;
    
    public class PolyObject {
        public static void main(String[] args) {
            //体验对象多态特点
    
            //animal 编译类型就是 Animal , 运行类型 Dog
            Animal animal = new Dog();
            //因为运行时，执行到该行时，animal运行类型是 Dog，所以 cry 就是 Dog 的 cry
            animal.cry(); //小狗汪汪叫
    
            //animal 编译类型 Animal,运行类型就是 Cat
            animal = new Cat();
            animal.cry(); //小猫喵喵叫
        }
    }
    
    public class Animal {
        public void  cry() {
            System.out.println("Animal cry() 动物在叫....");
        }
    }
    
    public class Dog extends Animal {
        public void cry() {
            System.out.println("Dog cry() 小狗汪汪叫...");
        }
    }
    
    public class Cat extends Animal {
        public void cry() {
            System.out.println("Cat cry() 小猫喵喵叫...");
        }
    }
    ```

##### 多态的注意事项和细节（！！！）

- 多态的前提是：两个对象（类）存在继承关系

- 多态的向上转型：

  - 本质：
    - 父类的引用指向子类的对象
  - 语法：
    - `父类类型 引用名 = new 子类类型();`
  - 特点：
    - 编译类型看左边，运行类型看右边
    - 可以调用父类中的所有成员（需要遵守访问权限）,
    - 不能调用子类特有成员
    - 最终运行效果看子类的具体实现

- 多态的向下转型：

  - 语法：
    - `子类类型 引用名 = (子类类型) 父类引用`
    - 只能强转父类的引用，不能强转父类的对象
    - 要求父类的引用必须指向的是当前目标类型的对象
    - 当向下转型后，可以调用子类类型中的所有成员

- 示例：

  - ```java
    package com.hspedu.poly_.detail_;
    
    public class Animal {
        String name = "动物";
        int age = 10;
        public void sleep(){
            System.out.println("睡");
        }
        public void run(){
            System.out.println("跑");
        }
        public void eat(){
            System.out.println("吃");
        }
        public void show(){
            System.out.println("hello,你好");
        }
    }
    
    public class Cat extends Animal {
        public void eat(){  //方法重写
            System.out.println("猫吃鱼");
        }
        public void catchMouse(){   //Cat特有方法
            System.out.println("猫抓老鼠");
        }
    }
    
    public class Dog extends Animal {//Dog是Animal的子类
    }
    
    public class PolyDetail {
        public static void main(String[] args) {
    
            //向上转型: 父类的引用指向了子类的对象
            //语法：父类类型 引用名 = new 子类类型();
            Animal animal = new Cat();
            Object obj = new Cat(); //可以，因为 Object 也是 Cat 的父类
    
            /*向上转型调用方法的规则如下:
                (1)可以调用父类中的所有成员(需遵守访问权限)
                (2)但是不能调用子类的特有的成员
                (3)因为在编译阶段，能调用哪些成员,是由编译类型来决定的
                   animal.catchMouse();错误
                (4)最终运行效果看子类(运行类型)的具体实现, 即调用方法时，按照从子类(运行类型)开始查找方法
                    ，然后调用，规则与方法调用规则一致。      */
            animal.eat();   //猫吃鱼..
            animal.run();   //跑
            animal.show();     //hello,你好
            animal.sleep(); //睡
    
            //若希望可以调用Cat的 catchMouse方法
            //多态的向下转型
            //语法：子类类型 引用名 =（子类类型）父类引用;
            //问一个问题? cat 的编译类型 Cat,运行类型是 Cat
            Cat cat = (Cat) animal;
            cat.catchMouse();//猫抓老鼠
            //要求父类的引用必须指向的是当前目标类型的对象
            //Dog dog = (Dog) animal; //这里不可以
    
            System.out.println("ok~~");
        }
    }
    ```

- 属性没有重写之说，属性的值看编译类型（而不是看运行类型）

- 示例：

  - ```java
    package com.hspedu.poly_.detail_;
    
    public class PolyDetail02 {
        public static void main(String[] args) {
            //属性没有重写之说！属性的值看编译类型
            
            Base base = new Sub();	//向上转型
            System.out.println(base.count);	//看编译类型 10
            
            Sub sub = new Sub();
            System.out.println(sub.count);	//20
        }
    }
    
    class Base { //父类
        int count = 10;//属性
    }
    
    class Sub extends Base {//子类
        int count = 20;//属性
    }
    ```

- `instanceOf` 比较操作符，用于判断对象的运行类型是否为 XX 类型或 XX 类型的子类型

- 示例：

  - ```java
    package com.hspedu.poly_.detail_;
    
    public class PolyDetail03 {
        public static void main(String[] args) {
            BB bb = new BB();
            System.out.println(bb instanceof  BB);// true
            System.out.println(bb instanceof  AA);// true
    
            AA aa = new AA();
            System.out.println(aa instanceof  BB);// 运行类型为AA，不是BB的子类，flase
            System.out.println(aa instanceof  AA);// true
    
            //aa 编译类型 AA, 运行类型是BB
            //BB是AA子类
            aa = new BB();
            System.out.println(aa instanceof AA);   //运行类型为BB，BB为AA的子类 true
            System.out.println(aa instanceof BB);   //true
    
            Object obj = new Object();
            System.out.println(obj instanceof AA);//false
            String str = "hello";
            //System.out.println(str instanceof AA);    这里为什么报错
            System.out.println(str instanceof Object);//true
        }
    }
    
    class AA {} //父类
    class BB extends AA {}//子类
    ```

##### Java的动态绑定机制

- Java 动态绑定机制：

  - 当调用对象方法时，该方法会和该对象的内存地址 / 运行类型绑定
  - 当调用对象属性时，没有动态绑定机制，哪里声明，哪里使用

- 示例：

  - ```java
    package com.hspedu.poly_.dynamic_;
    
    public class DynamicBinding {
        public static void main(String[] args) {
            //a 的编译类型是 A, 运行类型是 B
            A a = new B();  //向上转型
            System.out.println(a.sum());//40    //30
            System.out.println(a.sum1());//30   //20
        }
    }
    
    class A {//父类
        public int i = 10;
        //动态绑定机制:
    
        public int sum() {//父类sum()
            return getI() + 10; //方法有动态访问机制，调用子类的 getI()方法  20 + 10
        }
    
        public int sum1() { //父类sum1()
            return i + 10;  //属性没有动态绑定机制，使用父类的i 10 + 10
        }
    
        public int getI() {//父类getI
            return i;
        }
    }
    
    class B extends A {//子类
        public int i = 20;
    
        public int getI() {//子类getI()
            return i;
        }
    
    //    public int sum() {
    //        return i + 20;
    //    }
    
    //    public int sum1() {
    //        return i + 10;
    //    }
    }
    ```

##### 多态的应用

###### 多态数组：

- 数组的定义类型为父类类型，里面保存的实际元素类型为子类类型

- 应用实例：

  - 现有一个继承结构如下：要求创建 1 个 Person 对象、2 个 Student 对象和 2 个 Teacher 对象，统一放在数组中，并调用 say 方法

- 应用实例升级：

  - 如何调用子类特有的方法，比如 Teacher 有一个 teach() , Student 有一个 study() 怎么调用

- 示例：

  - ```java
    package com.hspedu.poly_.polyarr_;
    
    public class Person {//父类
        private String name;
        private int age;
    
        public Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public int getAge() {
            return age;
        }
    
        public void setAge(int age) {
            this.age = age;
        }
    
        public String say() {//返回名字和年龄
            return "姓名：" + name + "\t年龄：" + age;
        }
    }
    
    public class Student extends Person {
        private double score;
    
        public Student(String name, int age, double score) {
            super(name, age);   //调用父类有参构造器
            this.score = score;
        }
    
        public double getScore() {
            return score;
        }
    
        public void setScore(double score) {
            this.score = score;
        }
        //重写父类say
    
        @Override
        public String say() {
            return "学生 " + super.say() + "\t成绩:" + score;
        }
        //特有的方法
        public void study() {
            System.out.println("学生 " + getName() + " 正在学java...");
        }
    }
    
    public class Teacher extends Person {
        private double salary;
    
        public Teacher(String name, int age, double salary) {
            super(name, age);
            this.salary = salary;
        }
    
        public double getSalary() {
            return salary;
        }
    
        public void setSalary(double salary) {
            this.salary = salary;
        }
        //写重写父类的say方法
    
        @Override
        public String say() {
            return "老师 " + super.say() + "\t薪水：" + salary;
        }
        //特有方法
        public void teach() {
            System.out.println("老师 " + getName() + " 正在讲java课程...");
        }
    }
    
    public class PloyArray {
        public static void main(String[] args) {
            //应用实例:现有一个继承结构如下：要求创建1个Person对象、
            // 2个Student 对象和2个Teacher对象, 统一放在数组中，并调用每个对象say方法
    
            //父类引用指向子类对象
            Person[] persons = new Person[5];
            persons[0] = new Person("jack", 20);
            persons[1] = new Student("mary", 18, 100);
            persons[2] = new Student("smith", 19, 30.1);
            persons[3] = new Teacher("scott", 30, 20000);
            persons[4] = new Teacher("king", 50, 25000);
    
            //循环遍历多态数组，调用say
            for (int i = 0; i < persons.length; i++) {
                //person[i] 编译类型是 Person ,运行类型是 根据实际情况由JVM来判断
                System.out.println(persons[i].say());//动态绑定机制
                //输出特有方法时，使用 类型判断 + 向下转型.
                if(persons[i]  instanceof  Student) {   //判断person[i] 的运行类型是不是Student
                    Student student = (Student)persons[i];  //向下转型
                    student.study();
                    //等同于一条语句 ((Student)persons[i]).study();
                } else if(persons[i] instanceof  Teacher) {
                    Teacher teacher = (Teacher)persons[i];
                    teacher.teach();
                } else if(persons[i] instanceof  Person){
    
                } else {
                    System.out.println("类型有误");
                }
            }
        }
    }
    ```

###### 方法参数：

- 方法定义的形参为父类类型，实参类型可以为子类类型

- 应用实例：

  - 定义员工类 Employee ，包含私有属性（姓名和月工资），以及计算年工资方法 getAnnual
  - 普通员工和经理继承了员工类
  - 经理类多了奖金 bonus 和管理方法 manage 
  - 普通员工多了 work 方法
  - 普通员工和经理类要求分别重写 getAnnual 方法
  - 测试类中添加一个方法 showEmpAnnual(Employee e)，实现获取任何员工对象的年工资，并在 main 方法中调用该方法，e.getAnnual()
  - 测试类中添加一个方法 testWork，如果是普通员工，则调用 work 方法，如果是经理，则调用 manage 方法

- 示例：

  - ```java
    package com.hspedu.poly_.polyparameter_;
    
    public class Employee {
        private String name;
        private double salary;
    
        public Employee(String name, double salary) {
            this.name = name;
            this.salary = salary;
        }
    
        //得到年工资的方法
        public double getAnnual() {
            return 12 * salary;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public double getSalary() {
            return salary;
        }
    
        public void setSalary(double salary) {
            this.salary = salary;
        }
    }
    
    public class Worker extends Employee {
        public Worker(String name, double salary) {
            super(name, salary);
        }
        public void work() {
            System.out.println("普通员工 " + getName() + " is working");
        }
    
        @Override
        public double getAnnual() { //因为普通员工没有其它收入，则直接调用父类方法
            return super.getAnnual();
        }
    }
    
    public class Manager extends Employee{
    
        private double bonus;
    
        public Manager(String name, double salary, double bonus) {
            super(name, salary);
            this.bonus = bonus;
        }
    
        public double getBonus() {
            return bonus;
        }
    
        public void setBonus(double bonus) {
            this.bonus = bonus;
        }
        public void manage() {
            System.out.println("经理 " + getName() + " is managing");
        }
        //重写获取年薪方法
        @Override
        public double getAnnual() {
            return super.getAnnual() + bonus;
        }
    }
    
    public class PloyParameter {
        public static void main(String[] args) {
            Worker tom = new Worker("tom", 2500);
            Manager milan = new Manager("milan", 5000, 200000);
            PloyParameter ployParameter = new PloyParameter();  //测试类中的方法也需要创建对象才能调用
            ployParameter.showEmpAnnual(tom);
            ployParameter.showEmpAnnual(milan);
    
            ployParameter.testWork(tom);
            ployParameter.testWork(milan);
    
        }
    
        //showEmpAnnual(Employee e)
        //实现获取任何员工对象的年工资,并在main方法中调用该方法 [e.getAnnual()]
        public void showEmpAnnual(Employee e) {
            System.out.println(e.getAnnual());  //动态绑定机制
        }
    
        //添加一个方法，testWork,如果是普通员工，则调用work方法，如果是经理，则调用manage方法
        public void testWork(Employee e) {
            if(e instanceof  Worker) {
                ((Worker) e).work();    //向下转型，特有方法需要向下转型才能调用
            } else if(e instanceof Manager) {
                ((Manager) e).manage(); //向下转型
            } else {
                System.out.println("不做处理...");
            }
        }
    }
    ```

#### 11.Object 类详解

##### equals() 方法

- `==`与 equals 的对比：

  - `==`是一个比较运算符，既可以判断基本类型，又可以判断引用类型
    - `==`：如果判断基本类型，判断的是值是否相等
    - `==`：如果判断引用类型，判断的是地址是否相等，即判定是不是同一个对象
  - equals 是 Object 类的方法，只能判断引用数据类型
    - 默认判断的是地址是否相等，子类中往往重写此方法，用于判断内容是否相等

- 示例：

  - ```java
    package com.hspedu.object_;
    
    public class Equals01 {
    
        public static void main(String[] args) {
            A a = new A();
            A b = a;
            A c = b;
            System.out.println(a == c); //true，指向的是同一块内存
            System.out.println(b == c); //true
            B bObj = a;
            System.out.println(bObj == c);  //true，引用类型不同，但仍然指向的是同一块内存
            int num1 = 10;
            double num2 = 10.0;
            System.out.println(num1 == num2);   //true，基本数据类型，判断值是否相等
    
            //equals 方法，源码怎么查看
            //把光标放在equals方法，直接输入ctrl+b
            //如果你使用不了. 自己配置. 即可使用.
            
            "hello".equals("aaa");
            /*
            //Jdk的源码 String类的 equals方法
            //把Object的equals方法重写了,变成了比较两个字符串值是否相同
    
            public boolean equals(Object anObject) {
            if (this == anObject) { //如果是同一个对象
                return true;    //返回true
            }
            if (anObject instanceof String) {   //判断类型，如果是String类型，如果不是，则直接返回false
                String anotherString = (String)anObject;    //向下转型，转为String类型
                int n = value.length;   //获取字符串长度
                if (n == anotherString.value.length) {  //如果长度相同，则逐个进行比较；如果长度不相同，返回false
                    char v1[] = value;
                    char v2[] = anotherString.value;
                    int i = 0;
                    while (n-- != 0) {//然后一个一个的比较字符
                        if (v1[i] != v2[i])
                            return false;
                        i++;
                    }
                    return true;//如果两个字符串的所有字符都相等，则返回true
                }
            }
            return false;   //如果比较的不是字符串，则直接返回false
      	  }		 */
    
            //Object
            //看看Object类的 equals
            /*
            //即Object 的equals 方法默认就是比较对象地址是否相同
            //也就是判断两个对象是不是同一个对象.
             public boolean equals(Object obj) {
                return (this == obj);
            }       */
    
            /*
            //从源码可以看到 Integer 也重写了Object的equals方法,
            //变成了判断两个值是否相同
            public boolean equals(Object obj) {
                if (obj instanceof Integer) {
                    return value == ((Integer)obj).intValue();
                }
                return false;
            }       */
            Integer integer1 = new Integer(1000);
            Integer integer2 = new Integer(1000);
            System.out.println(integer1 == integer2);   //false，因为 == 比较引用类型时比较的是地址
            System.out.println(integer1.equals(integer2));  //true，equals比较的是内容
    
            String str1 = new String("hspedu");
            String str2 = new String("hspedu");
            System.out.println(str1 == str2);   //false
            System.out.println(str1.equals(str2));  //true
        }
    }
    
    class B {}
    class A extends B {}
    ```

- 如何重写 equals 方法

  - 示例1：

    - ```java
      package com.hspedu.object_;
      
      public class EqualsExercise01 {
          public static void main(String[] args) {
              Person person1 = new Person("jack", 10, '男');
              Person person2 = new Person("jack", 10, '男');
      
              System.out.println(person1.equals(person2));    //若未重写equals，则为假
          }
      }
      //判断两个Person对象的内容是否相等，
      //如果两个Person对象的各个属性值都一样，则返回true，反之false
      class Person{ //extends Object
          private String name;
          private int age;
          private char gender;
      
          //重写Object 的 equals方法
          public boolean equals(Object obj) {
              //判断如果比较的两个对象是同一个对象，则直接返回true
              if(this == obj) {
                  return true;
              }
              //类型判断
              if(obj instanceof Person) { //是Person，我们才比较
                  //进行向下转型, 因为需要得到obj的 各个属性
                  Person p = (Person)obj;
                  return this.name.equals(p.name) && this.age == p.age && this.gender == p.gender;
              }
              //如果不是Person ，则直接返回false
              return false;
          }
      
          public Person(String name, int age, char gender) {
              this.name = name;
              this.age = age;
              this.gender = gender;
          }
      
          public String getName() {
              return name;
          }
      
          public void setName(String name) {
              this.name = name;
          }
      
          public int getAge() {
              return age;
          }
      
          public void setAge(int age) {
              this.age = age;
          }
      
          public char getGender() {
              return gender;
          }
      
          public void setGender(char gender) {
              this.gender = gender;
          }
      }
      ```

  - 示例2：

    - ```java
      package com.hspedu.object_;
      
      public class EqualsExercise02 {
          public static void main(String[] args) {
      
              Person_ p1 = new Person_();
              p1.name = "hspedu";
      
              Person_ p2 = new Person_();
              p2.name = "hspedu";
      
              System.out.println(p1 == p2); //False
              System.out.println(p1.name.equals( p2.name));  //TRUE，注意这里不是比较两个对象，而是比较两个字符串，字符串的equals已经重写
              System.out.println(p1.equals(p2));  //False，这里比较的是类对象，这里并没有重写equals
      
              String s1 = new String("asdf");
      
              String s2 = new String("asdf");
              System.out.println(s1.equals(s2));  //T
              System.out.println(s1 == s2); //F
          }
      }
      
      class Person_{//类
          public String name;
      }
      ```

##### hashCode() 方法

- 返回该对象的哈希码值

- 小结：

  - 提高具有哈希结构的容器的效率
  - 两个引用，如果指向的是同一个对象，则哈希值肯定是一样的
  - 两个引用，如果指向的是不同对象，则哈希值是不一样的
  - 哈希值主要根据地址号来的，不能完全将哈希值等价于地址
  - 后面在集合中 hashCode 如果需要的话也会重写
  
- 示例：

  - ```java
    package com.hspedu.object_;
    
    public class HashCode_ {
        public static void main(String[] args) {
    
            AA aa1 = new AA();
            AA aa2 = new AA();
            AA aa3 = aa1;
            System.out.println("aa1.hashCode() = " + aa1.hashCode());
            System.out.println("aa2.hashCode() = " + aa2.hashCode());
            System.out.println("aa3.hashCode() = " + aa3.hashCode());
        }
    }
    class AA {}
    ```

##### toString() 方法

- 基本介绍：

  - 默认返回：全类名+@+哈希值的十六进制（查看 Object 的 toString 方法）
  - 子类往往重写 toString 方法，用于返回对象的属性信息

- 重写 toString 方法，打印对象或拼接对象时，都会自动调用该对象的 toString 形式.

- 当直接输出一个对象时，toString 方法会被默认的调用

  - 比如 ：`System.out.println(monster); //就会默认调用monster.toString()`

- 示例（）：

  - ```java
    package com.hspedu.object_;
    
    public class ToString_ {
        public static void main(String[] args) {
            /*Object的toString() 源码：
                (1)getClass().getName() 类的全类名(包名+类名 )
                (2)Integer.toHexString(hashCode()) 将对象的hashCode值转成16进制字符串
    
                public String toString() {
                    return getClass().getName() + "@" + Integer.toHexString(hashCode());
                }    */
    
            Monster monster = new Monster("小妖怪", "巡山的", 1000);
            System.out.println(monster.toString() + " hashcode = " + monster.hashCode());
    
            //当直接输出一个对象时，toString 方法会被默认的调用
            System.out.println(monster); //等价 monster.toString()
        }
    }
    
    class Monster {
        private String name;
        private String job;
        private double sal;
    
        public Monster(String name, String job, double sal) {
            this.name = name;
            this.job = job;
            this.sal = sal;
        }
    
        //重写toString方法, 输出对象的属性
        //使用快捷键即可 alt+insert -> toString
        @Override
        public String toString() {
            return "Monster{" +
                    "name = '" + name + '\'' +
                    ", job = '" + job + '\'' +
                    ", sal = " + sal +
                    '}';
        }
    
        @Override
        protected void finalize() throws Throwable {
            System.out.println("fin..");
        }
    }
    ```

##### Finalize() 方法

- 当对象被回收时，系统自动调用该对象的 finalize 方法。子类可以重写该方法，做一些释放资源的操作

- 什么时候被回收：当某个对象没有任何引用时，则 jvm 就认为这个对象是一个垃圾对象，就会使用垃圾回收机制来销毁该对象，在销毁该对象前，会先调用 finalize 方法。

- 垃圾回收机制的调用，是由系统来决定（即有自己的 GC 算法）, 也可以通过 System.gc() 主动触发垃圾回收机制

- 在实际开发中，几乎不会运用 finalize，所以更多就是为了应付面试.

- 示例：

  - ```java
    package com.hspedu.object_;
    
    //演示 Finalize的用法
    public class Finalize_ {
        public static void main(String[] args) {
            Car bmw = new Car("宝马");
    
            bmw = null;
            //这时 car对象就是一个垃圾,垃圾回收器就会回收(销毁)对象, 在销毁对象前，会调用该对象的finalize方法
            //程序员就可以在 finalize 中，写自己的业务逻辑代码(比如释放资源：数据库连接,或者打开文件..)
            //如果程序员不重写 finalize,那么就会调用 Object 类的 finalize, 即默认处理
            //如果程序员重写了finalize, 就可以实现自己的逻辑
    
            System.gc();    //需要主动调用垃圾回收器
            System.out.println("程序退出了....");
        }
    }
    class Car {
        private String name;
        //属性, 资源
        public Car(String name) {
            this.name = name;
        }
        //重写finalize
        @Override
        protected void finalize() throws Throwable {
            System.out.println("我们销毁 汽车" + name );
            System.out.println("释放了某些资源...");
        }
    }
    ```

#### 12.断点调试

- 在断点调试过程中，是运行状态，是以对象的运行类型来执行的

- 断点调试介绍：

  - 断点调试时指在程序的某一行设置一个断点，调试时，程序运行到这一行就会停住，然后可以一步步往下调试，调试过程中可以看到各个变量当前的值，出错的话，调试到出错的代码行即显示错误，停下，进行分析从而找到这个bug

- 断点调试快捷键：

  - F7：跳入（跳入方法内）
  - alt + shift + F7：强制进入方法（进入源码方法）
  - F8：跳过（逐行执行代码）
  - shift + F8：跳出（跳出方法）
  - F9：resume，执行到下一个断点
  - ctrl + F5：重新运行 debug
  - ctrl + F2：结束 debug

- 断点调试案例：

  - 案例1：

    - 错误代码：

      - ```java
        package com.hspedu.debug_;
        
        public class  Debug01 {
            public static void main(String[] args) {
                //演示逐行执行代码
                int sum = 0;
                for (int i = 0; i < 5; i++) {
                    sum += i;
                    System.out.println("i = " + i);
                    System.out.println("sum = " + i);	//这里出错
                }
                System.out.println("退出for....");
            }
        }
        ```

    - 修正代码：

      - ```java
        package com.hspedu.debug_;
        
        public class  Debug01 {
            public static void main(String[] args) {
                //演示逐行执行代码
                int sum = 0;
                for (int i = 0; i < 5; i++) {
                    sum += i;
                    System.out.println("i = " + i);
                    System.out.println("sum = " + sum);
                }
                System.out.println("退出for....");
            }
        }
        ```

  - 案例2：

    - 错误代码：

      - ```java
        package com.hspedu.debug_;
        
        public class Debug02 {
            public static void main(String[] args) {
                int[] arr = {1, 10, -1};
                for (int i = 0; i <= arr.length; i++) {	//数组越界
                    System.out.println(arr[i]);
                }
                System.out.println("退出for");
            }
        }
        ```

    - 修正代码：

      - ```java
        package com.hspedu.debug_;
        
        public class Debug02 {
            public static void main(String[] args) {
                int[] arr = {1, 10, -1};
                for (int i = 0; i < arr.length; i++) {
                    System.out.println(arr[i]);
                }
                System.out.println("退出for");
            }
        }
        ```

  - 案例3：

    - ```java
      package com.hspedu.debug_;
      
      import java.util.Arrays;
      
      public class Debug03 {
          public static void main(String[] args) {
              int[] arr = {1, -1, 10, -20 , 100};
              //看看Arrays.sort方法底层实现.->Debug
              Arrays.sort(arr);   //需要强制进入，或在设置中改为可以进入源码
              for (int i = 0; i < arr.length; i++) {
                  System.out.print(arr[i] + "\t");
              }
          }
      }
      ```

  - 案例4：

    - ```java
      package com.hspedu.debug_;
      
      import java.util.Arrays;
      
      //演示执行到下一个断点，同时支持动态的下断点.
      public class Debug04 {
          public static void main(String[] args) {
      
              int[] arr = {1, -1, 10, -20 , 100};
              //我们看看Arrays.sort方法底层实现.->Debug
              Arrays.sort(arr);
              for (int i = 0; i < arr.length; i++) {
                  System.out.print(arr[i] + "\t");
              }
              System.out.println();
      
              System.out.println("hello100");
              System.out.println("hello200");
              System.out.println("hello300");
              System.out.println("hello400");
              System.out.println("hello500");
              System.out.println("hello600");
              System.out.println("hello700");
          }
      }
      ```

  - 案例5：

    - ```java
      package com.hspedu.debug_;
      
      //debug对象创建的过程，加深对调试的理解
      public class DebugExercise {
          public static void main(String[] args) {
              /*  创建对象的流程:
                  (1) 加载 Person类信息
                  (2) 初始化 :
                      2.1 默认初始化
                      2.2 显式初始化
                      2.3 构造器初始化
                  (3) 返回对象的地址     */
              Person jack = new Person("jack", 20);
              System.out.println(jack);
          }
      }
      class Person {
          private String name;
          private int age;
      
          public Person(String name, int age) {
              this.name = name;
              this.age = age;
          }
      
          @Override
          public String toString() {
              return "Person{" +
                      "name='" + name + '\'' +
                      ", age=" + age +
                      '}';
          }
      }
      ```

#### 13.项目（零钱通）

##### 项目需求说明

- 使用 Java 开发 零钱通项目，可以完成收益入账，消费，查看明细，退出系统等功能

##### 项目界面

- 先完成显示菜单，并可以选择
- 完成零钱通明细
- 完成收益入账
- 消费
- 退出

##### 项目代码实现

- 先使用过程编程，后面改成 OOP 版本，体会 OOP 编程带来的好处

- 面向过程编程：

  - ```java
    package com.hspedu.smallchange;
    
    import java.text.SimpleDateFormat;
    import java.util.Date;
    import java.util.Scanner;
    
    public class SmallChangeSys {
    
        /*化繁为简:
            1. 先完成显示菜单，并可以选择菜单，给出对应提示
            2. 完成零钱通明细
            3. 完成收益入账
            4. 消费
            5. 退出
            6. 用户输入4退出时，给出提示"你确定要退出吗? y/n"，必须输入正确的y/n ，否则循环输入指令，直到输入y 或者 n
            7. 在收益入账和消费时，判断金额是否合理，并给出相应的提示        */
        public static void main(String[] args) {
    
            //定义相关的变量
            boolean loop = true;    //用于选择是否还要继续执行菜单
            Scanner scanner = new Scanner(System.in);   //用于接收键盘输入，选择菜单选项
            String key = "";    //用于保存用户的菜单选择
    
            //2. 完成零钱通明细
            /*思路：
                (1) 可以把收益入账和消费，保存到数组，但是数组大小不确定，需要动态变化
                (2) 可以使用对象
                (3) 也可以使用String拼接（不推荐，但这里采用的是String）       */
            String details = "-----------------零钱通明细------------------";    //后续每条入账和消费都会拼接在后面
    
            //3. 完成收益入账  完成功能驱动程序员增加新的变化和代码
            //思路：定义新的变量
            double money = 0;   //入账金额
            double balance = 0;     //余额
            Date date = null;   // date 是 java.util.Date 类型，表示日期
            SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd HH:mm"); //可以用于日期格式化的
    
            //4. 消费
            //定义新变量，保存消费的原因
            String note = "";
            do {
    
                //1. 先完成显示菜单，并可以选择菜单，给出对应提示
                System.out.println("\n============零钱通菜单============");
                System.out.println("\t\t\t1.零钱通明细");
                System.out.println("\t\t\t2.收益入账");
                System.out.println("\t\t\t3.消费");
                System.out.println("\t\t\t4.退出");
    
                System.out.print("请选择(1-4): ");
                key = scanner.next();
    
                //使用switch 分支控制
                switch (key) {
                    case "1":
                        System.out.println(details);
                        break;
                    case "2":
                        System.out.print("收益入账金额:");
                        money = scanner.nextDouble();
                        //money的值范围应该校验
                        //若金额条件不正确，给出提示, 然后直接break
                        if(money <= 0) {
                            System.out.println("收益入账金额 需要 大于 0");
                            break;
                        }
                        //金额条件正确
                        balance += money;
                        //拼接收益入账信息到 details
                        date = new Date(); //获取当前日期 //import java.util.Date;
                        details += "\n收益入账\t+" + money + "\t" + sdf.format(date) + "\t" + balance;
                        break;
                    case "3":
                        System.out.print("消费金额:");
                        money = scanner.nextDouble();
                        //money 的值范围应该校验
                        //找出金额不正确的情况
                        //过关斩将 校验方式.
                        if(money <= 0 || money > balance) {     //消费金额要大于0，小于等于余额
                            System.out.println("你的消费金额 应该在 0~" + balance);
                            break;
                        }
                        System.out.print("消费说明:");
                        note = scanner.next();  //接收字符串，消费说明
                        balance -= money;
                        //拼接消费信息到 details
                        date = new Date(); //获取当前日期
                        details += "\n" + note + "\t-" + money + "\t" + sdf.format(date) + "\t" + balance;
                        break;
                    case "4":
                        //用户输入4退出时，给出提示"你确定要退出吗? y/n"，必须输入正确的y/n ，
                        // 否则循环输入指令，直到输入y 或者 n
                        /* 思路分析：
                             (1) 定义一个变量 choice, 接收用户的输入
                             (2) 使用 while + break, 来处理接收到的输入时 y 或者 n
                             (3) 退出while后，再判断choice是y还是n ,就可以决定是否退出
                             (4) 建议一段代码，完成一个小功能，尽量不要混在一起      */
                        String choice = "";
                        //要求用户必须输入y/n ,否则就一直循环，避免出现其他字符而导致无法是否要退出
                        while (true) {
                            System.out.println("你确定要退出吗? y/n");
                            choice = scanner.next();
                            if ("y".equals(choice) || "n".equals(choice)) {
                                break;
                            }
                            //第二个方案
    //                        if("y".equals(choice)) {
    //                            loop = false;
    //                            break;
    //                        } else if ("n".equals(choice)) {
    //                            break;
    //                        }
                        }
    
                        //当用户退出while ,进行判断；若输入的是n，则还要进行菜单选择
                        if (choice.equals("y")) {
                            loop = false;
                        }
                        break;
                    default:
                        System.out.println("选择有误，请重新选择");
                }
    
            } while (loop);
    
            System.out.println("-----退出了零钱通项目-----");
        }
    }
    ```

- 面向对象编程：

  - 主类：

    - ```java
      package com.hspedu.smallchange.oop;
      
      /**
       * 这里我们直接调用SmallChangeSysOOP 对象，显示主菜单即可
       */
      public class SmallChangeSysApp {    //主类
      
          public static void main(String[] args) {
              System.out.println("====hello公司====");
              new SmallChangeSysOOP().mainMenu();
          }
      }
      ```

  - `SmallChangeSysOOP.java`

    - ```java
      package com.hspedu.smallchange.oop;
      
      import java.text.SimpleDateFormat;
      import java.util.Date;
      import java.util.Scanner;
      
      /**
       * 该类是完成零钱通的各个功能的类
       * 使用OOP(面向对象编程)
       * 将各个功能对应一个方法.
       */
      public class SmallChangeSysOOP {
      
          //属性：
          //定义相关的变量
          boolean loop = true;    //用于判断菜单是否继续循环执行
          Scanner scanner = new Scanner(System.in);
          String key = "";    //用于保存用户对菜单选项的选择
      
          //2. 完成零钱通明细
          String details = "-----------------零钱通明细------------------";
      
          //3. 完成收益入账  完成功能驱动程序员增加新的变化和代码
          //思路, 定义新的变量
          double money = 0;
          double balance = 0;
          Date date = null; // date 是 java.util.Date 类型，表示日期
          SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd HH:mm"); //可以用于日期格式化的
      
          //4. 消费
          //定义新变量，保存消费的原因
          String note = "";
      
          //先完成显示菜单，并可以选择
          public void mainMenu() {
              do {
      
                  System.out.println("\n================零钱通菜单(OOP)===============");
                  System.out.println("\t\t\t1 零钱通明细");
                  System.out.println("\t\t\t2 收益入账");
                  System.out.println("\t\t\t3 消费");
                  System.out.println("\t\t\t4 退     出");
      
                  System.out.print("请选择(1-4): ");
                  key = scanner.next();
      
                  //使用switch 分支控制
                  switch (key) {
                      case "1":
                          this.detail();
                          break;
                      case "2":
                          this.income();
                          break;
                      case "3":
                          this.pay();
                         break;
                      case "4":
                          this.exit();
                          break;
                      default:
                          System.out.println("选择有误，请重新选择");
                  }
      
              } while (loop);
          }
      
          //零钱通明细方法
          public void detail() {
              System.out.println(details);
          }
      
          //收益入账方法
          public void income() {
              System.out.print("收益入账金额:");
              money = scanner.nextDouble();
              //找出不正确的金额条件，然后给出提示, 就直接return
              if(money <= 0) {
                  System.out.println("收益入账金额 需要 大于 0");
                  return; //若金额条件不正确，则直接退出方法，不再执行后面的代码。
              }
              //找出正确金额的条件
              balance += money;
              //拼接收益入账信息到 details
              date = new Date(); //获取当前日期
              details += "\n收益入账\t+" + money + "\t" + sdf.format(date) + "\t" + balance;
          }
      
          //消费方法
          public void pay() {
              System.out.print("消费金额:");
              money = scanner.nextDouble();
              //找出金额不正确的情况
              if(money <= 0 || money > balance) {
                  System.out.println("你的消费金额 应该在 0-" + balance);
                  return;
              }
              System.out.print("消费说明:");
              note = scanner.next();
              balance -= money;
              //拼接消费信息到 details
              date = new Date(); //获取当前日期
              details += "\n" + note + "\t-" + money + "\t" + sdf.format(date) + "\t" + balance;
          }
      
          //退出方法
          public void exit() {
              //用户输入4退出时，给出提示"你确定要退出吗? y/n"，必须输入正确的y/n ，
              // 否则循环输入指令，直到输入y 或者 n
              /* 思路分析：
                               (1) 定义一个变量 choice, 接收用户的输入
                               (2) 使用 while + break, 来处理接收到的输入时 y 或者 n
                               (3) 退出while后，再判断choice是y还是n ,就可以决定是否退出
                               (4) 建议一段代码，完成一个小功能，尽量不要混在一起      */
              String choice = "";
              while (true) { //要求用户必须输入y/n ,否则就一直循环
                  System.out.println("你确定要退出吗? y/n");
                  choice = scanner.next();
                  if ("y".equals(choice) || "n".equals(choice)) {
                      break;
                  }
                  //第二个方案
      //                        if("y".equals(choice)) {
      //                            loop = false;
      //                            break;
      //                        } else if ("n".equals(choice)) {
      //                            break;
      //                        }
              }
      
              //当用户退出while ,进行判断
              if (choice.equals("y")) {
                  loop = false;
              }
          }
      }
      ```

#### 14.练习

##### 练习1

- 示例：

  - ```java
    package com.hspedu.homework;
    
    /*题目描述：
        定义一个Person类 {name, age, job}, 初始化Person 对象数组，有3个person对象，
        并按照 age 从 大到 小进行排序, 提示，使用冒泡排序        */
    
    public class Homework01 {
    
        public static void main(String[] args) {
    
            //初始化Person 对象数组，有3个person对象
            Person[] persons = new Person[3];
            persons[0] = new Person("mary",30, "PHP工程师");
            persons[1] = new Person("tom",50, "大数据工程师");
            persons[2] = new Person("smith",10, "JavaEE工程师");
    
            //输出当前对象数组
            for (int i = 0; i < persons.length; i++) {
                System.out.println(persons[i]); //默认对象的.toString()
            }
    
            //使用冒泡排序
            Person tmp = null;  //临时变量，用于交换
            for(int i = 0; i < persons.length -1 ;i++) {    //外层循环
                for(int j = 0; j < persons.length -1 - i; j++) {    //内层循环
                    //并按照 age 从 大到 小进行排序, 如果前面的人的age < 后面人的年龄，就交换
                    //若要求按照名字的长度从小到大 if(persons[i].getName().length() > persons[i+1].getName().length())
                    if(persons[j].getAge() > persons[j+1].getAge()) {   //私有属性，需要调用get方法
                        tmp = persons[j];
                        persons[j] = persons[j+1];
                        persons[j+1]= tmp;
                    }
    
                }
            }
    
            System.out.println("排序后的效果：");
            for (int i = 0; i < persons.length; i++) {
                System.out.println(persons[i]);//默认对象的.toString()
            }
    
        }
    }
    
    class Person {  //属性、构造器、getter and setter、重写toString
        private String name;
        private int age;
        private String job;
    
        public Person(String name, int age, String job) {
            this.name = name;
            this.age = age;
            this.job = job;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public int getAge() {
            return age;
        }
    
        public void setAge(int age) {
            this.age = age;
        }
    
        public String getJob() {
            return job;
        }
    
        public void setJob(String job) {
            this.job = job;
        }
    
        @Override
        public String toString() {
            return "Person{" +
                    "name='" + name + '\'' +
                    ", age=" + age +
                    ", job='" + job + '\'' +
                    '}';
        }
    }
    ```

##### 练习2

- 示例：

  - ```java
    package com.hspedu.homework;
    
    /*
    (1) 要求有属性“姓名name”，“年龄age”，“职称post”，“基本工资salary”
    (2) 编写业务方法， introduce（），实现输出一个教师的信息。         */
    
    public class Teacher {
        private String name;
        private int age;
        private String post;
        private double salary;
        //这里我们在增加一个工资级别
        private double grade;
    
        public Teacher(String name, int age, String post, double salary, double grade) {
            this.name = name;
            this.age = age;
            this.post = post;
            this.salary = salary;
            this.grade = grade;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public int getAge() {
            return age;
        }
    
        public void setAge(int age) {
            this.age = age;
        }
    
        public String getPost() {
            return post;
        }
    
        public void setPost(String post) {
            this.post = post;
        }
    
        public double getSalary() {
            return salary;
        }
    
        public void setSalary(double salary) {
            this.salary = salary;
        }
    
        public double getGrade() {
            return grade;
        }
    
        public void setGrade(double grade) {
            this.grade = grade;
        }
        public void introduce() {
            System.out.println("name: " + name + " age: " + age
                    + " post: " + post + " salary:" + salary + " grade:" + grade);
        }
    }
    
    //子类
    public class Professor extends Teacher {
        //特有属性...
        public Professor(String name, int age, String post, double salary, double grade) {
            super(name, age, post, salary, grade);
        }
    
        @Override
        public void introduce() {
            System.out.println("这是教授的信息：");
            super.introduce();
        }
    }
    
    public class Homework02 {
        public static void main(String[] args) {
            Professor professor = new Professor("贾宝玉", 30, "高级职称", 30000, 1.3);
            professor.introduce();
        }
    }
    ```

##### 练习3

- 示例：

  - ```java
    package com.hspedu.homework;
    
    import java.sql.SQLOutput;
    
    public class Employee {
    
        //属性：
        //员工属性：姓名，单日工资，工作天数
        private String name;
        private double daySal;
        private int workDays;
        //分析出还有一个属性等级
        private double grade;
        
        //打印工资方法
        //方法 void printSal() {}
        public void printSal() {
            System.out.println("姓名：" + name + " 工资： " + daySal * workDays * grade);
        }
    
        public Employee(String name, double daySal, int workDays, double grade) {
            this.name = name;
            this.daySal = daySal;
            this.workDays = workDays;
            this.grade = grade;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public double getDaySal() {
            return daySal;
        }
    
        public void setDaySal(double daySal) {
            this.daySal = daySal;
        }
    
        public int getWorkDays() {
            return workDays;
        }
    
        public void setWorkDays(int workDays) {
            this.workDays = workDays;
        }
    
        public double getGrade() {
            return grade;
        }
    
        public void setGrade(double grade) {
            this.grade = grade;
        }
    }
    
    public class Manager extends Employee {
        //特有属性
        private double bonus;   //奖金
        //创建Manager对象时，奖金是多少并不是确定的，因为老师在构造器中，不给bonus
        //可以通过setBonus
        public Manager(String name, double daySal, int workDays, double grade) {
            super(name, daySal, workDays, grade);
        }
    
        //方法:重写父类的 printSal
    
        @Override
        public void printSal() {
            //因为经理的工资计算方式和Employee不一样，所以我们重写
            System.out.println("经理姓名：" + getName() + " 工资："
                    + (bonus + getDaySal() * getWorkDays() * getGrade()));
        }
    
        public double getBonus() {
            return bonus;
        }
    
        public void setBonus(double bonus) {
            this.bonus = bonus;
        }
    }
    
    public class Worker extends Employee{
        //分析普通员工特有属性，没有特有的属性
    
        public Worker(String name, double daySal, int workDays, double grade) {
            super(name, daySal, workDays, grade);
        }
    
        //重写printSal
        //因为普通员工和Employee输出工资情况一下，所以直接调用父类的printSal()
        @Override
        public void printSal() {
            System.out.print("普通员工");//自己的输出信息
            super.printSal();//调用父类的方法，复用代码
        }
    }
    
    public class Homework03 {
        public static void main(String[] args) {
            Manager manage = new Manager("刘备", 100, 20, 1.2);
            //设置奖金
            manage.setBonus(3000);
            //打印经理的工资情况
            manage.printSal();
    
            Worker worker = new Worker("关羽",50, 10, 1.0);
            worker.printSal();
        }
    }
    ```

##### 练习4

- 示例：

  - `Employee.java`

    - ```java
      package com.hspedu.homework.homework5;
      
      public class Employee { //父类
          //属性
          //分析有一个带薪的月份 13 , 15, 12
          private String name;	//姓名
          private double sal;	//基本工资，月薪
          private int salMonth = 12;	//带薪的月份
          
          //方法
          //打印全年工资
          public void printSal() {
              System.out.println("姓名：" + name + " 年工资是: " + (sal * salMonth));
          }
      	
          //有参构造
          public Employee(String name, double sal) {
              this.name = name;
              this.sal = sal;
          }
      
          public String getName() {
              return name;
          }
      
          public void setName(String name) {
              this.name = name;
          }
      
          public double getSal() {
              return sal;
          }
      
          public void setSal(double sal) {
              this.sal = sal;
          }
      
          public int getSalMonth() {
              return salMonth;
          }
      
          public void setSalMonth(int salMonth) {
              this.salMonth = salMonth;
          }
      }
      ```

  - `Worker.java`

    - ```java
      package com.hspedu.homework.homework5;
      
      public class Worker extends Employee{ //子类
          //属性
          //工人,农民,服务生只有基本工资 sal
          public Worker(String name, double sal) {
              super(name, sal);
          }
      
          //方法
          @Override
          public void printSal() {
              System.out.print("工人:);
              super.printSal();//使用父类的printSal()
          }
      }
      
      ```

  - `Peasant.java`

    - ```java
      package com.hspedu.homework.homework5;
      
      public class Peasant extends Employee {//子类
          //属性
          //农民,服务生只有基本工资 sal
      
          //方法
          public Peasant(String name, double sal) {
              super(name, sal);
          }
          //年工资
      
          @Override
          public void printSal() {
              System.out.print("农民:");
              super.printSal();
          }
      }
      ```

  - `Teacher.java`

    - ```java
      package com.hspedu.homework.homework5;
      
      public class Teacher extends Employee{//子类
          //特有属性
          private int classDays; //一年上课次数
          private double classSal; //课时费
      
          public Teacher(String name, double sal) {
              super(name, sal);
          }
          
          //方法-重写printSal
          @Override
          public void printSal() { //老师不能使用super.printSal()
              System.out.print("老师：");
              System.out.println("姓名：" + getName() + " 年工资: "
                      + (getSal() * getSalMonth() + classDays * classSal ));
          }
      
          public int getClassDays() {
              return classDays;
          }
      
          public void setClassDays(int classDays) {
              this.classDays = classDays;
          }
      
          public double getClassSal() {
              return classSal;
          }
      
          public void setClassSal(double classSal) {
              this.classSal = classSal;
          }
      }
      
      ```

  - `Scientist.java`

    - ```java
      package com.hspedu.homework.homework5;
      
      public class Scientist extends Employee{ //子类
          //特有属性
          //年终奖 bonus
          private double bonus;
      
          //方法
          public Scientist(String name, double sal) {
              super(name, sal);
          }
          //重写年工资打印
      
          @Override
          public void printSal() {
              System.out.print("科学家 ");
              System.out.println(getName() + " 年工资是: " + (getSal() * getSalMonth() + bonus));
          }
      
          public double getBonus() {
              return bonus;
          }
      
          public void setBonus(double bonus) {
              this.bonus = bonus;
          }
      }
      
      ```

  - `Homework04.java`

    - ```java
      package com.hspedu.homework.homework5;
      
      public class Homework04 {
          public static void main(String[] args) {
              Worker jack = new Worker("jack", 10000);
              jack.setSalMonth(15);//灵活额修改带薪月份
              jack.printSal();
      
              Peasant smith = new Peasant("smith", 20000);
              smith.printSal();
      
              //老师测试
              Teacher teacher = new Teacher("顺平", 2000);
              //老师有课时费
              teacher.setClassDays(360);
              teacher.setClassSal(1000);
              teacher.printSal();
      
              //科学家
              Scientist scientist = new Scientist("钟南山", 20000);
              scientist.setBonus(2000000);
              scientist.printSal();
          }
      }
      ```

##### 练习5

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework05 {
        public static void main(String[] args) {
    
        }
    }
    class Test{ //父类
        String name = "Rose";
        Test(){     //无参构造器
            System.out.println("Test"); //输出的第一句话
        }
        Test(String name){  //name john   //有参构造器
            this.name = name;   //这里把父类的 name 修改 john
        }
    }
    class Demo extends Test{//子类
        String name="Jack";
        Demo()	{
            super();
            System.out.println("Demo"); //输出的第二句话
        }
        Demo(String s){
            super(s);
        }
        public void test(){
            System.out.println(super.name); //第三句话：Rose     第五句话：john
            System.out.println(this.name);  //第四句话：Jack     第六句话：Jack
        }
        public static void main(String[] args)	{
            //老韩分析
            //1. new Demo()
            new Demo().test(); //匿名对象
            new Demo("john").test();    //匿名
        }
    }
    ```

##### 练习6

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class BankAccount {//父类
        private double balance ;    //余额
        public BankAccount(double initialBalance) {
            this.balance = initialBalance;
        }
        //存款
        public void deposit(double amount)  {
            balance += amount;
        }
        //取款
        public void withdraw(double amount)  {
            balance -= amount;
        }
    
        public double getBalance() {
            return balance;
        }
    
        public void setBalance(double balance) {
            this.balance = balance;
        }
    }
    
    ```

  - ```java
    package com.hspedu.homework;
    
    //在上面类的基础上扩展 新类CheckingAccount对每次存款和取款都收取1美元的手续费
    public class CheckingAccount extends BankAccount{//新的账号
        //属性
        public CheckingAccount(double initialBalance) {
            super(initialBalance);
        }
    
        @Override
        public void deposit(double amount) {//存款
            super.deposit(amount - 1);//巧妙的使用了父类的 deposit
            //1 块钱转入银行的账号
        }
    
        @Override
        public void withdraw(double amount) {//取款
            super.withdraw(amount + 1);
            //1 块钱转入银行的账号
        }
    }
    ```

  - ```java
    package com.hspedu.homework;
    
    /*题目描述：
        扩展前一个练习的BankAccount类，
        新类 SavingsAccount 每个月都有利息产生(earnMonthlyInterest 方法被调用)，
        并且有每月三次免手续费的存款或取款。在 earnMonthlyInterest方法 中重置交易计数     */
    
    public class SavingsAccount extends BankAccount {
    
        //新增加属性
        private int count = 3;  //免手续费次数
        private double rate = 0.01; //利率
    
        //构造器
        public SavingsAccount(double initialBalance) {
            super(initialBalance);
        }
    
        public int getCount() {
            return count;
        }
    
        public void setCount(int count) {
            this.count = count;
        }
    
        public double getRate() {
            return rate;
        }
    
        public void setRate(double rate) {
            this.rate = rate;
        }
    
        public void earnMonthlyInterest() { //每个月初，我们统计上个月的利息，同时将   count=3
            count = 3;//
            super.deposit(getBalance() * rate); //利息，相当于调用存款方法，存入利息
        }
    
        @Override
        public void deposit(double amount) {    //存款
            //判断是否还可以免手续费
            if(count > 0) {
                super.deposit(amount);  //调用父类中无手续费的存款方法
            } else {
                super.deposit(amount - 1);  //1 块转入银行
            }
            count--;    //减去一次免手续费次数
        }
    
        @Override
        public void withdraw(double amount) {   //取款
            //判断是否还可以免手续费
            if(count > 0) {
                super.withdraw(amount); //调用父类中无手续费的取款方法
            } else {
                super.withdraw(amount + 1);//1 块转入银行
            }
            count--;
        }
    }
    
    ```

  - ```java
    package com.hspedu.homework;
    
    public class Homework06 {
        public static void main(String[] args) {
            CheckingAccount checkingAccount = new CheckingAccount(1000);
            checkingAccount.deposit(10);// 1010 - 1 = 1009
            checkingAccount.withdraw(9);//1009 - 9 = 1000 -1= 999
            System.out.println(checkingAccount.getBalance());
    
            //测试SavingsAccount
            SavingsAccount savingsAccount = new SavingsAccount(1000);
            savingsAccount.deposit(100);
            savingsAccount.deposit(100);
            savingsAccount.deposit(100);
            System.out.println(savingsAccount.getBalance());//1300
            savingsAccount.deposit(100);
            System.out.println(savingsAccount.getBalance());//1400-1=1399
    
            //月初，定时器自动调用一下 earnMonthlyInterest
            savingsAccount.earnMonthlyInterest();//统计利息
            System.out.println(savingsAccount.getBalance());//1399 + 13.99 =1412.99
            savingsAccount.withdraw(100);//免手续
            System.out.println(savingsAccount.getBalance());//1412.99 -100 =1312.99
            savingsAccount.withdraw(100);//免手续
            savingsAccount.withdraw(100);//免手续
            System.out.println(savingsAccount.getBalance());//1412.99 -200 =1112.99
            savingsAccount.deposit(100);//扣手续费
            System.out.println(savingsAccount.getBalance());//1112.99 + 100 = 1212.99 - 1 = 1211.99
        }
    }
    ```

##### 练习7

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Point {
        private double x;
        private double y;
    
        public Point(double x, double y) {
            this.x = x;
            this.y = y;
        }
    }
    
    public class LabeledPoint extends Point {
        //特有属性
        private String label;
    
        public LabeledPoint(String label, double x, double y) {
            super(x, y);
            this.label = label;
        }
        //方法
    }
    
    public class Homework07 {
        public static void main(String[] args) {
            new LabeledPoint("Black",1929,230.07);
        }
    }
    
    ```

##### 练习8

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Doctor {
        //属性
        //{name, age, job, gender, sal}
        private String name;
        private int age;
        private String job;
        private char gender;
        private double sal;
        //5个参数的构造器
    
        public Doctor(String name, int age, String job, char gender, double sal) {
            this.name = name;
            this.age = age;
            this.job = job;
            this.gender = gender;
            this.sal = sal;
        }
    
        //方法
        //相应的getter()和setter()方法
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public int getAge() {
            return age;
        }
    
        public void setAge(int age) {
            this.age = age;
        }
    
        public String getJob() {
            return job;
        }
    
        public void setJob(String job) {
            this.job = job;
        }
    
        public char getGender() {
            return gender;
        }
    
        public void setGender(char gender) {
            this.gender = gender;
        }
    
        public double getSal() {
            return sal;
        }
    
        public void setSal(double sal) {
            this.sal = sal;
        }
    
        //重写父类(Object)的equals()方法：public boolean equals(Object obj)，并判断测试类中创建的两个对象是否相等。相等就是判断属性是否相同
        public boolean equals(Object obj) {
            //判断两个比较对象是否相同
            if (this == obj) {
                return true;
            }
            //判断obj 是否是 Doctor类型或其子类
            //过关斩将 校验方式
            if (!(obj instanceof Doctor)) { //不是的话
                return false;
            }
    
            //向下转型, 因为obj的运行类型是Doctor或者其子类型
            Doctor doctor = (Doctor)obj;	//???这里有些不明白，关于向下转型和向上转型
            return this.name.equals(doctor.name) && this.age == doctor.age &&
                    this.gender == doctor.gender && this.job.equals(doctor.job) && this.sal == doctor.sal;
        }
    }
    
    public class Homework8 {
        public static void main(String[] args) {
            //测试
            Doctor doctor1 = new Doctor("jack", 20, "牙科医生", '男', 20000);
            Doctor doctor2 = new Doctor("jack", 21, "牙科医生", '男', 20000);
    
            System.out.println(doctor1.equals(doctor2));//T
        }
    }
    ```

  - 有些不明白，关于向下转型和向上转型

##### 练习9

- 示例：

  - ```java
    package com.hspedu.homework.homework13;
    /*
    抽取一个父类Person类，将共同属性和方法放到Person类
     */
    public class Person {//父类
        //属性
        private String name;
        private char gender;
        private int age;
    
        //有参构造
        public Person(String name, char gender, int age) {
            this.name = name;
            this.gender = gender;
            this.age = age;
        }
    
        //getter and setter
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public char getGender() {
            return gender;
        }
    
        public void setGender(char gender) {
            this.gender = gender;
        }
    
        public int getAge() {
            return age;
        }
    
        public void setAge(int age) {
            this.age = age;
        }
    
        //编写一个play 方法, 把共有的输出内容写到父类
        public String play() {
            return name + "爱玩";
        }
        //返回一个基本信息
        /*
        姓名：张飞
        年龄：30
        性别：男    */
        public String basicInfo() {
            return "姓名: " + name + "\n年龄: " + age + "\n性别: " + gender;
        }
    
        @Override
        public String toString() {
            return "Person{" +
                    "name='" + name + '\'' +
                    ", gender=" + gender +
                    ", age=" + age +
                    '}';
        }
    }
    
    ```

  - ```java
    package com.hspedu.homework.homework13;
    
    /*
    Student类有名称（name），性别(sex),年龄（age），学号（stu_id），
    做合理封装，通过构造器在创建对象时将4个属性赋值。
    
    学生需要有学习的方法（study），在方法里写生“我承诺，我会好好学习。”
     */
    public class Student extends Person{ //
        //属性
        private String stu_id;
    
        //有参构造
        public Student(String name, char gender, int age, String stu_id) {
            super(name, gender, age);
            this.stu_id = stu_id;
        }
    
        public String getStu_id() {
            return stu_id;
        }
    
        public void setStu_id(String stu_id) {
            this.stu_id = stu_id;
        }
    
        //特有方法：学习方法
        public void study() {
            System.out.println(getName() + "承诺，我会好好学习 老韩讲的 java");
        }
    
        //重写父类的play方法，学生爱玩足球
        @Override
        public String play() {
            return super.play() + "足球";
        }
    
        //编写一个输出信息的方法，这样体现封装
        public void printInfo() {
            System.out.println("学生的信息:");
            System.out.println(super.basicInfo());
            System.out.println("学号: " + stu_id);
            study();    //组合， 变化万千
            System.out.println(play());
        }
    
        @Override
        public String toString() {
            return "Student{" +
                    "stu_id='" + stu_id + '\'' +
                    '}' + super.toString();
        }
    }
    
    ```

  - ```java
    package com.hspedu.homework.homework13;
    
    /*
    写一个Teacher类，Teacher类有名称（name），性别（sex），年龄（age），工龄（work_age),
    做合理封装，通过构造器在创建对象时将4个属性赋值
     */
    public class Teacher extends Person {
        //属性
        private int work_age;
    
        //方法
        public Teacher(String name, char gender, int age, int work_age) {
            super(name, gender, age);
            this.work_age = work_age;
        }
    
    
        public int getWork_age() {
            return work_age;
        }
    
        public void setWork_age(int work_age) {
            this.work_age = work_age;
        }
    
        //特有方法：教师需要有教学的方法（teach），在方法里写上“我承诺，我会认真教学。
        public void teach() {
            System.out.println(getName() + "承诺，我会认真教学 java...");
        }
    
        //重写父类的play方法，老师爱玩象棋
        @Override
        public String play() {
            return super.play() + "象棋";
        }
    
        //输出信息方法
        public void printInfo() {
            System.out.println("老师的信息：");
            System.out.println(super.basicInfo());
            System.out.println("工龄: " + work_age);
            teach();
            System.out.println(play());
        }
    
        @Override
        public String toString() {
            return "Teacher{" +
                    "work_age=" + work_age +
                    '}' + super.toString();
        }
    }
    
    ```

  - ```java
    package com.hspedu.homework.homework13;
    
    public class Homework13 {
        public static void main(String[] args) {
    
            //测试老师
            Teacher teacher = new Teacher("张飞", '男', 30, 5);
    
            teacher.printInfo();
    
            //测试学生
            Student student = new Student("小明", '男', 15, "00023102");
            System.out.println("-----------------------------------");
            student.printInfo();//封装
    
    
            //定义多态数组，里面保存2个学生和2个教师，要求按年龄从高到低排序
            Person[] persons = new Person[4];
            persons[0] = new Student("jack", '男', 10, "0001");
            persons[1] = new Student("mary", '女', 20, "0002");
            persons[2] = new Teacher("smith", '男', 36, 5);
            persons[3] = new Teacher("scott", '男', 26, 1);
    
            //创建对象
            Homework13 homework13 = new Homework13();
            homework13.bubbleSort(persons);
    
            //输出排序后的数组
            System.out.println("---排序后的数组-----");
            for(int i = 0; i < persons.length; i++) {
                System.out.println(persons[i]);
            }
    
            //遍历数组，调用test方法
            System.out.println("=======================");
            for (int i = 0; i < persons.length; i++) {//遍历多态数组
                homework13.test(persons[i]);
            }
    
        }
    
        //方法,完成年龄从高到底排序
        //定义在主类中，使用时创建一个主类对象
        public void bubbleSort(Person[] persons) {
            Person temp = null; //用于交换时临时保存对象
            for (int i = 0; i < persons.length - 1; i++) {
                for (int j = 0; j < persons.length - 1 - i; j++) {
                    //判断条件, 注意这里的条件可以根据需要变化。这里是根据年龄判断
                    if(persons[j].getAge() < persons[j+1].getAge()) {
                        temp = persons[j];
                        persons[j] = persons[j + 1];
                        persons[j + 1] = temp;
                    }
                }
            }
        }
    
        //定义方法，形参为Person类型，功能：调用学生的study或教师的teach方法
        //分析这里会使用到向下转型和类型判断
        public void test(Person p) {
            if(p instanceof Student) {//p 的运行类型如果是Student
                ((Student) p).study();  //向下转型后才能调用子类的特有方法
            } else if(p instanceof  Teacher) {
                ((Teacher) p).teach();
            } else {
                System.out.println("do nothing...");
            }
        }
    }
    ```

##### 练习10

- 问题描述：

  - 什么是多态？多态的具体体现有哪些（可举例说明）？

- 回答：

  - 多态：
    - 方法或对象具有多种形态，是 OOP 的第三大特征，是建立在封装和继承基础之上的
  - 多态具体体现：
    - 方法多态：
      - 重载体现多态
      - 重写体现多态
    - 对象多态：
      - 对象的编译类型和运行类型可以不一致，编译类型在定义时就确定，不能变化
      - 对象的运行类型是可以变化的，可以通过 `getClass()`来 查看运行类型
      - 编译类型看 = 的左边，运行类型看 = 的右边

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework15 {
        public static void main(String[] args) {
            AAA aaa = new AAA();
            System.out.println("aaa的运行类型：" + aaa.getClass());   //AAA
    
            AAA obj = new BBB();    //向上转型，父类引用指向子类对象
            AAA b1 = obj;
            System.out.println("obj的运行类型：" + obj.getClass());   //BBB
    
            obj = new CCC();//向上转型
            System.out.println("obj的运行类型：" + obj.getClass());   //CCC
    
            obj = b1;
            System.out.println("obj的运行类型：" + obj.getClass());   //BBB
        }
    }
    
    class AAA {//超类
    
    }
    class BBB extends AAA {//父类
    
    }
    class CCC extends BBB {//子类
    
    }
    ```

### （八）项目 - 房屋出租系统

#### 1.项目需求

- 实现基于文本界面的《房屋出租软件》，能够实现对房屋信息的添加、修改和删除（用数组实现），并能够打印房屋明细表

#### 2.项目界面

1. 主界面
2. 新增房源
3. 查找房源
4. 删除房源
5. 修改房源
6. 房屋列表
7. 退出系统

#### 3.系统设计

- 当软件比较复杂，需要模式管理，这里使用分层模式
- 分层模式：
  - 程序入口类（主类）：`HouseRentApp.java`
    - 创建界面类 HouseView 对象
    - 调用该对象，显示主菜单
  - 界面类：`HouseView.java`
    - 显示菜单
    - 接收用户输入
    - 调用业务层类 HouseService 对象，完成对房屋信息的各种操作
  - 业务层类：`HouseService.java`
    - 个人理解：这个类的作用可能是因为：代码实现过程中，对象的操作会有多次重复，可以将对对象的各种操作封装到一个类
    - 定义`House[]`，保存 House 对象
    - 响应 HouseView 的调用
    - 完成对房屋的各种操作，增删改查
  - 数据层类（domain / model）：`House.java`
    - 一个 House 对象表示一个房屋信息
  - 工具类：`Utility`
    - 完成获取用户的各种输入

#### 4.系统实现

##### 工具类 Utility

- 实现：

  - ```java
    package com.hspedu.houserent.utils;
    
    /*  工具类的作用:
    	处理各种情况的用户输入，并且能够按照程序员的需求，得到用户的控制台输入。   */
    //这里仅仅是会用老师提供的工具类，具体实现还要进一步研究理解
    
    import java.util.*;
    
    public class Utility {
    	//静态属性：
        private static Scanner scanner = new Scanner(System.in);
        
        /**
         * 功能：读取键盘输入的一个菜单选项，值：1——5的范围
         * @return 1——5
         */
    	public static char readMenuSelection() {
            char c;
            for (; ; ) {
                String str = readKeyBoard(1, false);//包含一个字符的字符串
                c = str.charAt(0);//将字符串转换成字符char类型
                if (c != '1' && c != '2' && 
                    c != '3' && c != '4' && c != '5') {
                    System.out.print("选择错误，请重新输入：");
                } else break;
            }
            return c;
        }
    
    	/**
    	 * 功能：读取键盘输入的一个字符
    	 * @return 一个字符
    	 */
        public static char readChar() {
            String str = readKeyBoard(1, false);//就是一个字符
            return str.charAt(0);
        }
        /**
         * 功能：读取键盘输入的一个字符，如果直接按回车，则返回指定的默认值；否则返回输入的那个字符
         * @param defaultValue 指定的默认值
         * @return 默认值或输入的字符
         */
        
        public static char readChar(char defaultValue) {
            String str = readKeyBoard(1, true);//要么是空字符串，要么是一个字符
            return (str.length() == 0) ? defaultValue : str.charAt(0);
        }
    	
        /**
         * 功能：读取键盘输入的整型，长度小于2位
         * @return 整数
         */
        public static int readInt() {
            int n;
            for (; ; ) {
                String str = readKeyBoard(10, false);//一个整数，长度<=10位
                try {
                    n = Integer.parseInt(str);//将字符串转换成整数
                    break;
                } catch (NumberFormatException e) {
                    System.out.print("数字输入错误，请重新输入：");
                }
            }
            return n;
        }
        /**
         * 功能：读取键盘输入的 整数或默认值，如果直接回车，则返回默认值，否则返回输入的整数
         * @param defaultValue 指定的默认值
         * @return 整数或默认值
         */
        public static int readInt(int defaultValue) {
            int n;
            for (; ; ) {
                String str = readKeyBoard(10, true);
                if (str.equals("")) {
                    return defaultValue;
                }
    			
    			//异常处理...
                try {
                    n = Integer.parseInt(str);
                    break;
                } catch (NumberFormatException e) {
                    System.out.print("数字输入错误，请重新输入：");
                }
            }
            return n;
        }
    
        /**
         * 功能：读取键盘输入的指定长度的字符串
         * @param limit 限制的长度
         * @return 指定长度的字符串
         */
    
        public static String readString(int limit) {
            return readKeyBoard(limit, false);
        }
    
        /**
         * 功能：读取键盘输入的指定长度的字符串或默认值，如果直接回车，返回默认值，否则返回字符串
         * @param limit 限制的长度
         * @param defaultValue 指定的默认值
         * @return 指定长度的字符串
         */
    	
        public static String readString(int limit, String defaultValue) {
            String str = readKeyBoard(limit, true);
            return str.equals("")? defaultValue : str;
        }
    
    
    	/**
    	 * 功能：读取键盘输入的确认选项，Y或N
    	 * 将小的功能，封装到一个方法中.
    	 * @return Y或N
    	 */
        public static char readConfirmSelection() {
            System.out.println("请输入你的选择(Y/N): 请小心选择");
            char c;
            for (; ; ) {//无限循环
            	//在这里，将接受到字符，转成了大写字母
            	//y => Y n=>N
                String str = readKeyBoard(1, false).toUpperCase();
                c = str.charAt(0);
                if (c == 'Y' || c == 'N') {
                    break;
                } else {
                    System.out.print("选择错误，请重新输入：");
                }
            }
            return c;
        }
    
        /**
         * 功能： 读取一个字符串
         * @param limit 读取的长度
         * @param blankReturn 如果为true ,表示 可以读空字符串。 
         * 					  如果为false表示 不能读空字符串。
         * 			
    	 *	如果输入为空，或者输入大于limit的长度，就会提示重新输入。
         * @return
         */
        private static String readKeyBoard(int limit, boolean blankReturn) {
            
    		//定义了字符串
    		String line = "";
    
    		//scanner.hasNextLine() 判断有没有下一行
            while (scanner.hasNextLine()) {
                line = scanner.nextLine();//读取这一行
               
    			//如果line.length=0, 即用户没有输入任何内容，直接回车
    			if (line.length() == 0) {
                    if (blankReturn) return line;//如果blankReturn=true,可以返回空串
                    else continue; //如果blankReturn=false,不接受空串，必须输入内容
                }
    
    			//如果用户输入的内容大于了 limit，就提示重写输入  
    			//如果用户如的内容 >0 <= limit ,我就接受
                if (line.length() < 1 || line.length() > limit) {
                    System.out.print("输入长度（不能大于" + limit + "）错误，请重新输入：");
                    continue;
                }
                break;
            }
    
            return line;
        }
    }
    
    ```

##### 数据层类 House

- 实现：

  - ```java
    package com.hspedu.houserent.domain;
    
    //这里不需要导入其他包
    
    //House的对象表示一个房屋信息
    
    public class House {
        //属性、有参构造、getter and setter、重写toString
    
        //编号  房主  电话  地址  月租  状态(未出租/已出租)
        private int id;     //房屋编号
        private String name;    //房主名字
        private String phone;   //房主电话
        private String address; //房屋地址
        private int rent;   //月租
        private String state;   //房屋状态
    
        //有参构造
        public House(int id, String name, String phone, String address, int rent, String state) {
            this.id = id;
            this.name = name;
            this.phone = phone;
            this.address = address;
            this.rent = rent;
            this.state = state;
        }
    
        public int getId() {
            return id;
        }
    
        public void setId(int id) {
            this.id = id;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public String getPhone() {
            return phone;
        }
    
        public void setPhone(String phone) {
            this.phone = phone;
        }
    
        public String getAddress() {
            return address;
        }
    
        public void setAddress(String address) {
            this.address = address;
        }
    
        public int getRent() {
            return rent;
        }
    
        public void setRent(int rent) {
            this.rent = rent;
        }
    
        public String getState() {
            return state;
        }
    
        public void setState(String state) {
            this.state = state;
        }
    
        //重写 toString，为了方便的输出对象信息
        //编号  房主  电话  地址  月租  状态(未出租/已出租)
        @Override
        public String toString() {
            return  id +
                    "\t\t" + name +
                    "\t" + phone +
                    "\t\t" + address +
                    "\t" + rent +
                    "\t" + state ;
        }
    }
    
    ```

##### 界面类 HouseView

- 分析：

  - 方法：
    - 显示主菜单：`mainMenu()`
    - 列出房屋信息：`liseHouses()`
    - 添加房源：`addHouse()`
    - 删除房源：`delHouse()`
    - 通过 id 查找房源：`findHouse()`
    - 修改房屋信息：`updateHouse()`

- 实现：

  - ```java
    package com.hspedu.houserent.view;
    
    import com.hspedu.houserent.domain.House;
    import com.hspedu.houserent.service.HouseService;
    import com.hspedu.houserent.utils.Utility;
    
    /**
     * 1. 显示界面
     * 2. 接收用户的输入
     * 3. 调用HouseService完成对房屋信息的各种操作
     */
    public class HouseView {
    
        private boolean loop = true; //控制显示菜单
        private char key = ' '; //接收用户选择
        private HouseService houseService = new HouseService(10);    //new一个业务层对象，设置数组的大小为10，最多存10条房屋信息
    
        //显示主菜单
        public void mainMenu() {
    
            do {
                System.out.println("\n=============房屋出租系统菜单============");
                System.out.println("\t\t\t1 新 增 房 源");
                System.out.println("\t\t\t2 查 找 房 屋");
                System.out.println("\t\t\t3 删 除 房 屋 信 息");
                System.out.println("\t\t\t4 修 改 房 屋 信 息");
                System.out.println("\t\t\t5 房 屋 列 表");
                System.out.println("\t\t\t6 退      出");
                System.out.print("请输入你的选择(1-6): ");
                key = Utility.readChar();   //为什么不用接收int类型
                switch (key) {
                    case '1':
                        addHouse(); //
                        break;
                    case '2':
                        findHouse();
                        break;
                    case '3':
                        delHouse();
                        break;
                    case '4':
                        updateHouse();
                        break;
                    case '5':
                        listHouses();
                        break;
                    case '6':
                        exit();
                        break;
                }
            } while (loop);
        }
    
        //1.添加房源：addHouse()
        //接收输入，创建House对象，调用 HouseService类 中的 add 方法
        public void addHouse() {
            System.out.println("=============添加房屋============");
            System.out.print("姓名: ");
            String name = Utility.readString(8);
            System.out.print("电话: ");
            String phone = Utility.readString(12);
            System.out.print("地址: ");
            String address = Utility.readString(16);
            System.out.print("月租: ");
            int rent = Utility.readInt();
            System.out.print("状态: ");
            String state = Utility.readString(3);
            //创建一个新的House对象, 注意id 是系统分配的，
            House newHouse = new House(0, name, phone, address, rent, state);   //这里的0只是暂时赋值，在add方法中会更新id
            if (houseService.add(newHouse)) {   //验证add方法是否调用成功
                System.out.println("=============添加房屋成功============");
            } else {
                System.out.println("=============添加房屋失败============");
            }
    
        }
    
        //2.查找房源：findHouse()
        //根据id查找房屋信息,调用 HouseService 中的 findById
        public void findHouse() {
            System.out.println("=============查找房屋信息============");
            System.out.print("请输入要查找的id: ");
            int findId = Utility.readInt();
            //调用方法
            House house = houseService.findById(findId);
            if (house != null) {
                System.out.println(house);  //重写过 toString 方法
            } else {
                System.out.println("=============查找房屋信息id不存在============");
            }
        }
    
        //3.删除房屋信息：delHouse()
        //接收输入的id，调用 HouseService 的del方法
        public void delHouse() {
            System.out.println("=============删除房屋信息============");
            System.out.print("请输入待删除房屋的编号(-1退出):");
            int delId = Utility.readInt();
            if (delId == -1) {
                System.out.println("=============放弃删除房屋信息============");
                return;
            }
            //注意工具类中的该方法本身就有循环判断的逻辑,必须输出Y/N
            char choice = Utility.readConfirmSelection();
            if (choice == 'Y') {    //确定要删除
                if (houseService.del(delId)) {
                    System.out.println("=============删除房屋信息成功============");
                } else {
                    System.out.println("=============房屋编号不存在，删除失败============");
                }
            } else {
                System.out.println("=============放弃删除房屋信息============");
            }
    
        }
    
        //4.修改房屋信息：updateHouse()
        //根据id修改房屋信息
        public void updateHouse() {
            System.out.println("=============修改房屋信息============");
            System.out.println("请选择待修改房屋编号(-1表示退出)");
            int updateId = Utility.readInt();
            if (updateId == -1) {
                System.out.println("=============放弃修改房屋信息============");
                return;
            }
    
            //根据输入得到updateId，查找对象
    
            //特别提示:返回的是引用类型[即:就是数组的元素]，地址相同，就是同一个对象
            //因此对house.setXxx() ,可以直接修改到 HouseService 中 houses数组的元素
            House house = houseService.findById(updateId);
            if (house == null) {
                System.out.println("=============修改房屋信息编号不存在..============");
                return;
            }
    
            System.out.print("姓名(" + house.getName() + "): ");
            String name = Utility.readString(8, "");    //注意：这里如果用户直接回车表示不修改该信息,默认""
            if (!"".equals(name)) { //？？？这里是什么
                house.setName(name);
            }
    
            System.out.print("电话(" + house.getPhone() + "):");
            String phone = Utility.readString(12, "");
            if (!"".equals(phone)) {
                house.setPhone(phone);
            }
            System.out.print("地址(" + house.getAddress() + "): ");
            String address = Utility.readString(18, "");
            if (!"".equals(address)) {
                house.setAddress(address);
            }
            System.out.print("租金(" + house.getRent() + "):");
            int rent = Utility.readInt(-1);
            if (rent != -1) {
                house.setRent(rent);
            }
            System.out.print("状态(" + house.getState() + "):");
            String state = Utility.readString(3, "");
            if (!"".equals(state)) {
                house.setState(state);
            }
            System.out.println("=============修改房屋信息成功============");
        }
    
        //5.房屋列表：listHouse()
        //显示房屋列表
        public void listHouses() {
            System.out.println("=============房屋列表============");
            System.out.println("编号\t\t房主\t\t电话\t\t地址\t\t月租\t\t状态(未出租/已出租)");
            House[] houses = houseService.list();   //得到所有房屋信息，返回存在HouseService类中的House数组
            for (int i = 0; i < houses.length; i++) {
                if (houses[i] == null) {//如果为null,就不用再显示了
                    break;
                }
                System.out.println(houses[i]);  //已经重写过了 toString 方法
            }
            System.out.println("=============房屋列表显示完毕============");
        }
    
        //6.退出
        //完成退出确认
        public void exit() {
            //这里我们使用Utility提供方法，完成确认
            char c = Utility.readConfirmSelection();
            if (c == 'Y') {
                loop = false;
            }
        }
    }
    
    ```

##### 业务层类

- 分析：

  - 方法：
    - 返回所有房屋信息：`list()`
    - 把新的 House 对象添加到 Houses[] 数组中：`add()`
    - 删除数组中的这个对象：`del()`
    - 根据 id 查找数组中的这个对象：`findById()`

- 实现：

  - ```java
    package com.hspedu.houserent.service;
    
    import com.hspedu.houserent.domain.House;   //需要导入包含房屋信息类
    
    /*HouseService.java    业务层类
          定义House[] ,保存House对象
          1. 响应HouseView的调用
          2. 完成对房屋信息的各种操作(增删改查c[create]、r[read]、u[update]、d[delete])       */
    
    public class HouseService {
    
        private House[] houses;     //保存House对象
        private int houseNums = 1;  //记录当前有多少个房屋信息
        private int idCounter = 1;  //记录当前的id增长到哪个值
    
        //构造器
        public HouseService(int size) {
            //new houses
            houses = new House[size];//当创建HouseService对象，指定数组大小
            //为了配合测试列表信息，这里初始化一个House对象
            houses[0] = new House(1,"jack","112", "海淀区", 2000, "未出租");
        }
    
        //add方法，添加新对象,返回boolean
        //对应 HouseView 的 addHouse 方法
        public boolean add(House newHouse) {
            //判断是否还可以继续添加(知识储备不足，暂时不考虑数组扩容的问题，但实际是肯定需要考虑扩容的问题)
            if(houseNums == houses.length) {    //不能再添加
                System.out.println("数组已满，不能再添加了...");
                return false;
                //数组扩容
            }
            //把newHouse对象加入到，新增加了一个房屋
            houses[houseNums++] = newHouse;
            //需要设计一个id自增长的机制, 然后更新 newHouse 的 id
            newHouse.setId(++idCounter);
            return true;
        }
    
        //findById方法,返回House对象或者null
        //对应 HouseView 的 findHouse 方法
        public House findById(int findId) {
            //遍历数组
            for(int i = 0; i < houseNums; i++) {
                if(findId == houses[i].getId()) {
                    return houses[i];
                }
            }
            return null;    //若遍历完毕没有找到，则返回null
        }
    
        //del方法，删除一个房屋信息
        //对应 HouseView 中的 delHouse 方法
        public boolean del(int delId) {
    
            //应当先找到要删除的房屋信息对应的下标
            //一定要搞清楚 下标和房屋的编号不是一回事
            int index = -1; //用于保存根据id找到的房屋的数组下标
            for(int i = 0; i < houseNums; i++)  {
                if(delId == houses[i].getId()) {    //要删除的房屋(id),是数组下标为i的元素
                    index = i;//就使用index记录i
                }
            }
    
            if(index == -1) {   //说明delId在数组中不存在，没有找到
                return false;
            }
    
            //如果找到，则将这个房屋信息后面的所有房屋信息依次前移
            for(int i = index; i < houseNums - 1; i++) {
                houses[i] = houses[i+1];
            }
            //把当有存在的房屋信息的最后一个 设置null
            houses[--houseNums] = null; //比如：现在一共6条房屋信息，最后一条房屋信息的数组下标未5，将它置为null，并将nums减一
            return true;
        }
    
        //list方法，返回houses
        //对应 HouseView 中的 listHouses 方法
        public House[] list() {
            return houses;
        }
    }
    ```

##### 程序入口

- 主类：

  - ```java
    package com.hspedu.houserent;
    
    import com.hspedu.houserent.view.HouseView;
    
    public class HouseRentApp {
        public static void main(String[] args) {
    
            //创建HouseView对象,并且显示主菜单，是整个程序的入口
            new HouseView().mainMenu(); //匿名对象，不是静态方法
            System.out.println("===你退出房屋出租系统==");
        }
    }
    ```



## 二.第二阶段：提升编程思想

### （一）面向对象编程高级

#### 1.类变量和类方法

##### 类变量快速入门

- 问题描述：

  - 有一群小孩在玩堆雪人，不时有新的小孩加入，请问如何知道现在共有多少人在玩？编写程序解决

- 思路：

  - 在 main 方法中定义一个变量 count
  - 当一个小孩加入就 count++

- 存在问题分析：

  - count 是一个独立于对象的变量
  - 访问 count 时，没有用到 OOP
  - 因此，引入 类变量 / 类方法

- 思考：

  - 设计一个 `int count` 表示总人数，我们在创建一个小孩时，就把 `count` 加 1，并且 count 是所有对象共享的就 ok 了，使用类变量来解决

- 示例：

  - ```java
    package com.hspedu.static_;
    
    public class ChildGame {
    
        public static void main(String[] args) {
    
            //定义一个变量 count, 统计有多少小孩加入了游戏
            //这个是原有技术，不是类变量
            int count = 0;
    
            Child child1 = new Child("白骨精");
            child1.join();
            //count++;
            //这里是类变量
            child1.count++;
    
            Child child2 = new Child("狐狸精");
            child2.join();
            //count++;
            child2.count++;
    
            Child child3 = new Child("老鼠精");
            child3.join();
            //count++;
            child3.count++;
    
            //类变量，可以通过类名来访问
            System.out.println("共有 " + Child.count  + " 名小孩加入了游戏...");  //3
            //下面的代码输出什么?    //所有对象都可以共享访问同一个类变量
            System.out.println("child1.count：" + child1.count); //3
            System.out.println("child2.count：" + child2.count); //3
            System.out.println("child3.count：" + child3.count); //3
        }
    }
    
    class Child { //类
        private String name;    //定义一个变量 count ,是一个类变量(静态变量) static 静态
        //该变量最大的特点就是会被Child 类的所有的对象实例共享
        public static int count = 0;
        public Child(String name) {
            this.name = name;
        }
        public void join() {
            System.out.println(name + " 加入了游戏..");
        }
    }
    ```

##### 类变量内存布局

- 有的地方说类的静态变量存在方法区、有的地方说存在堆区，这与 jdk 的版本有关。（这不重要）
- 只需要记住，static 变量是共享的
- 不管 static 变量在哪里
  - static 变量是同一个类所有对象共享的
  - static 类变量，在类加载的时候就生成了

##### 类变量是什么

- 类变量，也叫 静态变量、静态属性，是该类所有对象共享的变量，任何一个该类的对象去访问它的时候，取到的都是相同的值，同样任何一个该类的对象去修改它的时候，修改的也是同一个变量

##### 如何定义类变量

- 定义语法：

  - ```java
    访问修饰符 static 数据类型 变量名;	//推荐
    static 访问修饰符 数据类型 变量名;	//不推荐
    ```

##### 如何访问类变量

- 访问语法：

  - ```java
    类名.类变量名		//推荐
    对象名.类变量名
    ```

- 示例：

  - ```java
    package com.hspedu.static_;
    
    public class VisitStatic {
        public static void main(String[] args) {
    
            //方式1：类名.类变量名
            //说明：类变量是随着类的加载而创建，所以即使没有创建对象实例也可以访问
            System.out.println(A.name);
            A a = new A();
    
            //方式2：通过对象名.类变量名
            System.out.println("a.name=" + a.name);
        }
    }
    
    class A {
        //类变量
        //类变量的访问，必须遵守 相关的访问权限.
        public static String name = "韩顺平教育";
        //普通属性/普通成员变量/非静态属性/非静态成员变量/实例变量
        private int num = 10;
    }
    ```

##### 类变量使用细节

- 类变量使用注意事项和细节讨论：

  1. 什么时候需要使用类变量：
     - 当我们需要让某个类的所有对象都共享一个对象时，就可以考虑使用类变量（静态变量）
  2. 类变量与实例变量（普通属性的区别）：
     - 类变量是该类的所有对象共享的，而实例变量是每个对象独享的
  3. 加上 static 称为类变量或静态变量，否则称为实例变量、普通变量、非静态成员变量、非静态变量
  4. 类变量可以通过 `类名.类变量名` 或 ` 对象名.类变量名` 来访问，但推荐使用第一种方式（前提是满足修饰符的访问权限和范围）
  5. 实例变量不能 ` 类名.变量名` 的方式来访问
  6. 类变量是在类加载时就初始化了，也就是说，即使没有创建对象，只要类加载了就可以使用类变量了
  7. 类变量的生命周期是随类的加载开始，随着类的消亡而销毁的

- 示例：

  - ```java
    package com.hspedu.static_;
    
    public class StaticDetail {
        public static void main(String[] args) {
            B b = new B();
            //System.out.println(B.n1);
            System.out.println(B.n2);
    
            //静态变量是类加载的时候，就创建了,所以我们没有创建对象实例
            //也可以通过类名.类变量名来访问
            System.out.println(C.address);
    
        }
    }
    
    class B {
        public int n1 = 100;
        public static int n2 = 200;
    }
    
    class C {
        public static String address = "北京";
    }
    ```

##### 类方法基本介绍

- 类方法，也叫静态方法
- 形式如下：
  - `访问修饰符 static 数据类型 方法名(){}	//推荐`
  - `static 访问修饰符 数据类型 方法名(){}`

##### 类方法的调用

- 使用方式：

  - 类名.类方法名	（推荐）
  - 对象名.类方法名

- 类方法的经典使用场景：

  - 当方法中不涉及到任何和对象相关的成员，则可以将方法设计为静态方法，提高开发效率
    - 比如：
      - 工具类中的方法
      - Math类、Arrays类、Collections类
  - 在程序员实际开发中，往往会将一些通用的方法，设计成静态方法，这样我们就不需要创建对象就可以使用

- 示例：

  - ```java
    package com.hspedu.static_;
    
    public class StaticMethod {
        public static void main(String[] args) {
            //创建2个学生对象，叫学费
            Stu tom = new Stu("tom");
            //tom.payFee(100);
            Stu.payFee(100);    //调用方式正确
    
            Stu mary = new Stu("mary");
            //mary.payFee(200);
            Stu.payFee(200);//对
    
    
            //输出当前收到的总学费
            Stu.showFee();  //300
    
            //如果我们希望不创建实例，也可以调用某个方法(即当做工具来使用)
            //这时，把方法做成静态方法时非常合适
            System.out.println("9开平方的结果是=" + Math.sqrt(9));
            System.out.println(MyTools.calSum(10, 30));
        }
    }
    //开发自己的工具类时，可以将方法做成静态的，方便调用
    class MyTools  {
        //求出两个数的和
        public static double calSum(double n1, double n2) {
            return  n1 + n2;
        }
        //可以写出很多这样的工具方法...
    }
    class Stu {
        private String name;    //普通成员
        //定义一个静态变量，来累积学生的学费
        private static double fee = 0;
    
        public Stu(String name) {
            this.name = name;
        }
        //说明
        //1. 当方法使用了static修饰后，该方法就是静态方法
        //2. 静态方法就可以访问静态属性/变量
        public static void payFee(double fee) {
            Stu.fee += fee; //累积学生的学费
        }
        public static void showFee() {
            System.out.println("总学费有:" + Stu.fee);
        }
    }
    ```

##### 类方法使用注意事项和细节讨论

- 类方法使用注意事项和细节讨论:

  1. 类方法和普通方法都是随着类的加载而加载，将结构信息存储在方法区：类方法中无this参数，普通方法中隐含this参数
  2. 类方法可以通过类名调用，也可以通过对象名调用
  3. 普通方和对象有关，需要通过对象名调用，不能通过类名调用
  4. 类方法中不允许使用和对象有关的关键字，比如 this 和 super。普通方法（成员方法）可以
  5. 类方法（静态方法）中 只能访问 静态变量 或静态方法
  6. 普通成员方法，既可以访问非静态成员，也可以访问静态成员

- 示例：

  - ```java
    package com.hspedu.static_;
    
    public class StaticMethodDetail {
        public static void main(String[] args) {
    
            D.hi();//ok
            //非静态方法，不能通过类名调用
            //D.say();   //非静态方法，不能通过类名调用，需要先创建对象，再调用
            new D().say();  //可以    //这里是通过创建匿名对象调用
        }
    }
    class D {
    
        private int n1 = 100;
        private static  int n2 = 200;
    
        public void say() {//非静态方法,普通方法
    
        }
    
        public static void hi() {//静态方法,类方法
            //System.out.println(this.n1);  //类方法中不允许使用和对象有关的关键字，比如this和super。普通方法(成员方法)可以。
        }
    
        //类方法(静态方法)中 只能访问 静态变量 或静态方法
        //口诀:静态方法只能访问静态成员.
        public static void hello() {
            System.out.println(n2);
            System.out.println(D.n2);
            //System.out.println(this.n2);  不能使用
            hi();   //OK
            //say();    //错误，静态方法不能调用非静态方法
        }
    
        //普通成员方法，既可以访问  非静态成员，也可以访问静态成员
        //小结: 非静态方法可以访问 静态成员和非静态成员
        public void ok() {
            //非静态成员
            System.out.println(n1);
            say();
            //静态成员
            System.out.println(n2);
            hello();
        }
    }
    ```

##### 练习

- 练习1：

  - ```java
    package com.hspedu.static_;
    
    public class StaticExercise01 {
        
    }
    
    class Test {
        static int count = 9;
        public void count() {
            System.out.println("count = " + (count++));
        }
        public static void main(String args[]) {
            new Test().count();     //9
            new Test().count();     //10
            System.out.println(Test.count);	    //11
        }
    }
    ```

- 练习2：

  - ```java
    package com.hspedu.static_;
    
    public class StaticExercise02 {
    
    }
    class Person {  //StaticExercise02.java 2min 时间
        private int id;
        private static int total = 0;
    
        public Person() {//构造器
            total++;  //total = 1
            id = total; //id = 1
        }
    
        public static int getTotalPerson() {
            //id++; //错误, 注销    //因为静态方法不可以访问非静态属性
            return total;
        }
    
    }
    class TestPerson {
        public static void main(String[] args) {
            System.out.println("Number of total is " +Person.getTotalPerson()); //0
            Person p1 = new Person();
            System.out.println( "Number of total is "+ Person.getTotalPerson()); //1
        }
    }
    ```

- 练习3：

  - ```java
    package com.hspedu.static_;
    
    public class StaticExercise03 {
    }
    
    class Person { //StaticExercise03.java 2min 看
        private int id;
        private static int total = 0;
        
        public Person() {//构造器
            total++;
            id = total;
        }
        
        public static void setTotalPerson(int total){
            // this.total = total;//错误，因为在static方法中，不可以使用this 关键字
    
            Person.total = total;
        }
        
        //编写一个方法，输出total的值
        public static void m() {
            System.out.println("total的值：" + total);
        }
    }
    class TestPerson {
        public static void main(String[] args) {
    
            Person.setTotalPerson(3);
            new Person(); //无参构造器中total++，变成4
            Person.m();//4
        }
    }
    ```

  - 小结：

    - 静态方法只能访问静态成员
    - 非静态方法可以访问所有成员
    - 仍然要遵守访问权限

#### 2.理解 main 方法语法

##### 深入理解 main 方法

- 解释 main 方法的形式：`public static void main(String[] args){}`
  1. main 方法是虚拟机调用
  2. Java 虚拟机需要调用类的 main 方法，所以该方法的访问权限必须是 public
  3. Java 虚拟机在执行 main 方法时不必创建对象，所以该方法必须是 static
  4. 该方法接收 String 类型的数组参数，该数组中保存执行 java 命令时传递给所运行的类的参数
  5. java 执行的程序 参数1 参数2 参数3

##### 特别提示

- 在 main 方法中，我们可以直接调用 main 方法所在类的静态方法或静态属性

- 但是不能直接访问该类中的非静态成员，必须创建该类的一个实例对象后，才能通过这个对象去访问类中的非静态成员

- 示例：

  - ```java
    package com.hspedu.main_;
    
    public class Main01 {
    
        //静态的变量/属性
        private static  String name = "韩顺平教育";
        //非静态的变量/属性
        private int n1 = 10000;
    
        //静态方法
        public static  void hi() {
            System.out.println("Main01的 hi方法");
        }
        //非静态方法
        public void cry() {
            System.out.println("Main01的 cry方法");
        }
    
        public static void main(String[] args) {
            
            //1. 静态方法main 可以访问本类的静态成员
            System.out.println("name：" + name);
            hi();
            
            //2. 静态方法main 不可以访问本类的非静态成员
            //System.out.println("n1：" + n1);//错误
            //cry();
            
            //3. 静态方法main 要访问本类的非静态成员，需要先创建对象 , 再调用即可
            Main01 main01 = new Main01();
            System.out.println(main01.n1);//ok
            main01.cry();
        }
    }
    ```

##### 案例演示

- 想要在 IDEA 中运行程序时像命令行一样添加参数，如何传递参数

  - `java 主类名 参数1 参数2 参数3` 

- 示例：

  - ```java
    package com.hspedu.main_;
    
    public class Main02 {
        public static void main(String[] args) {
            for ( int i = 0; i < args.length; i++ ) {	//args.length 为命令行参数个数
                System.out.println("args[" + i + "] ： " + args[i]);
            }
        }
    }
    ```

  - 在右上角 Main02 窗口点开、Edit Configurations、Program arguments 中添加参数（用空格隔开）

#### 3.代码块

##### 基本介绍

- 代码块：又称初始化块，属于类中的成员（是类的一部分），类似于方法，将逻辑语句封装在方法体中，通过`{}`包围起来
- 但和方法不同，没有方法名，没有返回，没有参数，只有方法体，而且不用通过对象或类显式调用，而是加载类时，或创建对象时隐式调用

##### 基本语法

- 语法：

  - ```java
    [修饰符]{
        代码;
    };
    ```


- 注意：
  - 修饰符可选，要写的话只能写 static
  - 代码块分为两类，使用 static 修饰的叫静态代码块，没有 static 修饰的叫普通代码块 / 非静态代码块
  - 逻辑语句可以分为任何逻辑语句（输入、输出、方法调用、循环、判断等）
  - 分号`;`可以写上，也可以省略

##### 代码块的好处和案例演示

- 代码块的好处：

  - 相当于另外一种形式的构造器（对构造器的补充机制），可以做到初始化的操作
  - 场景：如果构造器中都有重复的语句，可以抽取到初始化块中，提高代码的重用性

- 示例：

  - ```java
    package com.hspedu.codeblock_;
    
    public class CodeBlock01 {
        public static void main(String[] args) {
    
            Movie movie = new Movie("你好，李焕英");    //第一个构造器
            System.out.println("======================");
            Movie movie2 = new Movie("bbb", 200, "nnn");    //第二个构造器
            System.out.println("======================");
            Movie movie3 = new Movie("唐探3", 100, "陈思诚");    //第三个构造器
        }
    }
    
    class Movie {
        private String name;
        private double price;
        private String director;
    
        //3个构造器，重载
        /*解读：
            (1) 下面的三个构造器都有相同的语句
            (2) 这样代码看起来比较冗余
            (3) 这时我们可以把相同的语句，放入到一个代码块中，即可
            (4) 这样当我们不管调用哪个构造器，创建对象，都会先调用代码块的内容
            (5) 代码块调用的顺序优先于构造器..      */
    
        {
            System.out.println("电影屏幕打开...");
            System.out.println("广告开始...");
            System.out.println("电影正是开始...");
        };
    
        public Movie(String name) {
            System.out.println("Movie(String name) 被调用...");
            this.name = name;
        }
    
        public Movie(String name, double price) {
    
            this.name = name;
            this.price = price;
        }
    
        public Movie(String name, double price, String director) {
    
            System.out.println("Movie(String name, double price, String director) 被调用...");
            this.name = name;
            this.price = price;
            this.director = director;
        }
    }
    ```

##### 代码块使用注意事项和细节讨论

- 代码块使用注意事项和细节讨论：

  1. static 代码块也叫静态代码块，作用就是对类进行初始化，而且它随着类的加载而执行，并且只会执行一次。如果是普通代码块，每创建一个对象，都会执行一次
  2. 类什么时候会被加载（！！！很重要）
     1. 创建对象实例时（new）
     2. 创建子类对象实例，父类也会被加载
     3. 使用类的静态成员时（静态成员，静态方法）
  3. 普通的代码块，在创建对象实例时，会被隐式调用。被创建一次，就会被调用一次。如果只是使用类的静态成员时，普通代码块并不会执行
  4. 创建一个对象时，才一个类的调用顺序：（重点、难点）
     1. 调用静态代码块和静态属性初始化（注意：静态代码块和静态属性初始化调用的优先级一样，如果有多个静态代码块和多个静态变量初始化，则按它们定义的调用顺序调用）
     2. 调用普通代码块和普通属性初始化（注意：普通代码块和普通属性初始化调用的优先级一样，如果有多个普通代码块和多个普通变量初始化，则按它们定义的调用顺序调用）
     3. 调用构造方法
  5. 构造方法（构造器）的最前面隐含了调用 `super()`和调用普通代码块。静态相关的代码块、属性初始化，在类加载时，就执行完毕了，因此是优先于普通代码块和构造器执行的
  6. 创建一个子类时（继承关系），它们的静态代码块、静态属性初始化、普通代码块、普通属性初始化、构造方法的调用顺序：
     1. 父类的静态代码块和静态属性（优先级一样，按定义的顺序执行）
     2. 子类的静态代码块和静态属性（优先级一样，按定义的顺序执行）
     3. 父类的普通代码块和普通属性初始化（优先级一样，按定义的顺序执行）
     4. 父类的构造方法（优先级一样，按定义的顺序执行）
     5. 子类的普通代码块和普通属性初始化
     6. 子类的构造器
  7. 静态代码块只能直接调用静态成员（静态属性和静态方法），普通代码块可以调用任意成员

- 示例1（包含细节 1~3 ）：

  - ```java
    package com.hspedu.codeblock_;
    
    public class CodeBlockDetail01 {
        public static void main(String[] args) {
    
            //类被加载的情况举例
            //1. 创建对象实例时(new)
            //BB bb = new BB();
            //AA aa = new AA();
            //2. 创建子类对象实例，父类也会被加载, 而且，父类先被加载，子类后被加载
            //AA aa2 = new AA();
            //3. 使用类的静态成员时(静态属性，静态方法)
            //System.out.println(Cat.n1);
    
            //static代码块，是在类加载时，执行的，而且只会执行一次.
    //        DD dd = new DD();
    //        DD dd1 = new DD();
    
            //普通的代码块，在创建对象实例时，会被隐式的调用。(匿名方式创建也会调用)
            // 被创建一次，就会调用一次。
            // 如果只是使用类的静态成员时，普通代码块并不会执行
            //new DD().add();
    
            //System.out.println(DD.n1);    //8888, 静态模块块一定会执行    //普通代码块不会执行
    
        }
    }
    
    class BB {
        //静态代码块
        static {
            System.out.println("BB 的静态代码1被执行...");//1
        }
    }
    
    class AA extends BB {
        //静态代码块
        static {
            System.out.println("AA 的静态代码1被执行...");//2
        }
    }
    
    class DD {
        public static int n1 = 8888;//静态属性
        //静态代码块
        static {
            System.out.println("DD 的静态代码1被执行...");//
        }
        //普通代码块, 在new 对象时，被调用，而且是每创建一个对象，就调用一次
        //可以这样简单的，理解 普通代码块是构造器的补充
        {
            System.out.println("DD 的普通代码块...");
        }
    
        public void add()
        {
            System.out.println("DD 的 add 方法被调用");
        }
    }
    
    class Animal {
        //静态代码块
        static {
            System.out.println("Animal 的静态代码1被执行...");//
        }
    }
    
    class Cat extends Animal {
    
        public static  int n1 = 999;//静态属性
    
        //静态代码块
        static {
            System.out.println("Cat 的静态代码1被执行...");//
        }
    }
    ```

- 示例2（包含细节 4）：

  - ```java
    package com.hspedu.codeblock_;
    
    public class CodeBlockDetail02 {
        public static void main(String[] args) {
            A a = new A(); 
        }
    }
    
    class A {
        { //普通代码块
            System.out.println("A 普通代码块01");
        }
    
        private int n2 = getN2();   //普通属性的初始化  //注意这里是普通属性的赋值调用了普通方法，会在静态之后，构造器之前
        //private int n3 = getN1();   //这里普通属性的赋值调用了静态方法
    
    
        static { //静态代码块
            System.out.println("A 静态代码块01");
        }
    
        //静态属性的初始化
        private static  int n1 = getN1();
        //private static  int n4 = getN2(); //注意，静态属性的赋值不可以调用非静态方法
    
        public static int getN1() {
            System.out.println("静态方法 getN1 被调用...");
            return 100;
        }
        public int getN2() { //普通方法/非静态方法
            System.out.println("普通方法 getN2 被调用...");
            return 200;
        }
    
        //无参构造器
        public A() {
            System.out.println("A() 构造器被调用");
        }
    }
    ```

- 示例3（包含细节 5）：


    - ```java
      package com.hspedu.codeblock_;
      
      public class CodeBlockDetail03 {
          public static void main(String[] args) {
              new BBB();  //(1)AAA的普通代码块(2)AAA() 构造器被调用(3)BBB的普通代码块(4)BBB() 构造器被调用
          }
      }
      
      class AAA { //父类Object
          {
              System.out.println("AAA的普通代码块");
          }
          public AAA() {
              //(1)super()
              //(2)调用本类的普通代码块
              System.out.println("AAA() 构造器被调用....");
          }
      }
      
      class BBB extends AAA  {
          {
              System.out.println("BBB的普通代码块...");
          }
          public BBB() {
              //(1)super()
              //(2)调用本类的普通代码块
              System.out.println("BBB() 构造器被调用....");
          }
      }
      ```



  - 示例4（包含细节 6、7）：


    - ```java
      package com.hspedu.codeblock_;
      
      public class CodeBlockDetail04 {
          public static void main(String[] args) {
              //(1) 进行类的加载
              //     1.1 先加载 父类 A02 1.2 再加载 B02
              //(2) 创建对象
              //     2.1 从子类的构造器开始
              new B02();//对象
              /*
              1.先加载静态：
                  父类的静态属性和静态代码块
                  子类的静态属性和静态代码块
              2.父类构造器：
                  父类普通属性和普通代码块
                  父类构造
              3.子类构造器：
                  子类普通属性和普通代码块
                  子类构造
      
              */
      
              new C02();
          }
      }
      
      class A02 { //父类
          //静态属性
          private static int n1 = getVal01();
      
          //静态代码块
          static {
              System.out.println("A02的一个静态代码块..");//(2)
          }
      
          //普通代码块
          {
              System.out.println("A02的第一个普通代码块..");//(5)
          }
      
          //普通属性
          public int n3 = getVal02();//普通属性的初始化
      
          //静态方法
          public static int getVal01() {
              System.out.println("A02静态属性创建时调用静态方法getVal01");//(1)
              return 10;
          }
      
          //普通方法
          public int getVal02() {
              System.out.println("A02普通属性初始化时调用的普通方法getVal02");//(6)
              return 10;
          }
      
          public A02() {//构造器
              /*隐藏：
                  1.super()
                  2.普通代码和普通属性的初始化......       */
              System.out.println("A02的构造器");//(7)
          }
      }
      
      class B02 extends A02 { //
      
          private static int n3 = getVal03();
      
          static {
              System.out.println("B02的一个静态代码块..");//(4)
          }
          public int n5 = getVal04();
          {
              System.out.println("B02的第一个普通代码块..");//(9)
          }
      
          public static int getVal03() {
              System.out.println("B02的静态属性创建时调用的静态方法getVal03");//(3)
              return 10;
          }
      
          public int getVal04() {
              System.out.println("B02的普通属性初始化时调用的普通方法getVal04");//(8)
              return 10;
          }
          //一定要慢慢的去品..
          public B02() {//构造器
              //隐藏了
              //super()
              //普通代码块和普通属性的初始化...
              System.out.println("B02的构造器");//(10)
              // TODO Auto-generated constructor stub
          }
      }
      
      class C02 {
          private int n1 = 100;
          private static  int n2 = 200;
      
          private void m1() {
      
          }
          private static void m2() {
      
          }
      
          static {
              //静态代码块，只能调用静态成员
              //System.out.println(n1);错误
              System.out.println(n2);//ok
              //m1();//错误
              m2();
          }
          {
              //普通代码块，可以使用任意成员
              System.out.println(n1);
              System.out.println(n2);//ok
              m1();
              m2();
          }
      }
      ```

##### 练习

- 练习1：

  - ```java
    package com.hspedu.codeblock_;
    
    public class CodeBlockExercise01 {
    }
    class Person {
        public static int total;    //静态变量
        static {    //静态代码块
            total = 100;
            System.out.println("in static block!"); 
        }
    }
    
    class Test {
        public static void main(String[] args) {
            System.out.println("total = "+ Person.total); //100
            System.out.println("total = "+ Person.total); //100
        }
    }
    ```

- 练习2：

  - ```java
    package com.hspedu.codeblock_;
    
    public class CodeBlockExercise02 {
        
    }
    
    class Sample
    {
        Sample(String s)
        {
            System.out.println(s);
        }
        Sample()
        {
            System.out.println("Sample默认构造函数被调用");
        }
    }
    class Test{
        Sample sam1 = new Sample("sam1成员初始化");//
        static Sample sam = new Sample("静态成员sam初始化 ");//
        static{
            System.out.println("static块执行");//
            if(sam == null)
                System.out.println("sam is null");
        }
    
        Test()//构造器
        {
            System.out.println("Test默认构造函数被调用");//
        }
    
        //主方法
        public static void  main(String  str[])
        {
            Test a = new Test();  //无参构造器
        }
    }
    ```

#### 4.单例设计模式

##### 什么是设计模式

- 设计模式：
  - 静态方法和属性的经典使用
  - 设计模式是在大量的实践中总结和理论化后优选的代码结构、编程风格、以及解决问题的思考模式。设计模式就像是经典的棋谱，不同的棋局，我们用不同的棋谱，免去自己思考和摸索的过程
- 总体来说设计模式分为三大类：
  - 创建型模式，共五种：
    - 工厂方法模式
    - 抽象工厂模式
    - 单例模式
    - 建造者模式
    - 原型模式
  - 结构型模式，共七种：
    - 适配器模式
    - 装饰器模式
    - 代理模式
    - 外观模式
    - 桥接模式
    - 组合模式
    - 享元模式
  - 行为型模式，共十一种：
    - 策略模式
    - 模板方法模式
    - 观察者模式
    - 迭代子模式
    - 责任链模式
    - 命令模式
    - 备忘录模式
    - 状态模式
    - 访问者模式
    - 中介者模式
    - 解释器模式

##### 什么是单例模式

- 单例（单个的实例）：
  - 所谓类的单例设计模式，就是采取一定的方法保证在整个的软件系统中，对某个类只能存在一个对象实例，并且该类只能提供一个取得其对象实例的方法
  - 单例模式有两种方式：
    1. 饿汉式
    2. 懒汉式
- 补充英文：
  - instance：实例

##### 单例模式应用实例

- 演示饿汉式和懒汉式单例模式，步骤如下：

  1. 构造器私有化，防止直接 new
  2. 类的内部创建对象
  3. 向外暴露一个静态的公共方法：`getInstance`

- 饿汉式示例：

  - ```java
    package com.hspedu.single_;
    
    public class SingleTon01 {
    
        public static void main(String[] args) {
            /*
            按照传统的方法，可以创建多个对象
            GirlFriend xh = new GirlFriend("小红");
            GirlFriend xb = new GirlFriend("小白");       */
    
            //通过方法可以获取对象
            GirlFriend instance = GirlFriend.getInstance();
            System.out.println(instance);
    
            GirlFriend instance2 = GirlFriend.getInstance();
            System.out.println(instance2);
    
            System.out.println(instance == instance2);  //T，是同一个对象
    
            //System.out.println(GirlFriend.n1);
        }
    }
    
    //有一个类， GirlFriend
    //只能有一个女朋友
    class GirlFriend {
    
        private String name;
    
        //private static int n1 = 100;
    
        //为了能够在静态方法中，返回 gf对象，需要将其修饰为static（静态方法只能调用静态属性）
        //对象，通常是重量级的对象，饿汉式可能造成创建了对象，但是没有调用（如仅仅调用其他静态属性，对象会自动创建，但没有使用）
        private static GirlFriend gf = new GirlFriend("小红红");
    
        //如何保障我们只能创建一个 GirlFriend 对象
        /*步骤[单例模式-饿汉式]：
            1. 将构造器私有化
            2. 在类的内部直接创建对象(该对象是static)
            3. 提供一个公共的static方法，返回 gf对象      */
        private GirlFriend(String name) {
            System.out.println("构造器被调用");
            this.name = name;
        }
    
        public static GirlFriend getInstance() {
            return gf;
        }
    
        @Override
        public String toString() {
            return "GirlFriend{" +
                    "name='" + name + '\'' +
                    '}';
        }
    }
    ```

- 懒汉式示例：

  - ```java
    package com.hspedu.single_;
    
    //演示懒汉式的单例模式
    public class SingleTon02 {
        public static void main(String[] args) {
            //new Cat("大黃");    //private不可以创建在类外创建
            //System.out.println(Cat.n1);
    
            Cat instance = Cat.getInstance();
            System.out.println(instance);
    
            //再次調用getInstance
            Cat instance2 = Cat.getInstance();
            System.out.println(instance2);
    
            System.out.println(instance == instance2);//T
        }
    }
    
    //希望在程序运行过程中，只能创建一个Cat对象
    //使用單例模式
    class Cat {
        private String name;
        public static  int n1 = 999;
        private static Cat cat ; //默认是null
    
        /*步骤：
            1.仍然构造器私有化
            2.定义一個static静态属性对象
            3.提供一個public的static方法，可以返回一个Cat对象
            4.懒汉式，只有当用户使用getInstance时，才返回cat对象，后面再次调用时，会返回上次创建的cat对象，从而保证了单例    */
    
        private Cat(String name) {
            System.out.println("构造器被调用");
            this.name = name;
        }
        public static Cat getInstance() {
            //如果沒有创建cat对象，则创建，否则直接返回已经创建好的cat
            if(cat == null) {
                cat = new Cat("小可愛");
            }
            return cat;
        }
    
        @Override
        public String toString() {
            return "Cat{" +
                    "name='" + name + '\'' +
                    '}';
        }
    }
    ```

##### 饿汉式和懒汉式对比

- 饿汉式和懒汉式对比：
  1. 二者最主要的区别在于创建对象的时机不同：饿汉式是在类加载时就创建了对象实例，而懒汉式是在使用时才创建
  2. 饿汉式不存在线程安全问题，懒汉式存在线程安全问题（学习线程后会完善）
  3. 饿汉式存在浪费资源的可能。因为如果程序员一个对象实例都没有使用，那么饿汉式创建的对象就浪费了；懒汉式是使用时才创建，所以不存在这个问题
  4. 在 JavaSE 标志类中，java.lang.Runtime 就是经典的单例模式

#### 5.final 关键字

##### final 基本介绍

- final ：最后的、最终的

- final 可以修饰类、属性、方法和局部变量

- 在某些情况下，程序员可能有以下需求，就会用到 final：

  1. 当不希望类被继承时，可以用 final 修饰
  2. 当不希望父类的某个方法被子类覆盖 / 重写（override）时，可以用 final 关键字修饰
  3. 当不希望类的某个属性的值被修改，可以用 final 修饰
  4. 当不希望某个局部变量被修改，可以使用 final 修饰

- 示例：

  - ```java
    package com.hspedu.final_;
    
    public class Final01 {
        public static void main(String[] args) {
            E e = new E();
            //e.TAX_RATE = 0.09;
        }
    }
    
    //情况1：如果我们要求A类不能被其他类继承，可以使用final修饰 A类
    final class A { }
    
    //class B extends A {}  //此时A类不能被继承
    
    class C {
        //情况2：如果我们要求父类方法hi不能被子类重写，可以使用final修饰 hi方法
        public final void hi() {}
    }
    class D extends C {
    //    @Override
    //    public void hi() {
    //        System.out.println("重写了C类的hi方法..");
    //    }
    }
    
    //情况3：当不希望类的的某个属性的值被修改,可以用final修饰
    class E {
        public final double TAX_RATE = 0.08;
    }
    
    //情况4：当不希望某个局部变量被修改，可以使用final修饰
    class F {
        public void cry() {
            final double NUM = 0.01;    //这时，NUM 也称为 局部常量
            //NUM = 0.9;
            System.out.println("NUM = " + NUM);
        }
    }
    ```

##### final 使用注意事项和细节讨论

- final 使用注意事项和细节讨论:

  1. final 修饰的属性又叫常量，一般用 XX_XX_XX 来命名
  2. final 修饰的属性在定义时，必须赋初值，并且以后不能再修改，赋值可以在如下位置之一：
     1. 定义时直接赋初值
     2. 在构造器中
     3. 在代码块中
  3. 如果 final 修饰的属性是静态的，则初始化的位置只能是
     1. 定义时
     2. 在静态代码块，不能在构造器中赋值
  4. final 类不能继承，但是可以实例化对象
  5. 如果类不是 final 类，但是含有 final 方法，则该类可以被继承，但是该 final 方法不能重写
  6. 一般来说，如果一个类已经是 final 类了，就没有必要再将方法修饰成 final 方法（因为 final 类不能被继承，自然方法就不会被重写，不需要 final 修饰）
  7. final 不能修饰构造器
  8. final 和 static 往往搭配使用，效率更高，不会导致类加载。底层编译器做了优化处理
  9. 包装类（Integer、Double、Float、Boolean 等都是 final），String 也是 final 类

- 示例1（包含细节 1~5）：

  - ```java
    package com.hspedu.final_;
    
    public class FinalDetail01 {
        public static void main(String[] args) {
            CC cc = new CC();   //final类不能继承，但是可以实例化对象
    
            new EE().cal(); //会调用到父类DD的cal方法
        }
    }
    
    class AA {
        /*
        1. 定义时：如 public final double TAX_RATE1 = 0.08;
        2. 在构造器中
        3. 在代码块中        */
        public final double TAX_RATE1 = 0.08;    //1.定义时赋值
        public final double TAX_RATE2;
        public final double TAX_RATE3;
    
        public AA() {   //构造器中赋值
            TAX_RATE2 = 1.1;
        }
    
        {   //在代码块赋值
            TAX_RATE3 = 8.8;
        }
    }
    
    class BB {
        /*
        如果final修饰的属性是静态的，则初始化的位置只能是：
            1.定义时
            2.在静态代码块 不能在构造器中赋值      */
        public static final double TAX_RATE = 99.9; //定义时
        public static final double TAX_RATE2 ;
    
        static {
            TAX_RATE2 = 3.3;    //静态代码块中
        }
    
    
    }
    
    //final类不能继承，但是可以实例化对象
    final class CC { }
    
    
    //如果类不是final类，但是含有final方法，则该方法虽然不能重写，但是可以被继承
    //即，仍然遵守继承的机制.
    class DD {
        public final void cal() {
            System.out.println("DD的cal()方法");
        }
    }
    class EE extends DD { }
    ```

- 示例2（包含细节 6~9）：

  - ```java
    package com.hspedu.final_;
    
    public class FinalDetail02 {
        public static void main(String[] args) {
            System.out.println(BBB.num);    //此时不会类加载，静态代码块不会执行
    
            //包装类,String 是final类，不能被继承
            //String
            //Double
            //Integer
        }
    }
    
    //final 和 static 往往搭配使用，效率更高，不会导致类加载.底层编译器做了优化处理
    class BBB {
        public final static int num = 10000;
        static {
            System.out.println("BBB 静态代码块执行");
        }
    }
    final class AAA{
        //一般来说，如果一个类已经是final类了，就没有必要再将方法修饰成final方法
        //public final void cry() {}
    }
    ```

##### 练习

- 练习1：编写一个程序，能够计算圆形的面积，要求圆周率为 3.14。（final 修饰的属性赋值的位置用 3 个方式都写一下）

  - ```java
    package com.hspedu.final_;
    
    public class FinalExercise01 {
        public static void main(String[] args) {
            Circle circle = new Circle(5.0);
            System.out.println("面积:" + circle.calArea());
        }
    }
    
    class Circle {
        private double radius;  //半径
        private final double PI;    // 第一种方式，定义时赋值
        //构造器
        public Circle(double radius) {
            this.radius = radius;
            //PI = 3.14;    //第二种方法，构造器中赋值
        }
    
        {
            PI = 3.14;  //第三种方式，代码块中赋值
        }
    
        public double calArea() {
            return PI * radius * radius;
        }
    }
    ```

#### 6.抽象类

##### 抽象类的引入

- 当父类的某些方法，需要声明，但是又不确定如何实现时，可以将其声明为抽象方法，那么这个类就是抽象类
- 父类方法不确定性的问题：
  - 考虑将该方法设计为抽象（abstract）方法
  - 所谓抽象方法就是没有实现的方法
  - 所谓没有实现就是指没有方法体
  - 当一个类中存在抽象方法时，需要将该类声明为 abstract 类
  - 一般来说，抽象类会被继承，有其子类来实现抽象方法

##### 抽象类的介绍

- 抽象类的介绍：

  1. 用 abstract 关键字来修饰一个类时，这个类就叫抽象类

     - ```java
       访问修饰符 abstract 类名{
           
       }
       ```

  2. 用 abstract 关键字来修饰一个方法时，这个方法就是抽象方法

     - ```java
       访问修饰符 abstract 返回类型 方法名(形参列表);	//没有方法体
       ```

  3. 抽象类的价值更多作用在设计，是设计者设计好后，让子类来继承并实现抽象类

  4. 抽象类，在框架和设计模式使用较多

##### 抽象类使用的注意事项和细节讨论

- 抽象类使用的注意事项和细节讨论

  1. 抽象类不能被实例化
  2. 抽象类不一定要包含 abstract 方法。也就是说，抽象类可以没有 abstract 方法
  3. 一旦类包含了 abstract 方法，则这个类必须声明为 abstract
  4. abstract 只能修饰类和方法，不能修饰属性和其他的
  5. 抽象类可以有任意成员（抽象类的本质还是类，），比如：非抽象方法、构造器、静态属性等
  6. 抽象方法不能有主体，即不能实现
  7. 如果一个类继承了抽象类，则它必须实现抽象类的所有抽象方法，除非它自己也声明为 abstract 类
  8. 抽象方法不能使用 private、final 和 static 来修饰，因为这些关键字都是和重写相违背的
     - 抽象方向一定需要继承，而 final 不允许继承
     - static 关键字与方法重写无关，不可以重写
     - private 子类中不可以访问该方法

- 示例1（包含细节 1~4）：

  - ```java
    package com.hspedu.abstract_;
    
    public class AbstractDetail01 {
        public static void main(String[] args) {
            //new A();  //1.抽象类，不能被实例化
        }
    }
    //2.抽象类不一定要包含abstract方法。也就是说,抽象类可以没有abstract方法。但还可以有实现的方法。
    abstract class A {
        public void hi() {
            System.out.println("hi");
        }
    }
    //3.一旦类包含了abstract方法,则这个类必须声明为abstract
    abstract class B {
        public abstract void hi();
    }
    //4.abstract 只能修饰类和方法，不能修饰属性和其它的
    class C {
       // public abstract int n1 = 1;
    }
    ```

- 示例2（包含细节 5~8）：

  - ```java
    package com.hspedu.abstract_;
    
    public class AbstractDetail02 {
        public static void main(String[] args) {
            System.out.println("hello");
        }
    }
    //8.抽象方法不能使用 private、final 和 static 来修饰，因为这些关键字都是和重写相违背的
    abstract class H {
        public abstract void hi();  //抽象方法
    }
    
    //7.如果一个类继承了抽象类，则它必须实现抽象类的所有抽象方法，除非它自己也声明为abstract类
    abstract class E {
        public abstract void hi();
    }
    abstract class F extends E {
    
    }
    class G extends E {
        @Override
        public void hi() { //这里相等于G子类实现了父类E的抽象方法，所谓实现方法，就是有方法体
    
        }
    }
    
    //5.抽象类的本质还是类，所以可以有类的各种成员
    abstract class D {
        public int n1 = 10;
        public static  String name = "韩顺平教育";
        public void hi() {
            System.out.println("hi");
        }
        public abstract void hello();
        public static void ok() {
            System.out.println("ok");
        }
    }
    ```

##### 练习

- 示例：

  - `Employee.java`

    - ```java
      package com.hspedu.abstract_;
      
      abstract public class Employee {
          private String name;
          private int id;
          private double salary;
      
          public Employee(String name, int id, double salary) {
              this.name = name;
              this.id = id;
              this.salary = salary;
          }
      
          //将work做成一个抽象方法
          public abstract void work();
      
          //getter and setter
          public String getName() {
              return name;
          }
      
          public void setName(String name) {
              this.name = name;
          }
      
          public int getId() {
              return id;
          }
      
          public void setId(int id) {
              this.id = id;
          }
      
          public double getSalary() {
              return salary;
          }
      
          public void setSalary(double salary) {
              this.salary = salary;
          }
      }
      ```

  - `Manager.java`

    - ```java
      package com.hspedu.abstract_;
      
      public class Manager extends Employee {
      
          private double bonus;
      
          public Manager(String name, int id, double salary) {
              super(name, id, salary);
          }
      
          public double getBonus() {
              return bonus;
          }
      
          public void setBonus(double bonus) {
              this.bonus = bonus;
          }
      
          @Override
          public void work() {
              System.out.println("经理 " + getName() + " 工作中...");
          }
      }
      ```

  - `CommonEmployee.java`

    - ```java
      package com.hspedu.abstract_;
      
      public class CommonEmployee extends Employee{
          public CommonEmployee(String name, int id, double salary) {
              super(name, id, salary);
          }
      
          @Override
          public void work() {
              System.out.println("普通员工 " + getName() + " 工作中...");
          }
      }
      ```

  - `AbstractExercise01.java`

    - ```java
      package com.hspedu.abstract_;
      
      public class AbstractExercise01 {
          public static void main(String[] args) {
              //测试
              Manager jack = new Manager("jack", 999, 50000);
              jack.setBonus(8000);
              jack.work();
      
              CommonEmployee tom = new CommonEmployee("tom", 888, 20000);
              tom.work();
          }
      }
      ```

#### 7.模板设计模式

##### 基本介绍

##### 模板设计模式能解决的问题

##### 最佳实践

- 需求：
  - 有很多类，完成不同的任务 job
  - 要求统计得到各自完成任务的时间
  
- 示例：

  - `Template.java`

    - ```java
      package com.hspedu.abstract_;
      
      abstract public class Template { //抽象类-模板设计模式
      
          public abstract void job(); //抽象方法
      
          public void calculateTime() {   //实现方法，调用job方法
              //得到开始的时间
              long start = System.currentTimeMillis();
              job(); //动态绑定机制 //这里调用job方法
              //得的结束的时间
              long end = System.currentTimeMillis();
              System.out.println("任务执行时间 " + (end - start));
          }
      }
      
      ```

  - `AA.java`

    - ```java
      package com.hspedu.abstract_;
      
      public class AA extends Template {
      
          //计算任务：1+....+ 800000
          @Override
          public void job() { //实现Template的抽象方法job
              long num = 0;
              for (long i = 1; i <= 800000; i++) {        //快捷键：800000.for
                  num += i;
              }
          }
      
          public void job2() {    //这样会导致大量重复代码，代码复用性过低
              //得到开始的时间
              long start = System.currentTimeMillis();
              long num = 0;
              for (long i = 1; i <= 200000; i++) {
                  num += i;
              }
              //得的结束的时间
              long end = System.currentTimeMillis();
              System.out.println("AA 执行时间 " + (end - start));
          }
      }
      ```

  - `BB.java`

    - ```java
      package com.hspedu.abstract_;
      
      public class BB extends Template{
      
          public void job() {	//这里也重写了Template的job方法
              long num = 0;
              for (long i = 1; i <= 80000000; i++) {
                  num *= i;
              }
          }
      }
      ```

  - `TestTemplate.java`

    - ```java
      package com.hspedu.abstract_;
      
      public class TestTemplate {
          public static void main(String[] args) {
      
              AA aa = new AA();
              aa.calculateTime(); //这里还是需要有良好的OOP基础，对多态
      
              BB bb = new BB();
              bb.calculateTime();
          }
      }
      ```

#### 8.接口

##### 接口（interface）快速入门

- 示例：

  - `UsbInterface.java`

    - ```java
      package com.hspedu.interface_;
      
      public interface UsbInterface { //接口
          //规定接口的相关方法
          public void start();    //开始方法
          public void stop(); //停止工作
      }
      ```

  - `Phone.java`

    - ```java
      package com.hspedu.interface_;
      
      //Phone类 实现 UsbInterface
      /*解读：
          1. 即：Phone类 需要实现 UsbInterface接口 规定/声明的方法     */
      public class Phone implements UsbInterface {
      
          @Override
          public void start() {
              System.out.println("手机开始工作...");
          }
      
          @Override
          public void stop() {
              System.out.println("手机停止工作.....");
          }
      }
      ```

  - `Camera.java`

    - ```java
      package com.hspedu.interface_;
      
      public class Camera implements UsbInterface{    //实现接口,就是实现接口方法
      
          @Override
          public void start() {
              System.out.println("相机开始工作...");
          }
      
          @Override
          public void stop() {
              System.out.println("相机停止工作....");
          }
      }
      ```

  - `Computer.java`

    - ```java
      package com.hspedu.interface_;
      
      public class Computer {
          //编写一个方法, 计算机工作
          /*解读:
              1. UsbInterface usbInterface 形参是接口类型 UsbInterface
              2. 看到 接收 实现了 UsbInterface接口的类的对象实例    */
          public void work(UsbInterface usbInterface) {   //电脑工作时，接入一个UsbInterface接口
              //通过接口，来调用方法
              usbInterface.start();
              usbInterface.stop();
          }
      }
      ```

  - `Interface01.java`

    - ```java
      package com.hspedu.interface_;
      
      public class Interface01 {
          public static void main(String[] args) {
              //创建手机，相机对象
              //Camera 实现了 UsbInterface
              Camera camera = new Camera();
              //Phone 实现了 UsbInterface
              Phone phone = new Phone();
              //创建计算机
              Computer computer = new Computer();
              computer.work(phone);   //把手机接入到计算机
              System.out.println("===============");
              computer.work(camera);  //把相机接入到计算机
      
          }
      }
      ```

##### 基本介绍

- 基本介绍：

  - 接口就是给出一些没有实现的方法，封装到一起，到某个类要使用的时候，再根据具体情况把这些方法写出来

- 语法：

  - ```java
    interface 接口名{
        //属性
        //方法
    }
    ```

  - ```java
    class 类名 implements 接口名{
        //自己的属性
        //自己的方法
        //必须实现的接口的抽象方法
    }
    ```

  - 补充：implement（实现、实施）

- 小结：

  - 在 jdk7.0 前，接口里的所有方法都没有方法体，即都是抽象方法
  - 在 jdk8.0 后，接口可以有静态方法、默认方法，也就是说接口中可以有方法的具体实现

- 示例：

  - `AInterface.java`

    - ```java
      package com.hspedu.interface_;
      
      public interface AInterface {
          //写属性
          public int n1 = 10;
      
          //写方法
          //在接口中，抽象方法，可以省略abstract关键字
          public void hi();
      
          //在jdk8后，可以有默认实现方法,需要使用default关键字修饰
          default public void ok() {
              System.out.println("ok ...");
          }
          //在jdk8后, 可以有静态方法
          public static void cry() {
              System.out.println("cry ....");
          }
      }
      
      ```

  - `Interface02.java`

    - ```java
      package com.hspedu.interface_;
      
      public class Interface02 {
          public static void main(String[] args) {
      
          }
      }
      
      /*解读：
          如果一个类 implements 实现接口，需要将该接口的所有抽象方法都实现       */
      class A implements AInterface {
          @Override
          public void hi() {
              System.out.println("hi()....");
          }
      }
      ```

##### 接口深入讨论

- 示例：

  - `DBInterface.java`

    - ```java
      package com.hspedu.interface_;
      
      public interface DBInterface { //项目经理规定的接口
      
          public void connect();//连接方法
          public void close();//关闭连接
      }
      ```

  - `MysqlDB.java`

    - ```java
      package com.hspedu.interface_;
      
      //A程序员实现，连接Mysql
      public class MysqlDB implements DBInterface {
          @Override
          public void connect() {
              System.out.println("连接mysql");
          }
      
          @Override
          public void close() {
              System.out.println("关闭mysql");
          }
      }
      ```

  - `OracleDB.java`

    - ```java
      package com.hspedu.interface_;
      
      //B程序员连接Oracle
      public class OracleDB implements DBInterface{
      
          @Override
          public void connect() {
              System.out.println("连接oracle");
          }
      
          @Override
          public void close() {
              System.out.println("关闭oracle");
          }
      }
      ```

  - `Interface03.java`

    - ```java
      package com.hspedu.interface_;
      
      public class Interface03 {
          public static void main(String[] args) {
      
              MysqlDB mysqlDB = new MysqlDB();
              t(mysqlDB);     //调用本类中的静态方法
              OracleDB oracleDB = new OracleDB();
              t(oracleDB);
          }
      
          public static void t(DBInterface db) {  //本类中的静态方法  //传入一个接口
              db.connect();
              db.close();
          }
      }
      ```

##### 接口的注意事项和细节

- 接口的注意事项和细节：

  1. 接口不能被实例化
  2. 接口中所有的方法是 public 方法，接口中所有的抽象方法可以不用 abstract 修饰
  3. 一个普通类实现接口，就必须将接口的所有方法都实现
  4. 抽象类实现接口，可以不用实现接口的方法
  5. 一个类可以实现多个接口，必须同时实现所有接口的方法
  6. 接口中的属性，只能是final的，而且是 public static final 修饰符，必须初始化
  7. 接口中属性的访问形式：`接口名.属性名`
  8. 接口不能继承其它的类，但是可以继承多个别的接口
  9. 接口的修饰符 只能是 public 和默认，这点和类的修饰符是一样的

- 示例1（包含细节 1~4）：

  - ```java
    package com.hspedu.interface_;
    
    public class InterfaceDetail01 {
        public static void main(String[] args) {
            //new IA(); //接口不能被实例化
        }
    }
    
    //1.接口不能被实例化
    //2.接口中所有的方法是 public方法,  接口中抽象方法，可以不用abstract 修饰
    //3.一个普通类实现接口,就必须将该接口的所有方法都实现,可以使用alt+enter来解决
    //4.抽象类去实现接口时，可以不实现接口的抽象方法
    interface IA {
        void say(); //修饰符：public protected 默认 private
        void hi();
    }
    class Cat implements IA{
        @Override
        public void say() {
    
        }
    
        @Override
        public void hi() {
    
        }
    }
    abstract class Tiger implements  IA {
    
    }
    ```

- 示例2（包含细节 5~9）：

  - ```java
    package com.hspedu.interface_;
    
    public class InterfaceDetail02 {
        public static void main(String[] args) {
            //证明接口中的属性,是 public static final
            System.out.println(IB.n1);  //可以通过类名访问属性，说明n1 就是static
            //IB.n1 = 30;   //不可以修改，说明n1 是 final
        }
    }
    interface IB {
        //6.接口中的属性,只能是final的，而且是 public static final 修饰符
        int n1 = 10; //等价 public static final int n1 = 10;
        void hi();
    }
    interface IC {
        void say();
    }
    //8.接口不能继承其它的类,但是可以继承多个别的接口
    interface ID extends IB,IC {
    }
    //9.接口的修饰符 只能是 public 和默认，这点和类的修饰符是一样的
    interface IE{}
    
    //5.一个类同时可以实现多个接口，需要同时实现所有接口中的抽象方法
    class Pig implements IB,IC {
        @Override
        public void hi() {
        }
        @Override
        public void say() {
        }
    }
    ```

##### 练习1

- 示例：

  - ```java
    package com.hspedu.interface_;
    
    public class InterfaceExercise01 {
        public static void main(String[] args) {
            B b = new B();//ok
            System.out.println(b.a);  //23  //通过对象名访问
            System.out.println(A.a);  //23  //通过接口名访问
            System.out.println(B.a);  //23  //静态属性，通过类名访问
        }
    }
    
    interface A {
        int a = 23; //等价 public static final int a = 23;
    }
    
    class B implements A {//正确
    }
    ```

##### 实现接口与继承类的对比

- 实现接口与继承类的对比

  - 接口和继承解决的问题不同：
    - 继承：解决代码的复用性和可维护性
    - 接口：设计，设计好各种规范，让其他类去实现这些方法，可以更加灵活
  - 接口比继承更加灵活
    - 接口比继承更加灵活，继承满足子类是一种父类，而接口只需要满足子类像一个父类即可
  - 接口在一定程度上实现代码解耦（即：接口规范性 + 动态绑定机制）

- 示例：

  - ```java
    package com.hspedu.interface_;
    
    public class ExtendsVsInterface {
        public static void main(String[] args) {
            LittleMonkey wuKong = new LittleMonkey("悟空");
            wuKong.climbing();
            wuKong.swimming();
            wuKong.flying();
        }
    }
    
    //猴子
    class Monkey {
        private String name;
    
        public Monkey(String name) {    //有参构造
            this.name = name;
        }
        
        public void climbing() {    //爬树
            System.out.println(name + " 会爬树...");
        }
    
        public String getName() {
            return name;
        }
    }
    
    //接口
    interface Fishable {
        void swimming();
    }
    interface Birdable {
        void flying();
    }
    
    /*继承小结:  
        当子类继承了父类，就自动的拥有父类的功能
        如果子类需要扩展功能，可以通过实现接口的方式扩展
        可以理解 实现接口 是 对java 单继承机制的一种补充        */
    class LittleMonkey extends Monkey implements Fishable,Birdable {    //继承，并且拓展接口
    
        public LittleMonkey(String name) {
            super(name);
        }
    
        @Override
        public void swimming() {
            System.out.println(getName() + " 通过学习，可以像鱼儿一样游泳...");
        }
    
        @Override
        public void flying() {
            System.out.println(getName() + " 通过学习，可以像鸟儿一样飞翔...");
        }
    }
    ```

##### 接口的多态性

- 接口的多态性：

  1. 多态参数：接口引用可以指向实现了这个接口的类的对象
  2. 多态数组：
  3. 接口存在多态传递现象

- 示例1（多态参数）：

  - ```java
    package com.hspedu.interface_;
    
    public class InterfacePolyParameter {
        public static void main(String[] args) {
    
            //接口的多态体现：
            //接口类型的变量 if01 可以指向 实现了IF接口类的对象实例
            IF if01 = new Monster();
            if01 = new Car();
    
            //继承体现的多态：
            //父类类型的变量 a 可以指向 继承AAA的子类的对象实例
            AAA a = new BBB();
            a = new CCC();
        }
    }
    
    interface IF {}
    
    class Monster implements IF{}
    class Car implements  IF{}
    
    class AAA {
    
    }
    class BBB extends AAA {}
    class CCC extends AAA {}
    ```

- 示例2（多态数组）：

  - ```java
    package com.hspedu.interface_;
    
    public class InterfacePolyArr {
        public static void main(String[] args) {
    
            //多态数组 -> 接口类型数组
            Usb[] usbs = new Usb[2];
            usbs[0] = new Phone_();
            usbs[1] = new Camera_();
            /*题目描述：
                给Usb数组中，存放 Phone 和 相机对象，Phone类还有一个特有的方法call（），
                请遍历Usb数组，如果是Phone对象，除了调用Usb 接口定义的方法外，
                还需要调用Phone 特有方法 call        */
            for(int i = 0; i < usbs.length; i++) {
                usbs[i].work();     //动态绑定..
                //和前面一样，访问特定方法时，仍然需要进行类型的向下转型
                if(usbs[i] instanceof Phone_) { //判断他的运行类型是 Phone_
                    ((Phone_) usbs[i]).call();      //接口引用要向下转型为 实现类的引用
                }
            }
        }
    }
    
    interface Usb{
        void work();
    }
    class Phone_ implements Usb {
        public void call() {    //Phone_ 的特有方法
            System.out.println("手机可以打电话...");
        }
    
        @Override
        public void work() {
            System.out.println("手机工作中...");
        }
    }
    class Camera_ implements Usb {
    
        @Override
        public void work() {
            System.out.println("相机工作中...");
        }
    }
    ```

- 示例3（接口的多态传递）：

  - ```java
    package com.hspedu.interface_;
    
    //0演示多态传递现象
     
    public class InterfacePolyPass {
        public static void main(String[] args) {
            //接口类型的变量可以指向，实现了该接口的类的对象实例
            IG ig = new Teacher();
            //如果接口 IG 继承了 IH 接口，而Teacher 类实现了 IG接口
            //那么，实际上就相当于 Teacher 类也实现了 IH接口.
            //这就是所谓的 接口多态传递现象.
            IH ih = new Teacher();
        }
    }
    
    interface IH {
        void hi();
    }
    
    interface IG extends IH{ }
    
    class Teacher implements IG {
        @Override
        public void hi() {
        }
    }
    ```

##### 练习2

- 示例：

  - ```java
    package com.hspedu.interface_;
    
    public class InterfaceExercise02 {
        public static void main(String[] args) {
            new C().pX();
        }
    }
    
    interface A {
        int x = 0;      //public static final
    }
    
    class B {
        int x = 1;
    } //普通属性
    
    class C extends B implements A {    //C 继承 B，统计实现接口 A
        public void pX() {
            //System.out.println(x); //错误，原因不明确x
            /*可以明确的指定x：
                访问接口A的 x 就使用 A.x
                访问父类B的 x 就使用 super.x       */
            System.out.println("A的x：" + A.x);
            System.out.println("B的x：" + super.x);
        }
    }
    ```

#### 9.内部类

##### 基本介绍

- 一个类的内部又完整的嵌套了另一个类结构
- 被嵌套的类称为内部类（inner class），嵌套嵌套类的类称为外部类（outer class）
- 是类的第五大成员
  - 类的五大成员：属性、方法、构造器、代码块、内部类
- 内部类最大的特点就是：可以直接访问私有属性，并且可以体现类与类之间的包含关系

##### 基本语法

- 基本语法：

  - ```java
    class Outer{	//外部类
        class Inner{	//内部类
            
        }
    }
    class Other{	//外部其他类
        
    }
    ```

##### 快速入门案例

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class InnerClass01 { //外部其他类
        public static void main(String[] args) {
    
        }
    }
    class Outer { //外部类
        private int n1 = 100;   //属性
        
        public Outer(int n1) {  //构造器
            this.n1 = n1;
        }
        
        public void m1() {  //方法
            System.out.println("m1()");
        }
        
        {   //代码块
            System.out.println("代码块...");
        }
        
        class Inner {   //内部类, 在Outer类的内部
    
        }
    }
    ```

##### 内部类的分类

- 如果定义类在局部位置（方法中 / 代码块)
  1. 局部内部类（有类名）	（local inner class）
  2. 匿名内部类（没有类名）（重点！！！）  （anonymous inner class）
- 如果定义在成员位置：
  1. 成员内部类（没有用 static 修饰）	（）
  2. 静态内部类（使用 static 修饰）  （）

##### 局部内部类的使用

- 局部内部类的使用：局部内部类是定义在外部类的局部位置，通常在方法，并且有类名

  1. 可以直接访问外部类的所有成员，包含私有的
  2. 不能添加访问修饰符，因为它的地位就是一个局部变量，局部变量是不能使用修饰符的，但是可以使用 final 修饰
  3. 作用域：仅仅在定义它的方法或代码块中
  4. 局部内部类可以直接访问外部类的成员
  5. 外部类在方法中，可以创建内部类对象实例，再访问（注意：必须在作用域内）
  6. 外部其他类不能访问局部内部类（因为内部类地位是一个局部变量）
  7. 如果外部类和局部内部类的成员重名时，默认遵循就近原则，如果想访问外部类的成员，使用 `外部类名.this.成员`去访问

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    //演示局部内部类的使用
    public class LocalInnerClass {//
        public static void main(String[] args) {
            //演示一遍
            Outer02 outer02 = new Outer02();
            outer02.m1();
            System.out.println("outer02的hashcode：" + outer02);
        }
    }
    
    class Outer02 {     //外部类
        private int n1 = 100;
    
        private void m2() { //私有方法
            System.out.println("Outer02 m2()方法被调用");
        }
    
        public void m1() {  //方法
            //说明：局部内部类是定义在外部类的局部位置,通常在方法
            //2.不能添加访问修饰符,但是可以使用 final 修饰（不用 final 时，可以被其他内部类继承）
            //3.作用域 : 仅仅在定义它的方法或代码块中
            final class Inner02 {   //局部内部类(本质仍然是一个类)
                //1.可以直接访问外部类的所有成员，包含私有成员
                private int n1 = 800;
                public void f1() {
                    //4.局部内部类可以直接访问外部类的成员，比如下面 外部类n1 和 m2()
                    //7. 如果外部类和局部内部类的成员重名时，默认遵循就近原则，如果想访问外部类的成员，使用（外部类名.this.成员）去访问
                    //   解读: Outer02.this 本质就是外部类的对象, 即哪个对象调用了m1, Outer02.this就是哪个对象
                    System.out.println("内部类的n1：" + n1 + "\t外部类的n1：" + Outer02.this.n1);  //外部类名.this.成员
                    System.out.println("内部类的n1：" + this.n1);    //如果不加外部类名
                    System.out.println("Outer02.this的hashcode:" + Outer02.this);
                    m2();
                }
            }
            //5.外部类在方法中，可以创建Inner02对象，然后调用方法即可
            Inner02 inner02 = new Inner02();
            inner02.f1();
        }
    }
    ```

##### 匿名内部类的使用

- 匿名内部类：

  - 本质是类；是内部类；是匿名的；同时还是一个对象

  - 匿名内部类是定义在外部类的局部位置，比如方法中，并且没有类名

  - 基本语法：

    - ```java
      new 类或接口(参数列表){
          类体
      }
      ```

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    //演示匿名内部类的使用
    
    //import com.hspedu.interface_.Tiger;
    
    public class AnonymousInnerClass {
        public static void main(String[] args) {
            Outer04 outer04 = new Outer04();
            outer04.method();
        }
    }
    
    class Outer04 { //外部类
        //属性
        private int n1 = 10;
    
        //方法
        public void method() {
            //基于接口的匿名内部类
            /*解读：
                1.需求： 想使用IA接口,并创建对象
                2.传统方式：是写一个类，实现该接口，并创建对象
                3.需求是 Tiger/Dog 类只是使用一次，后面再不使用，传统方法会定义很多类
                4.可以使用匿名内部类来简化开发
                5.tiger的编译类型 是 IA   （等号左边）
                6.tiger的运行类型 就是匿名内部类 Outer04$1    （等号右边）     */
            /*
                我们看底层 会分配 类名 Outer04$1
                class Outer04$1 implements IA {
                    @Override
                    public void cry() {
                        System.out.println("老虎叫唤...");
                    }
                }
             */
            //7. jdk底层在创建匿名内部类 Outer04$1,立即马上就创建了 Outer04$1 的一个实例，并且把地址返回给 tiger
            //8. 匿名内部类使用一次，就不能再使用（这里指的是只能创建一次）。对象是可以反复使用的
            IA tiger = new IA() {   //匿名内部类的语法
                @Override
                public void cry() {
                    System.out.println("老虎叫唤...");
                }
            };
            System.out.println("tiger的运行类型：" + tiger.getClass());
            tiger.cry();
    
            IA tiger2 = new IA() {   //匿名内部类的语法
                @Override
                public void cry() {
                    System.out.println("老虎叫唤...");
                }
            };
            System.out.println("tiger2的运行类型：" + tiger2.getClass());     //这里就会发现已经不是同一个类了，会重新创建一个匿名类
            tiger2.cry();
    
            //传统方式，需要创建很多类
            /*
            IA tiger = new Tiger();
            tiger.cry();        */
    
            //=======================================================================
    
            //基于类的匿名内部类
    
            /*分析：
                1. father 的编译类型 Father
                2. father 的运行类型 Outer04$3
                3. 底层会创建匿名内部类     */
            /*
                class Outer04$2 extends Father{
                    @Override
                    public void test() {
                        System.out.println("匿名内部类重写了test方法");
                    }
                }
             */
            //4. 同时也直接返回了 匿名内部类 Outer04$2 的对象实例
            //5. 注意("jack") 参数列表会传递给 构造器
            Father father = new Father("jack"){ //匿名内部类
                @Override
                public void test() {
                    System.out.println("匿名内部类重写了test方法");
                }
            };
            System.out.println("father对象的运行类型：" + father.getClass());//Outer04$2
            father.test();
    
            //基于抽象类的匿名内部类（必须重写所有抽象方法）
            Animal animal = new Animal(){
                @Override
                void eat() {
                    System.out.println("小狗吃骨头...");
                }
            };
            animal.eat();
        }
    }
    
    //接口
    interface IA {
        public void cry();
    }
    
    //传统方式，两个类都实现接口IA
    /*
    class Tiger implements IA {
    
        @Override
        public void cry() {
            System.out.println("老虎叫唤...");
        }
    }
    class Dog implements IA{
        @Override
        public void cry() {
            System.out.println("小狗汪汪...");
        }
    }       */
    
    //类
    class Father {
        public Father(String name) {    //Father的有参构造器
            System.out.println("接收到name：" + name);
        }
        public void test() {//方法
        }
    }
    
    abstract class Animal { //抽象类
        abstract void eat();
    }
    ```

- 匿名内部类注意事项和细节：

  1. 匿名内部类的语法比较，因为匿名内部类既是一个类的定义，同时它本身也是一个对象，因此从语法上看，它既有定义类的特征，也有创建对象的特征，因此可以调用匿名内部类方法
  2. 可以直接访问外部类的所有成员，包含私有的
  3. 不能添加访问修饰符，因为它的地位就是一个局部变量
  4. 作用域 : 仅仅在定义它的方法或代码块中
  5. 匿名内部类也可以直接调用外部类成员，匿名内部类本身也是返回对象
  6. 外部其他类不能访问匿名内部类

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class AnonymousInnerClassDetail {
        public static void main(String[] args) {
    
            Outer05 outer05 = new Outer05();
            outer05.f1();
            //6.外部其他类---不能访问----->匿名内部类
            System.out.println("main outer05 hashcode：" + outer05);     //说明与Outer05.this是同一个对象
        }
    }
    
    class Outer05 {
        private int n1 = 99;
        public void f1() {
    
            //创建一个基于类的匿名内部类
    
            //3.不能添加访问修饰符,因为它的地位就是一个局部变量
            //4.作用域 : 仅仅在定义它的方法或代码块中
            Person p = new Person(){
                private int n1 = 88;
                @Override
                public void hi() {
                    //2.可以直接访问外部类的所有成员，包含私有的
                    //7.如果外部类和匿名内部类的成员重名时，匿名内部类访问的话，
                    //  默认遵循就近原则，如果想访问外部类的成员，则可以使用 （外部类名.this.成员）去访问
                    System.out.println("匿名内部类重写的hi方法\n内部类的n1：" + n1 +
                            "\n外部类的n1：" + Outer05.this.n1 );     //Outer05.this 就是指向外部类的对象
                    System.out.println("匿名内部类重写的hi方法\n内部类的n1：" + this.n1);  //this.n1 也是访问内部类的对象
                    System.out.println("Outer05.this hashcode：" + Outer05.this);
                }
            };  //注意这里有个分号
            p.hi();     //动态绑定, 编译类型是 Person，运行类型是 Outer05$1
    
            //5.匿名内部类也可以直接调用外部类成员, 匿名内部类本身也是返回对象
            // class 匿名内部类 extends Person {}
            new Person(){
                @Override
                public void hi() {
                    System.out.println("匿名内部类重写了hi()方法,哈哈...");
                }
                @Override
                public void ok(String str) {
                    super.ok(str);
                }
            }.ok("jack");   //直接调用外部类成员
        }
    }
    
    class Person {//类
        public void hi() {
            System.out.println("Person的hi()方法");
        }
        public void ok(String str) {
            System.out.println("Person的ok()方法\t" + str);
        }
    }
    //抽象类/接口...
    ```

- 匿名内部类的最佳实践：

  - 将匿名内部类当做方法的实参直接传递，简洁高效

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class InnerClassExercise01 {
        public static void main(String[] args) {
    
            //匿名内部类的最佳实践：将匿名内部类当做方法的实参直接传递，简洁高效当做实参直接传递，简洁高效
            f1(new IL() {
                @Override
                public void show() {
                    System.out.println("这是一副名画~~...");
                }
            });
            
            //传统方法：先定义一个实现接口的类，传入这个类的对象
            f1(new Picture());
        }
    
        //静态方法,形参是接口类型
        public static void f1(IL il) {  //传入接口引用
            il.show();  //接口名.方法名
        }
    }
    
    //接口
    interface IL {
        void show();
    }
    
    //类->实现IL => 编程领域 (硬编码)
    class Picture implements IL {
        @Override
        public void show() {        //重写接口IL的方法
            System.out.println("这是一副名画XX...");
        }
    }
    ```

- 练习：

  - 有一个铃声接口 Bell，里面有一个 ring 方法
  - 有一个手机类 Cellphone 具有闹钟功能，参数是 Bell 类型，调用 Bell 的 ring 方法
  - 测试手机的闹钟功能，通过匿名内部类作为参数，打印：懒猪起床了
  - 再传入另一个匿名内部类，打印：小伙伴上课了

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class InnerClassExercise02 {
        public static void main(String[] args) {
            /*问题描述：
                1.有一个铃声接口Bell，里面有个ring方法。(右图)
                2.有一个手机类Cellphone，具有闹钟功能alarmClock，参数是Bell类型(右图)
                3.测试手机类的闹钟功能，通过匿名内部类(对象)作为参数，打印：懒猪起床了
                4.再传入另一个匿名内部类(对象)，打印：小伙伴上课了     */
            CellPhone cellPhone = new CellPhone();  //创建一个手机实例
            /*解读：
                1. 传递的是实现了 Bell 接口的匿名内部类 InnerClassExercise02$1
                2. 重写了 ring
                3. Bell bell = new Bell() {
                            @Override
                            public void ring() {
                                System.out.println("懒猪起床了");
                            }
                        }     */
            cellPhone.alarmClock(new Bell() {     //调用手机类的闹钟功能，参数传递的是传递的是实现了 Bell 接口（重写 ring）的匿名内部类
                @Override
                public void ring() {
                    System.out.println("懒猪起床了");
                }
            });
    
            cellPhone.alarmClock(new Bell() {
                @Override
                public void ring() {
                    System.out.println("小伙伴上课了");
                }
            });
        }
    }
    interface Bell{     //接口
        void ring();    //方法
    }
    class CellPhone{//类
        public void alarmClock(Bell bell){  //形参是Bell接口类型
            System.out.println(bell.getClass());    //测试 bell 的运行类型
            bell.ring();	//动态绑定	会回到匿名内部类中重写的ring方法
        }
    }
    ```

##### 成员内部类的使用

- 成员内部类（member inner class）的使用：成员内部类是定义在外部类的成员位置，并且没有 static 修饰

  1. 可以直接访问外部类的所有成员，包含私有的
  2. 可以添加任意修饰符（public、protected、默认、private），因为它的地位就是一个成员
  3. 作用域，和外部类的其他成员一样，为整个类体
  4. 成员内部类可以直接访问外部类成员
  5. 外部类可以通过创建对象再访问成员内部类
  6. 外部其他类也可以访问成员内部类
  7. 如果外部类和内部类的成员重名时，内部类访问的话，默认遵循就近原则，如果想访问外部类的成员，则可以使用（外部类名.this.成员）去访问

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class MemberInnerClass01 {
        public static void main(String[] args) {
            Outer08 outer08 = new Outer08();    //创建一个外部类对象
            outer08.t1();
    
            //外部其他类，使用成员内部类的两种方式
            //第一种方式:先创建外部类对象
            //outer08.new Inner08(); 相当于把 new Inner08()当做是outer08成员
            //这就是一个语法，不要特别的纠结.
            Outer08.Inner08 inner08 = outer08.new Inner08();    //外部类名.内部类名 内部类对象名 = 外部类对象名.new 内部类名;
            inner08.say();
            // 第二方式:在外部类中，编写一个方法，可以返回 Inner08对象
            Outer08.Inner08 inner08Instance = outer08.getInner08Instance(); //外部类名.内部类名 内部类对象名 = 外部类对象名.方法名;
            inner08Instance.say();
        }
    }
    
    class Outer08 { //外部类
        private int n1 = 10;
        public String name = "张三";
    
        private void hi() {
            System.out.println("hi()方法...");
        }
    
        //注意: 成员内部类，是定义在外部内的成员位置上
        //2.可以添加任意访问修饰符(public、protected 、默认、private),因为它的地位就是一个成员
        public class Inner08 {      //成员内部类
            private double sal = 99.8;
            private int n1 = 66;
            public void say() {
                //1.可以直接访问外部类的所有成员，包含私有的
                //7.如果成员内部类的成员和外部类的成员重名，会遵循就近原则，可以通过（外部类名.this.属性）来访问外部类的成员
                System.out.println("n1：" + n1 + "\tname:" + name + "\t外部类的n1:" + Outer08.this.n1);
                hi();
            }
        }
        //方法，返回一个Inner08实例
        public Inner08 getInner08Instance(){    //返回值类型为 内部类Inner08
            return new Inner08();   //return一个new出来的内部类对象
        }
    
        //写方法
        public void t1() {
            //使用成员内部类
            //创建成员内部类的对象，然后使用相关的方法
            Inner08 inner08 = new Inner08();
            inner08.say();
            System.out.println(inner08.sal);
        }
    }
    ```

##### 静态内部类的使用

- 静态内部类的使用：静态内部类是定义在外部类的成员位置，并且有 static 修饰

  1. 可以直接访问外部类的所有静态成员，包含私有的，但不能直接访问非静态成员
  2. 可以添加任意访问修饰符（public、protected 、默认、private），因为它的地位就是一个成员
  3. 作用域 ：同其他的成员，为整个类体
  4. 静态内部类可以直接访问外部类静态成员
  5. 外部类需要先创建对象，再访问静态内部类成员
  6. 如果外部类和静态内部类的成员重名时，静态内部类访问的时，默认遵循就近原则，如果想访问外部类的成员，则可以使用 （外部类名.成员）

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class StaticInnerClass01 {
        public static void main(String[] args) {
            Outer10 outer10 = new Outer10();
            outer10.m1();
    
            //外部其他类 使用静态内部类
            //方式1：
            //因为静态内部类，是可以通过类名直接访问(前提是满足访问权限)
            Outer10.Inner10 inner10 = new Outer10.Inner10();    //这里是通过外部类名直接就可以访问它的静态成员静态内部类
            inner10.say();
            //方式2：
            //编写一个方法，可以返回静态内部类的对象实例.
            Outer10.Inner10 inner101 = outer10.getInner10();    //这里调用的是普通成员方法，通过对象外部类对象名调用
            System.out.println("============");
            inner101.say();
    
            Outer10.Inner10 inner10_ = Outer10.getInner10_();   //这里调用的是静态成员方法，通过外部类名调用
            System.out.println("************");
            inner10_.say();
        }
    }
    
    class Outer10 { //外部类
        private int n1 = 10;
        private static String name = "张三";
        private static void cry() {}
        //Inner10就是静态内部类，放在外部类的成员位置，使用static 修饰
        //1.可以直接访问外部类的所有静态成员，包含私有的，但不能直接访问非静态成员
        //2.可以添加任意访问修饰符(public、protected 、默认、private),因为它的地位就是一个成员
        //3.作用域 ：同其他的成员，为整个类体
        static class Inner10 {
            private static String name = "韩顺平教育";
            public void say() {
                //如果外部类和静态内部类的成员重名时，静态内部类访问的时，
                //默认遵循就近原则，如果想访问外部类的成员，则可以使用 （外部类名.成员）
                System.out.println("内部类的name：" + name + "\t外部类name:" + Outer10.name);
                System.out.println("内部类的name(用this)：" + this.name);
                cry();
            }
        }
    
        public void m1() { //外部类需要先创建对象，再访问静态内部类成员
            Inner10 inner10 = new Inner10();
            inner10.say();
        }
    
        public Inner10 getInner10() {
            return new Inner10();
        }
    
        public static Inner10 getInner10_() {
            return new Inner10();
        }
    }
    ```

##### 练习

- 示例：

  - ```java
    package com.hspedu.innerclass;
    
    public class InnerClassExercise {
        public static void main(String[] args) {
    
        }
    }
    
    class Test {//外部类
    
        public Test() {//构造器
            Inner s1 = new Inner();
            s1.a = 10;
            Inner s2 = new Inner();
            System.out.println(s2.a);
        }
    
        class Inner { //内部类，成员内部类
            public int a = 5;
        }
    
        public static void main(String[] args) {
            Test t = new Test();
            Inner r = t.new Inner();    //5
            System.out.println(r.a);    //5
        }
    }
    ```

### （二）枚举和注解

#### 1.入门需求

- 要求创建季节（Season）对象，请设计并完成

  - ```java
    class Season{//类
        private String name;
        private String desc;//描述
        //构造器
        //getXX
        //setXX
    }
    ```

- 示例：

  - ```java
    package com.hspedu.enum_;
    
    public class Enumeration01 {
        public static void main(String[] args) {
            //使用
            Season spring = new Season("春天", "温暖");
            Season winter = new Season("冬天", "寒冷");
            Season summer = new Season("夏天", "炎热");
            Season autumn = new Season("秋天", "凉爽");
    //        autumn.setName("XXX");
    //        autumn.setDesc("非常的热..");
            //因为对于季节而已，他的对象(具体值)，是固定的四个，不会有更多
            //按这个设计类的思路，不能体现季节是固定的四个对象
            //因此，这样的设计不好
            //引入枚举类（枚: 一个一个。举： 例举。即把具体的对象一个一个例举出来的类）
            //就称为枚举类
            Season other = new Season("红天", "~~~");
        }
    }
    class Season{//类
        private String name;
        private String desc;    //描述
    
        public Season(String name, String desc) {
            this.name = name;
            this.desc = desc;
        }
    
        public String getName() {
            return name;
        }
    
        public void setName(String name) {
            this.name = name;
        }
    
        public String getDesc() {
            return desc;
        }
    
        public void setDesc(String desc) {
            this.desc = desc;
        }
    }
    ```

- 分析问题:

  - 创建 Season 对象有如下特点：
    - 季节的值是有限的几个值（spring、summer、autumn、winter）
    - 只读，不需要修改

- 解决方案：枚举

  1) 枚举对应英文（enumeration, 简写 enum）
  2) 枚举是一组常量的集合
  3) 可以这里理解：枚举属于一种特殊的类，里面只包含一组有限的特定的对象

#### 2.枚举的二种实现方式

- 枚举的二种实现方式
  1) 自定义类实现枚举
  2) 使用 enum 关键字实现枚举

#### 3.自定义实现枚举

- 自定义实现枚举：

  1. 不需要提供 setXxx 方法，因为枚举对象值通常为只读
  2. 对枚举对象 / 属性使用 final + static 共同修饰，实现底层优化
  3. 枚举对象名通常使用全部大写，常量的命名规范
  4. 枚举对象根据需要，也可以有多个属性

- 示例：

  - ```java
    package com.hspedu.enum_;
    
    public class Enumeration02 {
        public static void main(String[] args) {
            System.out.println(Season.AUTUMN);
            System.out.println(Season.SPRING);
        }
    }
    
    //自定义枚举实现
    class Season {//类
        private String name;
        private String desc;//描述
    
        //定义了四个对象, 固定.
        public static final Season SPRING = new Season("春天", "温暖");
        public static final Season WINTER = new Season("冬天", "寒冷");
        public static final Season AUTUMN = new Season("秋天", "凉爽");
        public static final Season SUMMER = new Season("夏天", "炎热");
    
        //1. 将构造器私有化,目的：防止直接 new
        //2. 去掉setXxx方法, 防止属性被修改
        //3. 在 Season 内部，直接创建固定的对象
        //4. 优化，可以加入 final 修饰符
        private Season(String name, String desc) {
            this.name = name;
            this.desc = desc;
        }
    
        public String getName() {
            return name;
        }
    
        public String getDesc() {
            return desc;
        }
    
        @Override
        public String toString() {
            return "Season{" +
                    "name：'" + name + '\'' +
                    ", desc：'" + desc + '\'' +
                    '}';
        }
    }
    ```

- 小结：

  - 构造器私有化
  - 本类内部创建一组对象
  - 对外暴露对象（通过为对象添加 public final static 修饰符）
  - 可以提供 get 方法，但是不要提供 set

#### 4.enum 关键字实现枚举

- 示例：

  - ```java
    package com.hspedu.enum_;
    
    public class Enumeration03 {
        public static void main(String[] args) {
            System.out.println(Season2.AUTUMN);
            System.out.println(Season2.SUMMER);
        }
    }
    //使用enum关键字来实现枚举类
    enum  Season2 {
        //定义了四个对象, 固定.
    //    public static final Season SPRING = new Season("春天", "温暖");
    //    public static final Season WINTER = new Season("冬天", "寒冷");
    //    public static final Season AUTUMN = new Season("秋天", "凉爽");
    //    public static final Season SUMMER = new Season("夏天", "炎热");
    
        /*如果使用了enum 来实现枚举类：
            1. 使用关键字 enum 替代 class
            2. public static final Season SPRING = new Season("春天", "温暖")
               改为直接使用：SPRING("春天", "温暖")
               即：常量名(实参列表)
            3. 如果有多个常量(对象)， 使用逗号","间隔即可0
            4. 如果使用enum 来实现枚举，要求将定义常量对象，写在最前面
            5. 如果我们使用的是无参构造器，创建常量对象，则可以省略 ()      */
        SPRING("春天", "温暖"),
        WINTER("冬天", "寒冷"),
        AUTUMN("秋天", "凉爽"),
        SUMMER("夏天", "炎热");
        //若使用的是无参构造器，创建常量对象，则可以省略 ()
        //What;
    
        private String name;
        private String desc;    //描述
    
        private Season2() { //无参构造器
    
        }
    
        private Season2(String name, String desc) {
            this.name = name;
            this.desc = desc;
        }
    
        //getter setter 方法保留
        public String getName() {
            return name;
        }
    
        public String getDesc() {
            return desc;
        }
    
        //toString 方法保留
        @Override
        public String toString() {
            return "Season{" +
                    "name='" + name + '\'' +
                    ", desc='" + desc + '\'' +
                    '}';
        }
    }
    ```

- enum 关键字实现枚举注意事项：

  1. 当我们使用 enum 关键字开发一个枚举类时，默认会继承 Enum 类，而且是一个 final 类

  2. 传统的 `public static final Season2 SPRING = new Season2("春天", "温暖");` 简化成 `SPRING("春天", "温暖")`， 这里必须知道，它调用的是哪个构造器

  3. 如果使用无参构造器创建枚举对象，则实参列表和小括号都可以省略

  4) 当有多个枚举对象时，使用逗号`,`间隔，最后有一个分号结尾
  5) 枚举对象必须放在枚举类的行首
  
- enum 关键字实现枚举练习：

  - 下面代码是否正确, 并说明表示的含义?

    - ```java
      enum Gender{ //1min
      BOY , GIRL; 
      //这里其实就是调用 Gender 类的无参构造器
      }
      ```

      - 上面语法是 ok 的
      - 有一个枚举类 Gender， 没有属性
      - 有两个枚举对象 BOY、GIRL，使用的无参构造器创建

  - 下面代码输出什么：

    - ```java
      package com.hspedu.enum_;
      
      public class EnumExercise01 {
          public static void main(String[] args) {
              Gender2 boy = Gender2.BOY;//OK
              Gender2 boy2 = Gender2.BOY;//OK
              System.out.println(boy);//输出BOY
              // 本质就是调用 Gender2 的父类Enum的 toString()
      //        public String toString() {
      //            return name;
      //        }
              System.out.println(boy2 == boy);  //True
          }
      }
      
      enum Gender2{ //父类 Enum 的toString
          BOY , GIRL;
      }
      ```


#### 5.enum 常用方法说明

- 说明：使用关键字 enum 时，会隐式继承 Enum 类，这样我们就可以使用 Enum 类相关的方法

- enum 常用方法使用实例：

  1) `toString`：Enum 类已经重写过了，返回的是当前对象名，子类可以重写该方法，用于返回对象的属性信息

  2) `name`：返回当前对象名（常量名），子类中不能重写
  3) `ordinal`：返回当前对象的位置号，默认从 0 开始
  4) `values`：返回当前枚举类中所有的常量
  5) `valueOf`：将字符串转换成枚举对象，要求字符串必须为已有的常量名，否则报异常

  6) `compareTo`：比较两个枚举常量，比较的就是编号

- 示例：

  - ```java
    package com.hspedu.enum_;
    
    //演示Enum类的各种方法的使用
    
    public class EnumMethod {
        public static void main(String[] args) {
            //使用Season2 枚举类，来演示各种方法
            Season2 autumn = Season2.AUTUMN;
    
            //2.输出枚举对象的名字
            System.out.println(autumn.name());
    
            //3.ordinal() 输出的是该枚举对象的次序/编号，从0开始编号
            //AUTUMN 枚举对象是第三个，因此输出 2
            System.out.println(autumn.ordinal());
    
            //4.从反编译可以看出 values 方法，返回一个数组 Season2[]
            //含有定义的所有枚举对象
            Season2[] values = Season2.values();
            System.out.println("===遍历取出枚举对象(使用增强for)====");
            for (Season2 season: values) {  //增强for循环（依次次从 values 数组中取一个赋给 season，然后使用）
                System.out.println(season);
            }
    
            /*
            //补充了一个增强for
            int[] nums = {1, 2, 9};
            //普通的for循环
            System.out.println("=====普通的for=====");
            for (int i = 0; i < nums.length; i++) {
                System.out.println(nums[i]);
            }
            System.out.println("=====增强的for=====");
            //执行流程是 依次从nums数组中取出数据，赋给i, 如果取出完毕，则退出for
            for(int i : nums) {
                System.out.println("i=" + i);
            }       */
    
            //5.valueOf：将字符串转换成枚举对象，要求字符串必须为已有的常量名，否则报异常
            /*执行流程：
                1. 根据你输入的 "AUTUMN" 到 Season2的枚举对象去查找
                2. 如果找到了，就返回，如果没有找到，就报错       */
            Season2 autumn1 = Season2.valueOf("AUTUMN");
            System.out.println("autumn1：" + autumn1);
            System.out.println(autumn == autumn1);      //都是同一个对象，因为是 static 静态对象
    
            //6.compareTo：比较两个枚举常量，比较的就是编号
            /*解读：
                1. 就是把 Season2.AUTUMN 枚举对象的编号 和 Season2.SUMMER 枚举对象的编号比较
                2. 看看结果       */
            /*
            public final int compareTo(E o) {
    
                return self.ordinal - other.ordinal;
            }
            Season2.AUTUMN的编号[2] - Season2.SUMMER的编号[3]		*/
            System.out.println(Season2.AUTUMN.compareTo(Season2.SUMMER));   //2-1=1
        }
    }
    ```

- 练习：

  - ```java
    package com.hspedu.enum_;
    
    public class EnumExercise02 {
        public static void main(String[] args) {
            //使用 values() 获取到所有的枚举对象， 即数组
            Week[] weeks = Week.values();
            //遍历，使用增强for
            System.out.println("===所有星期的信息如下===");
            for (Week week : weeks) {
                System.out.println(week);
            }
        }
    }
    
    /*题目描述：
        声明Week枚举类，其中包含星期一至星期日的定义；
        MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY, SUNDAY;
        使用values 返回所有的枚举数组, 并遍历 , 输出左图效果        */
    
    enum Week   {
        //定义Week的枚举对象
        MONDAY("星期一"), TUESDAY("星期二"),
        WEDNESDAY("星期三"), THURSDAY("星期四"),
        FRIDAY("星期五"), SATURDAY("星期六"), SUNDAY("星期日");
    
        private String name;
    
        private Week(String name) { //构造器
            this.name = name;
        }
    
        //注意：这里要输出的是枚举对象的属性name，需要重写toString方法，父类的toString输出的是枚举对象名，而不是枚举对象的自定义属性name
        @Override
        public String toString() {
            return name;
        }
    }
    ```

#### 6.enum 实现接口

- enum 实现接口：

  1) 使用 enum 关键字后，就不能再继承其它类了，因为 enum 会隐式继承 Enum，而 Java 是单继承机制

  2) 枚举类和普通类一样，可以实现接口，如下形式：

     - ```java
       enum 类名 implements 接口 1，接口 2{}
       ```

- 示例：

  - ```java
    package com.hspedu.enum_;
    
    //enum 实现接口
    
    public class EnumDetail {
        public static void main(String[] args) {
            Music.CLASSICMUSIC.playing();   //枚举类名.枚举对象名.方法名
        }
    }
    class A {
    
    }
    
    //1.使用enum关键字后，就不能再继承其它类了，因为enum会隐式继承Enum，而Java是单继承机制
    /*
    enum Season3 extends A {
    
    }       */
    //2.enum实现的枚举类，仍然是一个类，所以还是可以实现接口的.
    interface IPlaying {
        public void playing();
    }
    enum Music implements IPlaying {
        CLASSICMUSIC;   //这是一个无参构造的常量
        @Override
        public void playing() {
            System.out.println("播放好听的音乐...");
        }
    }
    ```

#### 7.注解的理解

- 注解的理解
  1. 注解（Annotation）也被称为元数据（Metadata），用于修饰解释 包、类、方法、属性、构造器、局部变量等数据信息
  2. 和注释一样，注解不影响程序逻辑，但注解可以被编译或运行，相当于嵌入在代码中的补充信息
  3. 在 JavaSE 中，注解的使用目的比较简单，例如标记过时的功能，忽略警告等。在 JavaEE 中注解占据了更重要的角色，例如用来配置应用程序的任何切面，代替 java EE 旧版中所遗留的繁冗代码和 XML 配置等

#### 8.基本的注解 Annotation 介绍

- 基本的 Annotation 介绍：
  - 使用 Annotation 时要在其前面增加 @ 符号，并把该 Annotation 当成一个修饰符使用。用于修饰它支持的程序元素
- 三个基本的 Annotation：
  1) `@Override`: 限定某个方法，是重写父类方法，该注解只能用于方法
  2) `@Deprecated`: 用于表示某个程序元素（类, 方法等）已过时
  3) `@SuppressWarnings`: 抑制编译器警告

#### 9.基本的 Annotation 应用案例

##### `@Override` 注解案例

- `@Override`: 限定某个方法，是重写父类方法，该注解只能用于方法

- 示例：

  - ```java
    package com.hspedu.annotation_;
    
    public class Override_ {
        public static void main(String[] args) {
    
        }
    }
    
    class Father{//父类
        public void fly(){
            int i = 0;
            System.out.println("Father的fly方法");
        }
        public void say(){}
    }
    
    class Son extends Father {//子类
        /*解读：
            1.@Override 注解放在 fly 方法上，表示子类的 fly 方法时重写了父类的 fly
            2.这里如果没有写 @Override ，也还是重写了父类 fly
            3.写没写的区别在于：如果你写了@Override注解，编译器就会去检查该方法是否真的重写了父类的方法，
              如果的确重写了，则编译通过，如果没有构成重写，则编译错误
            4.看看 @Override的定义
              解读： 如果发现 @interface 表示是一个 注解类  
                @Target(ElementType.METHOD)
                @Retention(RetentionPolicy.SOURCE)
                public @interface Override {
                }                                  */
        @Override   //说明
        public void fly() {
            System.out.println("Son的fly方法");
        }
        @Override
        public void say() {}    
    }
    ```

- Override 使用说明：

  1. `@override`表示指定重写父类的方法（从编译层面验证），如果父类没有这个方法，则会报错
  2. 如果不写`@override`，而实际上重写了父类的方法，则也是正确的重写，只是编译时不会进行检查
  3. `@override`只能修饰方法，不能修饰其他类、包、属性等信息。（`@Target(ElementType.METHOD)`，说明只能修饰方法）
  4. `@Target`是修饰注解的注解，称为元注解

##### `@Deprecated`注解案例

- `@Deprecated`：用于表示某个程序元素（类，方法等）已过时

- 示例：

  - ```java
    package com.hspedu.annotation_;
    
    public class Deprecated_ {
        public static void main(String[] args) {
            A a = new A();  //表示过时的类会有一个横线
            a.hi(); //过时的方法
            System.out.println(a.n1);   //过时的成员属性
        }
    }
    
    /*解读：
        1. @Deprecated 修饰某个元素, 表示该元素已经过时
        2. 即不再推荐使用，但是仍然可以使用
        3. 查看 @Deprecated 注解类的源码
        4. 可以修饰方法，类，字段, 包, 参数  等等
        5. @Deprecated 可以做版本升级过渡使用        */
    /*
    @Documented
    @Retention(RetentionPolicy.RUNTIME)
    @Target(value={CONSTRUCTOR, FIELD, LOCAL_VARIABLE, METHOD, PACKAGE, PARAMETER, TYPE})   
    //构造器、字段（属性）、局部变量、方法、包、参数、类型
    public @interface Deprecated {
    }
     */
    @Deprecated
    class A {
        @Deprecated
        public int n1 = 10;
    
        @Deprecated
        public void hi(){
        }
    }
    ```

- `Deprecated`的说明：

  1. 可以用于表示某个程序元素的（类、方法等）已经过时
  2. 可以修饰方法、类、字段、包、参数等
  3. `@Target(value={CONSTRUCTOR, FIELD, LOCAL_VARIABLE, METHOD, PACKAGE, PARAMETER, TYPE})`

##### `@SuppressWarnings`注解案例

- `@SuppressWarnings`： 抑制编译器警告、

- 示例：

  - ```java
    package com.hspedu.annotation_;
    
    import java.util.ArrayList;
    import java.util.List;
    
    @SuppressWarnings({"rawtypes", "unchecked", "unused"})
    public class SuppressWarnings_ {
    
        /*解读：
            1. 当我们不希望看到这些警告的时候，可以使用 SuppressWarnings 注解来抑制警告信息
            2. 在{""} 中，可以写入你希望抑制(不显示)警告信息
            3. 可以指定的警告类型有：
                all，抑制所有警告
                boxing，抑制与封装/拆装作业相关的警告
                cast，抑制与强制转型作业相关的警告
                dep-ann，抑制与淘汰注释相关的警告
                deprecation，抑制与淘汰的相关警告
                fallthrough，抑制与switch陈述式中遗漏break相关的警告
                finally，抑制与未传回finally区块相关的警告
                hiding，抑制与隐藏变数的区域变数相关的警告
                incomplete-switch，抑制与switch陈述式(enum case)中遗漏项目相关的警告
                javadoc，抑制与javadoc相关的警告
                nls，抑制与非nls字串文字相关的警告
                null，抑制与空值分析相关的警告
                rawtypes，抑制与使用raw类型相关的警告
                resource，抑制与使用Closeable类型的资源相关的警告
                restriction，抑制与使用不建议或禁止参照相关的警告
                serial，抑制与可序列化的类别遗漏serialVersionUID栏位相关的警告
                static-access，抑制与静态存取不正确相关的警告
                static-method，抑制与可能宣告为static的方法相关的警告
                super，抑制与置换方法相关但不含super呼叫的警告
                synthetic-access，抑制与内部类别的存取未最佳化相关的警告
                sync-override，抑制因为置换同步方法而遗漏同步化的警告
                unchecked，抑制与未检查的作业相关的警告
                unqualified-field-access，抑制与栏位存取不合格相关的警告
                unused，抑制与未用的程式码及停用的程式码相关的警告
            4. 关于SuppressWarnings 作用范围是和你放置的位置相关
               比如 @SuppressWarnings 放置在 main方法，那么抑制警告的范围就是 main
               通常我们可以放置具体的语句, 方法, 类.
            5.  看看 @SuppressWarnings 源码
                (1) 放置的位置就是 TYPE, FIELD, METHOD, PARAMETER, CONSTRUCTOR, LOCAL_VARIABLE
                (2) 该注解类有数组 String[] values() 设置一个数组比如 {"rawtypes", "unchecked", "unused"}        */
        /*
            @Target({TYPE, FIELD, METHOD, PARAMETER, CONSTRUCTOR, LOCAL_VARIABLE})
                @Retention(RetentionPolicy.SOURCE)
                public @interface SuppressWarnings {
    
                    String[] value();
            }            */
        public static void main(String[] args) {
            List list = new ArrayList();
            list.add("jack");
            list.add("tom");
            list.add("mary");
            int i;
            System.out.println(list.get(1));
    
        }
    
        public void f1() {
    //        @SuppressWarnings({"rawtypes"})
            List list = new ArrayList();
    
    
            list.add("jack");
            list.add("tom");
            list.add("mary");
    //        @SuppressWarnings({"unused"})
            int i;
            System.out.println(list.get(1));
        }
    }
    ```

- 说明：

  - 生成`@SuppressWarings`时，直接点击左侧的黄色提示，就可以选择（可以指定生成的位置）

#### 10.JDK 的元注解

##### 元注解的基本介绍

- JDK 的元 Annotation 用于修饰其他 Annotation

##### 元注解的种类 (使用不多，了解, 不用深入研究)

1) `Retention 	//（保留）。指定注解的作用范围，三种：SOURCE、CLASS、RUNTIME`
2) `Target  //指定注解可以在哪些地方使用`
3) `Documented //指定该注解是否会在 javadoc 体现`
4) `Inherited //子类会继承父类注解`

##### @Retention 注解

- 说明：
  - 只能用于修饰一个 Annotation 定义，用于指定该 Annotation 可以保留多长时间
  - @Rentention 包含一个 RetentionPolicy 类型的成员变量，使用 @Rentention 时必须为该 value 成员变量指定值
- @Retention 的三种值：
  1. `RetentionPolicy.SOURCE`：编译器使用后，直接丢弃这种策略的注释
  2. `RetentionPolicy.CLASS`：编译器将把注解记录在 class 文件中。当运行 Java 程序时。JVM 不会保留注解。 这是默认值
  3. `RetentionPolicy.RUNTIME`：编译器将把注解记录在 class 文件中。当运行 Java 程序时, JVM 会保留注解。程序可以通过反射获取该注解

#### 11.作业练习（包含面向对象）

##### 练习1

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework01 {
        public static void main(String[] args) {
            Car c =new Car();
            Car c1=new Car(100);
            System.out.println(c); //9.0,red    //c的price被修改为了9.0      static 类型的共有的color被修改为了red
            System.out.println(c1); //100.0,red
        }
    }
    class Car{
        double price = 10;  
        static String color = "white";
        
        public String toString(){
            return price+"\t"+color;
        }
        
        public Car(){
            this.price = 9;
            this.color = "red";
        }
        
        public Car(double price){
            this.price = price;
        }
    }
    ```

##### 练习2

- 题目要求：

  1. 在 Frock 类中声明私有的静态属性 currentNum （int类型），初始值为 100000，作为衣服出厂的序列号起始值
  2. 声明公有的静态方法 getNextNum，作为生成上衣唯一序列号的方法。每调用一次，将 currentNum 增加100，并作为返回值
  3. 在 TestFrock 类的 main 方法中，分两次调用 getNextNum 方法，获取序列号并打印输出
  4. 在 Frock 类中声明 serialNumber (序列号）属性，并提供对应的 get 方法
  5. 在 Frock 类的构造器中，通过调用 getNextNum 方法为 Frock 对象获取唯一序列号，赋给 serialNumber 属性
  6. 在 TestFrock 类的 main 方法中，分别创建三个 Frock 对象，并打印三个对象的序列号，验证是否为按 100 递增

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework02 {
        public static void main(String[] args) {
    
        }
    }
    /*题目描述：
        1.在Frock类中声明私有的静态属性 currentNum[int类型]，初始值为100000，作为衣服出厂的序列号起始值。
        2.声明公有的静态方法getNextNum，作为生成上衣唯一序列号的方法。每调用一次，将currentNum增加100，并作为返回值。
        3.在TestFrock类的main方法中，分两次调用getNextNum方法，获取序列号并打印输出。
        4.在Frock类中声明serialNumber(序列号)属性，并提供对应的get方法；
        5.在Frock类的构造器中，通过调用getNextNum方法为Frock对象获取唯一序列号，赋给serialNumber属性。
        6.在TestFrock类的main方法中，分别创建三个Frock 对象，并打印三个对象的序列号，验证是否为按100递增        */
    class Frock {
        private static  int currentNum = 100000;
        private int serialNumber;
    
        public Frock() {
            serialNumber = getNextNum();
        }
    
        //理解：手动调用这个方法会改变序列号起始值，创建一个新frock也会自动调用这个方法增加序列号起始值
        public static int getNextNum() {    
            currentNum += 100; //将currentNum增加100
            return currentNum;
        }
    
        public int getSerialNumber() {
            return serialNumber;
        }
    }
    class TestFrock {
        public static void main(String[] args) {
            System.out.println(Frock.getNextNum());//100100
            System.out.println(Frock.getNextNum());//100200
            Frock frock = new Frock();//序列号就是 100300
            Frock frock1 = new Frock();//序列号就是 100400
            Frock frock2 = new Frock();//序列号就是 100500
            System.out.println(frock.getSerialNumber());//100300
            System.out.println(frock1.getSerialNumber());//100400
            System.out.println(frock2.getSerialNumber());//100500
        }
    }
    ```

##### 练习3

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework03 {
        public static void main(String[] args) {
            Animal cat = new Cat();
            Animal dog = new Dog();
            cat.shout();
            dog.shout();
        }
    }
    /*按要求实现下列问题： （抽象类的使用）
        动物类Animal包含了抽象方法  shout()；
        Cat类继承了Animal，并实现方法shout，打印“猫会喵喵叫”
        Dog类继承了Animal，并实现方法shout，打印“狗会汪汪叫”
        在测试类中实例化对象Animal cat =new  Cat(),并调用cat的shout方法
        在测试类中实例化对象Animal dog=new  Dog(),并调用dog的shout方法       */
    abstract class Animal { //抽象类
        public abstract void shout();
    }
    class Cat extends Animal {
    
        @Override
        public void shout() {
            System.out.println("猫会喵喵叫");
        }
    }
    class Dog extends Animal {
    
        @Override
        public void shout() {
            System.out.println("狗会汪汪叫");
        }
    }
    ```

##### 练习4

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework04 {
        public static void main(String[] args) {
            Cellphone cellphone = new Cellphone();  //先创建一个手机类
            
            //解读
            //匿名内部类是
            /*
                new ICalculate() {
                    @Override
                    public double work(double n1, double n2) {
                        return n1 + n2;
                    }
                }, 同时也是一个对象
                他的编译类型 ICalculate, 他的运行类型就是 匿名内部类
             */
            
            cellphone.testWork(new ICalculate() {
                @Override
                public double work(double n1, double n2) {
                    return n1 + n2;
                }
            }, 10, 8);  //18.0
            //n1 和 n2 作为testwork的参数传入之后，又会作为work的参数传入
    
            cellphone.testWork(new ICalculate() {
                @Override
                public double work(double n1, double n2) {
                    return n1 * n2;
                }
            }, 10, 8);
    
        }
    }
    /*题目要求：
        1.计算器接口具有work方法，功能是运算，
          有一个手机类Cellphone，定义方法testWork测试计算功能，调用计算接口的work方法，
        2.要求调用CellPhone对象的testWork方法，使用匿名内部类     */
    //编写接口
    interface ICalculate {
        //work方法 是完成计算，但是题没有具体要求，所以自己设计
        //至于该方法完成怎样的计算，我们交给匿名内部类完成
        public double work(double n1, double n2) ;
    }
    class Cellphone {
        //解读：当我们调用testWork方法时，直接传入一个实现了ICalculate接口的匿名内部类即可
        //该匿名内部类，可以灵活的实现work,完成不同的计算任务
        public void testWork(ICalculate iCalculate, double n1, double n2) { //传入接口和两个参数
            double result = iCalculate.work(n1, n2);    //动态绑定
            System.out.println("计算后的结果是=" + result);
        }
    }
    ```

##### 练习5

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework05 {
        public static void main(String[] args) {
            new A().f1();   //new一个外部类，调用外部类的f1方法
        }
    }
    /*题目要求：
        1. 编一个类A，在类中定义局部内部类B，B中有一个私有final常量name，有一个方法show()打印常量name。进行测试
        2. 进阶：A中也定义一个私有的变量name，在show方法中打印测试    */
    
    class A {
        private String NAME = "hello";
        
        public void f1() {
            class B { //局部内部类
                private final String NAME = "韩顺平教育";
                public void show() {
                    //如果内部类和外部类的属性重名，可以用 （外部类.this.属性名）来指定
                    System.out.println("内部类的NAME：" + NAME + "\t外部类的NAME：" + A.this.NAME);  //内部类：NAME 或 this.NAME
                }
            }
            B b = new B();
            b.show();
        }
    }
    ```

##### 练习6

- 示例：

  - `Vehicles.java`

    - ```java
      package com.hspedu.homework;
      
      public interface Vehicles {
          //1.有一个交通工具接口类Vehicles，有work接口
          public void work();
      }
      ```

  - `Horse.java`

    - ```java
      package com.hspedu.homework;
      
      //2.有Horse类和Boat类分别实现Vehicles
      
      public class Horse implements Vehicles {
          @Override
          public void work() {
              System.out.println(" 一般情况下，使用马儿前进...");
          }
      }
      ```

  - `Boat.java`

    - ```java
      package com.hspedu.homework;
      
      //2.有Horse类和Boat类分别实现Vehicles
      
      public class Boat implements Vehicles {
          @Override
          public void work() {
              System.out.println(" 过河的时候，使用小船.. ");
          }
      }
      ```

  - `VehiclesFactory.java`

    - ```java
      package com.hspedu.homework;
      
      //3.创建交通工具工厂类，有两个方法分别获得交通工具Horse和Boat
      
      public class VehiclesFactory {
          //若马儿始终是同一匹，则需要使用单例模式
          private static Horse horse = new Horse(); //饿汉式，提前创建好
      
          private VehiclesFactory(){}
      
          //这里，我们将方法做成static，设置成静态方法可以不创建类直接使用方法
          public static Horse getHorse() {
      //        return new Horse();
              return horse;
          }
          public static Boat getBoat() {
              return new Boat();
          }
          public static Plane getPlane() {
              return new Plane();
          }
      }
      ```

  - `Person.java`

    - ```java
      package com.hspedu.homework;
      
      //4.有Person类，有name和Vehicles属性，在构造器中为两个属性赋值
      //5.实例化Person对象“唐僧”，要求一般情况下用Horse作为交通工具，遇到大河时用Boat作为交通工具
      
      public class Person {
          private String name;
          private Vehicles vehicles;  //这里是一个接口引用
      
          //在创建人对象时，事先给他分配一个交通工具
          public Person(String name, Vehicles vehicles) {
              this.name = name;
              this.vehicles = vehicles;
          }
      
          //实例化Person对象“唐僧”，要求一般情况下用Horse作为交通工具，遇到大河时用Boat作为交通工具
          //这里涉及到一个编程思路，就是可以把具体的要求，封装成方法（这里就是编程思想）
          //思考一个问题，如何不浪费，在构建对象时，传入的交通工具对象
          public void passRiver() {
              //先得到船
              //判断一下，当前的 vehicles 属性是null, 就获取一艘船
      //        Boat boat = VehiclesFactory.getBoat();
      //        boat.work();
              //如何防止始终使用的是传入的马 instanceOf
              //if (vehicles == null) {
              //vehicles instanceof Boat 是判断 当前的 vehicles是不是Boat
              //(1) vehicles = null  : vehicles instanceof Boat  => false
              //(2) vehicles = 马对象 ：vehicles instanceof Boat  => false
              //(3) vehicles = 船对象 ：vehicles instanceof Boat  => true
              if (!(vehicles instanceof Boat)) {
                  vehicles = VehiclesFactory.getBoat();
              }
              vehicles.work();
          }
      
          public void common() {
              //得到马儿
              //判断一下，当前的 vehicles 属性是null, 就获取一匹马
              //if (vehicles == null) {
              if (!(vehicles instanceof Horse)) {
                  //这里使用的是多态，向上转型
                  vehicles = VehiclesFactory.getHorse();
              }
              //这里体现使用接口调用    运行类型为 horse
              vehicles.work();
          }
          //过火焰山
          public void passFireHill() {
              if (!(vehicles instanceof Plane)) {
                  //这里使用的是多态
                  vehicles = VehiclesFactory.getPlane();
              }
              //这里体现使用接口调用
              vehicles.work();
      
          }
      }
      ```

  - `Homework06.java`

    - ```java
      package com.hspedu.homework;
      
      public class Homework06 {
          public static void main(String[] args) {
      
              //Person tang = new Person("唐僧", new Horse());    //初始交通工具设置为马
              Person tang = new Person("唐僧", VehiclesFactory.getHorse()); //若要求为同一匹马，则应该改成这样才对
              tang.common();//一般情况下
              tang.passRiver();//过河
              tang.common();//一般情况下
              tang.passRiver();//过河
              tang.passRiver();//过河
              tang.passRiver();//过河
              //过火焰山
              tang.passFireHill();
      
          }
      }
      /*题目要求：
          1.有一个交通工具接口类Vehicles，有work接口
          2.有Horse类和Boat类分别实现Vehicles
          3.创建交通工具工厂类，有两个方法分别获得交通工具Horse和Boat
          4.有Person类，有name和Vehicles属性，在构造器中为两个属性赋值    （这里其实默认认为一个人同时只能使用一种交通工具）
          5.实例化Person对象“唐僧”，要求一般情况下用Horse作为交通工具，遇到大河时用Boat作为交通工具
          6.增加一个情况，如果唐僧过火焰山, 使用 飞机 ==> 程序扩展性, 我们前面的程序结构就非常好扩展
      使用代码实现上面的要求
          编程：需求---->理解---->代码-->优化		*/
      ```

##### 练习7

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework07 {
        public static void main(String[] args) {
            //实例化不同的car对象
            Car2 car2 = new Car2(60);
            car2.getAir().flow();
            Car2 car21 = new Car2(-1);
            car21.getAir().flow();
            Car2 car22 = new Car2(20);
            car22.getAir().flow();
        }
    }
    
    /*题目要求：
        有一个Car2类，有属性temperature（温度），车内有Air（空调）类，有吹风的功能flow，
        Air会监视车内的温度，如果温度超过40度则吹冷气。如果温度低于0度则吹暖气，如果在这之间则关掉空调。
        实例化具有不同温度的Car对象，调用空调的flow方法，测试空调吹的风是否正确
        体现类与类的包含关系的案例 类(内部类：成员内部类)        */
    class Car2 {
        private double temperature;
    
        public Car2(double temperature) {
            this.temperature = temperature;
        }
    
        //Air 成员内部类
        class Air {  //空调类
            public void flow() {
                if (temperature > 40) {
                    System.out.println("温度大于40，空调吹冷气..");
                } else if (temperature < 0) {
                    System.out.println("温度小于0，空调吹暖气..");
                } else {
                    System.out.println("温度正常，关闭空调..");
                }
            }
        }
    
        //使用成员内部类的第二种方式，在外部类中定义一个方法专门返回一个Air对象
        public Air getAir() {
            return new Air();
        }
    }
    ```

##### 练习8

- 示例：

  - ```java
    package com.hspedu.homework;
    
    public class Homework08 {
        public static void main(String[] args) {
            //演示一下枚举值得switch使用
            Color green = Color.GREEN;
            green.show();
            //比较一下
            //switch () 中，放入枚举对象
            //在每个case 后，直接写上在枚举类中，定义的枚举对象即可
            switch (green) {    //枚举对象
                case YELLOW:
                    System.out.println("匹配到黄色");
                    break;
                case BLACK:
                    System.out.println("匹配到黑色");
                    break;
                default:
                    System.out.println("没有匹配到..");
            }
        }
    }
    
    /*
    枚举类：创建一个Color枚举类：
        1.有 RED,BLUE,BLACK,YELLOW,GREEN 这个五个枚举值/对象；
        2.Color有三个属性redValue，greenValue，blueValue，
        3.创建构造方法，参数包括这三个属性，
        4.每个枚举值都要给这三个属性赋值，三个属性对应的值分别是
            red：255,0,0  blue:0,0,255  black:0,0,0  yellow:255,255,0  green:0,255,0
        5.定义接口，里面有方法show，要求Color实现该接口
        6.show方法中显示三属性的值
        7.将枚举对象在switch语句中匹配使用      */
    
    interface IMyInterface {
        public void show();
    }
    
    enum Color implements IMyInterface {
        //列举枚举对象的时候用逗号隔开，用分号结尾
        RED(255, 0, 0),
        BLUE(0, 0, 255),
        BLACK(0, 0, 0),
        YELLOW(255, 255, 0),
        GREEN(0, 255, 0);
    
        //三个属性
        private int redValue;
        private int greenValue;
        private int blueValue;
    
        //包含三个参数的有参构造器
        Color(int redValue, int greenValue, int blueValue) {
            this.redValue = redValue;
            this.greenValue = greenValue;
            this.blueValue = blueValue;
        }
    
        @Override
        public void show() {
            System.out.println("属性值为：" + redValue + "、" + greenValue + "、" + blueValue);
        }
    }
    ```

### （三）异常

#### 1.异常的引入

- 异常：exception

- 示例：

  - ```java
    package com.hspedu.exception_;
    
    public class Exception01 {
        public static void main(String[] args)  {
            int num1 = 10;
            int num2 = 0;//Scanner();
    
            //int res = num1 / num2;
    
            try {
                int res = num1 / num2;
            } catch (Exception e) {
                //e.printStackTrace();
                System.out.println("出现异常的原因：" + e.getMessage());//输出异常信息
            }
    
            /*解读：
                1. num1 / num2  -> 10 / 0
                2. 当执行到 num1 / num2 时，因为 num2 = 0，程序就会出现(抛出) 异常 ArithmeticException
                3. 当抛出异常后，程序就退出，崩溃了，下面的代码就不在执行
                4. 大家想想这样的程序好吗? 不好，不应该出现了一个不算致命的问题，就导致整个系统崩溃
                5. java 设计者，提供了一个叫 异常处理机制来解决该问题
                    int res = num1 / num2;
                    如果程序员，认为一段代码可能出现异常/问题，可以使用try-catch异常处理机制来解决从而保证程序的健壮性
                    操作步骤：将该代码块->选中->快捷键 ctrl + alt + t -> 选中 try-catch
                6. 如果进行异常处理，那么即使出现了异常，程序可以继续执行            */
    
            System.out.println("程序继续运行....");
    
        }
    }
    ```

#### 2.异常介绍

- 异常的基本概念：
  - Java 语言中，将程序执行中发生的不正常情况称为 异常。（开发中的语法错误和逻辑错误不是异常）
- 执行过程中所发生的异常实践可分为两大类：
  1. Error（错误）：Java 虚拟机无法解决的严重问题。
     - 如：JVM系统内部错误、资源耗尽等严重错误
     - 比如：StackOverflowError（栈溢出）、OOM（out of memory）
     - Error 是严重错误，程序会崩溃
  2. Exception：其他因编程错误或偶然的外在因素导致的一般性问题，可以使用针对性的代码进行处理
     - 例如空指针访问，试图读取不存在的文件，网络连接中断等等
     - Exception分为两大类：
       - 运行时异常（程序运行时发生的异常）
       - 编译时异常（编程时，由编译器检查出的异常）

#### 3.异常体系图

- 异常体系图：

  - Serializable（接口，被实现）
  - Object（类，被继承）
    - Throwable
      - Exception：异常
        - RuntimeException：运行时异常
          - NullPointException：空指针异常
          - ArithmeticException：算数异常
          - ArrayIndexOutOfBoundsException：数组索引越界异常
          - ClassCastException：类型转换异常
          - NumberFormatException：数组格式异常
          - NoSuchElementException
        - FileNotFoundException（属于编译异常）
        - ...
      - Error：致命错误
        - OutOfMemoryError：内存不足
        - StackOverflowError：栈溢出

- IDEA 继承图的使用

- 小结：

  1. 异常分为两大类：运行时异常和编译时异常
  2. 运行时异常，编译器不要求强制处置的异常。一般是指编程时的逻辑错误，是程序员应该避出现的错误。`java.lang.EuntimeExcepition`类及它的子类都是运行时异常
  3. 对于运行时异常，可以不做处理，因为这类异常很普遍，若全处理可能会对程序的可读性和运行效率产生影响
  4. 编译时异常，是编译器要求必须处置的异常

- 示例：

  - ```java
    package com.hspedu.exception_;
    
    import java.io.FileInputStream;
    import java.io.IOException;
    
    public class Exception02 {
        public static void main(String[] args) {
    
            /*
            FileInputStream fis;
            fis = new FileInputStream("d:\\aa.jpg");    //Unhandled exception: java.io.FileNotFoundException
            int len;
            while ((len = fis.read()) != -1) {
                System.out.println(len);        */
    
            try {
                FileInputStream fis;
                fis = new FileInputStream("d:\\aa.jpg");
                int len;
                while ((len = fis.read()) != -1) {
                    System.out.println(len);
                }
                fis.close();
            } catch (IOException e) {
                e.printStackTrace();
            }
        }
    }
    ```

#### 4.常见的运行时异常

- 常见的运行时异常包括：

  1) NullPointerException 空指针异常
  2) ArithmeticException 数学运算异常
  3) ArrayIndexOutOfBoundsException 数组下标越界异常
  4) ClassCastException 类型转换异常
  5) NumberFormatException 数字格式不正确异常

- 常见的运行时异常举例：

  1. NullPointerException 空指针异常：当应用程序试图在需要对象的地方使用 null 时，抛出该异常

     - ```java
       package com.hspedu.exception_;
       
       public class NullPointerException_ {
           public static void main(String[] args) {
       
               String name = null;
               System.out.println(name.length());
           }
       }
       ```

  2. ArithmeticException 数学运算异常：当出现异常的运算条件时，抛出此异常。例如，一个整数除以零时，抛出此类的一个实例

  3. ArrayIndexOutOfBoundsException 数组下标越界异常：用非法索引访问数组时抛出的异常。如果索引为负或大于等于数组大小，则该索引为非法索引

     - ```java
       package com.hspedu.exception_;
       
       public class ArrayIndexOutOfBoundsException_ {
           public static void main(String[] args) {
               int[] arr = {1,2,4};
               for (int i = 0; i <= arr.length; i++) {
                   System.out.println(arr[i]);
               }
           }
       }
       ```

  4. ClassCastException 类型转换异常：当试图将对象强制转换为不是实例的子类时，抛出该异常

     - ```java
       package com.hspedu.exception_;
       
       public class ClassCastException_ {
           public static void main(String[] args) {
               A b = new B(); //向上转型，父类引用执行子类对象
               B b2 = (B)b;    //向下转型，这里是OK
               C c2 = (C)b;    //这里抛出ClassCastException
           }
       }
       class A {}
       class B extends A {}
       class C extends A {}
       ```

  5. NumberFormatException 数字格式不正确异常：当应用程序试图将字符串转换成一种数值类型，但该字符串不能转换为适当格式时，抛出该异常。使用异常我们可以确保输入是满足条件数字

     - ```java
       package com.hspedu.exception_;
       
       public class NumberFormatException_ {
           public static void main(String[] args) {
       //        String name = "韩顺平教育";
               String name = "1234";
               //将String 转成 int
               int num = Integer.parseInt(name);   //抛出NumberFormatException
               System.out.println(num);    //1234
           }
       }
       ```

#### 5.编译异常

##### 编译异常介绍

- 编译异常是指在编译期间，就必须处理的异常，否则代码不能通过编译

##### 常见的编译异常

- SQLException：操作数据库时，查询表可能发生异常
- IOException：操作文件时，发生的异常
- FileNotFoundException：当操作一个不存在的文件时，发生异常
- ClassNotFoundException：加载类，而该类不存在时，异常
- EOFException：操作文件，到文件末尾，发生异常
- IllegalArguementException：参数异常

#### 6.异常处理

##### 异常处理基本介绍

- 异常处理就是当异常发生时，对异常处理的方式

##### 异常处理的方式

- 第一种方式：`try - catch -fianlly`

  - 程序员在代码中捕获发生的异常，自行处理

  - 示意图：

    - ```java
      try{
          代码（可能有异常）
      }catch(Exception e){
          //捕获到异常
          //1.当异常发生时
          //2.系统将异常封装成 Exception 对象 e，传递给 catch
          //3.得到异常对象后，程序员自己处理
          //4.如果try代码块没有发生异常，则catch代码块不会执行
      }finally{
          //1.不管try代码块是否有异常发生，始终要执行finally代码块
          //2.所以，通常将释放资源的代码，放在finally
      }
      ```

    - 

- 第二种方式：`throws`

  - 将发生的异常抛出，交给调用者来处理，最顶级的处理者就是 JVM
  - 示意图：
    - JVM → main → 方法1 → 方法1调用的方法2
    - JVM ←（throws）← main ← （throws）← 方法 ← （throws）← 方法1调用的方法2
  - throws 处理机制：
    - `try - catch -fianlly` 和 `throws` 二选一
    - 如果程序员，没有显示是处理异常，默认 throws

#### 7.try - catch 异常处理

##### try-catch 方式处理异常说明

- Java 提供 try 和 catch 块来处理异常。try 块用于包含可能出错的代码。catch 块用于处理 try 块中发生的异常。可以根据需要在程序中有多个 try...catch 块

##### 基本语法

- ```java
  try{
      //可疑代码
      //将异常生成的异常对象，传递给catch块
  }catch(Exception e){
      //捕获到异常
      //1.当异常发生时
      //2.系统将异常封装成 Exception 对象 e，传递给 catch
      //3.得到异常对象后，程序员自己处理
      //4.如果try代码块没有发生异常，则catch代码块不会执行
  }finally{	//如果没有finally，语法也可以通过
      //1.不管try代码块是否有异常发生，始终要执行finally代码块
      //2.所以，通常将释放资源的代码，放在finally
  }
  ```

##### try-catch 注意事项

- try-catch 注意事项：

  1. 如果异常发生了，则异常发生后面的代码不会执行，直接进入到 catch 块
  2. 如果异常没有发生，则顺序执行 try 的代码块，不会进入到 catch
  3. 如果希望不管是否发生异常，都执行某段代码（比如关闭连接，释放资源等）则使用 finally 代码块
  4. 如果try代码块有可能有多个异常，可以使用多个 catch 分别捕获不同的异常，相应处理。要求子类异常写在前面，父类异常写在后面   
  5. 可以进行 try-finally 配合使用, 这种用法相当于没有捕获异常，因此程序会直接崩掉 / 退出
     - 应用场景：就是执行一段代码，不管是否发生异常，都必须执行某个业务逻辑

- 示例1（包含细节 1~3）

  - ```java
    package com.hspedu.try_;
    
    public class TryCatchDetail {
        public static void main(String[] args) {
    
            //ctrl + atl + t
            //老韩解读
            //1. 如果异常发生了，则异常发生后面的代码不会执行，直接进入到catch块
            //2. 如果异常没有发生，则顺序执行try的代码块，不会进入到catch
            //3. 如果希望不管是否发生异常，都执行某段代码(比如关闭连接，释放资源等)则使用如下代码- finally
            try {
                String str = "aaa";
                int a = Integer.parseInt(str);  //这里会发生异常
                System.out.println("数字：" + a);  //这里不会执行
            } catch (NumberFormatException e) {
                System.out.println("异常信息：" + e.getMessage());   //若无异常，则catch不会执行
            } finally {
                System.out.println("finally代码块被执行...");
            }
    
            System.out.println("程序继续...");
        }
    }
    ```

- 示例2（包含细节 4）：

  - ```java
    package com.hspedu.try_;
    
    public class TryCatchDetail02 {
        public static void main(String[] args) {
    
            /*解读：
                1.如果try代码块有可能有多个异常
                2.可以使用多个catch 分别捕获不同的异常，相应处理
                3.要求子类异常写在前面，父类异常写在后面     
                4.捕获到一个异常之后就会退出try块，后面的异常不会捕获       */
            try {
                Person person = new Person();
                //person = null;
                System.out.println(person.getName());//NullPointerException
                int n1 = 10;
                int n2 = 0;
                int res = n1 / n2;//ArithmeticException
            } catch (NullPointerException e) {  //专门捕获空指针异常
                System.out.println("空指针异常：" + e.getMessage());
            } catch (ArithmeticException e) {   //专门捕获算术异常
                System.out.println("算术异常：" + e.getMessage());
            } catch (Exception e) {     //父类异常写在后面
                System.out.println(e.getMessage());
            } finally {
            }
        }
    }
    
    class Person {
        private String name = "jack";
    
        public String getName() {
            return name;
        }
    }
    ```

- 示例3（包含细节 5）：

  - ```java
    package com.hspedu.try_;
    
    public class TryCatchDetail03 {
        public static void main(String[] args) {
    
            /*
            5.可以进行 try-finally 配合使用, 这种用法相当于没有捕获异常，因此程序会直接崩掉/退出
            应用场景：就是执行一段代码，不管是否发生异常，都必须执行某个业务逻辑     */
            try{
                int n1 = 10;
                int n2 = 0;
                System.out.println(n1 / n2);
            }finally {
                System.out.println("执行了finally..");
            }	//若try块有异常，则finally块执行完后程序会直接崩掉，后面不会执行
            System.out.println("程序继续执行..");
        }
    }
    ```

##### try - catch 异常处理练习

- 练习1（？？？）：

  - ```java
    package com.hspedu.try_;
    
    public class TryCatchExercise01 {
    }
    
    class Exception01 {
        public static int method() {       //一个静态方法
            try {
                String[] names = new String[3];//String[]数组
                if (names[1].equals("tom")) {   //NullPointerException  空指针异常
                    System.out.println(names[1]);
                } else {
                    names[3] = "hspedu";    //数组下标越界
                }
                return 1;
            } catch (ArrayIndexOutOfBoundsException e) {
                return 2;
            } catch (NullPointerException e) {//捕获
                return 3;   //这里会执行，但是finally块必须执行（？？？）
            } finally { //finally块必须执行
                return 4; //所以返回4
            }
        }
    
        public static void main(String[] args) {
            System.out.println(method()); //4
        }
    }
    ```

- 练习2：

  - ```java
    package com.hspedu.try_;
    
    public class TryCatchExercise02 {
    }
    
    class Exception02 {
        public static int method() {
            int i = 1;
            try {
                i++; //i = 2
                String[] names = new String[3];
                if (names[1].equals("tom")) {   //空指针异常
                    System.out.println(names[1]);
                } else {
                    names[3] = "hspedu";
                }
                return 1;
            } catch (ArrayIndexOutOfBoundsException e) {
                return 2;
            } catch (NullPointerException e) {
                return ++i; //这里的++i会执行，但是return并不会执行，会转而去执行finally代码块，i = 3
            } finally { //finlly块必须执行
                return ++i; //i = 4
            }
        }
    
        public static void main(String[] args) {
            System.out.println(method());
        }
    }
    ```

- 练习3（？？？）：

  - ```java
    package com.hspedu.try_;
    
    public class TryCatchExercise03 {
    }
    
    class ExceptionExe01 {
        public static int method() {
            int i = 1;  //i = 1
            try {
                i++;    // i=2
                String[] names = new String[3];
                if (names[1].equals("tom")) { //空指针异常
                    System.out.println(names[1]);
                } else {
                    names[3] = "hspedu";
                }
                return 1;
            } catch (ArrayIndexOutOfBoundsException e) {
                return 2;
            } catch (NullPointerException e) {
                return ++i;  //i = 3 => 保存临时变量 temp = 3;    （？？？为什么）  //这里该return，但要先去执行完finally才回来返回
            } finally {
                ++i; //i = 4
                System.out.println("i = " + i);// i = 4
            }
        }
    
        public static void main(String[] args) {
            System.out.println(method());// 3
        }
    }
    ```

- 练习4：

  - ```java
    package com.hspedu.try_;
    
    import java.util.Scanner;
    
    public class TryCatchExercise04 {
        public static void main(String[] args) {
    
            //如果用户输入的不是一个整数，就提示他反复输入，直到输入一个整数为止
            /*思路：
                1. 创建Scanner对象
                2. 使用无限循环，去接收一个输入
                3. 然后将该输入的值，转成一个int
                4. 如果在转换时，抛出异常，说明输入的内容不是一个可以转成int的内容
                5. 如果没有抛出异常，则break 该循环        */
            Scanner scanner = new Scanner(System.in);
            int num = 0;	//int类型，用于保存最后的整数
            String inputStr = "";	//String类型，用于接收键盘输入
            while (true) {
    
                System.out.println("请输入一个整数:"); 
                inputStr = scanner.next(); 
                try {
                    num = Integer.parseInt(inputStr); //这里是可能抛出异常，如果输入的不是一个整数，则抛出异常
                    break;  //如果没有抛出异常，则break跳出while循环
                } catch (NumberFormatException e) {
                    System.out.println("你输入的不是一个整数:");
                }
            }
    
            System.out.println("你输入的值是：" + num);
        }
    }
    ```

#### 8.throws 异常处理

##### throws 基本介绍

- throws 基本介绍：
  1. 如果一个方法（中的语句执行时）可能生成某种异常，但是不能确定如何处理这种异常，则此方法应显式地声明抛出异常，表明该方法将不对这些异常进行处理，而由该方法的调用者处理
  2. 在方法中声明用 throws 语句可以声明抛出异常的的列表，throws 后面的异常类型可以是方法中产生的异常类型，也可以是它的父类

##### 快速入门案例

- 示例：

  - ```java
    package com.hspedu.throws_;
    
    import java.io.FileInputStream;
    import java.io.FileNotFoundException;
    
    public class Throws01 {
        public static void main(String[] args) {
    
        }
    
        public void f2() throws FileNotFoundException,NullPointerException,ArithmeticException {
            //创建了一个文件流对象（IO流章节会详细学习）
            /*解读:
                1. 这里的异常是一个 FileNotFoundException 编译异常
                2. 使用前面讲过的 try-catch-finally
                3. 使用throws ,抛出异常, 让调用f2方法的调用者(方法)处理
                4. throws后面的异常类型可以是方法中产生的异常类型，也可以是它的父类
                5. throws 关键字后也可以是 异常列表, 即可以抛出多个异常        */
            FileInputStream fis = new FileInputStream("d://aa.txt");
        }
    }
    ```

##### 注意事项和使用细节

- 注意事项和使用细节：
  1. 对于编译异常，程序中必须处理，比如 try-catch 或者 throws
  2. 对于运行时异常，程序中如果没有处理，默认就是 throws 的方式处理
  3. 子类重写父类的方法时，对抛出异常的规定：
     - 子类重写的方法，所抛出的异常类型要么和父类抛出的异常一致，要么为父类抛出的异常类型的子类型
  4. 在 throws 过程中，如果有方法 try-catch , 就相当于处理异常，就可以不必throws

#### 9.自定义异常

##### 自定义异常基本概念

- 当程序中出现了某些错误，但该错误信息并没有在 Throwsable 子类中描述处理，这个时候可以自己设计异常类，用于描述该错误信息

##### 自定义异常的步骤

- 自定义异常的步骤：
  1. 定义类：自定义异常类名（程序员自己写），继承 Exception 或 RuntimeException
  2. 如果继承 Exception，属于编译异常
  3. 如果继承 RuntimeException，属于运行异常（一般来说，继承 RuntimeException）

##### 自定义异常的应用实例

- 要求：

  - 当我们接收 Person 对象年龄时，要求范围在 18~120 之间，否则抛出一个自定义异常（要求：继承 RuntimeException），并给出提示信息

- 示例：

  - ```java
    package com.hspedu.customexception_;
    
    public class CustomException {
        public static void main(String[] args) /*throws AgeException*/ {
    
            int age = 180;
            //要求范围在 18 – 120 之间，否则抛出一个自定义异常
            if(!(age >= 18 && age <= 120)) {
                //这里我们可以通过构造器，设置信息
                throw new AgeException("年龄需要在 18~120之间");
            }
            System.out.println("你的年龄范围正确.");
        }
    }
    //自定义一个异常
    /*解读：
        1. 一般情况下，我们自定义异常是继承 RuntimeException
        2. 即把自定义异常做成 运行时异常。好处时：我们可以使用默认的处理机制，即比较方便       
        3. 如果继承 Exception，则认为是一个编译异常，必须立即处理		*/
    class AgeException extends RuntimeException {
        public AgeException(String message) {//构造器
            super(message);
        }
    }
    ```

#### 10.throw 和 throws 的区别

- throw 和 throws 的区别：

  - throw：是手动生成异常对象的关键字
    - 用于在方法体中
    - 后面跟异常对象
  - throws：是异常处理的一种方式
    - 用在方法声明处
    - 后面跟异常类型

- 练习：

  - ```java
    package com.hspedu.throws_;
    
    public class ThrowException {
        public static void main(String[] args) {
            try {
                ReturnExceptionDemo.methodA();  //调用A方法
            } catch (Exception e) {
                System.out.println(e.getMessage()); //第三句输出
            }
            ReturnExceptionDemo.methodB();  //调用B方法
        }
    }
    
    class ReturnExceptionDemo {
        static void methodA() {
            try {
                System.out.println("进入方法A");    //第一句输出
                throw new RuntimeException("制造异常"); //抛出一条异常声明  //由catch输出
            } finally {
                System.out.println("用A方法的finally");     //第二句输出
            }
        }
    
        static void methodB() {
            try {
                System.out.println("进入方法B");    //第四句输出
                return;
            } finally {
                System.out.println("调用B方法的finally");    //第五句输出
            }
        }
    }
    ```

#### 11.作业练习

- 练习1：

  - ```java
    package com.hspedu.homework;
    
    public class Homework01 {
        public static void main(String[] args) {    //命令行参数是由args数组来接收的
            /*题目要求：
                1.编写应用程序EcmDef.java，接收命令行的两个参数(整数)，计算两数相除。
                2.计算两个数相除，要求使用方法 cal(int n1, int n2)
                3.对数据格式不正确(NumberFormatException)、
                    缺少命令行参数(ArrayIndexOutOfBoundsException)、
                    除0(ArithmeticException) 进行异常处理              */
    
            try {
                //先验证输入的参数的个数是否正确 两个参数
                if(args.length != 2) {
                    throw new ArrayIndexOutOfBoundsException("参数个数不对"); //手动抛出异常
                }
    
                //先把接收到的参数，转成整数     //这里若有异常会自动抛出
                int n1 = Integer.parseInt(args[0]);
                int n2 = Integer.parseInt(args[1]);
    
                double res = cal(n1, n2);   //该方法可能抛出ArithmeticException
                System.out.println("计算结果是：" + res);
    
            } catch (ArrayIndexOutOfBoundsException e) {    //检查是否有 缺少命令行参数 异常
                System.out.println(e.getMessage());
            } catch (NumberFormatException e) { //检查是否有 数据格式不正确 异常
                System.out.println("参数格式不正确，需要输出整数");
            } catch (ArithmeticException e) {       //检查是否有 除0 异常
                System.out.println("出现了除0的异常");
            }
        }
    
        //编写cal方法，就是两个数的商
        public static double cal(int n1, int n2) {
            return n1 / n2;
        }
    }
    ```

- 练习2：

  - ```java
    package com.hspedu.homework;
    
    public class Homework02 {
        public static void main(String[] args) {
            //args.length = 0
            //这里发生的是 ArrayIndexOutOfBoundsException
    
            if(args[4].equals("john")){  //可能发生NullPointerException，若参数不足5个，则这里发生空指针异常
                System.out.println("AA");
            }else{
                System.out.println("BB");
            }
            Object o = args[2];     //String->Object ，向上转型  //若执行到这里，则说明参数至少5个，不会发生空指针异常
            Integer i = (Integer)o;    //错误，这里一定会发生 ClassCastException  //因为参数类型传入时为 String类型
        }
    }
    ```

- 练习3：

  - ```java
    package com.hspedu.homework;
    
    public class Homework03 {
        public static void func() {//静态方法
            try {
                throw new RuntimeException();   //这里手动抛出一个运行异常
            } finally {
                System.out.println("B");    //这里一定执行    //第一条输出
            }
        }
    
        public static void main(String[] args) {//main方法
            try {
                func();
                System.out.println("A");    //因为func() 已经抛出了异常，所以这里不在执行
            } catch (Exception e) {
                System.out.println("C");    //try中有抛出异常，第二条输出
            }
            System.out.println("D");    //第三条输出
        }
    }
    ```

- 练习4：

  - ```java
    package com.hspedu.homework;
    
    public class Homework04 {
        public static void main(String[] args) {//main方法
            try {
                showExce();     //编译异常被 try-catch 处理，程序可以继续执行
                System.out.println("A");    //这里不再执行
            } catch (Exception e) {
                System.out.println("B");    //第一条输出
            } finally {
                System.out.println("C");    //第二条输出
            }
            System.out.println("D");    //第三条输出
        }
    
        public static void showExce() throws Exception {
            throw new Exception();  //直接抛出一条编译异常
        }
    
    }
    
    ```

### （四）包装类

#### 1.包装类

##### 包装类的分类

- 包装类的分类：

  1) 针对八种基本数据类型相应的引用类型——包装类

  2) 有了类的特点，就可以调用类中的方法

  3) 基本数据类型与包装类的对应：

     - | 基本数据类型 | 包装类        |
       | ------------ | ------------- |
       | boolean      | Boolean       |
       | char         | **Character** |
       | byte         | Byte          |
       | short        | Short         |
       | int          | **Integer**   |
       | long         | Long          |
       | float        | Float         |
       | double       | Double        |

- 补充，显示继承图：

  - 在类中，右键、diagrams、show diagrams

##### 包装类和基本数据的转换

- 包装类和基本数据的转换：

  1. jdk5 前的手动装箱和拆箱方式。装箱：基本类型 -> 包装类型。反之，拆箱
  2. jdk5 后（含 jdk5）的自动装箱和拆箱方式
  3. 自动装箱底层调用的是 valueof 方法。比如：`Integer.valueof()`
  4. 其他包装类的用法类似

- 示例：

  - ```java
    package com.hspedu.wrapper;
    
    public class Integer01 {
        public static void main(String[] args) {
            //演示int <--> Integer 的装箱和拆箱
    
            //jdk5前是手动装箱和拆箱
            //手动装箱 int->Integer
            int n1 = 100;
            Integer integer = new Integer(n1);  //手动装箱方式1
            Integer integer1 = Integer.valueOf(n1);  //手动装箱方式2
    
            //手动拆箱
            //Integer -> int
            int i = integer.intValue();     //对象名.intValue()
    
            //jdk5后，就可以自动装箱和自动拆箱
            int n2 = 200;
            //自动装箱 int->Integer
            Integer integer2 = n2;  //直接将int类型赋给Integer类型的对象    //底层使用的是 Integer.valueOf(n2)
            //可以通过 debug，F7 进入查看
    
            //自动拆箱 Integer->int
            int n3 = integer2; //底层仍然使用的是 intValue()方法
        }
    }
    ```

- 练习：

  - ```java
    package com.hspedu.wrapper;
    
    public class WrapperExercise01 {
        public static void main(String[] args) {
            Double d = 100d; //ok, 自动装箱 Double.valueOf(100d);
            Float f = 1.5f; //ok, 自动装箱 Float.valueOf(1.5f);
    
            Object obj1 = true? new Integer(1) : new Double(2.0);   //三元运算符（是一个整体）
            System.out.println(obj1);   // 什么? 1.0      //后面2.0是double类型，整体会类型提升到double，而不是int
    
            Object obj2;
            if(true)
                obj2 = new Integer(1);
            else
                obj2 = new Double(2.0); //这里else不会指向，最后还是int类型
            System.out.println(obj2);   //1
        }
    }
    ```

  - 三元运算符（！！！）

##### 包装类型和 String 类型的相互转换

- 示例：

  - ```java
    package com.hspedu.wrapper;
    
    public class WrapperVSString {
        public static void main(String[] args) {
            //包装类(Integer)->String
            
            Integer i = 100;    //自动装箱
            //方式1
            String str1 = i + "";
            //方式2
            String str2 = i.toString();
            //方式3
            String str3 = String.valueOf(i);
    
            //String -> 包装类(Integer)
            String str4 = "12345";
            //方式1
            Integer i2 = Integer.parseInt(str4);    //方法返回的是int类型   //使用到自动装箱
            //方式2
            Integer i3 = new Integer(str4); //Integer的构造器之一     //参数可以是String类型
    
            System.out.println("ok~~");
        }
    }
    ```

##### Integer 类和 Character 类的常用方法

- 示例：

  - ```java
    package com.hspedu.wrapper;
    
    public class WrapperMethod {
        public static void main(String[] args) {
            System.out.println(Integer.MIN_VALUE); //Integer.MIN_VALUE：返回int类型的最小值
            System.out.println(Integer.MAX_VALUE);//Integer.MAX_VALUE：返回最大值
    
            System.out.println(Character.isDigit('a'));//Character.isDigit('a')：判断是不是数字
            System.out.println(Character.isLetter('a'));//Character.isLetter('a')：判断是不是字母
            System.out.println(Character.isUpperCase('a'));//Character.isUpperCase('a')：0判断是不是大写
            System.out.println(Character.isLowerCase('a'));//Character.isLowerCase('a')：判断是不是小写
    
            System.out.println(Character.isWhitespace('a'));//Character.isWhitespace('a')：判断是不是空格
            System.out.println(Character.toUpperCase('a'));//Character.toUpperCase('a')：转成大写
            System.out.println(Character.toLowerCase('A'));//Character.toLowerCase('A')：转成小写
    
        }
    }
    ```

- 补充：在继承体系图中，点击上方选项中的 method 可查看所有方法

##### Integer 类面试题

- 示例：

  - ```java
    package com.hspedu.wrapper;
    
    public class WrapperExercise02 {
        public static void main(String[] args) {
            Integer i = new Integer(1);
            Integer j = new Integer(1); //new出来的一定不是同一个对象
            System.out.println(i == j);  //False
    
            //所以，这里主要是看范围，如果传入的int的值在 -128 ~ 127 就是直接返回
            /*
                解读：
                    1. 如果i 在 IntegerCache.low(-128)~IntegerCache.high(127),就直接从数组返回
                    2. 如果不在 -128~127,就直接 new Integer(i)
             public static Integer valueOf(int i) {
                if (i >= IntegerCache.low && i <= IntegerCache.high)
                    return IntegerCache.cache[i + (-IntegerCache.low)];
                return new Integer(i);
            }
             */
            Integer m = 1; //底层 Integer.valueOf(1); -> 阅读源码
            Integer n = 1;  //底层 Integer.valueOf(1);
            System.out.println(m == n);     //T
            //Integer.valueOf(1);
    
            //所以，这里主要是看范围 -128 ~ 127 就是直接返回，否则，就 new Integer(xx);
            Integer x = 128;    //底层Integer.valueOf(1);
            Integer y = 128;    //底层Integer.valueOf(1);
            System.out.println(x == y); //False
        }
    }
    ```

##### Intege 类面试题总结

- 示例：

  - ```java
    package com.hspedu.wrapper;
    
    public class WrapperExercise03 {
        public static void main(String[] args) {
            //-128~127
            //只要是new出来的一定不是同一个对象
    
            //示例一
            Integer i1 = new Integer(127);
            Integer i2 = new Integer(127);
            System.out.println(i1 == i2);   //F
    //示例二
            Integer i3 = new Integer(128);
            Integer i4 = new Integer(128);
            System.out.println(i3 == i4);   //F
    
    //示例三
            Integer i5 = 127;   //底层Integer.valueOf(127)
            Integer i6 = 127;   //-128~127
            System.out.println(i5 == i6); //T
    //示例四
            Integer i7 = 128;
            Integer i8 = 128;   //new
            System.out.println(i7 == i8);   //F
    //示例五
            Integer i9 = 127; //Integer.valueOf(127)
            Integer i10 = new Integer(127);
            System.out.println(i9 == i10);  //F
    
    //示例六
            Integer i11 = 127;
            int i12 = 127;
            //只要有基本数据类型，判断的是，值是否相同
            //Integer和int比较，Integer会拆箱，比较值
            System.out.println(i11 == i12); //T
    //示例七
            Integer i13 = 128;
            int i14 = 128;
            System.out.println(i13 == i14);//T
        }
    }
    ```

#### 2.String 类

##### String 类的理解和创建对象

1. String 对象用于保存字符串，也就是一组衣服序列。String声明的是一个引用地址，而不是对其进行赋值

2. 字符串常量对象是用双引号扩起的字符序列

3. 字符串的字符使用 Unicode 字符编码，一个字符（不区分字母还是汉字）占两个字节

4. String 类较常用的构造器

   - ```java
     String s1 = new String();
     String s2 = new String(String rriginal);
     String s3 = new String(char[] a);
     String s4 = new String(char[] a, int startIndex, int count);
     ...
     ```

5. String 类继承了 Object 类，实现了 Serializable（使 String 类可以串行化，可以进行网络传输）、Comparable（使 String 类的对象可以相互比较大小）、CharSequence 三个接口

6. String 是 final 类，不能被其他的类继承

7. String 有属性：`private final char value[];` 用于存放字符串内容（底层仍然是一个char数组）

8. 一定要注意：value 是一个 final 类型， 不可以修改。即value不能指向新的地址，但是单个字符内容是可以变化 （地址不可修改，但是内容可以修改）

- 示例：

  - ```java
    package com.hspedu.string_;
    
    public class String01 {
        public static void main(String[] args) {
            /*String 的介绍：
                1.String 对象用于保存字符串，也就是一组字符序列
                2. "jack" 字符串常量, 双引号括起的字符序列
                3. 字符串的字符使用Unicode字符编码，一个字符(不区分字母还是汉字)占两个字节
                4. String 类有很多构造器，构造器的重载
                   常用的有：
                        String  s1 = new String();
                        String  s2 = new String(String original);
                        String  s3 = new String(char[] a);
                        String  s4 =  new String(char[] a,int startIndex,int count)
                        String s5 = new String(byte[] b)
                5. String 类实现了：
                        接口 Serializable（String 可以串行化:可以在网络传输）
                        接口 Comparable （String 对象可以比较大小）
                        接口 CharSequence
                6. String 是 final 类，不能被其他的类继承
                7. String 有属性：private final char value[]; 用于存放字符串内容（底层仍然是一个char数组）
                8. 一定要注意：value 是一个 final 类型， 不可以修改(需要功力)
                    即value不能指向新的地址，但是单个字符内容是可以变化 （地址不可修改，但是内容可以修改）        */
    
            String name = "jack";   //name可以理解为变量 而"jack"是字符串常量
            name = "tom";   //name内容可以修改，这里其实是新建了一个tom字符串常量，原来的jack仍然存在，需要垃圾回收机制后续自动回收
            final char[] value = {'a','b','c'};
            char[] v2 = {'t','o','m'};
            value[0] = 'H'; //内容可以修改
            //value = v2;   //地址不可以修改，value地址
        }
    }
    ```

##### 创建 String 对象的两种方式

- 创建 String 对象的两种方式：

  1. 直接赋值：`String s = "aaa";`
  2. 调用构造器：`String s = new String("aaa");`

- 两种创建 String 对象的区别（？？？）：

  1. 方式一：先从常量池查看是否有`"aaa"`数据空间，如果有，则直接指向；如果没有则创建新的数据空间，如何指向。s 最终指向的是常量池内的空间地址
  2. 方式二：先在堆中创建空间，里面维护了 value 属性，指向常量池的 `"aaa"`空间。如果常量池没有`"aaa"`，则创建一个新的。如果有，则直接通过 value指向。最终指向的是队中的空间地址

- 示例：

  - ```java
    ```

##### 练习

- 示例：

  - ```java
    ```

  - 
