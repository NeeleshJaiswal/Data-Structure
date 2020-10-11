# Efficiency

-We want a quantifiable way to measure how efficient certain data structure are at different tasks we 		might ask for it
-searching through
-Modifying
-Accessing

# Measuring Efficiency with BigO Notation

the industry standard for this kind of measurement is ## BigO Notation which is kind of report card

# BigO Notation

A way to basically "score" a data structure based on 4 criteria
## Accessing elements
## Searching for an element
## Inserting an element
## Deleting an element

# Time Complexity Equations
It works by inserting the size of the data set as an integer n, and returning the number of operations that need to be conducted by the computer before the function can finish.


It's called BigO notation because the syntax for the Time Complexity equation include a BigO and then a set of parenthesis
- the parenthesis houses the function.
	
# 6 most common time complexity equation

# 1. - O(1)
the absolute best data structure can score on each criteria is O(1).
No matter what the size of your data set is , the task will be completed in a single instruction

# 2. - O(log n)
The next fastest type of complexity equation as O(log n).
 - Still provides fast completion time
 - Gets more efficient as the size of data set increases
 ex - Binary search

# 3. - O(n)
The last and decent equation to be used and above this complexity all the other complexities are inefficient
# 4. - O(n log n)
relatively bad
# 5. - O(n^2)
# 6. - O(2^n)

both 2 O(n^2) & O(2^n) must be avoided and they are exponential in structure. It become worst with the larger data set but some provide the other functionality that makes them extremely useful.
