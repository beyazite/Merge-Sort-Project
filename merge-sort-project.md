## [Patika](www.patika.dev) merge sort projesidir.

## [Patika](www.patika.dev) merge sort project.

---

# Merge Sort

## 1. [16,21,11,8,12,22] merge sort the given array. 

> ### Divide

| | | | | | [16,21,11,8,12,22] | | | | | |
|---|---|---|---|---|---|---|---|---|---|---|
| | | |  | [16,21,11] |  | [8,12,22] | | | | |
| | | | [16,21] | [11] | | [8,12] | [22] | | | | 
| | | [16] | [21] | [11] | | [8] | [12] | [22] | | |

> ### Merge

| | | [16] | [21] | [11] | | [8] | [12] | [22] | | |
|---|---|---|---|---|---|---|---|---|---|---|
| | | | [16,21] | [11] | | [8,12] | [22] | | | | 
| | | |  | [11,16,21] |  | [8,12,22] | | | | |
| | | | | | [8,11,12,16,21,22] | | | | | |


## 2. Show Big O notation.

Big O notation and time complexity for the merge sort is O(n log(n)) for worst, best and avarage cases since it is a recursive algorithm. In this scenario O(6 log(6)) . 

---

#### Resources
[Geeks for Geeks - Merge Sort](https://www.geeksforgeeks.org/merge-sort/)

[Patika-Merge Sort](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort)





