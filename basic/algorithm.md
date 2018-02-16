# 数据结构&算法
## 排序算法
(p4) 如何评价一个排序算法？

答：
1. 稳定性。稳定排序算法会依照相等的关键（换言之就是值）维持纪录的相对次序。也就是一个排序算法是稳定的，就是当有两个有相等关键的纪录R和S，且在原本的串行中R出现在S之前，在排序过的串行中R也将会是在S之前。
2. 计算复杂度（最差、平均、最好）

## 稳定排序
* 冒泡排序（Bubble Sort） — O(n²)
* 插入排序（Insertion Sort）— O(n²)
* 桶排序（Bucket Sort）— O(n); 需要 O(k) 额外空间
* 计数排序 (Counting Sort) — O(n+k); * 需要 O(n+k) 额外空间
* 合并排序（Merge Sort）— O(nlogn); 需要 O(n) 额外空间
* 二叉排序树排序 （Binary tree sort） — O(n log n) 期望时间; O(n²)最坏时间; 需要 O(n) 额外空间
* 基数排序（Radix sort）— O(n·k); 需要 O(n) 额外空间

## 不稳定排序
* 选择排序（Selection Sort）— O(n²)
* 希尔排序（Shell Sort）— O(nlogn)
* 堆排序（Heapsort）— O(nlogn)
* 快速排序（Quicksort）— O(nlogn) 期望时间, O(n²) 最坏情况; 对于大的、乱数串行一般相信是最快的已知排序

## 快速排序
(p3) 表述快排思想

(p3) 实现快速排序


备注：https://hit-alibaba.github.io/interview/basic/algo/Sorting.html





