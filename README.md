| 题目                                | 出现次数 | 链接                                                         | 体会                                         |
| ----------------------------------- | -------- | ------------------------------------------------------------ | -------------------------------------------- |
| 206. 反转链表                       | 5        | https://leetcode-cn.com/problems/reverse-linked-list         | 链表题，熟悉双向链表单向链表，学会修改方向   |
| 53. 最大子序和                      | 4        | https://leetcode-cn.com/problems/maximum-subarray            | 数组题，动态规划                             |
| 1143. 最长公共子序列                | 3        | https://leetcode-cn.com/problems/longest-common-subsequence  | 动态规划，看不懂                             |
| 442. 数组中重复的数据               | 2        | https://leetcode-cn.com/problems/find-all-duplicates-in-an-array | easy,字典                                    |
| 300. 最长上升子序列                 | 2        | https://leetcode-cn.com/problems/longest-increasing-subsequence | 需要复习回顾                                 |
| 8. 字符串转换整数 (atoi)            | 2        | https://leetcode-cn.com/problems/string-to-integer-atoi      | 处理文本，可用re或按规则进行修改就行         |
| 215. 数组中的第K个最大元素          | 2        | https://leetcode-cn.com/problems/kth-largest-element-in-an-array | sorted（nums,reverse=True）                  |
| 121. 买卖股票的最佳时机             | 2        | https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock | 设置最小值和差值，不用记录最大值             |
| 141. 环形链表                       | 1        | https://leetcode-cn.com/problems/linked-list-cycle           | 都可以记录进来                               |
| 21. 合并两个有序链表                | 1        | https://leetcode-cn.com/problems/merge-two-sorted-lists      | 新建一个结构体和指针思路会清晰一些           |
| 494. 目标和                         | 1        | https://leetcode-cn.com/problems/target-sum                  | 跳过                                         |
| 227. 基本计算器 II                  | 1        | https://leetcode-cn.com/problems/basic-calculator-ii         | eval 栈 easy但是代码有点烦                   |
| 72. 编辑距离                        | 1        | https://leetcode-cn.com/problems/edit-distance               | 明白了状态转移方程的含义，感谢熊猫刷题       |
| 633. 平方数之和                     | 1        | https://leetcode-cn.com/problems/sum-of-square-numbers       | easy(遍历就行)                               |
| 125. 验证回文串                     | 1        | https://leetcode-cn.com/problems/valid-palindrome            | 双指针即可，easy                             |
| 152. 乘积最大子数组                 | 1        | https://leetcode-cn.com/problems/maximum-product-subarray    | 需要复习，关心正负                           |
| 15. 三数之和                        | 1        | https://leetcode-cn.com/problems/3sum                        | 时间超限，需要修改                           |
| 105. 从前序与中序遍历序列构造二叉树 | 1        | https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal | 树的题目，需要递归                           |
| 148. 排序链表                       | 1        | https://leetcode-cn.com/problems/sort-list                   | 解决方案太easy                               |
| 239. 滑动窗口最大值                 | 1        | https://leetcode-cn.com/problems/sliding-window-maximum      | 时间超时；deque()                            |
| 22. 括号生成                        | 1        | https://leetcode-cn.com/problems/generate-parentheses        | 递归/树                                      |
| 75. 颜色分类                        | 1        | https://leetcode-cn.com/problems/sort-colors                 | easy,双指针往中间走，while比较好             |
| 20. 有效的括号                      | 1        | https://leetcode-cn.com/problems/valid-parentheses           | 栈 列表的pop()                               |
| 169. 多数元素                       | 1        | https://leetcode-cn.com/problems/majority-element            | 最佳解法：中位数                             |
| 171. Excel表列序号                  | 1        | https://leetcode-cn.com/problems/excel-sheet-column-number   | ord的用法                                    |
| 5. 最长回文子串                     | 1        | https://leetcode-cn.com/problems/longest-palindromic-substring | 中间插入＃，"#".join，然后逐个为中心进行扩散 |
| 43. 字符串相乘                      | 1        | https://leetcode.cn/problems/multiply-strings/               | easy                                         |
| 63. 不同路径 II                     | 1        | https://leetcode-cn.com/problems/unique-paths-ii             | 动态规划                                     |
| 146. LRU缓存机制                    | 1        | https://leetcode-cn.com/problems/lru-cache                   | 跳过                                         |
| 补充题6. 手撕堆排序                 | 1        | https://leetcode-cn.com/problems/sort-an-array               |                                              |
| 160. 相交链表                       | 1        | https://leetcode-cn.com/problems/intersection-of-two-linked-lists |                                              |
| 补充题4. 手撕快速排序               | 1        | https://leetcode-cn.com/problems/sort-an-array               |                                              |
| 113. 路径总和 II                    | 1        | https://leetcode-cn.com/problems/path-sum-ii                 |                                              |

LLM2SQL_study&thinking

- prompt方面
  
1. prompt 结构化(包括但不止于：DDLs，Examples)
2. DDLs，将数据库结构/格式 进行描述/其他处理方案
3. DDLs，定时将数据库 将高频样例作为描述的一部分（理解：将高频数据作为 表头的说明）
4. 语法树（编译原理），对数据库的操作不仅仅是查询，还有各种数据库，选择在工程上，保证 sql 合法且合适（select  group by limit等更多限制性的东西，保证查询效果）
5. 构建prompt详细步骤与堆输出结果的限制，
6. 适当通过prompt引导查询从子查询等方案中选择优秀的方案
7. 了解主流 sql（多种 sql 都能解决同一问题）考虑优化，让模型输出简单的 sql（子查询、联表查询相互替换；与查询序列联系起来）

- model方面

1. 模型本身（目前除了熟悉ChatGLM系列，LLamma系列和Alpaca系列），了解底层逻辑（需要了解主流模型即可 Qianwen 和 llamma 一样）
2. 微调经验很重要, 微调（数据配比，喂哪些数据类型，喂多少的经验）
3. 构造数据的经验，与 gpt4 进行博弈了解构建
4. 学习主流课程/提出自己的见解

- 课程安排1 微调：https://www.youtube.com/watch?v=C7cX74SGiNY&list
- 课程安排2 transformer：李沐transformer
- 课程安排3 针对iclass数据库进行设计与实现，记录困难问题
