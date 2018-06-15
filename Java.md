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

# 面试总结

[](https://blog.csdn.net/diyinqian/article/details/72935272)

# 计算机网络

## Circuit Switching and Packet Switching

广域网 WAN (Wide Area Network)

局域网 LAN (Local Area Network)

城域网 MAN (Metropolitan Area Network)

Switched Network

Nodes

Station

Switching

Public Circuit Switched Network

Circuit Establishment

blocking network

non-blocking network

Space Division Switch

3 Stage Space Division Switch

Time Division Switching

Softswitch

Traditional Circuit Switching

Packet Switching

Core of Internet

Switching Techniques

Datagram Diagram

Virtual Circuit Diagram

Packet Size

propagation delay

transmission time

node delay

X.25

Frame Relay

ATM

## Data and Computer Communications

Routing in Packet Switched Network

Performance Criteria

Decision Time and Place

Network Information Source and Update Timing

Routing Strategies - Fixed Routing

Fixed Routing Tables

Routing Strategies - Flooding

Properties of Flooding

Routing Strategies - Random Routing

Routing Strategies - Adaptive Routing

Classification of Adaptive Routing Startegies

**Chapter 1**
End system P28 端系统
Modem P29 调制解调器（俗称：猫）
Base station P29 基站
Communication link P30 通信链路
Physical media P30 物理介质
Coaxial cable P30 同轴电缆
Fiber optics P30 光纤
Radio spectrum P30 射频频谱
Transmission rate P30 传输速率
Packets P30 （数据）包，或分组
Routers P30 路由器
Link-layer switches P30 链路层交换机/ˈleɪə US -ər/
Path P30 路径
ISP (Internet Service Provider) P30 网络服务提供商
TCP (Transmission Control Protocol) P31 传输控制协议
IP ( Internet Protocol) P31 网际协议
Intranets P31 内网
API (Application Programming Interface) P32 应用程序编程接口
Network edge P35 网络边缘
Access Networks P38 接入网
Ethernet P42 以太网
Network core P48 网络核心
Circuit Switching P50 电路转换
Packet Switching 分组交换
FDM (frequency-division multiplexing) P50 频分多路复用
TDM (time-division multiplexing) P50 时分多路复用
Statistical Multiplexing 统计复用
Store-and-forward 存储转发
Queuing delays P53 排队延迟
Transmission delay P60 传输延迟，或发送延迟
 Propagation delay P60 传播延迟
Throughput P59 吞吐量
Internet backbone P57 骨干网
Delay P59 延迟，或时延
Loss P59 丢包
Packet-Switched Network P59 分组交换网络
Nodal processing delay P60 节点处理延迟
End-to-end delay P66 端到端延迟
Instantaneous throughput P68 瞬时吞吐量
Network interface card P74 网络接口卡（即网卡）
Message P75 消息，或报文
Segment P75 （报文）段
Datagram P75 数据报
Frames P75 帧
Packet sniffer P82 数据包监听器
Protocol Stack 协议栈
Peer entities 对等实体

**Chapter 2 应用层**
Server farm P110 服务器集群
Infrastructure P110 基础设施，或基础架构
Self-scalability P111 自扩展性
Timing P114 实时性
Bandwidth-sensitive applications P115带宽敏感应用
Connection-oriented service P117 面向连接的服务
Directory service P121 目录服务
Base HTML file P122 基本HTML文件
Stateless protocol P124 无状态协议
RTT (round-trip time ) P126 往返时间
Web proxy caches P128 网页代理缓存
Status line P130 状态行
Out-of-band P141 （频）带外（的）
In-band P141 带内（的）
User agents P144 用户代理
Mail servers P144 邮件服务器
Pull protocol P148 拉式协议
Push protocol p148 推式协议
Host aliasing P158 主机别名
Canonical hostname P158 规范主机名
Mail server aliasing P158 邮件服务器别名
Load distribution P158 负载分配
Top-level domain (TLD) servers P161 顶级域名服务器
Authoritative DNS servers P161 权威域名服务器
Iterative queries P168 迭代查询
Resource records (RRs) P165 资源记录
Overlay network P179 覆盖网
Nonpersistent HTTP 非持久HTTP，或非坚持HTTP
Persistent HTTP 持久性HTTP，或坚持的HTTP
Peer-to-Peer (P2P) Network 对等网络
Socket programming 套接字编程

**Chapter 3 传输层**
Multiplexing and demultiplexing P226 复用与分用
Unidirectional data transfer P241 单向数据传送
Finite-state machine (FSM) P242 有限状态机
Positive acknowledgments P243 肯定确认
Negative acknowledgments P243 否定确认
Countdown timer P250 （倒数）计时器
Cumulative acknowledgment P258 累积确认
Receive buffer P269 接收缓冲区，或接收缓存
Resource-management cells 资源管理单元
Source (port number) 源端口号
Destination (port number) 目的端口号
Checksum 校验和
Pipelined protocols 流水线（型）协议
Go-back-N 回退N
Selective Repeat 选择重传
Timeout （定时器）超时
Fast Retransmit 快速重传
Flow Control 流量控制
Three way handshake 三次握手
sequence number 序列号（简写为seq）
acknowledgement number 确认号（简写为ack；注意与大小的ACK不同）
Congestion Control 拥塞控制
additive increase, multiplicative decrease 加性增乘性减
Slow Start 慢启动
congestion-avoidance 拥塞避免
fast recovery 快速恢复
duplicate (ACK) 冗余（ACK）
Random Early Detection 随机早期检测

**Chapter 4 网络层**
Forwarding table P338 转发表
Virtual-circuit networks P343 虚电路网络
Datagram networks P343 数据报网络
Signaling message P346 信令报文
Content Addressable Memory P354 内容可寻址存储器
Crossbar switch P356 纵横开关
Active queue management 主动队列管理
Head-of-the-line (HOL) 队头
Classless interdomain routing (CIDR) P371 无类域间路由
Plug-and-play P376 即插即用
Anycast P386 任播
Interior gateway protocols P414 内部网关协议
Routing information Protocol P414 路由信息协议（RIP）
Open shortest Path First OSPF P414 开放最短路径优先
Area border routers P419 区域边界路由器
Sequence-number-controlled flooding P430 序列号控制的洪泛，或带序列号的受控洪泛
Reverse path forwarding (RPF) P431 逆向路径转发
Rendezvous point P433 汇聚点
Longest prefix matching 最长前缀匹配
Scheduling 调度
Fragmentation 分片，或分段
Fragment Offset 报文段偏移量
Network Address Translation (NAT) 网络地址转换
NAT traversal NAT穿越
Multicast 组播，或多播
Unicast 单播
Tunneling 隧道技术
Link-State Routing Algorithm 链路状态路由算法
Distance Vector Routing Algorithm 距离向量路由算法
Count to Infinity Problem 无穷计数问题
Hierarchical Routing 分层路由
autonomous systems 自治系统
BGP (Border Gateway Protocol) 边界网关协议
in-network duplication 网内复制
broadcast storm 广播风暴
spanning tree 生成树
redundant packets 冗余数据包

**Chapter 5 数据链路层，或链路层**
Broadcast channels P461 广播信道
Trailer fields P464 尾部字段
Link access P464 链路接入，或链路访问
Network interface card P466 网络接口卡（即网卡）
Parity checks P469 奇偶校验
Forward error correction (FEC) P471 前向纠错
Cyclic Redundancy Check 循环冗余校验
Polynomial code P472 多项式码（即CRC码）
Multiple access P475 多路接入
Random access protocols P477 随机接入协议
CSMA/CD P484 带冲突检测的载波侦听多路访问
CSMA/CA 带冲突避免的载波侦听多路访问
Token passing protocol P487 令牌传递协议
ARP P491 地址解析协议
Preamble P497 前导（字段）
Exponential backoff P502 指数回退，或指数退避
Repeater P504 中继器
Virtual-channel identifier P520 虚拟信道标识
Cell-loss priority P520 信元丢失优先权
Label-switched router P524 标签交换路由器
Framing （封装）成帧
error detection 误差检测，或检错
Channel Partitioning 信道分割式（MAC协议）
Taking turns MAC protocol 轮流式MAC协议
Collision 冲突，或碰撞
Time Slot 时隙
Slotted ALOHA 时隙ALOHA
Unslotted ALOHA 无时隙ALOHA
Nonpersistent CSMA 非坚持CSMA
1-persistent CSMA 1坚持CSMA
p-persistent CSMA p坚持CSMA
Token Ring 令牌环
(Wireless) LAN （无线）局域网
Hub 集线器
Collision domain 冲突域
Bridge 网桥

# 推理思维

### 三段论推理

大前提

小前提

结论

### 数学归纳法

1 令n=1时 结论成立
2 假设n=k时结论成立，证明n=k+1时结论也成立
3 得证

### 反证法

假设A成立，并且由此导出矛盾，因此非A为真。

# 数学建模算法总结

### 蒙特卡洛算法

### 数据拟合、参数估计、插值等数据处理

### 规划类问题算法

线性规划

整数规划

多元规划

二次规划

### 图论问题

Dijkstra

Floyd

Prime

Bellman-Ford

最大流

二分匹配

### 计算机算法设计 中的问题

**动态规划:**

最优子结构、自底向上

**回溯搜索：**

DFS、

**分治：**

分、治、合

**分支定界法（求解整数解）：**

约束函数、BFS

### 最优化理论的三大经典算法

**模拟退火算法**

问题的解空间和初始解->目标函数->新解产生->目标函数差->Metropolis接受准则

应用：背包问题的求解。

**神经网络**

数据并行处理、自学能力

BP神经网络：输入层、隐含层、输出层、神经元连接强度

**遗传算法**

编码->解码->交配->突变->倒位->个体适应度评估->复制

应用：无约束目标函数最大值、多约束线性规划问题、电子商务中转化率影响因素研究。

### 粒子群算法

粒子数、惯性因子、加速常数、最大飞翔速度

### 网格搜索和穷举算法

### 连续问题离散化的方法

差分代替微分

求和代替积分

### 数值分析方法

函数的数值逼近

数值微分与数值积分

非线性返程的数值解法

数值代数

常微分方程数值解

### 图像处理算法

# 电影

《美国往事》

《肖申克的救赎》

《放风筝的人》

《美丽心灵》

《怦然心动》

《傲慢与偏见》

《大话西游之月光宝盒》

《大话西游之仙履奇缘》

《头文字D》

# 高情商

1) 讲话做事善于【照顾他人感受】
2)【 解读对方情感和意图的能力强】
3) 【辐射正能量】，和他们在一起，你会感到舒服、轻松、快乐、热情
4) 善于【维系亲近的关系】，也能【保持独立和自我】
5) 深刻理解【“意图与结果”的巨大差异】，会关注和主动获取对方的【反馈】，加以调整
6) 【朋友圈子广】，能容纳多种类型的人
7) 善于【鼓励和夸奖他人 】

# 健身

#### 人鱼线雕刻

#### 跑步

5公里法特莱克跑

音乐跑.绿野仙踪

#### 徒手胸肌进阶训练

#### 瑜伽

##### 腰腹塑形

##### 减压放松

简易盘坐调息

猫伸展式

半骆驼式

兔式

蜥蜴式

半起眼镜蛇式

# 电子商务

转化率

搜索流量

商品页停留时间