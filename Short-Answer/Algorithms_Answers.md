#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n)

While this, at first, appears to be a polynomial operation because N is cubed in the while loop definition, because N is then doubled within the while loop, those two N's cancel out two of the N's in the while loop definition, so it's actually a linear operation.

b) O(n log n)

At first, this appears to be a simple nested loop which would be an O(n^2) operation, but because J is doubled on each iteration inside the nested loop, the nested loop has a logarithmic component, which when combined with the outer loop makes for a linearithmic operation.

c) O(n)

This is a linear operation. The function is recursive, and calls itself in a linear relations to the size of N.

## Exercise II

Because the floors are, in effect, sorted from min to max height, you could use a binary search algorithm to find floor F. You would first find the middlepoint of the floors, drop an egg to see if it breaks, and if it breaks you would then know that floor F is in the floors below you, or vice versa if the egg didn't break. You'd repeat this process until you find floor F.

The runtime of this operation is O(log n).
