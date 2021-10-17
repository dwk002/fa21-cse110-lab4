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
12. 