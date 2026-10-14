# 054. Implement Trie (Prefix Tree)

## 题目描述

实现 Trie，支持插入单词、判断完整单词是否已插入，以及判断是否有已插入单词以给定字符串为前缀。重复插入不改变查询结果。

## 输入描述

第一行输入 q。接下来 q 行为 insert word、search word 或 startsWith prefix；参数仅含小写英文字母。

## 输出描述

每次 search 和 startsWith 各输出一行 true 或 false；insert 不输出。

## 示例 1

输入：

```text
6
insert apple
search apple
search app
startsWith app
insert app
search app
```

输出：

```text
true
false
true
true
```

## 示例 2

输入：

```text
2
search a
startsWith a
```

输出：

```text
false
false
```

## 数据范围

1 <= q <= 30000；1 <= 参数长度 <= 2000。
