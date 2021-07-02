树的高度，深度: 题目里面都会说清楚高度、深度的定义：深度和层都是从上往下数，高度是从下往上计数，深度和高度都从0开始编号，层从1开始编号

如果用pure recursion, 遍历的时候每个节点还是只遍历一次，但是在连接 左，根，右这三部分的时候，还有多余的拷贝list,要先连接再返回
如何避免这些多余的拷贝？  维护一个全局的数据结构，把遍历过的点保存在里面





递归只看一层

### Full Binary Tree 
- A Binary Tree is a full binary tree if every node has 0 or 2 children. The following are the examples of a full binary tree. We can also say a full binary tree is a binary tree in which all nodes except leaf nodes have two children. 
```
               18
           /       \  
         15         30  
        /  \        /  \
      40    50    100   40

             18
           /    \   
         15     20    
        /  \       
      40    50   
    /   \
   30   50

               18
            /     \  
          40       30  
                   /  \
                 100   40

```

### Complete Binary Tree
-  A Binary Tree is a Complete Binary Tree if all the levels are completely filled except possibly the last level and the last level has all keys as left as possible 

The following are examples of Complete Binary Trees 
```



               18
           /       \  
         15         30  
        /  \        /  \
      40    50    100   40


               18
           /       \  
         15         30  
        /  \        /  \
      40    50    100   40
     /  \   /
    8   7  9 
```

### Perfect Binary Tree
-  A Binary tree is a Perfect Binary Tree in which all the internal nodes have two children and all leaf nodes are at the same level. 
The following are the examples of Perfect Binary Trees. 
```
               18
           /       \  
         15         30  
        /  \        /  \
      40    50    100   40


               18
           /       \  
         15         30  
```


二叉树的存储：
- 基于指针的存储
- 基于数组的存储：完全二叉树，堆，线段树




![alt txt](https://raw.githubusercontent.com/corykingsf/hack-system-design-pixel/main/imgSnipaste_2021-06-23_12-42-22.png)