1. 3, the length of the prices array will be logged because i was declared using var, so it is accessible outside of the scope of the for loop
2. 150, the discount of the last price in the prices array will be logged because discountedPrice was declared using var
3. 150, the final price of the last price in the prices array  will be logged since the finalPrice variable was declared using var
4. [50, 100, 150] the code will return an array of discounted prices given an array of prices and a flat discount. The code iterates over the prices array, applies the discount to each price, and stores the discount in the discount array. Once every price has had a discount applied and stored, the discount array is returned
5. this code will return error because i was declared with let and does not exist outside the scope of the loop
6. this code will return error because discountedPrice was declared with let and does not exist outside the scope of the loop
7. 150, the final price of the last price in the prices array  will be logged since though finalPrice was declared using let, it was declared in the same scope as line 14
8. [50, 100, 150] the code will return an array of discounted prices, since all of the variables have the scope necessary to function. The discount will be applied to every price in the prices array, saved in the discount array, and the discount array will be returned
9. there will be an error since i does not exist outside of the scope of the for loop, as it was declared with let
10. 3, the length of the prices array will be printed since it exists in the scope of the log
11. [50, 100, 150] the code will return an array of discounted prices since it iterates through the prices array and applied the discount, stores it in the discount array, and returns the discount array after applying the discount to every element in the prices array
12. a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. a. 32 - 2 maps to string representation
    b. 1 - 3 is converted to int
    c. 3 - null maps to 0
    d. 3null - null maps to string representation
    e. 4 - true maps to null
    f. 0 - both false and null map to 0
    g. 3undefined - undefined maps to string representation
    h. NaN - undefined dpes not map to a number
14. a. true - 2 becomes a number
    b. false - 2 is behind in lexicographical order
    c. true - 2 becomes a number
    d. false - different types
    e. false - true maps to 0
    f. true - with Boolean function, everything that has a values (ie is non zero, null, NaN, undefined, etc) is true
15. `==` checks values with type conversions, so values of different types can evaluate to true. `===` is the strict equality operator, and checks equality without a type conversion so there is less room for error and different types are always false
16. in js file
17. [2, 4, 6] is returned. The callback function is a function that can be called inside the `modifyArray` function since it is passed in. Since the callback function returns the value passed in times 2, and we pass in the values of the array, it returns double of each value in the array [1, 2, 3]. The returned value of the callback function is added into the `newArr` array, which is then returned
18. in js file
19. 1, 4, 3, 2