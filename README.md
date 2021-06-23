# hack-interview-handbook
背诵模板，背诵模型， 不是背诵解法

coding:主体框架与细节分开
代码outstanding: 预判

### 练习反向思维，正着不行反着来,几个例子：
- 岛屿的最大面积 --> 内陆湖也算在岛内呢?
- 满足不等式的最大值


#### target
easy:5mins
medium:15-20mins
hard:20-30mins

### "三刷五步"
初学建议分类刷 ->后期建议综合刷

一刷：每个小类别的代表性题目，各刷几道
此时如果需要看题解，很正常


二刷：
复习代表性题目
小类别合成大类别，刷改分类更多的题目，举一反三，在尽量少的提示下完成


三刷：
综合性题目，尽量独立实现+测试

![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-09-58.png)

### 如何做题： //从模型出发
- 第一步 理解体面
  - 想一想更多的例子和测试数据，看看有没有遗漏的地方
  - 提炼题目中的关键信息、变化信息
  - 面试的时候，跟面试官确认自己的理解
  - 
- 第二步 部分实现
- 无论什么题目，先尝试实现一个朴素解法(比如搜索)
- 或者是部分场景下的解法
- 尽量让自己的解法更优，覆盖更多的场景
- 

 - 第三步 有提示解答
  - 看提示 != 看题解
  - 可以看题解的一部分，试试能否找到突破口
  - 例如题目类别，题解标题，时间复杂度，一个小结论
  - 面试是一个交互的过程，你可以与面试官交流获取适当的提示
  - 要能明白面试官在引导你什么，这就要从平时练起
 - 

- 第四步 独立解答
- 独立完成求解，同时注意测试
- 初期训练是通常可以都从第二步的搜索出发
- 搜索时关注了哪些信息？
- 他们有没有冗余？能不能更好的维护？
- ‘有没有同类的子问题


- 第五步 写题解
- 尝试给别人讲(面试的时候也是要讲的)，尝试分析对比各种不同的解法
- 题解也可以写成日记的形式，记录自己遇到的难点
- 有助于加深自己的理解，以后也可以回看自己的题解，快速复习



### 时间复杂度的logn为什么没有底数？  log以2为底, 通过换底公式，可以除一个常数，在底数不一样的对数之间变换，复杂度里常数是忽略的，所以没有底数


![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-03-59.png)



linux 默认系统栈只有8M
堆基本上跟内存大小同级


### 数据驱动算法
- 先学线性数据结构,然后学习其上各种灵活的算法
- 了解树，图等结果，然后学习递归、搜索等算法
- 形成集合、维度、状态空间等概念，然后学习动态规划等高级算法

- 抛开数据的支持，算法是假大空
- 脑子里有了数据结构的具体形状，算法将会更加形象，容易理解

### 知识框架
## 三条主线 +两个副本

三条主线
### 线性结构线
- 数组、链表、栈、队列 --> 前缀和、差分、双指针、滑动窗  -->哈希、集合、映射 ->字符串


### 树形结构线
- 递归、分治 -> 树与图 ->搜索  ->堆、二叉搜索树  ->字典树、并查集  -> 图论算法

### 状态空间线
![alt txt](https://raw.githubusercontent.com/corykingsf/hack-interview-handboook-pixel/main/imgSnipaste_2021-06-21_23-05-11.png)


### 两个副本
- 顺序优化副本: 排序、二分
- 高级数据结构副本：平衡树、跳表、树状数组、线段树

## 为什么 vs 怎么想到
- 情景引入,分析use case --> 问题模型化(解决一套模型而不是一个题目) --> 知识点 --> 实战题目(讲思路的形成过程，代码落地,如何写得又快又对,如何让代码结构简洁易懂，如何模块化处理细节, 如何预判避免错误)

### 代码主结构简单易懂，模块化处理细节

### 训练时间
![alt txt](https://raw.githubusercontent.com/corykingsf/hack-interview-handboook-pixel/main/imgSnipaste_2021-06-21_23-13-37.png)


### 听课的方法
课前预习
- 浏览ppt, 标注自己完全不懂的地方
- 每个只是点选一道立体，看看题意，大致想想

课上听讲:
- 紧跟老师的大思考方向，不要太拘泥于细节的证明，可以之后在回放
- 承认算法和数据结果的复杂性，课上之听懂60%-70%是正常的额

课后回顾:
- 不要1.0倍整体播放，只需要回访重点，不理解的地方，或者1.5-2.0倍速回放
- 自己举例实践老师讲的算法，有时间及时提问

### 算法学习的误区
- 误区1 对待题解的两个极端
  - 看题解刷题 - 看似速度快，做的提多，实际上抛开题解大脑一片空白
  - 坚决不看题解，自己死扣- 陷入自己原有的思路里，学不到高票题解，高票代码的优秀思路
  
误区2 - Leetcoe每题只做一遍或者leetcode随机刷综合题
正确做法: 坚持分类三刷

误区3： 面对一道题，拿学过的算法挨个试解
- 正确做法： 坚持五步刷题，剖析题目关键点->回想学过的模型->根据特征找到算法，题目特征驱动算法，而不是猜测算法试解题目

知识点：
- 基本技能
- 时间、空间复杂度分析
- 面试中的程序调试与测试
- 位运算
- 线性数据结构及相关算法
- 数组、链表、栈
- 哈希表、集合、映射
- 前缀和、差分
- 双指针扫描、滑动窗口
- 树形数据结构及相关算法
- 递归、分治
- 树、二叉树、二叉搜索树
 - 堆
- 字典树
- 并查集
- 跳跃表
- 平衡二叉树
- 树状数组、线段树
- 搜索
- 深度优先搜索
- 广度优先搜索
- 动态规划
- 线性动态规划
- 树形动态规划
- 图论
- 最短路
- 最小生成树
- 字符串处理
- 模式匹配
- 字符串哈希
- 二分
- 排序
- 贪心


![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-05-45.png)

![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-06-53.png)


![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-07-24.png)


![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-07-55.png)

![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-08-32.png)


![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-22_22-08-43.png)