1. 3; this line prints out the value of i (+1 exceeding the loop condition) after being incremented by the for loop.
2. 150; this line prints our the current value of discountedPrice, which is most recently defined by the last iteration of for loop. This corresponds to discounted[3]*(1-0.5)=150.
3. 150; this line prints out the current value of finalPrice, which is most recently defined by the last iterfation of for loop. This correponds to Math.round(150*100)/100=150.
4. [50, 100, 150]; this is returned by line 19's call to the discountPrices, which returns an array where each element is discounted by the specified percentage.
5. Error, the i variable defined by let does not exist outside of the current scope. 
6. 150; the discountedPrice variable exists in the outermost scope and thus retains the value of its last alteration in the for loop (same as #2).
7. 150; the finalPrice variable exists in the outermost scope and this retains the value of its last alteration in the for loop (same as #3).
8. [50, 100, 150]; this is returned by line 19's call to the discountPrices, which returns an array where each element is discounted by the specified percentage.
9. Error, the i variable defined by let does not exist outside of the current scope. 
10. 3; line prints out the variable of length which was calculated in line 4 and remained unchanged.
11. [50, 100, 150]; this is returned by line 19's call to the discountPrices, which returns an array where each element is discounted by the specified percentage.The code works because discounted was not reassigned, length was unchanged, and discountedPrice was unchanged within each for loop iteration.
12. a) student.name
    b) student['Grad Year']
    c) student.greeting()
    d) student['Favorite Teacher'].name
    e) student.courseLoad[0]
13. a) '32', 2 concatonated to the string '3'
    b) 1, 3 converted to int for arithmetic of subtraction with 2
    c) 3, null treated as 0
    d) '3null', null treated as a string and concatonated to the string '3'
    e) 4, true converted to int of 1 and added to 3
    f) 0, false and null both converted to int of 0 and added together
    g) '3undefined', undefined treated as a string and concatonated to '3'
    h) NaN, arithmatic operation of subtraction attempted  on undefined which results in error.
14. a) true, '2' converted to int and compared with 1
    b) false, string comparison compares the first character of each side, thus '2' is greater than '12'
    c) true, type conversion of '2' to int 2
    d) false, === signifies same type 
    e) false, true == 1.
    f) true, both sides are same type and #>0 is for Boolean(#) is true.
15. == type converts and checks whereas === requires both sides to be of the same type.