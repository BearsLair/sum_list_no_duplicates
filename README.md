# sum_list_no_duplicates

# Algorithm:

1. if empty array ([]), return 0.

2. sort the list from smaller to greater

3. create new set with list

4. nested for loop to check if number in set occurs more than once (twice) in orginal list
   counter in inner loops keeps track of occurrences, resets when inner loop completes
   if counter is 1 at end of the inner loops, add the number in the list to new empty addition array

5. reduce method on addition array to find sum, then return sum
