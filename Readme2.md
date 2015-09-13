## Data Structure and Algorithms Problems

<center>

| Current Status|     Stats     |
| :------------: | :----------: |
| Total Problems | 40 |
| Current Streak | 28 |
| Longest Streak | 28 ( August 17, 2015 - September 13, 2015 ) |

</center>

### LinkedList Problems 
| Problem | Solution |
| :------------ | :----------: |
| Find the nth node of linked list from last. | [nthToLastNode.cpp] (linked_list_problems/nthToLastNode.cpp) |
| Add numbers where each digit of the number is represented by node of a linkedlist.  Give output as a linked list. | [add_two_numbers_lists.cpp] (linked_list_problems/add_two_numbers_lists.cpp) |
| Swap nodes of a linkedlist without swapping data. | [swapNodesWithoutSwappingData.cpp] (linked_list_problems/swapNodesWithoutSwappingData.cpp) |
| Given a linked list, reverse alternate nodes and append at the end. | [reverseAlternateNodes.cpp](linked_list_problems/reverseAlternateNodes.cpp) |
| Only given a node pointer, delete the node from the linked list. | [deleteNode.cpp](linked_list_problems/deleteNode.cpp) |
| Delete the entire linkedlist. | [deleteLinkedlist.cpp](linked_list/deleteLinkedlist.cpp) |
| Print middle node of linkedlist without iterating twice. | [printMiddleNode.cpp](linked_list_problems/printMiddleNode.cpp) | | Detecting and removing a cycle in linkedlist.| [floyedCycleDetection.cpp](linked_list_problems/floyedCycleDetection.cpp)|
| Determine if a linked list is a pallindrome. | [listPallindrome.cpp](linked_list_problems/listPallindrome.cpp) |
| Insert data in a sorted linked list.|[insertInASortedLinkedList.cpp](linked_list_problems/insertInASortedLinkedList.cpp) |


### Include 
Include contains single header implementation of data structures and some algorithms.

| DS/ALG |     Implementation   |
| :------------: | :----------: |
| Generic Macros and Algorithms like swap, random number generation | [generic.h](include/generic.h) |
| Stack Implementation | [stack.h](include/stack.h) |
| Queue Implementation | [queue.h](include/queue.h) |
| List Implementation  | [list.h] (include/list.h) |
| Binary Search Tree Implementation | [binarySearchTree.h] (include/binarySearchTree.h)
| Quick Sort Implementation | [quickSort.h] (include/quickSort.h) |
| Merge Sort Implementation | [mergeSort.h] (include/bubbleSort.h)|
| Selection Sort Implementation | [selectionSort.h] (include/selectionSort.h) |
| Bubble Sort Implementation | [bubbleSort.h] (include/bubbleSort.h) |

###Bit Manipulation Problems
| Problem | Solution |
| :------------ | :----------: |
| Determine if a number is a power of 2. | [power_of_2.cpp](bit_manipulation/power_of_2.cpp) |
| Add two binary number represented as string. | [addBin.cpp](bit_manipulation/addBin.cpp) |
| Determine the next power of 2 for a given number. | [next_power_of_2.cpp](bit_manipulation/next_power_of_2.cpp) |
| Using bit manipulation determine if a number is multiple of 3. | [multiple_of_3.cpp](bit_manipulation/multiple_of_3.cpp) |
| Determine endianess of the machine, print a number in reverse Endianess. | [reverseEndianness.cpp](bit_manipulation/reverseEndianness.cpp) |
| Find the parity of given number. | [find_parity.cpp](bit_manipulation/find_parity.cpp) |
| Implement fast multiplication of a number to 7 using bit manipulation. | [multiply_by_7.cpp](bit_manipulation/multiply_by_7.cpp) |
| Reverse bits of unsigned integer (two methods - Reversing bit by bit & divide and conquer). | [reverseBitsOfAnInteger.cpp](bit_manipulation/reverseBitsOfAnInteger.cpp) |

### Cracking the coding interview problems
| Problem | Solution |
| :------------ | :----------: |
| Problem 1 : Edition 6: Write an algorithm to determine whether a string has unique characters or not. Can we do it without using addtional data structures? | [1-1-hasUniqueChars.cpp](cracking_the_coding_interview_problems/1-1-hasUniqueChars.cpp)|
| Problem 2 : Edition 5: Reverse a string when you are a pass a null terminated C string.|[1-2-edi5-reverseString.cpp ](cracking_the_coding_interview_problems/1-2-edi5-reverseString.cpp)|
| Problem 2 : Edition 6: Given two strings, determine if one is permutation of other.|[1-2-perm-strings.cpp](cracking_the_coding_interview_problems/1-2-perm-strings.cpp)|
| Problem 3 : Edition 5: Write an algorithm to remove duplicate chars from a string.|[1-3-edi5-removeDuplicates.cpp](cracking_the_coding_interview_problems/1-3-edi5-removeDuplicates.cpp)|
| Problem 3 : Edition 6: URLify: Replace all the spaces in a string with '%20'. Preferebly Inplace |[1-3-URLify.cpp](cracking_the_coding_interview_problems/1-3-URLify.cpp)|
| Problem 4 : Edition 6: Given a string, write a function to check if it is a permutation of a pallindrome.|[1-4-pallindrome-permutations.cpp ](cracking_the_coding_interview_problems/1-4-pallindrome-permutations.cpp)|
| Problem 5 : Edition 6: There are three possible edits that can be performed on a string - Insert a char, Delete a char, Replace a char. Given two strings, determine if they are one or 0 edit away.|[1-5-one-edit-away.cpp ](cracking_the_coding_interview_problems/1-5-one-edit-away.cpp)|


### Tree Problems
| Problem | Solution |
| :------------ | :----------: |
|Iterative Level order traversal of Tree using queue |[levelOrderTraversalIterative.cpp](tree_problems/levelOrderTraversalIterative.cpp)|
|Recursive Level order traveral of Tree | [levelOrderTraversalRecursive.cpp](tree_problems/levelOrderTraversalRecursive.cpp)|
|ZigZag Traversal of Tree | [zigZagTraversal.cpp](tree_problems/zigZagTraversal.cpp)|
|Predecessor and Successor of a given node in Binary Search Tree | [predecessorSuccessor.cpp](tree_problems/predecessorSuccessor.cpp)|


### String Problems
| Problem | Solution |
| :------------ | :----------: |
| Implementation of Robin-Karp algorithm for string search | [robinKarpStringMatching.cpp](string_problmes/robinKarpStringMatching.cpp) |

### Math Problems
| Problem | Solution |
| :------------ | :----------: |
|  Print all the permutations of a string. Example: Permutations of ABC are ABC, ACB, BCA, BAC, CAB, CBA | [string_permutations.cpp] (math_problems/string_permutations.cpp) |

### Stack Problems
| Problem | Solution |
| :------------ | :----------: |
|  We have series of n daily price quotes for a stock. We need to calculate span of stock's price for all n days. Span for ith day is defined as maximum number of consecutive days, for which the price of the stock was less than or equal to ith day. For stock quotes {100, 60, 70, 65, 80, 85} span will be {1, 1, 2, 1, 4, 5}. Span for day 1 is always 1, now for day 2 stock is at 60, and there is no day befor it when stock was less than 60. So span remains 1. For day 3, the stock is priced at 70, so its span is 2, as previous day it was 60, and so on. | [stock_span_problem.cpp](stack_problems/stock_span_problem.cpp) |
