1. Line 12 will print 3 because since i is a ```var``` variable, is has a 
function scope which means is can be accessed anywhere in the function. So,
since line 12 is in the function, it prints the value of i. The reason why i 
is equal to 3 is because it went through the for loop and incremented by +1,
3 times until i == prices.length which was 3 in this case.
2. It will print 150 because discountedPrice is a ```var``` variable, so it has
a function scope and the last thing that discountedPrice was reassigned to
before line 13 was 150 (since 300 with a discount of 50% is 150).
3. It will print 150 because finalPrice is a ```var``` variable, so it has a
function scope and the last thing that finalPrice was reassigned to before
line 13 was 150.
4. The function will return [50, 100, 150] because this is what ```discounted```
is equal to after the applying the discount to all of the prices. Also, it's 
because ```discounted``` is a ```var``` variable which has a function scope
which allowed ```discounted``` tp be updated appropriately as the forloop was 
applying the discounts.
5. The code causes an error because ```i``` is not defined. Since ```i``` is a 
```let``` variable defined in the forloop, it's scope is limited to the forloop.
In this case, line 12 is outside the forloop, thus the error.
6. The code causes an error because ```discountedPrice``` is a ```let```
variable with a blocked scope and since it was defined in the forloop, it only
exists in the forloop. Line 13, which calls ```discountedPrice``` is outside
the forloop, thus the error.
7. Line 14 prints 150 because ```finalPrice``` is a ```let``` variable that was
created inside the function, so that means is has the scope of the entire
function. Because of that, line 14 will print the last value of ```finalPrice```
as it's gone through the forloop.
8. The function will return [ 50, 100, 150] because ```discounted``` is a ```let```
variable that was defined in the function thus it has the score of the function.
And, what this function does is apply the given discount to all the given prices
and adds those prices into ```discounted```.
9. The code causes an error because ```i``` is not defined. This is because ```i```
is a ```let``` variable defined in the forloop, so it's scope is limited to that
forloop. Since line 11 is outside of that scope, the code causes an error.
10. Line 12 prints 3 because ```length``` is a ```let``` variable that was 
assigned in the function, so it has the scope of the entire function. Since line
12 is within the scope of ```length```, it doesn't throw an error. 3 is printed
because that's the length of the list ```prices```.
11. This function will return [50, 100, 150] because ```discounted``` was 
defined in the scope of the function and the return statement on line 14 is
within the scope of the function. The values are the discounts being applied to
all the prices.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0];
13. A. '32' since integers map to the exact string representation
    B. 1 because `3` maps to it's integer representation 3
    C. 3 since ```null``` has no value so 3 remains unchanged
    D. '3null' since  '3' is a string so null is converted to 'null' string
    E. 4 because true maps to 1 and 1 + 3 = 4
    F. 0 since false maps to 0 and null has no value so it's equal to 0
    G. '3undefined' because 3 is a string so undefined maps to 'undefined'
    string, then they are concatenated
    H. NaN because undefined maps to NaN for numeric conversion
14. A. true because '2' maps to 2 which is greater than 1
    B. false since 2 is greater than the first char of the '12' which is '1'
    C. true because '2' maps to 2 and 2 is equal to 2
    D. false since 2 is a integer and '2' is a string
    E. false beccause true maps to 1 and 1 is not equal to 2
    F. true because Boolean(2) is true and they are both boolean types
15. == is true when the value on each side is equal and false otherwise.
=== us true when the value and type on each side is equal, otherwise false.
17. The result will be an array of [2, 4, 6]. Function doSomething(num) returns num*2. The function modifyArray(array, callback) loops through each element of the array and calls the function in the callback parameter which in this case is doSomething. Therefore, if the function modifyArray([1, 2, 3], doSomething) is called, it will loop through each element of the given array which is [1, 2, 3] and multiply each number with 2 which gives us an array of [2, 4, 6].
19. 1 4 3 2