leetcode 每日一题
- 8 字符串转换整数 (atoi)
- 42 接雨水
- 289 生命游戏(未操作表示状态) 
- 820 字典树
- 892 数组 正方体表面积
- 912 数组排序
- 914 数字分组
- 999 二维数组
- 1111 有效货号字符串
- 1162 地图分析 广度优先搜索
- 面试题62 圆圈中最后剩下的数字 约瑟夫环
### 10.4
#### jz50 第一个只出现一次的字符
哈希表
#### jz09 两个栈实现队列
（使用LinkedList实现栈），一个栈用来push，另一个栈用来pop
#### jz59-1
滑动窗口最大值 单调队列
#### jz30 包含min的栈
和上一题有相似之处，一个是非严格递减，一个是非严格递增
#### jz40 最小的k个数
（快排，最大堆）
#### jz05 替换空格
遍历 
#### jz03 数组中重复的数组
set/hashmap/原地交换顺序
#### jz17 打印从1到最大的n位数
注意大数解法
#### jz61 扑克牌中的顺子
直接用最大最小值比较最简单/逐个相减
#### jz58-2
字符串拼接 substring不能用的话用stringbuilder，还可以有个取余的骚操作
#### jz53-1
在排序数组中查找数字
#### jz57 和为s的两个数字
对撞双指针
#### jz57-2
和为s的连续正数序列  滑动窗口，r++的循环中，l在条件中++
### 10.6
#### jz55-1 二叉树的深度
dfs
#### jz55-2 判断平衡二叉树
每一层进行dfs比较慢，可以后序遍历，如果下边的就已经不满足了，剪枝。
#### jz18 删除链表的节点 
注意头节点，一般new 一个dummy放在头结点前面
#### jz06 从尾到头打印链表
递归回溯，或者利用栈
#### jz32-2 从上到下打印二叉树
层序遍历问题，还写了生成树的
#### jz27 二叉树的镜像
后序遍历反转即可
#### jz68-2 二叉树的最近公共祖先 *
要先分析两个结点的公共祖先，两个结点的分布可能分两种情况
  - 两个结点在公共祖先两侧
  - 两个结点在一侧，这样这两个节点其中一个肯定是公共祖先
  - 分别遍历左结点，和右结点情况

#### jz54 二叉搜索树的第k大的节点
中序遍历，处理结果即可

#### jz68-1 二叉搜索树的最近公共祖先

区别于68-2，这道题是二叉搜索树。 根据二叉搜索树左 中  右的顺序特点做

#### jz15 二进制中1的个数

注意无符号运算符`>>>`

#### jz65 不用加减乘除做加法

位运算实现加法器：非进位和是异或，进位和是与。一直加到没有进位位置

### 10.11

#### 14 最长公共前缀

#### 409 最长回文串

#### 125 验证回文串

#### 5535 括号的最大嵌套深度

#### 2 两数相加

#### [剑指 Offer 31. 栈的压入、弹出序列](https://leetcode-cn.com/problems/zhan-de-ya-ru-dan-chu-xu-lie-lcof/)

弄个栈就完事