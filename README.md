# 代码随想录刷题日记（按照专题刷）
## 第六章 字符串
#### 6.2 反转字符串
--0321打卡：解题Issue #8
#### 6.3 反转字符串II
--0321打卡：解题Issue #9
#### 6.4 反转字符串里的单词
--0321打卡：解题Issue #10
## 第十一章 动态规划
### （一）方法论总结
  ##### 1、遍历顺序
  ###### 先物品还是先容量？
  先物品的情况：无序组合问题、01背包问题
  先容量的情况：有序排列问题、完全背包问题
  ###### 前向后还是后向前？
  前向后的情况：依赖于前一项or前几项做出决策的问题
  后向前的情况：滚动数组，覆盖式更新
  ##### 2、初始值
  ###### dp[0]为0还是1？
  dp[0]为0的情况：通常是最小凑数问题，需要逐个累加
  dp[0]为1的情况：通常是组合问题，需要各个情况考虑到
  ###### 其他值为0/INT_MAX/INT_MIN？
  0的情况：通常是递推方程为非最大最小的相加/相减，即无最优情况
  INT_MAX/INT_MIN：通常是递推方程含有最优求解
### （二）刷题笔记
#### 11.8 不同的二叉搜索树
--0320打卡：解题Issue #1
#### 1.9 0-1背包理论基础
#### 1.10 分割等和子集
--0320打卡：解题Issue #2
#### 1.11 目标和
--0320打卡：解题Issue #3
#### 11.12 一和零
#### 11.13 完全背包理论基础
#### 11.14 零钱兑换I
--0321打卡：解题Issue #5
#### 11.15 拼凑出一个正整数
--0321打卡：解题Issue #6
#### 11.16 多步爬楼梯
#### 11.17 零钱兑换II
--0321打卡：解题Issue #4
#### 1.18 完全平方数
--0321打卡：解题Issue #7
#### 1.19 单词拆分
#### 1.20 买卖股票的最佳时机
--0322打卡：解题Issue #11
#### 1.21 买卖股票的最佳时机II
--0322打卡：解题Issue #12
#### 1.22 买卖股票的最佳时机III
--0322打卡：解题Issue #13
#### 1.23 买卖股票的最佳时机IV
#### 1.24 最佳买卖股票时机（含冷冻期）
