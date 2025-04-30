# Part 2

1. `3` will be printed to the console, as discountPrices was passed a 3 item list, and `var i` remains in scope after the for loop concluded.
2. `150` will be printed to the console, as this is the last value that the `discountPrice` variable held, which is still in scope after the for loop concluded.
3. `150` will be printed to the console, as this is the last value that the `finalPrice` variable held, which is still in scope after the for loop concluded.
4. The function will return a list of prices equalling the list it was passed discounted by the rate it was passed. 
5. The script will reutrn an error on line 12, as `i` is referenced while not in scope. It was declared with a `let` statement in a now-closed block
6. The script will reutrn an error on line 12, as `discountedPrice` is referenced while not in scope. It was declared with a `let` statement in a now-closed block
7. `150` will be printed to the console, as this is the last value that the `finalPrice` variable held, which is still in scope after the for loop concluded because it was declared outside of the for loop.
