# unit49.2BigO

**Step one:  simplify expressions:**
1.  O(n+10) = O(n)
2.     O(100*n) = O(n)
3.  O(25) = O(1)
4.    O(n^2 + n^3) = O(n^3)
5.  O(n + n + n + n) = O(4n), which reduces to O(n) since the constant factor (4) is insignificant in terms of growth rate
6.    O(1000 * log(n) + n) = O(n)
7.  O(1000 * n * log(n) + n) = O(n * log(n))     
8.     O(2^n + n^2) cannot be simplified since it represents an exponential term, (2^n) and a quadratic term, (n^2), both of which are in a final complexity
9.   O(5 + 3 + 1) = O(1)
10.     O(n + n^(1/2) + n^2 + n * log(n)^10) = O(n^2) 

**Step Two: Calculating Time Complexity**

1.  O(n)
2.    O(max(n, 10))
3.  O(min(n, 10))
4.     O(n)
5.  O(n^2)
6.    O(m)

**Step Two: short answer**
1.  True
2.    True
3.  False
4.   O(n) 
5.  O(n)
6.   O(n)
7.  O(n log n) 
8.   O(n) 
9.  O(1)
10.  O(n) or O(1), it's dependent on the number of elemetns being added or removed as well as the location of the element(s) in the array 
11.    O(1)  
12.  O(n)
13.   O(n)  

