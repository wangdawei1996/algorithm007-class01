学习笔记

- 二叉树  想要存储一棵二叉树，我们有两种方法，一种是基于指针或者引用的二叉链式存储法，一种是基于数组的顺序存储法。
    -- 前序遍历是指，对于树中的任意节点来说，先打印这个节点，然后再打印它的左子树，最后打印它的右子树。
    -- 中序遍历是指，对于树中的任意节点来说，先打印它的左子树，然后再打印它本身，最后打印它的右子树。
    -- 后序遍历是指，对于树中的任意节点来说，先打印它的左子树，然后再打印它的右子树，最后打印这个节点本身。
- 树的遍历通常都是递归 时间复杂度 因为是 n倍关系所以是  O(n)

- 分治算法
  分而治之 ，也就是将原问题划分成 n 个规模较小，并且结构与原问题相似的子问题，递归地解决这些子问题，然后再合并其结果，就得到原问题的解。
  分治算法是一种处理问题的思想，递归是一种编程技巧。


  分解：将原问题分解成一系列子问题；
  解决：递归地求解各个子问题，若子问题足够小，则直接求解；
  合并：将子问题的结果合并成原问题。
- 回溯算法 
  有规律地枚举所有可能的解，避免遗漏和重复。   一般用递归实现。