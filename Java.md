# Java

## 数据类型

### 引用类型

- Classes
- Arrays
- Interfaces

### 基本类型

boolean

char

byte

short

int

long

float

double

void

## 对象

### 接口

## 初始化和清理

constructor（构造器）

garbage collector（垃圾回收器）

## 访问控制

package（包）

public

private

protected

## 重用类

composition（组合）

inheritance（继承）

super

name hiding（名称隐藏）

incremental development（增量式开发）

upcasting（向上转换）

final

has-a

is-a

## Polymorphism(多态)

Early Function Call Binding

dynamic binding or run-time binding

Extensibility

Downcasting（向下转型）

Run-Time Type Identification

Class object

Reflection:runtime class information

## Abstract Class Interface(抽象类接口)

Abstract Classes

interface & implements 

Extending an interface with inheritance

functional interface

Default Methods

Grouping constants

## Generic

Generic Pair Class

autoboxing

unboxing

Parameterized Types

Raw types

Bounded Type Parameters

wildcards

## Inner Classes

.this

static nested classes

local classes

Anonymous inner classes

Shadowing

## Error Handling with Exceptions

try

catch

throw

throws

finally

Throwable

Types of program Exceptions/Errors

Exception inheritance hierarchy

Checked vs. Runtime Exception

Throwing Checked Exceptions

Throwing Runtime Exceptions

Exception enforcement

BAD Exception Handling

Debugging/Bug-prevention

try-with-resources

AutoCloseable

multi-catch

Exception guidelines 

## Arrays

One-Dimensional Arrays

Two-Dimensional Arrays

Ways of initialized & assigned

Containers of primitives

Array as a Parameter

Returning an array

Filling an array

Copying an array

Comparing arrays

Array element comparisons

Sorting an array

## String

String Constructors

String Methods

Strings->Numbers

String Comparison

StringJoiner

StringBuilder

StringTokenizer

Regular Expressions

Regex

Pattern

Matcher

## Collections of Objects

collection

List interface

Set

SortedSet

Queue & Deque

Map

SortedMap

Container taxonomy

Iterable

Collection functionality

List<E> functionality

ArrayList and LinkedList

ArrayList in a program

LinkedList in a program

making a stack from a LinkedList

Making a queue from a LinkedList

Comparison to Vector

PriorityQueue

Set functionality

SortedSet<E> interface

NavigableSet<E> interface

Map<K,V> interface

Map Details

Accessing all members of Map

SortedMap

LinkedHashMap

Hashing and hash codes

Understanding hashCode()

Holding references

Iterators

Choosing an implementation

Sorting and searching Lists

Making a Collection or Map unmodifiable

Synchronizing a Collection or Map

Unsupported operations

Type Conversion

## The Java I/O System

java.io.File and Scanner

Stream

Stream Hierarchy

Using input Streams

Using output streams

Filtered streams

Readers & Writers

InputStreamReader

BufferedReader

Added functionality

Buffer Files

Reading from a file

Input from Memory

Formatted Memory input

I/O from the command line

Basic file output

PrintWriter

Storing and Recovering Data

RandomAccessFile

Piped Streams

Object Serialization

classes used for serialization

Making your classes serializable

Transient variables

I/O exception

## Concurrency

Parallel Processing

Java Thread

What is a Thread?

Tread use

A multithreaded program

The Thread object

Thread Creation diagram

Runnable interface

java.util.concurrent.Callable<V>

Thread Lifecycle

Blocking Threads

Sleeping

Thread scheduling

Yielding（让步）

Daemon threads

Joining a thread

Catching exceptions

Thread starvation

Thread Priorities: General strategies

Race conditions

Thread Synchronization

Thread deadlock

Wait and notify

Wait/Notify sequence

ForkJoin framework

Incrementor

## Graphic User Interface

AWT(Abstract Windowing Toolkit)

Java Foundation classes

Swing = Lightweight

Swing = Consistent

JButton

JLabel

JPanel

JMunu

JMenuBar

SwingSet

JFrame

JFrame Closing Behaviors

Using RootPaneContainer

JDialog

JWindow 

JApplet

JInternalframe

#### GUI Helper Classes

Dimension

Font

FontMetrics

Color

Graphics

#### Swing GUI Components

JButton

JCheckBox

JRatioButton

JTextField

JPasswordField

JTextArea

JLabel 

JList

JComboBox

JPanel

JOptionPane

JScrollBar

JSlider

------

JOptionPane

JSlider

JProgressBar

JToolTip

Tabbed Pane

JEditorPane

Split pane

Event Support

Event Actions

Actions

Actions Implemented

Text Actions

Listener & Action of JTextField

Listener & Action of JEditorPane

Key Strokes

Model/View/Controller

Swing and MVC

Delegate/Model View

JTree

JList

JComboBox

JTable

JTable Output

Swing's Threading Policy

