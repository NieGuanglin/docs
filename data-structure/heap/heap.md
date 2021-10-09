[TOC]

# 堆

## 定义

1. 堆是一个完全二叉树。

2. 堆中每个节点的值，都大于等于（或小于等于）其左右子节点。

   

## 性质

使用数组实现堆时，下标为i的节点：

- 从下标0开始存储数据

  左子节点下标：2\*i+1，右子节点下标：2\*i+2。

  父节点下标：(i-1)/2。

  建堆时，从n/2 - 1到0，进行自上向下堆化。

- 从下标1开始存储数据

  左子节点下标：2\*i，右子节点下标：2\*i+1。

  父节点下标：i/2。

  建堆时，从n/2到0，进行自上向下堆化。



## 堆化

1. 建堆时，自上向下堆化。
2. 新增元素时，向队尾添加元素，自下向上堆化。
3. 删除元素时，弹出堆顶元素，队尾元素放在堆顶，自上向下堆化。
4. 保持堆中元素个数不变

### 时间复杂度

### 空间复杂度



## 使用场景