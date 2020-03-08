# LeetCodeNotes
我的 LeetCode 笔记

# 一、打卡记录

## 1.1 普通题

|    日期    |                    题目编号                    |
| :--------: | :--------------------------------------------: |
| 2019-12-24 |           206   141   21   19   876            |
| 2020-02-01 |                   1   2   3                    |
| 2020-02-02 |                     5   6                      |
| 2020-02-03 |                     7   8                      |
| 2020-02-04 |               9   11  12  13  14               |
| 2020-02-05 |                 15  16  17  18                 |
| 2020-02-06 |                 19  20  21 22                  |
| 2020-02-07 |                 23  24  25  26                 |
| 2020-02-09 |                   27  28  29                   |
| 2020-02-10 |                     31  33                     |
| 2020-02-11 |                 34  35  36  38                 |
| 2020-02-12 |                 39  40  41  42                 |
| 2020-02-13 |                 43  45  46  47                 |
| 2020-02-14 |                 48  49  50  51                 |
| 2020-02-15 |                 52  53  54  55                 |
| 2020-02-16 |                 56  57  58  59                 |
| 2020-02-17 |                 60  61  62  63                 |
| 2020-02-18 |                 64  65  66  67                 |
| 2020-02-19 |                 68  69  70  71                 |
| 2020-02-20 |                 72  73  74  75                 |
| 2020-02-21 |                 76  77  78  79                 |
| 2020-02-22 |                 80  81  82  83                 |
| 2020-02-23 |                 84  85  86  87                 |
| 2020-02-24 |             88  89  90  91  92  93             |
| 2020-02-25 |               94  95  96  97  4                |
| 2020-02-26 |              98  99  100  101  10              |
| 2020-02-27 |             102  103  104  105  30             |
| 2020-02-28 |           106  107  108  109  32  44           |
| 2020-02-29 |        110  111  112  113  114  37  115        |
| 2020-03-01 |  225  116  117  118  119  120  <br />121  122  |
| 2020-03-02 |       206  123  188  124  125  126  127        |
| 2020-03-03 |      面试题10.01  128  129  130  131  132      |
| 2020-03-04 |                      994                       |
| 2020-03-05 |         1103  133  134  135  136  137          |
| 2020-03-06 |      面试题57-II  138  139  141  142  140      |
| 2020-03-07 | 面试题59-II  143  144  145<br />146   147  155 |
| 2020-03-08 |            322  148  149  150  151             |

## 1.2 多线程

|    日期    | 题目编号 |
| :--------: | :------: |
| 2020-02-13 |   1114   |

## 1.3 Shell

|    日期    | 题目编号 |
| :--------: | :------: |
| 2020-02-24 |   192    |



# 二、待解决/需要重写的题目

|             类型             |                           题目编号                           |
| :--------------------------: | :----------------------------------------------------------: |
|             数组             |                5(Manacher 算法)  128(并查集)                 |
|          正则表达式          |                            10  44                            |
|          字符串匹配          |                              28                              |
|            线段树            |                              45                              |
| 贪心(需要理解为什么贪心成立) |                           45  135                            |
|           卡特兰数           |                              96                              |
|           二分查找           |                              4                               |
|           动态规划           |                      97  123  188  132                       |
|           滑动窗口           |                              30                              |
|      通过但是性能比较差      | 14  15  16  19  23  38  49  56  57  58<br />60  65  67  71  77  78  79  87  90  95  98  114  117<br />130 332 |
|             其他             |                  29  53  105  109  140  149                  |
|            多线程            |                             1114                             |
|            Shell             |                             192                              |



# 三、目前的规划

|    时间    |                           规划内容                           |
| :--------: | :----------------------------------------------------------: |
| 2020-02-01 | 1.每天按顺序刷，争取先刷150道 (Java)  2.中间插入一些专题复习 <br />因为是练习刷题的手感，所以就不用按专题来，以避免陷入思维定式，而学习某个类型专题时，刷专题可以帮助理解 |
|            |                                                              |
|            |                                                              |

#  四、一些细节

+   **`不要使用异或运算来进行值交换`**，**这是错误的做法**，既不能加快运算速度，也不能节省运行内存。
+   自己写的方法使用 `static` 修饰可以提高性能。 
+   静态变量每次使用前一定要重新初始化。