# Part 1 Javascript 

## var declaration
1.  "values added: 20" is printed by line 9, the code does not return an error. JavaScript successfully calculates num1 + num2 and stores it in the variable result, which exists within the function scope (this difference will be seen in questions 4-5) in addition to add being true.

2. "final result: 20" is printed by line 13, the code does not return an error as the variable is acessible outside of if(add) (result is using var which means function scope).

3. Based on questions 1 and 2, we can see that the variable result is accesible even outside of the block. By this, var should not be used because this overwriting can lead to bugs. Regardless what happens in the code, var also does hoisting which even if we wrote the variable later on in our code, when compliing the varible would act as if it was already declared (will not say undefined but what you assigned it to).

4. Line 9 prints "value added: 20". This is because the result varibale is within the if(add) block.

5. The code returns the error that result is not define: "ReferenceError: result is not defined". This is because result variable now uses let, meaning it is block-scoped, contained in the if(add) block and this call to result is outside of that.


## const declaration
6. There is already an error at line 7 at result = num1 + num2 because a constant type cannot be alter. Therefore this error is shown before we reach the print statement at line 9.

7. Similar to question 6, an error will be shown at line 7 at result = num1 + num2 because a constant type cannot be alter. In additon, const is also block scoped like let, so we would not be able to access it at line 13 as it is outside the if(add) block.