lengthy GUI-interaction tasks

Setting up the CelsiusConverter project

Adding the Application Logic

## GUI - RUNNING IN BROWSERS

Applet

Java Applet Features

Applet Life Cycle

Java Network Launching Protocol(JNLP)

Java Web Start

JavaFX GUI framework

Structure of a JavaFX Program

Panes, UI Controls, and Shapes

CSS styles

## JDBC

JDBC(Java Database Connectivity)

JDBC Architecture

Four ways to access a database

The four types of Java drivers

Popular JDBC database URL formats

DBMS

Typical JDBC Programming Procedure

Driver Manager

Connecting to and Querying a Database

Wrap into DisplayAuthors

Querying the books Database

JDBC APIs in java.sql package

Java Types vs. SQL Types

Time

Transactions

JDBC Class Diagram

Stored Procedures

JDBC Data Source Architecture

## Java Network Programming 

### Socket

Internet Architecture

TCP/IP stack

Client/Server Communication Paradigm

Socket Programming API

What APIs Needed?

Socket: Conceptual View

Java Socket Programming API

Addressing

Making TCP Connections

TCP Socket

Sending/Receiving Datagram Packets via UDP

UDP Socket

UDP DatagramPacket

Locating/Identifying Network Resources

Security

Establishing a Simple Server Using Stream Sockets

Java Socket Programming Flows(TCP)

Java Socket Programming (UDP)

Compiling and Running 

Iterative server

Concurrent server

Client/Server Interaction with Stream Socket Connections

## functional-style programming and Lambdas,streams

### Functional-style programming

### Lambda expressions

Syntax:->

Method and lambda equivalent

Processing a collection

Reduced lambda syntax

### Ideal use case for lambda expressions

Scenario

members

1:Create Methods that search for members that match one characteristic

2:Create More generalized search methods

3:Specify search criteria code in a local class

4: Specify Search Criteria Code in an Anonymous Class

5: Specify Search Criteria Code with a Lambda Expression

6: Use Standard Functional Interfaces with Lambda Expressions

7: Use Lambda Expressions Throughout Your Application

8: Use Generics More Extensive

9: Use Aggregate Operations That Accept Lambda Expressions as Parameters

#### aggregate operations

filter

map

forEach

#### Lambda expressions in GUI Application

#### Accessing Local Variables of the enclosing scope

#### Target Typing

Target Types and Method arguments

::Method Reference

### Streams

Filters, maps and reductions

A pipeline of operations

Pipelines

Removal from a collection using a predicate lambda

## 关键字及方法

instanceof

#### Collection

put()

keySet()

iterator()

hasNext()

next()

remove()

getKey()

getValue()

super()

extends

implements

setSize()

setLocation

setLayout

setBounds

add()

GridLayout()

setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE)

setVisible()

FlowLayout()

BorderLayout.NORTH

addActionListener()

ActionListener

actionPerformed()

ActionEvent

getSource()

parseDouble()

getText()

setText()

requestFocus()

selectAll()

DateFormat

SimpleDateFormat

Date

DateFormat.parse()

SimpleDateFormat.format()

ParseException

printStackTrace()

Calendar

getInstance()

Calendar.getTime()

Calendar.setTime()

Calendar里的add()和set()

Runnable

Thread里的start()

Thread里的run()

InterruptedException

toString()

finally

IOException

File

FileReader

BufferedReader

FileWriter

BufferedWriter

BufferedWriter的write()和newLine()和close()

Calendar里的add()

ImageIcon

setIcon()

ImageIcon的getIconWidth()和getIconHeight()

addMouseListener()

MouseListener

MouseEvent

mouseClicked()

mousePressed()

mouseReleased()

mouseEntered()

Random

nextInt()

isVisible()

setVisible()

KeyEvent里的getKeyCode()

mouseExited()

addKeyListener()

KeyListener

keyTyped()

KeyEvent

KeyPressed()

JDialog里的setModal()

JButton里的setPreferredSize()

Dimension

BorderLayout()

JLabel里的setForeground()

ButtonGroup

bCheckBox里的setSelected()

JOptionPane里的showConfirmDialog(), showInputDialog(), showMessageDialog()

JPasswordField里的getPassword()

JTextArea里的append(), setLineWrap()

JProgressBar里的setMaximum(), setValue(), setStringPainted()

JPanel里的setBackground()

JSplitPane里的setDividerLocation(), JSplitPane.HORIZONTAL_SPLIT

JFrame里的setContentPane()

JTabbedPane里的setTitleAt(), setIconAt()

JMenuBar

JMenu以及JMenu里的addSeparator()

JMenuItem

JFrame里的setJMenuBar()

JToolBar

JTable里的getColumnModel()

JScrollPane

File里的getAbsolutePath(), exists(), isDirectory(), isFile(), length(), lastModified(), setLastModified, renameTo(),  list(), listFiles(), getParent(), getParentFile(), mkdir(), mkdirs(), createNewFile(), getParentFile().mkdirs(), listRoots(), delete()

