# Insertion Sort
## **1-Insertion sort of [22,27,16,2,18,6]**
### Initial state :[22] [27,16,2,18,6]
---
### Step 1
### pre-processing
[22,27] [16,2,18,6]
### post-processing
**[22,27]** [16,2,18,6]
---
### Step 2
### pre-processing
[22,27,16] [2,18,6]
### post-processing
**[16,22,27]** [2,18,6]
---
### Step 3
### pre-processing
[16,22,27,2] [18,6]
### post-processing
**[2,16,22,27]** [18,6]
---
### Step 4
### pre-processing
[2,16,22,27,18] [6]
### post-processing
**[2,16,18,22,27]** [6]
---
### Step 5
### pre-processing
[2,16,18,22,27,6] []
### post-processing
**[2,6,16,18,22,27]** []

## **2-Big O notation**
O(n²)

## **3-Time Complexity**
Best Case(the number is in the beginning of the array): O(n)
Average Case(the number is in the middle of the array): O(n²)
Worst Case(the number is in the end of the array): O(n²)

## **4-Which case does number 18 fit after the array is sorted?**
The answer is average case. Because number 18 is in the middle of the array.

## **Insertion sort of [7,3,5,8,2,9,4,15,6](just first 4 step)**
### Initial state :[7] [3,5,8,2,9,4,15,6]
---
### Step 1
### pre-processing
[7,3] [5,8,2,9,4,15,6]
### post-processing
**[3,7]** [5,8,2,9,4,15,6]
---
### Step 2
### pre-processing
[3,7,5] [8,2,9,4,15,6]
### post-processing
**[3,5,7]** [8,2,9,4,15,6]
---
### Step 3
### pre-processing
[3,5,7,8] [2,9,4,15,6]
### post-processing
**[3,5,7,8]** [2,9,4,15,6]
---
### Step 4
### pre-processing
[3,5,7,8,2] [9,4,15,6]
### post-processing
**[2,3,5,7,8]** [9,4,15,6]