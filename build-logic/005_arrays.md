# Arrays

## beginner - intermediate

1. Find sum of an array and display the output . Example [10,4,5,2,5,6,9].
2. Find average of an array and display the output.
3. Find maximum and minimum of an array.
4. Find Median and Mode of an array.
    - Median : (N+1/2)th term.
    - Mode : Most repeating term
5. Find sum of two arrays.
    - [3,5,2,9,4] = 3+5+2+9+4 = 23
    - [6,2,8,1,3] = 6+2+8+1+3 = 20
    - Final Output : 20+23 = 43
6. Find number of constants and vowels in a string.
7. Shift an array by X to right.
    - Example [1,2,3,4,5] after shifting to right [5,1,2,3,4]
8. Given an array of numbers, pick any two numbers `a`  and `b`, we could get the difference by `Math.abs(a - b)`  . Write a function to get the largest difference in the array.

9. Given an array and size k, break the array into chunks of k-length and return them as an array.
    ```javascript
    Input: arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10], k = 3
    Output: [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10]]
    ```
10. Given an array `nums` with length `n` , return the element which occurred at least `n/2` times in the array.
    ```javascript
    Input: nums = [2,2,1,1,1,2,2]
    Output: 2
    ```
11. Given a string `s`, find the first non-repeating character in it and return its index If it does not exist, return `-1`
    ```javascript
    Input: s = "neogcamp"
    Output: 0

    Input: s = "nneeooggccaammpp"
    Output: -1
    ``` 

## Advanced

1. Find the sum of two matrix.
2. Display transpose of matrix. Explaination https://www.varsitytutors.com/linear_algebra-help/the-transpose
3. Find Identity matrix. Explanation https://www.varsitytutors.com/hotmath/hotmath_help/topics/identity-matrix

4. Given an array `arr` with different counts of number we have to find the number with most frequency and return it. 
If there are two or more numbers with same most frequency the return the biggest number.
1. Given an array of integers `nums`  and an integer `target`, check if there are two numbers in the array such that they add up to target . Return any one pair that add up to `target`
    ```javascript
    Input: nums = [3,7,11,15], target = 18
    Output: [3,15]
    Explanation : nus[0] + nums[3] = 18
    ```
1. Given an array `arr` with different counts of number we have to find the number with least frequency and return it.   
If there are two or more numbers with same least frequency the return the biggest number.
    ```javascript
    Input: arr = [2, 2, 2, 3, 3, 3, 4, 4, 4, 2, 5, 5, 5, 6, 6]
    Output: 6
    ```
1. Given an integer array `nums`, move all `0's` to the end of it while maintaining the relative order of the non-zero elements.
   ```javascript
    Input: nums = [0,2,0,3,12,0]
    Output: [2,3,12,0,0,0]
   ```
