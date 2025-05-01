# Part 2

1. `3` will be printed to the console, as discountPrices was passed a 3 item list, and `var i` remains in scope after the for loop concluded.
2. `150` will be printed to the console, as this is the last value that the `discountPrice` variable held, which is still in scope after the for loop concluded.
3. `150` will be printed to the console, as this is the last value that the `finalPrice` variable held, which is still in scope after the for loop concluded.
4. The function will return a list of prices equalling the list it was passed, discounted by the rate it was passed. 
5. The script will reutrn an error on line 12, as `i` is referenced while not in scope. It was declared with a `let` statement in a now-closed block
6. The script will reutrn an error on line 12, as `discountedPrice` is referenced while not in scope. It was declared with a `let` statement in a now-closed block.
7. `150` will be printed to the console, as this is the last value that the `finalPrice` variable held, which is still in scope after the for loop concluded because it was declared outside of the for loop.
8. The function will return a list of prices equalling the list it was passed, discounted by the rate it was passed. Using let instead of var did not change this behavior.
9. The script will reutrn an error on line 11, as `i` is referenced while not in scope. It was declared with a `let` statement in a now-closed block.
10. `3` will be printed to the console, as `const length` was set to  a the length of a 3 item list, and the variable remains in scope when it is printed.
11. The function will return a list of prices equalling the list it was passed, discounted by the rate it was passed. While `const discountedPrice` never changes, it is redeclared and initialized on each new for-loop iteration, so all values of the prices are possible. 
12. Question 12:
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. Question 13:
    1. '32' -- the 2 is connverted to a string and then concatenated.
    2. 1 -- '3' is converted to a number as subtraction expects numerical operands.
    3. 3 -- null is converted to the number 0 to match 3
    4. '3null' -- null is converted to the string 'null' to match the type of '3'
    5. 4 -- true is converted to the number 1 when it is an addition operand
    6. 0 -- both false and null are converted to numbers for the addition, both 0
    7. '3undefined' -- undefined is converted to a string as it is being concatenated to another string
    8. NaN -- the subtraction operator converts its operands to a number, and the number undefined maps to is NaN
14. Quesiton 14:
     1.  true -- '2' is converted to its corresponding number and 2 > 1 (or perhaps 1 is converted to a string... the behaviors are logically equivalent)
     2.  false -- the string '2' is lexicographically larger than the string '12'
     3.  true -- '2' is converted to a number and compared to 2
     4.  false -- 2 and '2' are different types so fail a strict equallity check
     5.  false -- true is converted to the number 1, which does not equal 2
     6.  true -- 2 is converted to the boolean value true (as 2 is nonzero), and true is strictly equal to true
15. The difference between the == and === operators is that === resolves to true only for strictly equal operands: that is, variables/literals with both the same type and the same value. == on the other hand will convert mismatched types before comparing their values.
16. part2-question16.js
```
  for(item in statistics) {
    if (item[0] == 'r') {
      console.log(statistics[item]);
    }
    else if (statistics[item] % 2 == 1) {
      console.log(statistics[item]);
    }
  }
```
17. [ 2, 4, 6 ] will be the result. This is because modify array is passed [ 1, 2, 3 ], and it then calls the doSomething function to double each element of the array.
18. (see part2-question18.js)
19. The output is 1 then 4 then 3 then one second later 2. 