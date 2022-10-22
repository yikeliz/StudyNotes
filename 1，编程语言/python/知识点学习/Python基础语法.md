# Python基础语法

[TOC]



# 一，数据类型

# 一，数字（Number）

Python里面有四种数据类型

```python
int
bool
float
complex
```



## 二，字符串（String）

1，反斜杠可以用来转义，使用 **r** 可以让反斜杠不发生转义。 如 **r"this is a line with \n"** 则 **\n** 会显示，并不是换行。

```python
>>> print(r'\n')      # 输出 \n
\n
```

2，字符串可以用 **+** 运算符连接在一起，用 ***** 运算符重复。

```python
print(str * 2)             # 输出字符串两次
```

1，str.title：大写,

2，去除字符串的空白：str.rstrip和strlstrip 左边和右边

3，强制转换：str（18），int("a")



## 三，列表（List）

```python
t = ['a', 'b', 3]  #定义

```

1，-1代表最后一个

2，增删改查

```python
list.append("  ") #最后加上

list.insert(0,"  ") #位置插入

del list[1] #删除

list.remove("     ")  #删除
```

3，排序

```python



```

## 四，元组（Tuple）

```
tuple = ('a', 'bb', 234)
```



## 五，集合（set）



## 六，字典（Dictionary）



## 七，总结

- **不可变数据（3 个）：**Number（数字）、String（字符串）、Tuple（元组）；
- **可变数据（3 个）：**List（列表）、Dictionary（字典）、Set（集合）。

# 二，语句结构

## 一，条件判断



## 二，循环

### 1)while循环



### 2)for循环

# 四，文件操作



