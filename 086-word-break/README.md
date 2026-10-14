# 086. Word Break

## 题目描述

判断字符串 s 能否切分为若干字典单词。字典中的单词可以重复使用，切分片段按顺序连接必须恰好为 s。

## 输入描述

第一行输入 s，第二行输入字典词数 n，随后 n 行各输入一个单词。

## 输出描述

可切分输出 true，否则输出 false。

## 示例 1

输入：

```text
leetcode
2
leet
code
```

输出：

```text
true
```

## 示例 2

输入：

```text
catsandog
5
cats
dog
sand
and
cat
```

输出：

```text
false
```

## 数据范围

1 <= |s| <= 300；1 <= n <= 1000；1 <= 单词长度 <= 20；所有字符为小写英文字母；字典单词互异。
