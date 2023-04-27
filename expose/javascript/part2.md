1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

  the code will print the value of i (which is equal to the length of the prices array) because the loop stops when i = length of prices
  
2. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^

  It will log the last value of discountedPrice after the loop finishes executing because it's function scoped
  
3. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^

  It will log the last value of final prices after the loop finishes executing because it's function scoped it can be accessed 
  
4. ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^

  The function will return an array of discounted prices based on the input prices array and discount percentage. The function 
  calculates the discounted price of each item in the prices array by multiplying the original price with (1 - discount), 
  rounds the result to two decimal places, and pushes it into a new array called discounted.
  
5. What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).

   This code will cause an error because the variable i is declared in the for loop block such that it is not accessable outside the block
   
6. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^

   This code will cause an error because the variable discountedPrice is in the for loop block so it can't not be accessed outside the block

7. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^

   It will log the last value of final prices after the loop finishes executing because the variable finalPrice was declared before 
   entering the loop
   
8. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^

   The function will return an array of discounted prices based on the input prices array and discount percentage. The function 
   calculates the discounted price of each item in the prices array by multiplying the original price with (1 - discount), 
   rounds the result to two decimal places, and pushes it into a new array called discounted.
   
9. ^^^ What will happen at line 11 and why? If the code causes an error, explain why. ^^^

   At line 11 there will be an error because the variable i is in the scope of the loop and console.log(i) is outside the loop 
   
10. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

  It will print the length of the prices arrary which in this case is 3
  
11. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^

  This function, discountPrices(), will return an array containing the discounted price values of the input prices array based on the given   
  discount percentage.
  
12.Given the above Object, write the notation for:  (These should be in your part2.md). <br>
  A. Accessing the value of the name property in the student object. <br>
     student.name <br>
  B. Accessing the value of the Grad Year property in the student object.<br>
     student['Grad Year'] <br>
  C. Calling the function for the greeting property in the student object. <br>
     student.greeting() <br>
  D. Accessing the name property of the object in the Favorite Teacher property in student. <br> 
     student['Favorite Teacher'].name <br>
  E. Access index zero in the array of the courseLoad property of the student object. <br>
     student.courseLoad[0] <br>
     
For each of the following questions, note down the output as well as a brief explanation why that output was given  (These should be in your part2.md). <br>

13. Arithmetic. <br>
  A. ‘3’ + 2. <br> 
     Output: '32'. <br>
     Explanation: integers map to their exact string representation. <br>
  B. ‘3’ - 2. <br>
     Output: 1. <br>
     Explanation: string map to their exact integer representation . <br>
  C. 3 + null. <br>
     Output: 3. <br>
     Explanation: null is being converted to the value 0. <br>
  D. ‘3’ + null. <br>
     Output: '3null'. <br>
     Explanation: null is being mapped to it's exact string representation. <br>
  E. true + 3. <br>
     Output: 4. <br>
     Explanation: boolean map to their exact integer representation. <br>
  F. false + null. <br>
     Output: 0. <br>
     Explanation: false and null is being mapped to their integer representation. <br>
  G. '3' + undefined. <br>
     Output: '3undefined'. <br>
     Explanation: undefined is being mapped to it's exact string representation. <br>
  H. '3' - undefined. <br>
     Output: NaN. <br>
     Explanation: '3' turned into integer but undefined doesn't have integer representation so return (Not a number). <br>
     
14. Comparision. <br>
  A. ‘2’ > 1. <br>
     Output: true. <br>
     Explanation: string mapped to it's exact integer representation and being compared. <br>
  B. ‘2’ < ‘12’. <br>
     Output: false. <br>
     Explanation: compares the length of the strings. <br>
  C. 2 == ‘2’. <br> 
     Output: true. <br>
     Explanation: == operator perform type coercion, string mapped to it's exact integer representation and being compared.  <br>
  D. 2 === ‘2’. <br>
     Output: false. <br>
     Explanation: === operator does not perform type coercion, number != string. <br>
  E. true == 2. <br>
     Output: false. <br>
     Explanation: boolean map to it's exact integer representation. <br>
  F. true === Boolean(2). <br>
     Output: true. <br>
     Explanation: Boolean(2) converts to true because 2 is a truthy value. <br>
     
15. Explain the difference between the == and === operators. <br>
  The == operator is called the "abstract equality" operator. It compares two values for equality after performing type coercion.
  The === operator, on the other hand, is called the "strict equality" operator. It compares two values for equality without 
  performing type coercion.
  
16. (see part2-question16.js) <br>

17. function call modifyArray([1,2,3], doSomething). <br>

    when modifyArray is called with the array [1, 2, 3] and the callback function doSomething, it first
    calls doSomething(1) which returns 2, and pushes it to newArr. Then it calls doSomething(2) which 
    returns 4, and pushes it to newArr. Finally, it calls doSomething(3) which returns 6, and pushes it to 
    newArr. The resulting newArr is [2, 4, 6], which is then returned. 
  
  
18. (see part2-question18.js) <br>

19. '1', '4', '3', '2' <br>
