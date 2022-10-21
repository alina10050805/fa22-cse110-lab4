1. log `3` to the console. The variable `i` is declared with the var keyword and can be accessed anywhere inside the `funtion discountPrices(prices, discount)` include line 12. The length of `prices=[100, 200, 300]` is 3. The for loop will stop when `i=prices.length=3`.

2. log `150` to the console. The variable `discountedPrice` is declared with the var keyword and can be accessed anywhere inside the `funtion discountPrices(prices, discount)` include line 13. The variable `discountedPrice` will update the value in each time of for loop.The value of discountedPrice in line 13 is the **last discountedPrice update value** in the for loop. The last discountedPrice update value in for loop is used the last element in prices, so discountedPrice=300*(1-0.5)=**150**.

3. log `150` to the console. The variable `finalPrices` is declared with the var keyword and can be accessed anywhere inside the `funtion discountPrices(prices, discount)` include line 14. Same to the question 2, the **last finalPrices update value** in the for loop will go to line 14. The last `finalPrices` update value in for loop will use the last discountedPrice 150, so finalPrice=Math.round(150*100)/100=**150**.

4. The function will return the array [50, 100, 150]. The variable `discounted` is declared with the var keyword and can be accessed anywhere inside the `funtion discountPrices(prices, discount)` include return line. The for loop will run 3 times and push each `finalPrice` to the array `discounted`. For the first time of loop, the `finalPrice=((100*0.5)*100)/100=50` will push to the array `discounted`. Then, the `finalPrice=((200*0.5)*100)/100=100` and `finalPrice=((300*0.5)*100)/100=150` push to the array `discounted`.

5. The code returns `error`, because the variable `i`, which is declared with the let keyword, can only be accessed within the `for(let i=0; i<prices.length; i++) {...}` block scope, and the line 12 is **outside** the block and does **NOT** have access.

6. Same as question 5. The code returns `error`, because the variable `discountedPrice`, which is declared with the let keyword, can only be accessed within the `for(let i=0; i<prices.length; i++) {...}` block scope, and the line 13 is **outside** the block and does **NOT** have access.

7. log `150` to the console. The variable `finalPrice` is declared with the let keyword and can be accessed within the `funtion discountPrices(prices, discount)` block scope include line 14. Same as question 3, finalPrice=Math.round(150*100)/100=**150**.

8. The function will return the array [50, 100, 150]. The variable `discounted` is declared with the let keyword and can be accessed within inside the `funtion discountPrices(prices, discount)` include return line. Calculate same as question 4.

9. The code returns `error`, because the variable `i`, which is declared with the let keyword, can only be accessed within the `for(let i=0; i<prices.length; i++) {...}` block scope, and the line 11 is **outside** the block and does **NOT** have access.

10. log `3` to the console. The variable `length`, which is declared with the const keyword, be first assigned to the `prices.lenth=3` in line 4 and can not be reassigned after it.

11. The function will return the array [50, 100, 150]. The variable `discounted` , which is declared with the const keyword, be first assigned in line 3 and can not be reassigned after it. However, const just means the variable cannot be reassigned, but we still can manipulate it. Calculate same as question 4.

12. A. `student.name`

    B. `student['Grad Year']`

    C. `student.greeting()`

    D. `student['Favorite Teacher'].name`

    E. `student.courseLoad[0]`

13. A. **'32'**, integers map to exact string representation

    B. **1**, numeric conversion happens in mathematical expressions

    C. **3**, numeric conversion happens in mathematical expressions and null becomes 0

    D. **'3null'**, string conversion happens when we need the string form of a value and null becomes 'null'

    E. **4**, numeric conversion happens in mathematical expressions and true becomes 1

    F. **0**, numeric conversion happens in mathematical expressions, false becomes 0, and null becomes to 0

    G. **3undefined**, string conversion happens when we need the string form of a value and undefined becomes 'undefined'

    H. **NaN**, numeric conversion happens in mathematical expressions and undefined becomes NaN

14. A. **true**, string '2' becomes a number 2

    B. **false**, string compared, compare the firse letter '2'>'1'

    C. **true**, string '2' becomes a number 2

    D. **false**, the types are different

    E. **false**, true becomes to 1

    F. **true**, 2 is a non-zero integer, so Boolean(2) return true

15. The operator `==` can conver types to campare two different type. The operator `===` can **NOT** conver types to campare two different type.

16. code in part2-question16.js file.

17. The result will be an array [2,4,6]. In the `modifyArray` function, it will call the function `doSomething` 3 time with input from 3 element in the array and push the value to the newArr. The function doSomething is return the 2 times num, so `modifyArray([1,2,3], doSomething)` will return an array with each element times 2, which is from `[1,2,3]` to `[2,4,6]`.

18. code in part2-question18.js file.

19. 1

    4

    3
    
    2