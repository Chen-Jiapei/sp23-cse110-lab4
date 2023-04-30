Question 1:

Line 12 will print "3". The functions takes prices [100, 200, 300] and discount 0.5 as input. There are 3 elements in prices, so the for loop will iterate 3 times and the variable "i" will be added to 3. Since the variable "i" is declared with "var" keyword, line 12 has access to "i" and therefore will print "3".

Question 2:

Line 13 will print "150". The functions takes prices [100, 200, 300] and discount 0.5 as input. The last element in prices is 300, so in the last iteration of the for loop, the variable "discountedPrice" is created and assigned with value 150. Since the variable "discountedPrice" is declared with "var" keyword, line 12 has access to "discountedPrice" and therefore will print "150".

Question 3:

Line 14 will print "150". The functions takes prices [100, 200, 300] and discount 0.5 as input. The last element in prices is 300, so in the last iteration of the for loop, the variable "finalPrice" is assigned with value 150. Since the variable "finalPrice" is declared with "var" keyword, line 12 has access to "finalPrice" and therefore will print "150".

Question 4:

The function will return [50, 100, 150]. The functions takes prices [100, 200, 300] and discount 0.5 as input. For each price in prices, the function multiplies it by (1 - discount) = (1 - 0.5) = 0.5, rounds it to two decimal places, and push it into discounted array. Therefore, according to the description above, the function will return [50, 100, 150].

Question 5:

The code causes an error. The variable "i" is created in the for loop block with keyword "let", which means it can only be accessed in the block. Since line 12 is outside the block, it has no access to the variable "i". Therefore, the code causes an error.

Question 6:

The code causes an error. The variable "discountedPrice" is created in the for loop block with keyword "let", which means it can only be accessed in the block. Since line 13 is outside the block, it has no access to the variable "discountedPrice". Therefore, the code causes an error.

Question 7:

Line 14 will print "150". The functions takes prices [100, 200, 300] and discount 0.5 as input. The last element in prices is 300, so in the last iteration of the for loop, the variable "finalPrice" is assigned with value 150. Since the variable "finalPrice" is declared with "let" keyword, line 14 has access to "finalPrice" and therefore will print "150".

Question 8:

The function will return [50, 100, 150]. The functions takes prices [100, 200, 300] and discount 0.5 as input. For each price in prices, the function multiplies it by (1 - discount) = (1 - 0.5) = 0.5, rounds it to two decimal places, and push it into discounted array. Therefore, according to the description above, the function will return [50, 100, 150].

Question 9:

The code causes an error. The variable "i" is created in the for loop block with keyword "let", which means it can only be accessed in the block. Since line 12 is outside the block, it has no access to the variable "i". Therefore, the code causes an error.

Question 10:

Line 12 will print "3". The functions takes prices [100, 200, 300] and discount 0.5 as input. There are 3 elements in prices, so the length of prices is 3. Since the variable "length"  is declared with "const" keyword and assigned with value "prices.length", the value of the variable "length" is 3. line 12 has access to the variable "length" and therefore will print "3".

Question 11:

The function will return [50, 100, 150]. The function returns the variable "discounted". Although the variable "discounted" is declared with keyword "const" and assigned with value [], its elements can be updated or removed. Therefore, the function will return [50, 100, 150].

Question 12:

A. alert(student.name);

B. alert(student["Grad Year"]);

C. student.greeting();

D. alert(student['Favorite Teacher'].name);

E. alert(student.courseLoad[0]);

Question 13:

A. '3' + 2 = '32'

2 is converted to a string and the addition operator combines '3' and '2' to get '32'.

B. '3' - 2 = 1

'3' is converted to number 3 and the subtraction operator deducts 2 from 3 to get 1.

C. 3 + null = 3

null is converted to number 0 and the addition operator adds 3 to 0 to get 3.

D. '3' + null = '3null'

null is converted to a string and the addition operator combines '3' and 'null' to get '3null'.

E. true + 3 = 4

true is converted to number 1 and the addition operator adds 1 to 3 to get 4.

F. false + null = 0

false is converted to number 0 and null is converted to number 0. The addition operator adds 0 to 0 to get 0.

G. '3' + undefined = '3undefined'

undefined is converted to a string and the addition operator combines '3' and 'undefined' to get '3undefined'.

H. '3' - undefined = NaN

'3' is converted to number 3 and undefined is converted to NaN in numeric conversion. The subtraction operator deducts NaN from 3 to get NaN. 

Question 14:

A. '2' > 1: true

'2' is converted to number 2, which is greater than 1. Therefore, the comparison returns true.

B. '2' < '12': false

In dictionary order, the first letter of '2' is greater than the first letter of '12'. Therefore, the comparison returns false.

C. 2 == '2': true

'2' is converted to number 2, which is equal to 2. Therefore, the comparison returns true.

D. 2 === '2': false

The strict euqality operator === checks the equality without type converstion. In this case, 2 is not equal to '2' because their types are different. Therefore, the comparison returns false.

E. true == 2: false

true is converted to number 1, which is smaller than 2. Therefore, the comparison returns false.

F. true === Boolean(2): true

Boolean(2) returns true, which is strictly equal to true. Therefore, the comparison returns true.

Question 15:

When using == to compare values of different types, Javascript will turn both sides into numbers and then compare them. When using === to compare values of different types, Javascript will compare them directly without type converstion and will return false because the types of the values are different.

Question 17:

The result is the function "modifyArray" will return an array [2, 4, 6]. The function "modifyArray" takes an array [1, 2, 3] and a function "doSomething" as input. The function "modifyArray" takes each element in the input arrat as the parameter of the function "doSomething" and pushes the return values of the function "doSomething" to an array "NewArr". Then the function "modifyArray" will return the array "NewArr", whose value is [2, 4, 6] in this case.

Question 19:

1

4

3

2
