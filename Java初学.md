- 网课（韩顺平）（共）：61

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
- Object类详解
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
- enum关键字实现枚举
- JDK内置的基本注解类型
- 元注解：对注释进行注解

#### 3.Exception

- 异常的概念
- 异常体系图
- 常见的异常
- 异常处理
- 自定义异常
- throw和throws的对比

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

## 第三部分：JavaWEB

## 第四部分：主流框架和项目管理



# Java基础

## 一.第一阶段：建立编程思想

### （一）Java概述

#### 1.Java技术体系平台

- Java SE（Java Standard Edition）标准版：
  - 支持面向桌面级应用（如Windows下的应用程序的Java平台，提供了完整的Java核心API，此版本以前称为J2SE
- Java EE（Java Enterprise Edition）企业版：
  - 是为开发企业环境下的应用程序提供的一套解决方案。该技术体系中包含的技术，如：Serclet、Jsp等，主要针对与Web应用程序开发。该版本以前称为J2EE
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
    
    		//怎么把字符串转成字符char -> 含义是指 把字符串的第一个字符得到
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
