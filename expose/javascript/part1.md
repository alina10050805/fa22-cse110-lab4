### Part 1

1. `values added: 20`

2. `final result: 20`

3. `values added: 20`

4. The code returns `error`, because the variable `result`, which is declared with the let keyword, can only be accessed within the `if(add) {...}` block scope, and the line 13 is **outside** the block and does **NOT** have access.

5. The code returns `error`. The variable `result`, which is declared with the const keyword, be first assigned in line 5 and can not be reassigned after it. In line 7 try to reassigned variable `result`after initialization, so it causes a error and will **NOT executed any code after line 7** includ line 9.

6. Same to question 5. The code returns `error`. The variable `result`, which is declared with the const keyword, be first assigned in line 5 and can not be reassigned after it. In line 7 try to reassigned variable `result`after initialization, so it causes a error and will **NOT executed any code after line 7** includ line 13.