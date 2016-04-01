# Problem Solving Diagnostic

## Question 1

Write a biggestNum function so that given an array of numbers >= 0, will
arrange them such that they form the biggest number.

Example:

```javascript
biggest([1, 2, 3]) === '321'
biggest([3, 30, 34, 5, 9]) === '9534330'
```

Place your code within the following code block:

```javascript
  //code in here
```

## Question 2

Write a function that will solve a 9x9 Sudoku puzzle. The function will take
one argument consisting of the 2D puzzle array, with the value 0 representing
an unknown square.

There will be no need to assume and test possibilities on unknowns and this can
be solved with a brute-force approach.

Example:

```javascript
var puzzle = [
            [5,3,0,0,7,0,0,0,0],
            [6,0,0,1,9,5,0,0,0],
            [0,9,8,0,0,0,0,6,0],
            [8,0,0,0,6,0,0,0,3],
            [4,0,0,8,0,3,0,0,1],
            [7,0,0,0,2,0,0,0,6],
            [0,6,0,0,0,0,2,8,0],
            [0,0,0,4,1,9,0,0,5],
            [0,0,0,0,8,0,0,7,9]];

sudoku(puzzle);
/* Should return
[[5,3,4,6,7,8,9,1,2],
[6,7,2,1,9,5,3,4,8],
[1,9,8,3,4,2,5,6,7],
[8,5,9,7,6,1,4,2,3],
[4,2,6,8,5,3,7,9,1],
[7,1,3,9,2,4,8,5,6],
[9,6,1,5,3,7,2,8,4],
[2,8,7,4,1,9,6,3,5],
[3,4,5,2,8,6,1,7,9]]
*/
```

Place your code within the following code block:

```javascript
  //code in here
```
