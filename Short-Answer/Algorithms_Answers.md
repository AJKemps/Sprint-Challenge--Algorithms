#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O c^n

This is a polynomial operation. Because the while loop condition is set by cubing N, this means that while loop run time will scale in an ever increasing manner as N increases. E.g. with an n of 2 the while loop would run 8 times, and with an n of 3 it would run 27 times.

b) O(n^2)

This is a simple nested loop function where we have to iterate through two loops based on N, so N\*N is O(n^2)

c) O(n)

This is a linear operation. The function is recursive, and calls itself in a linear relations to the size of N.

## Exercise II

Eggs are broken if dropped from a floor F or higher. The building is N floors tall. In order to minimize the number of eggs broken, you want F to be as high as possible. There's nothing stopping us from making the top floor of the buidling floor F every time, as that would mean only the top floor could break eggs. Thus, you'd simply set floor F to be last floor. This is a constant O(1) run time because the work does not change as N changes.
