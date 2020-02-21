# Set 1

## Q1

After the `first` iteration, the `mid` value will  be `3` and it's coressponding array element is ```x[3] = 90```. After the `second` iteration, the `mid` value will  be `5` and it's coressponding array element is ```x[5] = 99```.

## Q2

### Can this algorithm perform well in every input?

```
Using random pivoting we improve the expected or average time complexity to O(N log N). The Worst Case complexity
is still O ( N^2 ).
```

### Explain with an example

```
```

### What will be the expected time?

```
```

## Q3


#### Explain with an example  what task is performed by Algorithm 2.

```
We see that the for-loop runs upto n-1 and inside the loop it checks if the current element is greater than the
next element, if the conditon satisfies then, it is swaping them.

And after the for-loop ends, it is again calling the same function but by reducing the value of n by 1, because
after the execution of  the for-loop, the largest element will always be at last.
```

For deatiled example visit: https://www.geeksforgeeks.org/recursive-bubble-sort/

#### Find the complexity of  the algorithm

1. We are calling the same function recursively for each element of the array and inside the function, we are looping till the given length of the array, So Time complexity is O(n ^ n) = O(n ^ 2).

2. We are recursively calling the function for each element of the array, So space complexity is O(n).

#### Can you identify the type of algorithm?

`Algorithm 2 is performing Recursive Buble Sort.`

