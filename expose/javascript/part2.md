# Part 2 Javascript 

1.  At line 12, the console wil print 3 as i is var, function scoped indicating the last value of i of 3 will run, returning the current index of the array after it finishes.

2. At line 13, the console will print 150 as the last price is 300 of the arry and with a discount of 0.5, it will return 150.

3. At line 14, the console will reutrn 150 because the last price is 300 of the array and with a discount of 0.5, it will return 150, rounded to the nearest integer.

4. This function will return an array of discounted price rounded to the nearest integer. This mean [100,200,300] would return as [50,100,150] with the usage of this function.

5. At line 12, this code will have an error because the loop varibale is decalred with let, meaning it is blockscoped within the loop, so using it outside will cause an error as the i is inacessible.

6. At line 13, the code will have an error as discountedPrice is declared with let, meaning accesing discountedPrice outside of the loop will return an error as it is inaccessible. 

7. At line 14, the console will output 150 because while let is block-scope, console.log(finalPrice) is at the same blockscope as when finalPrice is declared.

8. The function will return [50,100,150], list of discounted price items.

9. At line 11, the code will have an error because in the loop, i is declared with let withint the loop, being blockscoped, meaning console.log(i) is outside of the block.

10. At line 12, 3 will be printed as lenght is never changed, it is lenght of the array.
    
11. The function will return [50,100,150], the list of dicounted items.

12. <br>
A. student.name<br>
B. student["Grad Year"]<br>
C. student.greeting()<br>
D. student.[Favorite Teacher"].name<br>
E. student.couseLoad[0]<br>


13. <br>
A. 32 will be the output, this is due to the + operator that does string concatenation.<br>
B. 1 will be the output due to the - operator, as 3 and 2 will be converted into numbers by js and substraction will occur.<br>
C. 3 will be the output as 3 + null, null is equal to 0 in js.<br>
D. 3null will be the ouput as null will be turned to a string and conatentated with the 3. This is as '3' is a string in this case.<br>
E. 4 will be the output, this is as true is equivalent to 1.<br>
F. 0 will be the output as both false and null are equal to 0 in js.<br>
G. 3undefined will be the output, as the + symbol does concatenation and undefined will be converted into a string becuase 3 is a string.<br>
H. NaN will be the ouput, this is as undefined is not a number and can't be subtracted from 3 which turned from a string to a number.<br>


14. <br>
A. true will be the ouput, because 2 is greater than 1 (as 2 will be interpreted as a number).<br>
B. false will be the ouput, because 12 is greater than 2, this is a string comparsion as both are strings.<br>
C. true will be the ouput, as == is type coercion meaning that '2' will be intrepreted as a number than the comparsion will be performed, 2 is equal to 2 so this is true.<br>
D. false will be the ouput, as although the values are the same the type is different, with one a string and other a number.<br>
E. false will be the ouput, as true will be 1 and 1 is not equal to 2.<br>
F. true will be the ouput, this is as Boolean(2) will be equal to true and therefore be of same type.<br>

15. The difference between == and === is that === checks for type equality while the other does not. == is a loose equal sign, comparing values and converts types such as string to numbers.

16. see part2-question16.js

17. The result will be [2,4,6]. This is due to how in the loop there is a call to the function doSomething (callback) which multiple the number by 2. Basically modifyArray([1,2,3]) is called, where it loops thru [1,2,3], as it goes to thorugh each number it will push the new number after it has been modified by the function doSomething which mutiples the number by 2. This new array will be returned.

18. see part2-question18.js

19.  The output will be: <br>
1<br>
4<br>
3<br>
2<br>

SetTimeout is asynchronous, meaning it will let some code run while it runs later. Therefore, 1 and 4 will be printed out first because they have no setTimeOut. As setTimeout for 3 sets it as 0, it will run first while for 2 it is set at 1000 therefore running last.
