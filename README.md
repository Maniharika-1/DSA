## DSA
DSA Practice questions and solutions

### 1. Majority Element - LeetCode
Problem Statement:  
Given an array nums of size n, return the majority element.  
The majority element is the element that appears more than ⌊n / 2⌋ times. You may assume that the majority element always exists in the array.

Example 1:  
Input: nums = [3,2,3]  
Output: 3  

Example 2:  
Input: nums = [2,2,1,1,1,2,2]  
Output: 2  

Constraints:  
* n == nums.length  
* 1 <= n <= 5 * 104  
* -231 <= nums[i] <= 231 - 1  

Follow-up: Could you solve the problem in linear time and in O(1) space?  

Find the solution [here](https://github.com/Maniharika-1/DSA/blob/main/Majority%20Element%20-%20LeetCode.txt).  

### 2. Merge Sorted Array - LeetCode  
Problem Statement:  
You are given two integer arrays nums1 and nums2, sorted in non-decreasing order, and two integers m and n, representing the number of elements in nums1 and nums2 respectively.  
Merge nums1 and nums2 into a single array sorted in non-decreasing order.  
The final sorted array should not be returned by the function, but instead be stored inside the array nums1. To accommodate this, nums1 has a length of m + n, where the first m elements denote the elements that should be merged, and the last n elements are set to 0 and should be ignored. nums2 has a length of n.  

Example 1:  
Input: nums1 = [1,2,3,0,0,0], m = 3, nums2 = [2,5,6], n = 3  
Output: [1,2,2,3,5,6]  
Explanation: The arrays we are merging are [1,2,3] and [2,5,6].  
The result of the merge is [1,2,2,3,5,6] with the underlined elements coming from nums1.  

Example 2:  
Input: nums1 = [1], m = 1, nums2 = [], n = 0  
Output: [1]  
Explanation: The arrays we are merging are [1] and [].  
The result of the merge is [1].  

Example 3:  
Input: nums1 = [0], m = 0, nums2 = [1], n = 1  
Output: [1]  
Explanation: The arrays we are merging are [] and [1].  
The result of the merge is [1].  
Note that because m = 0, there are no elements in nums1. The 0 is only there to ensure the merge result can fit in nums1.   

Constraints:  
* nums1.length == m + n  
* nums2.length == n  
* 0 <= m, n <= 200  
* 1 <= m + n <= 200  
* -109 <= nums1[i], nums2[j] <= 109   

Follow up: Can you come up with an algorithm that runs in O(m + n) time?  

Find the solution [here](https://github.com/Maniharika-1/DSA/blob/main/Merge%20Sorted%20Array%20-%20LeetCode.txt).  

### 3. Two Sum II - Input Array is Sorted - LeetCode
Problem Statement:
Given an array of integers numbers that is already sorted in non-decreasing order, find two numbers such that they add up to a specific target number.  
Return the indices of the two numbers (1-indexed) as an integer array answer of size 2, where 1 <= answer[0] < answer[1] <= numbers.length.  
The tests are generated such that there is exactly one solution. You may not use the same element twice.  

Example 1:  
Input: numbers = [2,7,11,15], target = 9  
Output: [1,2]  
Explanation: The sum of 2 and 7 is 9. Therefore index1 = 1, index2 = 2.  

Example 2:  
Input: numbers = [2,3,4], target = 6  
Output: [1,3]  

Example 3:  
Input: numbers = [-1,0], target = -1  
Output: [1,2]   

Constraints:  
* 2 <= numbers.length <= 3 * 104  
* -1000 <= numbers[i] <= 1000  
* numbers is sorted in non-decreasing order.  
* -1000 <= target <= 1000  
* The tests are generated such that there is exactly one solution.  

Find the solution [here](https://github.com/Maniharika-1/DSA/blob/main/Two%20Sum%20II%20-%20Input%20Array%20is%20Sorted%20-%20LeetCode.txt).  




