# Expose: Javascript
## Part 2
1. Line 12 will print `3`. Since `var i` is still accessible within all of the function, not only the for block.
2. Line 13 will print `150`, since `var discountedPrice` is accessible outside of the for block, and it's final value was `300 * 0.5 = 150`
3. Line 14 will print `150`, since `var discountedPrice` is accessible outside of the for block, and it's final value was `150 * 100 / 100 = 150`
4. The function will return `[50, 100, 150]`. Each entry of `prices` was halved. And `discounted` is accessible. 
5. Line 12 will return an `error:`i not defined. Since `i` is let type variable it is not accessible outside of the for block.
6. Line 13 will return an `error:` discountedPrice is not defined. Since `discountedPrice` is let type variable it is not accessible outside of the for block.
7. Line 14 will print `150`. Since `finalPrice` is defined outside of for block, it is accessible for line 14.
8. The function will return `[50, 100, 150]`. `discounted` is defined outside of for block, it is accessible for return function.
9. Line 11 will return an `error:`i not defined. Since `i` is let type variable it is not accessible outside of the for block.
10. Line 12 will print `3`. Since length was never reassigned, and it is still accessible for line 12. 
11. The function will return `[50, 100, 150]`. `discounted` is defined outside of for block, it is accessible for return function. Also, it is never reassigned, only **modified**.
12. Object Notation
    1. `student.name`
    2. `student['Grad Year']`
    3. `student.greeting();`
    4. `student['Favorite Teacher'].name`
    5. `student.courseLoad[0]`
13. Arithmetic
    1. `'3'+2= '32'`: integers map to their exact string representation
    2. `'3'-2= 1`: String converted to their int representation
    3. `3+null= 3`: null's number conversion is 0
    4. `'3'+null= '3null'`: null's string conversion is 'null' 
    5. `true+3= 4`: true's num conversion is 1
    6. `false + null= 0`: false and null num conversion is 0
    7. `'3'+undefined= '3undefined`: undefined string conversion is 'undefined'
    8. `'3'-undefined= NaN`: undefined numeric conversion is NaN
14. Comparison
    1. `'2'>1 = true`:'2' becomes 2
    2. `'2' < '12' = false`: As a string '2' comes before '12' in "dictionary" order
    3. `2 == '2'= true`: '2' becomes 2
    4. `2 === '2' = false`: 'A strict equality operator === checks the equality without type conversion.'
    5. `true == 2`: false, true is 1 in numeric form
    6. `true == Boolean(2)`: Any number other than 0 is true, so Boolean(2) is true!
15. `==` compares type converted results, while `===` compares without type conversion 
16. [part2question16_jsfile](part2-question16.js)
17. Result will be `[2, 4 ,6]`. Each value in `array` is multiplied by 2 through the `doSomething(num)` function called by `callback` parameter. 
18. [part2question18_jsfile](part2-question18.js)
19. `1 4 3 2`