# 035. LRU Cache

## 题目描述

实现容量为 capacity 的缓存。get key 返回对应值，不存在返回 -1；成功读取使该键成为最近使用。put key value 插入或更新并标记为最近使用；插入导致超容量时删除最久未被使用的键。两种操作的平均时间须为 O(1)。

## 输入描述

第一行输入 capacity 和操作数 q。随后 q 行，每行是 get key 或 put key value。

## 输出描述

仅对每次 get 输出一行结果，按操作顺序排列；没有 get 时不输出任何内容。

## 示例 1

输入：

```text
2 9
put 1 1
put 2 2
get 1
put 3 3
get 2
put 4 4
get 1
get 3
get 4
```

输出：

```text
1
-1
-1
3
4
```

## 示例 2

输入：

```text
1 4
put 1 2
put 1 3
get 1
get 2
```

输出：

```text
3
-1
```

## 数据范围

1 <= capacity <= 3000；1 <= q <= 200000；0 <= key <= 10000；0 <= value <= 100000。
