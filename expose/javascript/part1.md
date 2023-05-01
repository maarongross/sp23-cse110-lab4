1. `values added:  20`
2. `final result:  20`
3. `values added:  20`
4. Line 13 is trying to access the `result` variable, but it is outside of the block it was declared in. `result` being declared as a let causes the error.
5. Line 9 is never reached because the function is trying to modify a constant, which is impossible.
6. Same as 5.