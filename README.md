# linear_search
It is the simplest searching algorithm. In Linear search, we simply traverse the list completely and match each element of the list with the item whose location is to be found. If the match is found, then the location of the item is returned; otherwise, the algorithm returns NULL.Linear search is also called as sequential search algorithm. The steps used in the implementation of Linear Search are listed as follows -

First, we have to traverse the array elements using a for loop.

In each iteration of for loop, compare the search element with the current array element, and -

If the element matches, then return the index of the corresponding array element.

If the element does not match, then move to the next element.

If there is no match or the search element is not present in the given array, return -1.
# Algorithm
Linear_Search(a, n, val) // 'a' is the given array, 'n' is the size of given array, 'val' is the value to search

Step 1: set pos = -1

Step 2: set i = 1

Step 3: repeat step 4 while i <= n

Step 4: if a[i] == val

set pos = i

print pos

go to step 6

[end of if]

set ii = i + 1

[end of loop]

Step 5: if pos = -1

print "value is not present in the array "

[end of if]

Step 6: exit

# output
![image](https://user-images.githubusercontent.com/93450820/234483936-1d0cba61-76fd-47c9-9534-407000979d33.png)
