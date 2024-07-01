# sum_list_no_duplicates

if empty array ([]), return 0.
sort the list from smaller to greater
create new set with list
nested for loop to check if number in set occurs more than once in orginal list
counter in inner loops keeps track of occurrences, resets when inner loop completes
if counter is 1 at end of the inner loops, add the number in the list to new empty addition array
reduce method on addition array to find sum, then return sum
