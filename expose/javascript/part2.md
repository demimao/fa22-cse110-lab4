question1:
  at line 12, the code prints 3. Because variable "i" is defined as a var, which means it ignores the block it is defined in. It's defined inside a for loop, initialized 0, and increment 1 at every loop. When the loop ends, i turns into 3.
  
question2:
  at line 13, the code prints 150. Variable "discountedPrice" is a var, which means it ignores the block it's defined in. The value of "discountedPrice" is updated every loop. In the final loop, its value is the last value in list prices times half, which is 300 * 0.5 = 150.
  
question3:
  at line 14, the code prints 150. Variable "finalPrice" is a var, which means it ignores the block it's defined in. The value of "finalPrice" is updated every loop. In the final loop, the discountedPrice is 150. finalPrice is calculated as round(150 * 100) / 100, which gives 150.
  
question4:
  The function will return [50, 100, 200]. Variable "discounted" is a list, and is a var, which means it ignores the block it's defined in. It's initialized as an empty list before the for loop. At each for loop, it pushes the finalPrice of each price in list prices into discounted. 
  
question5: 
  The code returns an error: i is not defined. Since variable i is defined with "let", it has scope within the for loop, so it can't be accessed outside the for loop.
  
question6:
  The code returns an error: discountedPrice is not defined. discountedPrice is initialized inside the for loop with "let", so it has its scope within the for loop.
  
question7:
  at line 14, it prints 150. variable "finalPrice" is defined with "let". It is outside the for loop and inside the function, so it has the same scope as line 14. finalPrice has the value it's updated in the final round of loop.
  
question8:
  The function returns [50, 100, 150]. Variable "discounted" is defined with "let". It is outside the for loop and inside the function, so it has the same scope as the return statement. For every round of the loop, it pushes the discounted price into the list "discounted".

question9:
  The code causes an error: i is not defined. Variable i is defined with "let" and initialized inside for loop, so it has its scope within the for loop. Line 11 is outside the scope, and thus can't access variable i.
  
question10:
  At line 12, it prints 3. Variable length is defined as a const at the beginning, within the same scope as line 12. Furthermore, as a const, its value doesn't get updated, so there's no error.

question11:
  The function returns [50, 100, 150]. Variable "discounted" is initialized within the same scope as the return statement, so it can be accessed. Although it's a const, as a const array, its elements can be updated. Variable "discounted" is updated inside the for loop.

Data Types
question12:
console.log(student.name);
console.log(student["Grad Year"]);
console.log(student.greeting);
console.log(student["Favorite Teacher"].name);
console.log(student.courseLoad[0]);

Basic Operators and Type Conversion
question13:
A. '32'
B. 1
C. 3
D. '3null'
E. 4
F. 0
G. '3undefined'
H. NaN

Comparison
question14:
A. true
B. false
C. true
D. false
E. false
F. true

question15:
"==" is a regular equality operator. "===" is a strict equality operator which checks equality without type conversion.

question17:
The result is [2, 4, 6]. Line 13 calls function modifyArray. The parameter array is [1, 2, 3] and callback is function doSomething. A new array is created. Inside the for loop, at line 4, the callback function is called, which is doSomething function. The function multiplies the parameter by 2. Then back at line 4, it pushes the new element into the new array. At last, return the new array.

question19:
1
4
3
2
