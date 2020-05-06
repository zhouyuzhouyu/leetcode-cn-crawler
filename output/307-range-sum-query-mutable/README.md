# [区域和检索 - 数组可修改][title]

## Description

给定一个整数数组   _nums_ ，求出数组从索引  _i  _到  _j   _( _i_  ≤  _j_ ) 范围内元素的总和，包含  _i,   j
_两点。

_update(i, val)_ 函数可以通过将下标为  _i  _的数值更新为  _val_ ，从而对数列进行修改。

**示例:**
            Given nums = [1, 3, 5]        sumRange(0, 2) -> 9    update(1, 2)    sumRange(0, 2) -> 8    

**说明:**

  1. 数组仅可以在  _update  _函数下进行修改。
  2. 你可以假设 _update_ 函数与 _sumRange_ 函数的调用次数是均匀分布的。


**Tags:** Binary Indexed Tree, Segment Tree

**Difficulty:** Medium

## 思路

[title]: https://leetcode-cn.com/problems/range-sum-query-mutable
