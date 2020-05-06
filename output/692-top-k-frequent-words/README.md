# [前K个高频单词][title]

## Description

给一非空的单词列表，返回前  _k  _个出现次数最多的单词。

返回的答案应该按单词出现频率由高到低排序。如果不同的单词有相同出现频率，按字母顺序排序。

**示例 1：**
            **输入:** ["i", "love", "leetcode", "i", "love", "coding"], k = 2    **输出:** ["i", "love"]    **解析:** "i" 和 "love" 为出现次数最多的两个单词，均为2次。        注意，按字母顺序 "i" 在 "love" 之前。    



**示例 2：**
            **输入:** ["the", "day", "is", "sunny", "the", "the", "the", "sunny", "is", "is"], k = 4    **输出:** ["the", "is", "sunny", "day"]    **解析:** "the", "is", "sunny" 和 "day" 是出现次数最多的四个单词，        出现次数依次为 4, 3, 2 和 1 次。    



**注意：**

  1. 假定 _k_ 总为有效值， 1 ≤ _k_ ≤ 集合元素数。
  2. 输入的单词均由小写字母组成。



**扩展练习：**

  1. 尝试以  _O_ ( _n_ log _k_ ) 时间复杂度和  _O_ ( _n_ ) 空间复杂度解决。


**Tags:** Heap, Trie, Hash Table

**Difficulty:** Medium

## 思路

[title]: https://leetcode-cn.com/problems/top-k-frequent-words
