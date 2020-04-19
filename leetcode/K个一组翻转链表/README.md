# K个一组翻转链表 解题笔记

![题目描述](./pic/题目.png)

难度：Hard

## 解题方法一：迭代法

![步骤分析](./pic/迭代法步骤.png)

* 过程图解
![过程图解](./pic/迭代法图解.jpg)

* 代码如下：
![代码图](./pic/迭代code.jpg)

* 以上过程参考：
  <https://leetcode-cn.com/problems/reverse-nodes-in-k-group/solution/tu-jie-kge-yi-zu-fan-zhuan-lian-biao-by-user7208t/>

* 复杂度计算：
  
  需要翻转的段数为  n/k , 每一段是O(k)   所以总的复杂度是 O(k) *  (n/k) 还是 O(n)

  while的复杂度O(n/k) {
    for循环复杂O(k) +  reverse复杂度O(k) = 2k
  }

## 解题方法二：递归实现

* 一个单链表反转的递归动画
![动图演示](http://emoji.qpic.cn/wx_emoji/VXNGEiaqHR4FteNp2jCgvUf2GvdxJFDX9qmicRtJx6x01koa2OKBrdhgd8b35ezEGh/)

* 代码如下：
![代码图](./pic/递归code.png)
