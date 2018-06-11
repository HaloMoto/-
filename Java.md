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

addMouseListener()

MouseListener

MouseEvent

mouseClicked()

mousePressed()

mouseReleased()

mouseEntered()

Random

nextInt()

mouseExited()

addKeyListener()

KeyListener

keyTyped()

KeyEvent

KeyPressed()



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



#计算机组成与原理

## 进制数

decimal（十进制）

hexadecimal（十六进制）

octal（八进制）

# 操作系统

Four conditions of deadlock

Avoiding deadlock

Atomicity and volatility