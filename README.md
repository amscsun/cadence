## Summer 2019

Keep track of the leetcode problems solved throughout the summer. The priority is on the Facebook tagged ones.

### Algorithm and Data Structures

  * String and Array Algorithms (07/01/2019 ).

    __P287 Find the Duplicate Number:__
      Pretty basic, warming up the syntax and use both brute force, set and sorting solution.

    __P280 Wiggle Sort:__ Doing careful and patient analysis.


    __P695 Max Area of an Island:__ Review basics on BFS, as well as arrays.

    __P48 Rotate Image:__ Figure out change of indexes for symmetric operations.

  * Arrays Continued: Stocks (07/02/2019)

    __P665 Non-decreasing Array:__ I would not classify it as _easy_.

    __P88 Merge Sorted Array:__ Rather strange problem.

    __P189 Rotate Array:__ Could not find the approach with $O(1)$ space complexity.

    __P11 Container with Water:__ Checked discussion. Consider two pointer approach. An excellent article on this problem can be found [here](https://leetcode.com/articles/container-with-most-water/).

  * Arrays Continued (07/03/2019).
    ```diff
    - Date Night!
    ```

  * Arrays Continued (07/04/2019).

    __P792 Number of Matching Subsequences:__ Still encountering time limit errors after optimization.

    __P162 Find Peak Element:__ Rather strange problem.

    __P80 Remove Duplicates from Array:__ Another rather strange one.

    __P73 Set Matrix Zeros:__ Routine.

    __P238 Product of Array Except Itself:__ Place VS Time complexity.

  * Arrays Continued: Sub arrays. (07/08/2019)

    __P52 Maximum Subarray:__ Definitely not an easy problem. Involving DP.

    __P152 Maximum Product Subarray:__ Similar to P52.

    __P643 Maximum Avarge Subarray:__



  * Arrays Continued (07/05/2019)


    __P121 Best Time to Buy and Sell a Stock:__ Practice two pointers for stock type of problems.

    __P122 Best Time to Buy and Sell a Stock II:__
    ```python
    def profit(prices: List[int])->int:
      profit = 0
      for i in range(len(prices)-1):
        profit = profit + max( 0, prices[i+1]-prices[i] )
        return profit
    ```
    This solution is not exactly intuitive.
