
## Minimum Swaps 2
You are given an unordered array consisting of consecutive integers ([1, 2, 3, ..., n]) without any duplicates. You are allowed to swap any two elements. You need to find the minimum number of swaps required to sort the array in ascending order.

For example, given the array <i>arr = [7, 1, 3, 2, 4, 5, 6]</i> we perform the following steps:<br/>

	i   arr                         swap (indices)
	0   [7, 1, 3, 2, 4, 5, 6]   swap (0,3)
	1   [2, 1, 3, 7, 4, 5, 6]   swap (0,1)
	2   [1, 2, 3, 7, 4, 5, 6]   swap (3,4)
	3   [1, 2, 3, 4, 7, 5, 6]   swap (4,5)
	4   [1, 2, 3, 4, 5, 7, 6]   swap (5,6)
	5   [1, 2, 3, 4, 5, 6, 7]
It took <i>5</i> swaps to sort the array.<br/><br/>

<b>Function Description</b>

Complete the function minimumSwaps in the editor below. It must return an integer representing the minimum number of swaps to sort the array.
minimumSwaps has the following parameter(s):
- arr: an unordered array of integers<br/><br/>

<b>Input Format</b>

The first line contains an integer, <i>n</i>, the size of <i>arr</i>.<br/>The second line contains <i>n</i> space-separated integers <i>arr[i]</i> .<br/><br/>

<b>Constraints</b><br/>
- 1 <=<i> n </i><= 10<sup>5</sup>
- 1 <=<i> arr[i] </i><= <i> n </i>

<b>Output Format</b><br/>
Return the minimum number of swaps to sort the given array.

<b>Sample Input</b><br/>
```
4
4 3 1 2
```

<b>Sample Output</b><br/>
```
0
```
<br/>
