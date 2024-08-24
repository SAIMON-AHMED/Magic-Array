# Magic-Array

Gavin has a magical array of integers that start changing every hour since its creation. These changes follow a specific rule, where after n hours since creation, all the numbers in the array become n times the numbers at the time of creation. For example, if the array's values were a0, a1, a2,... at the time of creation (i.e., at 0th hour), then after n hours, the array's values will be n*a0, n*a1, n*a2,.... Gavin wants you to develop a smart contract that can determine the value of the ith integer in the array (i.e., a[i]) after n hours.

The smart contract must contain the following public funtion:

 

findValue(int[] a, uint ind, uint hrs) returns (int): This function returns the value of a[ind] after hrs number of hours.
