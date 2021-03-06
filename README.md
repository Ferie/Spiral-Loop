# Spiral-Loop

This JavaScript function loops in a spiral way trough a given matrix (counterclockwise).

### Example

E.g. if you are passing a matrix like this one:

```javascript
/* Input */

var matrix = [
    [ 1,  2,  3,  4,  5,  6],
    [ 7,  8,  9, 10, 11, 12],
    [13, 14, 15, 16, 17, 18],
    [19, 20, 21, 22, 23, 24],
    [25, 26, 27, 28, 29, 30],
    [31, 32, 33, 34, 35, 36]
];
```

the result will be the following

![alt text][matrix]

[matrix]: https://github.com/Ferie/Spiral-Loop/blob/master/Spiral-Loop.jpg "Spiral Loop example"

```javascript
/* Output */

1 2 3 4 5 6 12 18 24 30 36 35 34 33 32 31 25 19 13 7 8 9 10 11 17 23 29 28 27 26 20 14 15 16 22 21
```

This function is working for matrices of any sizes.
