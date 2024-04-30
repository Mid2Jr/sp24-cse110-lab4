1. Line 12 prints out 2 because i=2 after the for loop finishes
2. Line 13 should print out an array "[50, 100, 150]", because the function goes through the array and multiply each variable in the array by 1 - 0.5, and then round the value to its hundredth place, then pushes it into discount array.
3. At line 14, "150" should be printed, this is because finalprice is last set to 150 in the for loop. 
4. The function should return an array [50, 100, 150], as discounted has such values at the end of the function.
5. An error will occur, this is because i is declared as a let in the for loop, so outside that scope, i is not defined. And line 12 is outside of the scope
6. An error will occur, this is because discountedPrice is also a let declared in the for loop, and line 13 is outside of its scope. So discountedPrice will not be found
7. The final price 150 will be printed, this is because finalPrice is declared in the function scope, and line 14 is inside of the same scope.
8. The function discountedPrice will return array [50, 100, 150] Because none of the variables declared in the for loop is used outside the for loop scope. And all let variables declared inside the function is used in the function's scope, so the code runs normally.
9. An error will orrur, this is because i is a let declared inside the for loop's scope, so it cannot be called outside the for loop. So line 11 will cause an error.
10. Line 12 will just print out 3, because the length of the prices array is 3, and const length is used in the right scope.
11. The function will return an array of [50, 100, 150], this is because that although discounted is const, it is an array, and although it cannot be redeclared, but the array can be modeled, so no error will occur.
12. 
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. 
    a. '32', because '3' is a string and 2 maps to '2', so '3' + '2' is '32'
    b. 1, because string '3' cannot minus 2, and '3' maps to 3, so 3-2 = 1
    c. 3 is an interger, and null maps to 0, so 3+null = 3
    d. '3' is a string, null maps to 'null', so '3'+null = '3null'
    e. 4, because true map to 1, so 1+4 = 4
    f. 0, false maps to 0 and null maps to 0, so false + null = 0
    g. '3undefined', undefined maps to 'undefined', so '3' + undefined is '3undefined'
    h. NaN, because undefined cannot be mapped to a number, and strings cannot be subtracted, so NaN is the output
14. 
    a. true, because '2' maps to 2, and 2>1 is true
    b. false, because the string '2' is greater than '12' in lexicographical order
    c. true, because '2' maps to 2, so 2 == '2'
    d. false, because without conversion 2 != '2'
    e. false, because true maps to 1, and 1 != 2
    f. true, because Boolean(2) = true, so true === Boolean(2)
15. == compares with type conversion, and === compares without type conversion
17. [2, 4, 6], the function first creates a const called newArr, and then gets the first element of the array, 1, and runs doSomething on it, which times it by 2. 1 Becomes 2, and gets pushed into newArr. The same thing is done to 2 and 3, getting 4 and 6.
19. 1432, this is because 1 and 4 are printed first due to no delay, and then 3 with the least delay and 2 with delay of 1 second.