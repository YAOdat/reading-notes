# Linked Lists

###  A linked lists is a sequential collection of elements.

## Singly Linked Lists


### Each element in the singly linked list is called Node each node has two pieces of information the data in the node itself and a reference to the next node in the link. A linked list has a head and a tail.

![Singly Linked List](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20200922124319/Singly-Linked-List1.png)


**Note that**: 
* A linked list head is a reference to the first node in the list. (the head is not a node)
* The tail is a reference that points to null. It is the last element in the linked list.


## Doubly Linked Lists

### In the doubly linked list, there are three pieces of information, the data, previous reference, next reference. Each node points to the next node and to the previous node.

![Doubly Linked List](https://www.alphacodingskills.com/imgfiles/doubly-linked-list.PNG)

## Circular linked Lists

### In the circular linked list, all nodes are connected to each other forming a circle, the first node and the last node are connected to each other, so there is no NULL at the last node.

![Doubly Linked List](https://camo.githubusercontent.com/ae6ba50b0ad6af9f2ff90d07aab3ef24b31297be6ee5fef52020d9af6e6b2c60/68747470733a2f2f7374617469632e6a61766174706f696e742e636f6d2f64732f696d616765732f63697263756c61722d73696e676c792d6c696e6b65642d6c6973742e706e67)


## Arrays vs Linked Lists

Arrays must be stored next to each other in memory, meanwhile, linked lists can be stored anywhere in the memory.

![image](https://user-images.githubusercontent.com/108061232/188967114-72e08d0b-da2c-4fa1-8a1c-492da6e32e48.png)

This type of storing has positive and negative sides. Unlike the array, you can't just access directly to the data that you want to access to, but you need to go through the linked list till you find the element that you want. However, with this, the linked list saves more memory than an array does.

