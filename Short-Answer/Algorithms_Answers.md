#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

```
a) O(n)  space O(1)


b)  O(nlogn)   space O(1)


c) O(n)   space O(n)
```

## Exercise II

```
Egg Drop average O(n)

Binary Search, cut the floors in half each time O(logn)

we will start on the ground floor. Then find the middle floor, drop the egg.

There are two possibilities the egg breaks or the egg does not break.

1) if the egg breaks - we will move from the middle floor down to the new middle floor which is the middle between the ground and the current floor you were on.

2) if the egg does not break - we will move to the middle floor between the current floor we are on to the top floor.

repeat until you find the highest floor the egg does not break.

```
