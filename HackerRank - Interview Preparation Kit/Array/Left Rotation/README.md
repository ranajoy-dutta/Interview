
## Array: Left Rotation
A left rotation operation on an array shifts each of the array's elements 1 unit to the left. For example, if 2 left rotations are performed on array [1, 2, 3, 4, 5], then the array would become [3, 4, 5, 1, 2]. Note that the lowest index item moves to the highest index in a rotation. This is called a circular array.

Given an array <i>a</i> of <i>n</i> integers and a number, <i>d</i>, perform <i>d</i> left rotations on the array. Return the updated array to be printed as a single line of space-separated integers.<br/><br/>

<b>Function Description</b><br/>
Complete the function rotLeft in the editor below.<br/>
rotLeft has the following parameter(s):<br/>
- int a[n]: the array to rotate<br/>
- int d: the number of rotations<br/><br/>

<b>Returns</b><br/>
- int a'[n]: the rotated array
<b>Input Format</b><br/>
The first line contains two space-separated integers <i>n</i> and <i>d</i>, the size of <i>a</i> and the number of left rotations.
The second line contains <i>n</i> space-separated integers, each an <i>n[i]</i>.<br/><br/>

<b>Constraints</b><br/>
- 1 <=<i> n </i><= 10<sup>5</sup>
- 1 <=<i> d </i><= <i> n </i>
- 1 <=<i> a[i] </i><= 10<sup>6</sup><br/><br/>

<b>Sample Input</b><br/>
```
5 4
1 2 3 4 5
```
<br/>

<b>Sample Output</b><br/>
```
1 2 3 4 5
```
<br/>
