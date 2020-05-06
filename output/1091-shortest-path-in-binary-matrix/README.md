# [二进制矩阵中的最短路径][title]

## Description

在一个 N × N 的方形网格中，每个单元格有两种状态：空（0）或者阻塞（1）。

一条从左上角到右下角、长度为 `k` 的畅通路径，由满足下述条件的单元格 `C_1, C_2, ..., C_k` 组成：

  * 相邻单元格 `C_i` 和 `C_{i+1}` 在八个方向之一上连通（此时，`C_i` 和 `C_{i+1}` 不同且共享边或角）
  * `C_1` 位于 `(0, 0)`（即，值为 `grid[0][0]`）
  * `C_k` 位于 `(N-1, N-1)`（即，值为 `grid[N-1][N-1]`）
  * 如果 `C_i` 位于 `(r, c)`，则 `grid[r][c]` 为空（即，`grid[r][c] == 0`）

返回这条从左上角到右下角的最短畅通路径的长度。如果不存在这样的路径，返回 -1 。



**示例 1：**
            **输入：** [[0,1],[1,0]]    ![](https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/06/16/example1_1.png)    **输出：** 2    ![](https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/06/16/example1_2.png)    

**示例 2：**
            **输入：** [[0,0,0],[1,1,0],[1,1,0]]    ![](https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/06/16/example2_1.png)    **输出：** 4    ![](https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/06/16/example2_2.png)    



**提示：**

  1. `1 <= grid.length == grid[0].length <= 100`
  2. `grid[i][j]` 为 `0` 或 `1`


**Tags:** Breadth-first Search

**Difficulty:** Medium

## 思路

[title]: https://leetcode-cn.com/problems/shortest-path-in-binary-matrix
