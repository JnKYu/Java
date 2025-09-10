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

---

### 5.注释与代码风格
- **单行注释**：//
- **多行注释**：/*...*/
- **缩进、良好的命名习惯提高可读性**
- **Java使用大驼峰民名法（类名大写开头，每个单词首字母大写）**

---

### 6. 更多输出方法

* `System.out.print()`：输出但不换行
* `System.out.println()`：输出并换行
* 转义字符：`\n` 换行，`\t` 制表，`\"` 输出双引号，`\\` 输出反斜杠

---

### 7. 调试与错误类型

* **编译错误**：语法错误（漏分号、拼写错误） → 编译器报错
* **运行时错误**：程序运行时出错（如除零异常） → JVM 中断
* **逻辑错误**：代码能运行但结果不对 → 最难发现

---

# 🔑 高效学习建议

* 这一章的核心：理解 **Java 程序执行流程** + 能写出 **Hello World** 程序
* 必须掌握：

  * Java 编译运行过程（javac → java）
  * class、main 方法、System.out.println
  * 注释与命名规范
  * 转义字符的使用
* 次重点（可以浅看）：Java 历史、计算机组成、低级/高级语言对比

---

要不要我帮你把这个大纲整理成一个 **思维导图（图形化总结版）**，让你一眼就能看到章节逻辑和重点？

