# 076. Find Median from Data Stream

## 题目描述

维护一个初始为空的整数数据流，支持加入整数和查询当前全部整数的中位数。数量为偶数时取排序后中间两数的平均值。

## 输入描述

第一行输入 q，随后 q 行为 addNum x 或 findMedian。保证查询时至少已有一个整数。

## 输出描述

每次 findMedian 输出一行中位数，固定保留 1 位小数；addNum 不输出。

## 示例 1

输入：

```text
5
addNum 1
addNum 2
findMedian
addNum 3
findMedian
```

输出：

```text
1.5
2.0
```

## 示例 2

输入：

```text
2
addNum -1
findMedian
```

输出：

```text
-1.0
```

## 数据范围

1 <= q <= 50000；-100000 <= x <= 100000。
