1. The code will print `3` to the console since the length of `prices` is 3.
2. The code will print `150` to the console since the most recent value of `discountedPrice` is half of the third value of the `prices` array.
3. The code prints `150` to the console since the most recent value of `finalPrice` is the most recent modified value of `discountedPrice`.
4. The function returns the array `discounted = [50, 100, 150]`, since the function multiplied each value in the array by 0.5 and put the modified value into the `discounted` array.
5. The code causes an error since `i` is of type `let`, so it cannot be accessed outside of its scope.
6. Same as 5., but with the `discountedPrice` variable.
7. The value for `finalPrice` is printed to the console. This works since `finalPrice` is still in scope and it is a `let`.
8. It returns the same array as in 4., since the only thing that changed between those two implementations was the change from type `var` to type `let`.
9. The exact same error as 5.
10. The program prints out the length of the array `length` to the console.
11. The same values as 4. and 8. are printed to the console.
12. A. student.name; B. student["Grad Year"]; C. student.greeting(); D. student["Favorite Teacher"].name; E. student.courseLoad[0]
13. Arithmetic
- `32`, due to string concatenation
- `1`, since 3 was converted to an integer because of the subtraction
- `3`, since `null` maps to the integer `0`
- `3null`, since it adds the string `"null"` to `'3'`
- `4`, since `true` maps to the integer `1`
- `0`, since `false` maps to the integer `0`, and null maps to `0`
- `3undefined`, since `undefined` gets mapped to the string `'undefined'` that gets concatenated to `'3'`
- `NaN`, since `undefined` maps to the integer `NaN` during subtraction
14. Comparison
- `true`, `'2'` becomes the integer `2`, which is greater than `1`
- `false`, the strings are compared lexicographically, so `'2'` comes after `'12'`
- `true`, the string `'2'` is converted to an integer, so they are equal
- `false`, comparison is made without type conversion
- `false`, `true` maps to the integer `1`, so not equal
- `true`, since the RHS is already converted to Boolean, and is `true` since `2` is nonzero
15. `==` performs type conversion between operands, while `===` does not.
16. See part2-question16.js
17. The array `[1,2,3]` is doubled due to the callback to `doSomething` in the `modifyArray` function.
18. See part2-question18.js
19. `1`,`4`, and `3` are printed to the console, with `2` being printed one second later.