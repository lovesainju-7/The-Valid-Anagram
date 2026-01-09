# The-Valid-Anagram
First, the 1st string (s) and the 2nd string (t) are compared.
If their lengths are different, the function returns false because strings of different lengths cannot be anagrams.

If the lengths are the same, both strings are sorted.
After sorting, if both strings become equal and same, it means they contain the same characters, 
so the function returns true; otherwise

# Time Complexity
The main operation is sorting both strings.
Sorting a string of length n takes O(n log n) time.

So, the overall time complexity is:
O(n log n)

# Space Complexity
The sorting is done on the same strings without using extra data structures.
Therefore, the space complexity is:
O(1) (constant extra space)
