1. 3, because i has increased for four times (from 0 to 3), and when i is 3, it finishes the for loop and is printed at line 12
2. 150, because the last time `discountedPrice` is modified happens when `prices[2] * (1 - 0.5)` which gives us `150`.
3. 150, because the last time `finalPrice` is modified happens when `Math.round(150 * 100) / 100` which gives us `150`.
4. The function will return `[ 50, 100, 150 ]` because the `finalPrice` is pushed three times to the `discoutned` list
5. `ReferenceError: i is not defined` the result is because at line 12, `i` is out of scope since it is let not var.
6. `ReferenceError: discountedPrice is not defined` the result is because at line 13, `discountedPrice` is out of scope since it is let not var.
7. 150, since `let finalPrice` is defined in the function scope, which is the same scope as line 14 is.
8. The function will return `[ 50, 100, 150 ]` because the `finalPrice` is pushed three times to the `discoutned` list and  `discoutnedPrice` is defined in the function scope
9. `ReferenceError: i is not defined` because i is defined as let, inside the for loop, but line 11 is out of scope.
10. 3, because length is a const defined in the function scope, so it has a value of 3 because discounted has 3 elements
11. The function will return `[ 50, 100, 150 ]` because the `discountedPrice` is pushed three times to the `discoutned` list and  `discoutned` is defined in the function scope
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. 32, since integers map to their exact string representation
    B. 1, since integers map to their exact string representation
    C. 3, since integers map to their exact string representation and null is 0
    D. 3null, null maps to string null
    E. 4, true is 1, 1 + 3
    F. 0, false is 0, null is 0
    G. 3undefined, two strings combined together
    H. NaN, no - operation in string, so an error occurs as NaN
14. A. true,  string '2' becomes a number 2
    B. false, string 2 is greater than string 12 because the first number 2 is greater than 1
    C. true, string 2 becomes number 2
    D. false, string and number are different types
    E. false, true is 1, 1 does not equal to 2
    F. true, Boolean(2) is true, and === checks the type as well, so true === true is true
15. A strict equality operator === checks the equality without type conversion. In other words, if a and b are of different types, then a === b immediately returns false without an attempt to convert them. However, == will compare and convert certain types and the result depends. 