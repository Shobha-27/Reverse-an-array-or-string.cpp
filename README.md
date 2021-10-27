# Reverse an array or string 

Given an array (or string), the task is to reverse the array/string.

Examples : 

 

Input  : arr[] = {1, 2, 3}

Output : arr[] = {3, 2, 1}

Input :  arr[] = {4, 5, 1, 2}

Output : arr[] = {2, 1, 5, 4} 



Iterative way :

 

1) Initialize start and end indexes as start = 0, end = n-1 

2) In a loop, swap arr[start] with arr[end] and change start and end as follows : 

start = start +1, end = end – 1


1 2 3 4 5 6 

Reversed array is 

6 5 4 3 2 1 


Time Complexity : O(n)



Recursive Way :

 

1) Initialize start and end indexes as start = 0, end = n-1 

2) Swap arr[start] with arr[end] 

3) Recursively call reverse for rest of the array.


Output : 

1 2 3 4 5 6 

Reversed array is 

6 5 4 3 2 1 


Time Complexity : O(n)
