# 📘 Java 课程内容大纲（PPT 第 0 章：Hello World）

## 📖 课程信息
- 教师：**Yepang Liu 博士**
- 教材：
  - **主教材**：《Java: How to Program（Java大学教程，第八版）》Deitel
  - **参考书**：
    - Liang：《Introduction to Java Programming》
    - Downey：《Think Java》

---

## 📚 课程总体大纲（Syllabus）
1. Introduction to Computers and Java Applications  
2. Primitive Data Types  
3. Control Statements and Structured Programming  
4. Arrays  
5. Methods and APIs（过程化编程）  
6. Classes, Objects, Methods（面向对象入门）  
7. Strings and Wrapper Classes  
8. Classes, Objects, Methods 深入  
9. Inheritance（继承）  
10. Polymorphism（多态）  
11. GUI 编程  
12. Generics（泛型类与方法）  
13. Exception Handling  

> 💡 这一大纲和你需要学习的数据结构与算法用到的 Java 语法高度一致。

---

## 📝 第 0 章内容梳理

### 1. 基础概念
- **计算机 = 硬件 + 软件**
- **程序**：一组指令，告诉计算机执行任务
- **语言**：
  - **低级语言**：机器能懂
  - **高级语言**：人能懂

---

### 2. Java 背景
- **诞生**：1991 年 Sun 公司研发，目标 **Write Once, Run Anywhere**
- **特点**：跨平台、面向对象、应用广泛
- **三大环境**：
  - **JVM**：运行 Java 程序的虚拟机
  - **JRE = JVM + 核心类库**（运行环境）
  - **JDK = JRE + 开发工具**（编译器 javac、运行 java、打包 jar、文档 javadoc 等）

---

### 3. Java 程序的编译与执行流程
1. 编写源文件（`.java`）
2. 编译为字节码（`.class`）
3. JVM 解释并执行字节码

---

### 4. 第一个 Java 程序：Hello World

```java
 public class Welcome1 {
   public static void main(String[] args) {
       System.out.println("Welcome to Java Programming!");
   }
}
```
要点：
- **class**：每个Java程序至少有一个类
- **main方法**：程序入口
- **System.out.println**：输出语句（带换行）
- **标识符命名规则**：区分大小写，不能用数字开头，不能用关键字
