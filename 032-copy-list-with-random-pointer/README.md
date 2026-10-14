# 032. Copy List with Random Pointer

## 题目描述

链表节点具有 val、next 和 random；random 可指向任意节点或空。创建完全独立的深拷贝，使值和指针关系与原链表一致。拷贝中的任何指针都不能指回原节点；必须实际构造新节点，不能仅回显输入。

## 输入描述

第一行输入 n。接下来 n 行按 next 顺序各输入 val randomIndex；randomIndex 为从 0 开始的节点下标，-1 表示空。next 指向下一行节点，最后一个 next 为空。请自行构造原链表。

## 输出描述

第一行输出拷贝的节点数，随后按拷贝的 next 顺序每行输出 val randomIndex，下标重新按拷贝顺序编号。空链表只输出 0。

## 示例 1

输入：

```text
3
7 -1
13 0
11 1
```

输出：

```text
3
7 -1
13 0
11 1
```

## 示例 2

输入：

```text
0
```

输出：

```text
0
```

## 数据范围

0 <= n <= 1000；-10000 <= val <= 10000；randomIndex = -1 或 0 <= randomIndex < n。
