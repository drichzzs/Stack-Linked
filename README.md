# Stack-Linked

This code defines a Java class called MyStackLinked that implements the MyStack interface and represents a stack data structure using a linked list.

A stack is a data structure that allows you to add and remove elements in a Last-In, First-Out (LIFO) manner. This means that the last element you added to the stack will be the first one you remove.

The MyStackLinked class has four instance variables: top, which is a reference to the top node in the stack; count, which is an integer that keeps track of the number of elements in the stack; MAX, which is an integer representing the maximum number of elements that the stack can hold; and data, which is an object that stores the data associated with the node.

The MyStackLinked class has four methods:

isFull(): This method returns false because the stack has no fixed size and therefore can never be full.

isEmpty(): This method returns true if the stack is empty and false otherwise.

push(Object item): This method adds an element to the top of the stack.

pop(): This method removes and returns the element at the top of the stack.

peek(): This method returns the element at the top of the stack without removing it.

toString(): This method returns a string representation of the elements in the stack.
