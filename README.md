# LeetCode Hot 100 — Java ACM Mode

LeetCode Hot 100 的 Java ACM 模式练习仓库，模拟牛客机考的标准输入输出环境。

每道题只有 `README.md`（题面与样例）和 `Main.java`（空白入口）。独立编译每道题，使用 JDK 8 或更高版本。

## 使用方式

在本仓库目录打开终端，进入任意题目：

```powershell
cd 001-two-sum
javac -encoding UTF-8 Main.java
java Main
```

自行实现输入解析和解题代码，再粘贴题面中的一组输入。按已知长度读取即可；若代码一直读到文件结束，Windows 终端用 Ctrl+Z 后回车结束输入，Linux/macOS 用 Ctrl+D。

PowerShell 也可直接传入样例（先完成代码并编译）：

```powershell
"4", "2 7 11 15", "9" | java Main
```

Bash：

```bash
printf '4\n2 7 11 15\n9\n' | java Main
```

一次运行对应一组输入，只输出题目要求的结果，不输出输入提示。每题从空白入口开始，自行实现全部解析、节点与逻辑，不提供题解或算法提示。请逐题编译，不要将所有同名 Main 类一起编译。

## Problems

题单及顺序于 2026-10-05 对照[力扣官方热题 100](https://leetcode.cn/studyplan/top-100-liked/)核对，中文题面为独立改写的 ACM 版本。

- [001. Two Sum](./001-two-sum/)
- [002. Group Anagrams](./002-group-anagrams/)
- [003. Longest Consecutive Sequence](./003-longest-consecutive-sequence/)
- [004. Move Zeroes](./004-move-zeroes/)
- [005. Container With Most Water](./005-container-with-most-water/)
- [006. 3Sum](./006-3sum/)
- [007. Trapping Rain Water](./007-trapping-rain-water/)
- [008. Longest Substring Without Repeating Characters](./008-longest-substring-without-repeating-characters/)
- [009. Find All Anagrams in a String](./009-find-all-anagrams-in-a-string/)
- [010. Subarray Sum Equals K](./010-subarray-sum-equals-k/)
- [011. Sliding Window Maximum](./011-sliding-window-maximum/)
- [012. Minimum Window Substring](./012-minimum-window-substring/)
- [013. Maximum Subarray](./013-maximum-subarray/)
- [014. Merge Intervals](./014-merge-intervals/)
- [015. Rotate Array](./015-rotate-array/)
- [016. Product of Array Except Self](./016-product-of-array-except-self/)
- [017. First Missing Positive](./017-first-missing-positive/)
- [018. Set Matrix Zeroes](./018-set-matrix-zeroes/)
- [019. Spiral Matrix](./019-spiral-matrix/)
- [020. Rotate Image](./020-rotate-image/)
- [021. Search a 2D Matrix II](./021-search-a-2d-matrix-ii/)
- [022. Intersection of Two Linked Lists](./022-intersection-of-two-linked-lists/)
- [023. Reverse Linked List](./023-reverse-linked-list/)
- [024. Palindrome Linked List](./024-palindrome-linked-list/)
- [025. Linked List Cycle](./025-linked-list-cycle/)
- [026. Linked List Cycle II](./026-linked-list-cycle-ii/)
- [027. Merge Two Sorted Lists](./027-merge-two-sorted-lists/)
- [028. Add Two Numbers](./028-add-two-numbers/)
- [029. Remove Nth Node From End of List](./029-remove-nth-node-from-end-of-list/)
- [030. Swap Nodes in Pairs](./030-swap-nodes-in-pairs/)
- [031. Reverse Nodes in k-Group](./031-reverse-nodes-in-k-group/)
- [032. Copy List with Random Pointer](./032-copy-list-with-random-pointer/)
- [033. Sort List](./033-sort-list/)
- [034. Merge k Sorted Lists](./034-merge-k-sorted-lists/)
- [035. LRU Cache](./035-lru-cache/)
- [036. Binary Tree Inorder Traversal](./036-binary-tree-inorder-traversal/)
- [037. Maximum Depth of Binary Tree](./037-maximum-depth-of-binary-tree/)
- [038. Invert Binary Tree](./038-invert-binary-tree/)
- [039. Symmetric Tree](./039-symmetric-tree/)
- [040. Diameter of Binary Tree](./040-diameter-of-binary-tree/)
- [041. Binary Tree Level Order Traversal](./041-binary-tree-level-order-traversal/)
- [042. Convert Sorted Array to Binary Search Tree](./042-convert-sorted-array-to-binary-search-tree/)
- [043. Validate Binary Search Tree](./043-validate-binary-search-tree/)
- [044. Kth Smallest Element in a BST](./044-kth-smallest-element-in-a-bst/)
- [045. Binary Tree Right Side View](./045-binary-tree-right-side-view/)
- [046. Flatten Binary Tree to Linked List](./046-flatten-binary-tree-to-linked-list/)
- [047. Construct Binary Tree from Preorder and Inorder Traversal](./047-construct-binary-tree-from-preorder-and-inorder-traversal/)
- [048. Path Sum III](./048-path-sum-iii/)
- [049. Lowest Common Ancestor of a Binary Tree](./049-lowest-common-ancestor-of-a-binary-tree/)
- [050. Binary Tree Maximum Path Sum](./050-binary-tree-maximum-path-sum/)
- [051. Number of Islands](./051-number-of-islands/)
- [052. Rotting Oranges](./052-rotting-oranges/)
- [053. Course Schedule](./053-course-schedule/)
- [054. Implement Trie (Prefix Tree)](./054-implement-trie-prefix-tree/)
- [055. Permutations](./055-permutations/)
- [056. Subsets](./056-subsets/)
- [057. Letter Combinations of a Phone Number](./057-letter-combinations-of-a-phone-number/)
- [058. Combination Sum](./058-combination-sum/)
- [059. Generate Parentheses](./059-generate-parentheses/)
- [060. Word Search](./060-word-search/)
- [061. Palindrome Partitioning](./061-palindrome-partitioning/)
- [062. N-Queens](./062-n-queens/)
- [063. Search Insert Position](./063-search-insert-position/)
- [064. Search a 2D Matrix](./064-search-a-2d-matrix/)
- [065. Find First and Last Position of Element in Sorted Array](./065-find-first-and-last-position-of-element-in-sorted-array/)
- [066. Search in Rotated Sorted Array](./066-search-in-rotated-sorted-array/)
- [067. Find Minimum in Rotated Sorted Array](./067-find-minimum-in-rotated-sorted-array/)
- [068. Median of Two Sorted Arrays](./068-median-of-two-sorted-arrays/)
- [069. Valid Parentheses](./069-valid-parentheses/)
- [070. Min Stack](./070-min-stack/)
- [071. Decode String](./071-decode-string/)
- [072. Daily Temperatures](./072-daily-temperatures/)
- [073. Largest Rectangle in Histogram](./073-largest-rectangle-in-histogram/)
- [074. Kth Largest Element in an Array](./074-kth-largest-element-in-an-array/)
- [075. Top K Frequent Elements](./075-top-k-frequent-elements/)
- [076. Find Median from Data Stream](./076-find-median-from-data-stream/)
- [077. Best Time to Buy and Sell Stock](./077-best-time-to-buy-and-sell-stock/)
- [078. Jump Game](./078-jump-game/)
- [079. Jump Game II](./079-jump-game-ii/)
- [080. Partition Labels](./080-partition-labels/)
- [081. Climbing Stairs](./081-climbing-stairs/)
- [082. Pascal's Triangle](./082-pascals-triangle/)
- [083. House Robber](./083-house-robber/)
- [084. Perfect Squares](./084-perfect-squares/)
- [085. Coin Change](./085-coin-change/)
- [086. Word Break](./086-word-break/)
- [087. Longest Increasing Subsequence](./087-longest-increasing-subsequence/)
- [088. Maximum Product Subarray](./088-maximum-product-subarray/)
- [089. Partition Equal Subset Sum](./089-partition-equal-subset-sum/)
- [090. Longest Valid Parentheses](./090-longest-valid-parentheses/)
- [091. Unique Paths](./091-unique-paths/)
- [092. Minimum Path Sum](./092-minimum-path-sum/)
- [093. Longest Palindromic Substring](./093-longest-palindromic-substring/)
- [094. Longest Common Subsequence](./094-longest-common-subsequence/)
- [095. Edit Distance](./095-edit-distance/)
- [096. Single Number](./096-single-number/)
- [097. Majority Element](./097-majority-element/)
- [098. Sort Colors](./098-sort-colors/)
- [099. Next Permutation](./099-next-permutation/)
- [100. Find the Duplicate Number](./100-find-the-duplicate-number/)

## Extras

Hot 100 之外的补充练习：手写经典排序算法。

- [101. Merge Sort](./101-merge-sort/)
- [102. Quick Sort](./102-quick-sort/)
- [103. Heap Sort](./103-heap-sort/)
