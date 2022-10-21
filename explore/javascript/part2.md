1. The value "3" is printed. This is because at line 12, we are logging the value of index i after the for loop is run. The variable i is declared using the var keyword, which means it can be accessed anywhere inside the function it is defined in. After the for loop is run, i = 3 because i is incremented by 1 each time the for loop runs and quits when i is no longer less than the length of the prices array. Here, the length of prices is 3, so the for loop is exited when i = 3. 

2. The value "150" is printed. This is because at line 13, we are logging the value of discountedPrice after the for loop is run. The variable discountedPrice is declared using the var keyword, which means it can be accessed anywhere inside the function it is defined in. During the last run of the content inside the for loop, i = 2. The value of prices[i] is 300, which is multiplied by (1 - discount) = (1 - 0.5) = 0.5. Thus, the value of discountedPrice is set to 300 * 0.5 = 150. 

3. The value "150" is printed. This is because at line 14, we are logging the value of finalPrice after the for loop is run. The variable finalPrice is declared using the var keyword, which means it can be accessed anywhere inside the function it is defined in. During the last run of the content inside the for loop, the value of finalPrice is set to (discountedPrice * 100)/100 = (150 * 100)/100 = 150. Math.round rounds the value to the nearest integer, which is still 150. Thus, the value of finalPrice is set to 150.

4. This function will return [ 50, 100, 150 ]. The variable discounted is first declared as an empty array on line 3. Inside the for loop, the changing values of finalPrice are calculated and then pushed to the discounted array. In JavaScript, Array.push() pushes the item to the back of the array, which is why the final prices corresponding to the original prices in the prices array get pushed to the discounted array in order.

5. There is an error, "ReferenceError: i is not defined," because the variable i was defined using the let keyword and can only be accessed within the block it is defined in, which would be the for loop. 

6. There is an error, "ReferenceError: discountedPrice is not defined," because the variable discountedPrice was defined using the let keyword and can only be accessed within the block it is defined in, which would be the for loop. 

7. The value "150" is printed. This is because the variable finalPrice was defined using the let keyword and can only be accessed within the block it is defined in, which would be the entire discountPrices function. 

8. The function will return [ 50, 100, 150 ]. The reasoning for the values returned follows the same reasoning as answer 4. The reason the use of the let keyword as opposed to the var keyword does not affect the return value of the function is because on line 16, where the return statement is, the variable discounted is still in the block it is defined in, which is the entire discountPrices function. The value of discounted is returned from the function normally. 

9. There is an error, "ReferenceError: i is not defined," because the variable i was defined using the let keyword and can only be accessed within the block it is defined in, which would be the for loop. 

10. The value "3" is printed. This is because the variable length is declared with the const keyword and can only be accessed within the block it is defined in, which would be the entire discountPrices function. 

11. The function will return [ 50, 100, 150 ]. The reasoning for the values returned follows the same reasoning as answer 4. The reason the use of the const keyword as opposed to the var keyword does not affect the return value of the function is because on line 14, where the return statement is, the variable discounted is still in the block it is defined in, which is the entire discountPrices function. The value of discounted is returned from the function normally. 

12. A) student.name
    B) student['Grad Year']
    C) student.greeting()
    D) student['Favorite Teacher'].name
    E) student.courseLoad[0]
    
13. A) '32' because integers map to their exact string representation
    B) 1 because '3' maps to 3
    C) 3 because null maps to 0
    D) '3null' because null maps to a string
    E) 4 because true maps to 1
    F) 0 because false and null both map to 0
    G) '3undefined' because undefined maps to a string
    H) NaN because of numeric conversion rules, undefined becomes NaN
    
14. A) true because '2' becomes a number
    B) true because '2' and '12' become numbers
    C) true because '2' becomes a number
    D) false because === checks the equality without type conversion and a number is not equal to a string
    E) false because true maps to 1 and 1 is not equal to 2
    F) true because true maps to 1, Boolean(2) equals true which maps to 1, and 1 equals to 1
    
15. The difference between the == and the === operators is that the == operator is an equality operator that converts operands of different types to numbers, while === is a strict equality operator that checks the equality without type conversion.

17. The result is [ 2, 4, 6 ]. This is because within the for loop, we are calling the callback function doSomething with the value of the array at index 1. In the callback function, we double the value before pushing the value to newArr. We repeat this for each value in the array ([1, 2, 3]) before we return newArr, which is how we end up with the doubled values in newArr.

19. The output of the code is:
1
4
3
2