FileInputStream里的read(), close()

FileOutputStream里的write(), close()

FileReader里的read()

FileWriter里的write()

InputStreamReader

String里的toCharArray(), length

BufferedReader里的readLine(),

PrintWriter里的flush()

DataInputStream里的readBoolean(), readInt(), readUTF()

DataOutputStream里的writeBoolean(), writeInt(), writeUTF()

ObjectOutputStream里的writeObject()

ObjectInputStream里的readObject()

System.in

Scanner里的nextLine(), nextInt()

ArrayList里的add(), size(), contains(), get(), indexOf(), remove(), set(), toArray(), addAll(), clear()

LinkedList里的addFirst(), addLast(), getFirst(), getLast(), removeFirst(), removeLast()

Queue里的offer(), poll(), peek()

HashMap里的put(), get(), clear(), size()

HashSet里的add(), size()

Collections里的reverse(), shuffle(), sort(), swap(), rotate(), synchronizedList(), 

Class里的forName()

DriveManager里的getConnection()

Connection里的createStatement(), close()

Statement里的executeQuery(), close()

ResultSet里的getMetaData(), close()

ResultSetMetaData里的getColumnCount(), getColumnName()

SQLException

ClassNotFoundException

ServerSocket里的accept(), close()

Socket里的getInputStream(), getOutputStream(), close()

DatagramSocket里的receive()

DatagramSocket里的send()



## 一般概念

- 字面量
- 下划线（underscores）
- Unicode
- ASCII
- 作用域
- 操作符
- lambda
- static
- 注释（comments）
- break
- continue
- switch
- Method overloading（方法重载）
- decoupling



# 计算机组成与原理

## 进制数

decimal（十进制）

hexadecimal（十六进制）

octal（八进制）

### 第一章

主机

CPU

运算器：

ALU

外围设备

数据

指令

透明

位

字

字节

字长

地址

存储器

总线

硬件

软件

兼容

软件兼容

程序

寄存器

容量

主存

辅存

操作系统

汇编程序

汇编语言

编译程序

解释程序

系统软件

应用软件

指令流

数据流

计数器

系统软件

软件与硬件的区别和关系

### 第二章

原码

补码

反码

移码

阶码

尾数

基数

机器零

上溢

下溢

规格化数

Booth算法

海明距离

冯.诺依曼舍入法

检错码

纠错码

海明码

循环码

## 第三章

RAM

ROM

SRAM

DRAM

EDODRAM

PROM

EPROM

EEPROM

SDRAM

快闪存储器

相联存储器

多体交叉存储器

访存局部性

直接映像

全相联映像

组相联映像

全写法

写回法

按写分配

不按写分配

虚拟存储器

层次化存储体系

访问时间

访问周期时间

带宽

段式管理

页式管理

段页式管理

块表

页表

段表

固件

地址译码的方式：单译码方式和双译码方式

## 第四章

指令系统

计算机指令

指令编码

指令格式

立即数

指令字长度

助记符

汇编语言

伪指令

小端法

堆栈

操作数寻址方式

系统指令

特权指令

中断指令

寻址方式

相对转移

绝对转移

无条件转移

条件转移

## 第五章

指令周期

机器周期

指令仿真

指令模拟

硬连线逻辑

微程序

微指令

微操作

微地址

水平型微指令

控制存储器

## 第六章

猝发传输方式

四边沿协议（全互锁）

码元

波特率

比特率

UART

主设备

从设备

总线事务

总线协议

链式查询方式

计数器定时查询方式

独立请求方式

系统总线

数据帧

串行传输

并行传输

复合传输

消息传输方式

# 操作系统

Four conditions of deadlock

Avoiding deadlock

Atomicity and volatility

# 数据结构

二叉树排序：插入数据，

# SQL

select ... from ...

distinct

# 数学建模算法总结

#### 蒙特卡洛算法

#### 数据拟合、参数估计、插值等数据处理

#### 规划类问题算法

线性规划

整数规划

多元规划

二次规划

#### 图论问题

Dijkstra

Floyd

Prime

Bellman-Ford

最大流

二分匹配

#### 计算机算法设计 中的问题

动态规划

回溯搜索

分治

分支定界法（求解整数解）

#### 最优化理论的三大经典算法

模拟退火算法

神经网络

遗传算法

#### 网格搜索和穷举算法

#### 连续问题离散化的方法

差分代替微分

求和代替积分

#### 数值分析方法

函数的数值逼近

数值微分与数值积分

非线性返程的数值解法

数值代数

常微分方程数值解

#### 图像处理算法

# 电影

《美国往事》

《肖申克的救赎》

《放风筝的人》

《美丽心灵》

《怦然心动》

《傲慢与偏见》

# 高情商

