# [从叶结点开始的最小字符串][title]

## Description

给定一颗根结点为 `root` 的二叉树，树中的每一个结点都有一个从 `0` 到 `25` 的值，分别代表字母 `'a'` 到 `'z'`：值 `0` 代表
`'a'`，值 `1` 代表 `'b'`，依此类推。

找出按字典序最小的字符串，该字符串从这棵树的一个叶结点开始，到根结点结束。

_（小贴士：字符串中任何较短的前缀在字典序上都是较小的：例如，在字典序上  `"ab"` 比 `"aba"` 要小。叶结点是指没有子结点的结点。）_



**示例 1：**

**![](https://assets.leetcode-cn.com/aliyun-lc-
upload/uploads/2019/02/02/tree1.png)**
            **输入：** [0,1,2,3,4,3,4]    **输出：** "dba"    

**示例 2：**

**![](https://assets.leetcode-cn.com/aliyun-lc-
upload/uploads/2019/02/02/tree2.png)**
            **输入：** [25,1,3,1,3,0,2]    **输出：** "adz"    

**示例 3：**

**![](https://assets.leetcode-cn.com/aliyun-lc-
upload/uploads/2019/02/02/tree3.png)**
            **输入：** [2,2,1,null,1,0,null,0]    **输出：** "abc"    



**提示：**

  1. 给定树的结点数介于 `1` 和 `8500` 之间。
  2. 树中的每个结点都有一个介于 `0` 和 `25` 之间的值。


**Tags:** Tree, Depth-first Search

**Difficulty:** Medium

## 思路

[title]: https://leetcode-cn.com/problems/smallest-string-starting-from-leaf
