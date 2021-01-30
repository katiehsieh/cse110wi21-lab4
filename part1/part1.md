1. At line 11, it will print `i` because it is a var variable that is scoped to the entire function.
2. At line 12, it will print `discountedPrice` because it is a var variable that is scoped to the entire function.
3. At line 13, it will print `finalPrice` because it is a var variable that is scoped to the entire function.
4. The function will return a list of discounted prices `[50, 100, 150]` because it loops through the input prices and applies a 50% discount to each price.
5. At line 11, there is an error because `i` is declared using let and only visible inside the for loop.
6. At line 12, there is an error because `discountedPrice` is declared using let and only visible inside the for loop.
7. At line 13, it will print `finalPrice` because it is declared using let (outside the for loop) and visible inside the function.
8. The function will return a list of discounted prices `[50, 100, 150]` because it loops through the input prices and applies a 50% discount to each price.
9. At line 11, there is an error because `i` is declared using let and only visible inside the for loop.
10. At line 12, there is an error becuase `discountedPrice` is declared using const and only visible inside the for loop.
11. At line 13, it will print `0` because `finalPrice` is declared using const and initially set to `0` (if ignoring the error of reassigning `finalPrice` in the for loop).
12. The function will return the list `[0, 0, 0]` becuase `finalPrice` is declared using const (if ignoring the errors of reassigning `discountedPrice` and `finalPrice` in the for loop).
13. Object notation\
  A. `student.name`\
  B. `student['Grad Year']`\
  C. `student.greeting()`\
  D. `student['Favorite Teacher'].name`\
  E. `student.courseLoad[0]`
14. Arithmetic\
  A. `'32'` (one operand is a string, so + operation is string concatenation)\
  B. `1` (string operand is converted to number for subtraction operation)\
  C. `3` (null is converted to number of value 0 for addition operation)\
  D. `'3null'` (null is converted to string for string concatenation)\
  E. `4` (true is converted to number of value 1 for addition operation)\
  F. `0` (false and null are both converted to number of value 0 for addition operation)\
  G. `'3undefined'` (undefined is converted to string for string concatenation)\
  H. `NaN` (3 is converted to number and undefined is converted to NaN, so substraction operation results in NaN)
15. Comparison\
  A. `true` (2 is converted to number)\
  B. `false` (string comparison, '2' is greater than '1')\
  C. `true` (2 is converted to number)\
  D. `false` (strict equality operator, 2 and '2' are different types)\
  E. `false` (true is converted to 1)\
  F. `true` (Boolean(2) converts 2 to boolean value of true)
16. The `==` equality operator converts operands of different types to numbers before comparing, while the `===` strict equality operator checks the equality without type conversion (operands must be of the same type to be equal).
17. `How are you?` gets printed because in the first if statement, true is converted to 1, so the statement 2 == 1 is false. In the else if statement, 2 is converted to boolean value of true.
18. (See part1-question18.js)
19. The result is `[6, 8, 10]`. The array `[1, 2, 3]` and the function `doSomething` are passed into `modifyArray`. In the `modifyArray` function, it loops through the elements in the input array and pushes the result of calling the callback function `doSomething`. The array element and another callback function are passed into `doSomething`. In the `doSomething` function, it calls this second callback function by passing in the array element + 2. So for each array element `x`, the result is `(x + 2) * 2`.
20. (See part1-question20.js)
21. The output is `1 4 3 2`.