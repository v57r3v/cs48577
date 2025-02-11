java c
AP/ITEC 2620 3.0 
INTRODUCTION TO DATA STRUCTURES 
Assignment 
Question 1 (15 marks)    Short Answer (maximum 20 words): 
Answer all five parts below.
Part A (3 marks):    What is the average-case time   complexity   for binary   search on   a   minimum-   level BST with n   elements?    Explain.
Part B (3 marks):    The first time you run algorithm   A   on   a   dataset   of n   elements; it   is   faster than   algorithm B.    The second time   you run algorithm A on   a   dataset   of n   elements; it   is   slower than         algorithm B.    Explain how this is possible.    Give an example   for   algorithm A   and   algorithm   B.
Part C (3 marks):    If   both have   n   nodes   and   are   sorted   smallest to   largest,   will   it be   faster to   find   the smallest value in a sorted linked list   or   a   minimum-level   BST?      Explain.
Part D   (3 marks):    What   is the time   complexity   to   delete   the   root   of a minimum-level   BST   with   n   nodes?    Explain.
Part E (3 marks):    An implementation of   quicksort has its worst   case   of   O(n2)   for   an   array   in inverse sorted 代 写AP/ITEC 2620 3.0 INTRODUCTION TO DATA STRUCTURESR
代做程序编程语言order.    How long will this implementation of   quicksort take   on   an   array   already   in   sorted order?
Question 2 (10 marks)    Complexity Analysis/Estimation: 
What   is   the   complexity   of the   given   code   as   a   function   of the   problem   size   n?      Show   all   of the   details   of   your   analysis.
for   (int   i =   0;   i   < 2*n; i++)
{
if   (i   ==   n)   {
for   (int   j =   0;   j   < i; j++)
for   (int   k =   0;   k   < i; k++)
O(1)
}
else   {
for   (int   j =   0;   j   < i; j++)
O(1)
}
}
Question 3 (10 marks)    Recursion: 
Write   a recursive function that   will   calculate   the   height   of   a   binary   tree.

Note: root1 and root2 are instances   of   the   class   BinNode:
public class   BinNode   {
public char   value;
public BinNode   left;
public BinNode   right;
}
Thus, the following statements would lead to the underlined output:
Example   1:
System.out.println( treeHeight (root1) );
3 
Example 2:
System.out.println( treeHeight (root2) );
1 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
