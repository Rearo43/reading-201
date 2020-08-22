# Implementation: Stacks and Queues
## STACKS
### Terminology
  - Push: Nodes put into the stack
  - Pop: Nodes removed from the stack 
    > When there is an empty stack an exception should be raised
  - Top: Top of stack
  - Peek: View value of the top Node in the stack
    > When there is an empty stack an exception should be raised
  - IsEmpty: Boolean
## Stack Flow
### `FILO` - `F`irst `I`n `L`ast `O`ut
### `LIFO` - `L`ast `I`n `F`irst `O`ut

Push O(1)
Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.

Pop O(1)
Popping a Node off a stack is the action of removing a Node from the top. When conducting a pop, the top Node will be re-assigned to the Node that lives below and the top Node is returned to the user.

Peek O(1)
When conducting a peek, you will only be inspecting the top Node of the stack.

IsEmpty O(1)
Here is the pseudocode for isEmpty


## QUEUES
### Terminology
Enqueue - Nodes or items that are added to the queue.
Dequeue - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
Front - This is the front/first Node of the queue.
Rear - This is the rear/last Node of the queue.
Peek - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
IsEmpty - returns true when queue is empty otherwise returns false.
