# Answers to Part 2
1. Line 12 prints 3 which is the index in the for loop which runs upto `i = 2` and then increments to 3 and then the loop exits after checking the condition of `i < prices.length` and since that is 3 it will return false. The variable is still in scope since the variable was declared with `var` and the console log is within the same function.
2. It prints 150 which is the discount for the last item in the prices array. The variable is still in scope due to similar reasons as the previous answer.
3. Similar to the previous answer, the last assignment inside the loop leads to the variable having the price after the discount stored in it.
4. The function returns the prices given in the `prices` function argument and returns a parallel list containing the prices after applying the `discount` given in the second argument.
5. It throws an error since the variable `i` is out of scope due to being declared inside the for loop using `let`
6. It throws an error since the variable `discountedPrice` is out of scope due to being declared inside the for loop using `let`
7. It returns the correct discounted price since the variable `finalPrice` is declared using `let` in the top level of the function.
8. The function returns the prices given in the `prices` function argument and returns a parallel list containing the prices after applying the `discount` given in the second argument.
9. It throws an error since the variable `i` is out of scope due to being declared inside the for loop using `let`
10. It prints the length of the list which is 3
11. The function returns the prices after discount
12. 
    1. `student['name']`
	2. `student['Grad Year']`
	3. `student['greeting']`
	4. `student['Favourite Teacher']['name']`
	5. `student['courseLoad'][0]`
13. 
    1. The 2 gets converted to a string and gets concatenated with 3 to produce 32
    2. The 3 gets downcasted to an integer due to - to produce 1
    3. `null` gets interpreted as 0 to produce 3
    4. `null` gets interpreted as a string to produce 3null
    5. True becomes 1 producing 4
    6. Both of the them get interpreted as a number to produce 0
    7. `undefined` become the string undefined to produce 3undefined
    8. `undefined` becomes `NaN` and produces `NaN` with '3' which gets converted to number
14. 
    1. '2' becomes a number and produces true when compared with 1
    2. elementwise string comparison produces false when 2 is compared with 1 (str)
    3. 2 (rhs) gets casted to a number and produces true
    4. Strict equality checks for type equality as well so int ≠ string so false
    5. True is 1 when casted to number so its not equal to 2 so false
    6. Boolean 2 is true since any non 0 number is truthy
15. `===` Checks for type equality while `==` doesn't
16. (check `part2-question16.js`)
17. In line 4, we can replace `callback` with the function `doSomething` which we can replace with `array[i] * 2` (that's not exactly what happens but just to give an idea) which thus produces the list 2, 4, 6.
18. (check `part2-question18.js`)
19. `1 4 3 2` (each in separate line)
20. 