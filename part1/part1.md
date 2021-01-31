1. Line 11 prints i because it is defined in the for loop.
2. Line 12 prints discountedPrice, which is defined in the for loop.
3. Line 13 prints finalPrice.
4. Calling discountPrices([100, 200, 300], .5) will return [50, 100, 150] because that is each of the prices discounted by the discount and rounded. 
5. Line 11 produces an error because i is only defined in the for loop.
6. Line 12 produces another error because discountedPrice is only defined in the for loop.
7. Line 13 prints 0 because using "let" doesn't allow its value to be updated.
8. Calling discountPrices([100, 200, 300], .5) will return [50, 50, 50] because discountedPrice can't be updated after it's defined as the first discounted price.
9. Line 11 produces an error because i is only defined in the for loop.
10. Line 12 prints discountedPrice, which is prices[0] * (1 - discount) because it is const.
11. Line 13 prints 0 because finalPrice is defined with const, so it can't be updated by the for loop.
12. Calling discountPrices[(100, 200, 300), .5] will return [0, 0, 0].
13. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
14. 
    A. '32', because '3' is a string so using '+' concatenates '3' and 2 (as a string) together.
    B. 1, because you can't remove 2 from the string '3' so you have to do it as a number.
    C. 3, because null is nothing so 3 doesn't change.
    D. '3null' because '3' is a string, so '+' is used to concatenate 'null' with '3'.
    E. 4, because true can also be represented as 1.
    F. 0, because false and null are both representable as 0.
    G. "3undefined", because "3" is a string, so "+" is used to concatenate.
    H. NaN, because it doesn't know what to subtract from 3, since it's undefined.
15. 
    A. true, because '2' as a number is greater than 1.
    B. false, because as strings, '12' has a greater ASCII value than just '2'.
    C. true, because type conversion makes them equal.
    D. false, because without type conversion they are different types, and thus not equal.
    E. false, because true has a numerical value of 1.
    F. true, because 2 as a Boolean value is true since it's not 0.
16. Using === checks equality without using type conversion, while == may try to convert a value to a different type and then check equality. 
17. It prints 'Goodbye' because 2 != true; if (2) checks the same thing, so they both evaluate to false, so it prints 'Goodbye'.
18. see file
19. It returns [6, 8, 10]. The for loop calls doSomething(array[i], function(x)), where function(x) returns x * 2. doSomething returns function(array[i]+2), so it returns 2 * (array[i] + 2). 
20. see file
21. It prints 3, 2 and 4 in that order. 