# 070. Min Stack

## 题目描述

实现一个支持 push、pop、top 和 getMin 的栈，getMin 返回当前栈中最小元素。每种操作均须为 O(1) 时间。

## 输入描述

第一行输入 q，随后 q 行为 push x、pop、top 或 getMin。保证 pop、top、getMin 调用时栈非空。

## 输出描述

仅 top 和 getMin 各输出一行结果。

## 示例 1

输入：

```text
7
push -2
push 0
push -3
getMin
pop
top
getMin
```

输出：

```text
-3
0
-2
```

## 示例 2

输入：

```text
4
push 5
push 5
pop
getMin
```

输出：

```text
5
```

## 数据范围

1 <= q <= 30000；x 为 32 位有符号整数。
