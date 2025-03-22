# Cat-2-DSA
# 188164 Shatra Maina
Question 1.
i)Ignore Constants
   O(2n) -> O(n)
   
ii)Focus on Dominant term
   O(n2 + n) -> O(n2)
   
iii)Consider input size changes - where you consider logarithimic growth if the input size reduces.

iv)Drop non dominant terms
    O(n+n2+logn) ->O(n2)

Question 2.
Array allocate memory in a contiguous block where all elements are stored next to each other and the size is fixed when creating an array while in linked lists the nodes are scattered throughtout the memory and the size is dynamic where the nodes are added or removed.

In performance arrays have a faster performance since one can directly index into the array using the element`s position while linked lists have a slower access since one has to traverse from the head node to the desired node.

In terms of insertion and deletion operations arrays are time consuming since it may require shifting elements to maintain the contigious block of memory while linked lists have an easier way of operation such operations mainly if you have the reference to the node where operations if to be performed.
