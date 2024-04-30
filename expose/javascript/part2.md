1. It will print the value of i (which is 3) to the console when line 12 is executed because the loop increments i each iteration from 0 to prices.length - 1, and when the loop finishes, i will be equal to prices.length.
2. It will print 150. This variable is declared within the for loop in line 7, which makes it a block-scoped variable.
3. It will print 150. This variable is declared within the for loop in line 7, which makes it a block-scoped variable.
4. For the given input array [100, 200, 300] and a discount rate of 0.5, the function would return the array [50.00, 100.00, 150.00] because it applies a 50% discount to each price and rounds the result to two decimal places.
5. Since Line 12 is outside of the block scope of i, then i is not defined for Line 12, and will return an error.
6.  As discountedPrice is declared inside of the for loop by using let thus it is not defined outside of the for loop, so it will return an error.
7.  Return an error because finalPrice would throw an exception about it not being defined.
8.  Return the array of discounted prices that were calculated in the function which is [50,100,150]
9.  Return an error because the for loop is trying to change the value of a const variable.
10.  It prints out 3 because the length of the array of prices is 3 and is declared in the same block
11.  It returns [50, 100, 150]. Even though the variable is a const, you are still able to add to the array or change the elements so it does not cause an error.
12.  A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]
13. A. '3' + 2 = '32' because the the string concatenates
B. '3' - 2 = 1, 3 is treated as an int and subtracts
C. 3 + null = 3, null is treated as a 0
D. 3null, treats null as a string
E. 4, true treated as a 1
F. 0, both treated as a 0
G. 3undefined, undefined treated as a string and concatenates
H. NaN, '3' treated as an in and subtracting with an undefined number causes an Nan result
14. A. True, treats '2' as an int
B. False, compares the strings lexographically
C. True, treats '2' as an int
D. False, === checks if the two variables of the same type aswell
E. False, treats true as a 1
F. True, anything not 0 will be considered true when wrapped with a boolean
15. == is the loose equality operator, which allows for types to change in order to fit the comparison context naturally. === however, is strict, and does not allow for type coersion, and will return false for any two differing types.
