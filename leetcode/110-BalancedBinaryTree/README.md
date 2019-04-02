**110. 平衡二叉树**  
---
[https://leetcode-cn.com/problems/balanced-binary-tree/](https://leetcode-cn.com/problems/balanced-binary-tree/)  

给定一个整数数组 nums 和一个目标值 target，请你在该数组中找出和为目标值的那 两个 整数，并返回他们的数组下标。

你可以假设每种输入只会对应一个答案。但是，你不能重复利用这个数组中同样的元素。

给定一个二叉树，判断它是否是高度平衡的二叉树。

本题中，一棵高度平衡二叉树定义为：

>一个二叉树每个节点 的左右两个子树的高度差的绝对值不超过1。  

**示例 1:**  

```  
给定二叉树 [3,9,20,null,null,15,7]

    3
   / \
  9  20
    /  \
   15   7
返回 true 。
```  

**示例 2:**  

```  
给定二叉树 [1,2,2,3,3,null,null,4,4]

       1
      / \
     2   2
    / \
   3   3
  / \
 4   4
返回 false 。
```  
