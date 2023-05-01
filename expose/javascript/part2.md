1. The number 3 will be outputted to console because i is a var.
2. The number 150 will be outputted to console because discountedPrice is a var.
3. The number 150 will be outputted to console because finalPrice is set to 150 after the for loop ends.
4. The function will return [50, 100, 150] because each price with its discount was pushed to the discounted array, which is a var.
5. There will be an error because the variable i is not defined in the scope.
6. There will be an error because the variable discountedPrice is not defined in the scope.
7. The number 150 will be outputted to console because finalPrice is set to 150 after the for loop ends.
8. The function will return [50, 100, 150] because each price with its discount was pushed to the discounted array, and it is defined within the scope of the return statement.
9. Error: i is not defined within the scope.
10. The number 3 will be outputted to console because length is a const value which represents the length of the prices array.
11. The function will return [50, 100, 150] because each price with its discount was pushed to the discounted array, and it is defined within the scope of the return statement. Even though the array is constant, we are still able to push values to it since this isn't considered reassignment.


A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]


13. Arithmetic
‘3’ + 2 -> 32, concatenates the numbers
‘3’ - 2 -> 1, substracts 2 from 3
3 + null -> 3, treats null as 0
‘3’ + null -> 3null, concatenates them together
true + 3 -> 4, true is 1
false + null -> 3, false is 0
'3' + undefined -> 3undefined, concatenates them together
'3' - undefined -> NaN, is undefined when subtracting

14. Comparison
‘2’ > 1 -> true, string 2 becomes the number 2
‘2’ < ‘12’ -> false, string 2 and string 12 convert to numbers
2 == ‘2’ -> true, string 2 converts to number, they are equal
2 === ‘2’ -> false, string 2 is not the same type as number 2 (strictly equal, must have same type)
true == 2 -> false, true is 1, not 2
true === Boolean(2) -> Boolean(2) represent the boolean value for 2, which is non-empty, non-zero

15. == checks for equality of the value, === checks for same type and equality, so === is basically a strict equality.
