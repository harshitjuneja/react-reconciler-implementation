Goal: This pet project is intended to serve the following purpose/purposes:

1. Understand how react performs reconciliation (Fibre reconciliation)
2. History of the reconciliation process (Stack reconciliation)
3. Decision making in choosing how data is efficiently represented to be worked upon (Data Structure choice)
4. The Algorithm approach in itself (Hopefully understand the complexity)
5. Line by line code analysis inside react/src/packages/reconciler/
6. Mimicing the fiber logic with practical examples
7. Write and share my understanding with the broader community.

Reconciler: the mechanism that tracks changes (performs the updation to the virtual DOM if requried) and makes it visible on the screen

Focus/Output: 
Given two trees find out a way to identify changes optimally and flush the difference to the browser DOM efficiently. 

History:
We know that react team moved to a fiber based implemenation from a stack based implementation and async rendering. What made them do so? How did they come about an async approach (was it simply just logical?)

What data structures were used and brainstromed upon when building react?

Selling point: Incremental rendering.


Inspiration/References:

1. https://medium.com/react-in-depth/inside-fiber-in-depth-overview-of-the-new-reconciliation-algorithm-in-react-e1c04700ef6e

2. 