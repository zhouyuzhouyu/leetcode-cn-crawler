# [单词接龙 II][title]

## Description

给定两个单词（ _beginWord_ 和 _endWord_ ）和一个字典 _wordList_ ，找出所有从 _beginWord_ 到
_endWord_ 的最短转换序列。转换需遵循如下规则：

  1. 每次转换只能改变一个字母。
  2. 转换过程中的中间单词必须是字典中的单词。

**说明:**

  * 如果不存在这样的转换序列，返回一个空列表。
  * 所有单词具有相同的长度。
  * 所有单词只由小写字母组成。
  * 字典中不存在重复的单词。
  * 你可以假设 _beginWord_ 和 _endWord_ 是非空的，且二者不相同。

**示例 1:**
            **输入:**    beginWord = "hit",    endWord = "cog",    wordList = ["hot","dot","dog","lot","log","cog"]        **输出:**    [      ["hit","hot","dot","dog","cog"],      ["hit","hot","lot","log","cog"]    ]    

**示例 2:**
            **输入:**    beginWord = "hit"    endWord = "cog"    wordList = ["hot","dot","dog","lot","log"]        **输出:** []        **解释:**   _endWord_ "cog" 不在字典中，所以不存在符合要求的转换序列。


**Tags:** Breadth-first Search, Array, String, Backtracking

**Difficulty:** Hard

## 思路

[title]: https://leetcode-cn.com/problems/word-ladder-ii
