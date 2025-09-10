
# Java 基础 - 数据类型与计算

## 1. 数据类型 (Data Types)

* 程序由 **数据** 和对数据的 **操作** 组成

* 数据类型的作用：

  * 定义数据的含义
  * 指定可进行的操作
  * 规定在内存中的存储方式（二进制表示）

* Java 数据类型分类：

  * **基本数据类型 (primitive types)**
  * **引用数据类型 (reference types / non-primitive types)**

---

## 2. Java 基本数据类型 (Primitive Data Types)

* **整数类型 (Integral types)**: `byte`, `short`, `int`, `long`
* **浮点数类型 (Floating-point types)**: `float`, `double`
* **布尔类型 (Boolean type)**: `boolean` (`true` / `false`)
* **字符类型 (Char type)**: `char` (Unicode 字符)

### 整数类型 (Integers)

| 类型    | 位数 | 范围                  |
| ----- | -- | ------------------- |
| byte  | 8  | -128 \~ 127         |
| short | 16 | -32,768 \~ 32,767   |
| int   | 32 | -2.147e9 \~ 2.147e9 |
| long  | 64 | -9.22e18 \~ 9.22e18 |

示例:

```java
int age = 20;
```

### 浮点数类型 (Floating-point numbers)

| 类型     | 位数 | 范围                             |
| ------ | -- | ------------------------------ |
| float  | 32 | -3.4E38 \~ 3.4E38 (约7位小数精度)    |
| double | 64 | -1.7E308 \~ 1.7E308 (约16位小数精度) |

示例:

```java
double pi = 3.1415926;
float f = 234.5f;
```

> 注意：浮点数存在精度问题，若需高精度可使用 `BigDecimal`。

### 布尔类型 (boolean)

* 只有两个值：`true` / `false`
* 常用于条件判断

```java
boolean isChecked = true;
```

### 字符类型 (char)

* 16位 Unicode 字符，范围 `\u0000` \~ `\uffff`
* 示例：

```java
char c1 = 'a';
char c2 = '\u5357'; // 南
```

---

## 3. 算术运算 (Arithmetic Computation)

* 算术运算符：

  * `+` 加法（也可用于字符串拼接）
  * `-` 减法
  * `*` 乘法
  * `/` 除法（整数除法会截断小数部分）
  * `%` 取余（模运算）

示例：

```java
int x = 3, y = 2;
int z = x / y; // z = 1
int c = 10 % 3; // c = 1
```

---

## 4. 运算优先级与结合性 (Precedence & Associativity)

* `*`, `/`, `%` 优先级高于 `+`, `-`
* 同级运算符：按 **从左到右** 顺序计算
* 括号 `()` 拥有最高优先级，可改变默认运算顺序

  * 例：(1 + 2) \* 3

---

## 5. 条件表达式 (Conditional Expressions)

* **相等运算符 (Equality operators)**: `==`, `!=`
* **关系运算符 (Relational operators)**: `>`, `<`, `>=`, `<=`
* 结果为 `true` 或 `false`

---

## 6. 输入与输出

### 使用 `Scanner` 输入

```java
import java.util.Scanner;

Scanner input = new Scanner(System.in);
int number = input.nextInt();
```

### 使用 `printf` 格式化输出

```java
System.out.printf("%d\n", -123);
System.out.printf("Total: $%.2f\n", 1234.5678);
System.out.printf("%s World", "Hello");
```

* `%d` → 整数
* `%f` → 浮点数
* `%s` → 字符串

支持表格对齐输出：

```java
System.out.printf("%-10s%-10s%-10s\n", "radius", "perimeter", "area");
```

---

## 7. 关键术语 (Glossary)

* 注释 (Comment)
* 语法错误 (Syntax error)
* 字符串 (String)
* 格式字符串 (Format string)
* 基本数据类型 (Primitive types)
* 算术操作符 (Arithmetic operator)
* 优先级 (Precedence) / 结合性 (Associativity)
* 相等运算符 (Equality operator) / 关系运算符 (Relational operator)
