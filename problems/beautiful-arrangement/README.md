<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

## 526. Beautiful Arrangement (Medium)

<p>
Suppose you have <b>N</b> integers from 1 to N. We define a beautiful arrangement as an array that is constructed by these <b>N</b> numbers successfully if one of the following is true for the i<sub>th</sub> position (1 <= i <= N) in this array:
<ol>
<li>The number at the i<sub>th</sub> position is divisible by <b>i</b>.</li>
<li><b>i</b> is divisible by the number at the i<sub>th</sub> position.</li>
</ol>
</p>

<p>
Now given N, how many beautiful arrangements can you construct?
</p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> 2
<b>Output:</b> 2
<b>Explanation:</b> 
<br/>The first beautiful arrangement is [1, 2]:
<br/>Number at the 1st position (i=1) is 1, and 1 is divisible by i (i=1).
<br/>Number at the 2nd position (i=2) is 2, and 2 is divisible by i (i=2).
<br/>The second beautiful arrangement is [2, 1]:
<br/>Number at the 1st position (i=1) is 2, and 2 is divisible by i (i=1).
<br/>Number at the 2nd position (i=2) is 1, and i (i=2) is divisible by 1.
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li><b>N</b> is a positive integer and will not exceed 15.</li>
</ol>
</p>

### Related Topics
  [[Backtracking](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### Similar Questions
  1. [Beautiful Arrangement II](https://github.com/openset/leetcode/tree/master/problems/beautiful-arrangement-ii) (Medium)
