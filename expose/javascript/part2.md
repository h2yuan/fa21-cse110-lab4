1. it will output 3: since var can be reached out of the block & i++ will do three times after running the for loop, which is 0 + 1 + 1 + 1 = 3
2. it will output 150: car can be reached out of the block & for the last time assign value to discountedPrice is 300 * (1 - 0.5) = 150
3. it will output 150: car can be reached out of the block & for the last time assign value to discountedPrice is 300 * (1 - 0.5) = 150. Since it's already integer, Math.round will not make any change to it so will also be 150.
4. it will return the list [ 50, 100, 150 ], which is the list of prices after discount. The for loop runs 3 times and each time it will calculated the discounted price of one of the original prices and push to the new list 'discounted'. It is "return" and will not show on the screen since not call console.log or others to print out.
5. it will cause an error: since let cannot be reached out of the for loop(the block), then it is not defined in line 12.
6. it will cause an error: since let cannot be reached out of the for loop(the block), then it is not defined in line 13.
7. it will output 150: since let finalPrice is defined in line 4, so it can be reached in the discountPrices function. Thus, it is defined and can be output normally in line 14.
8. it will return the list [ 50, 100, 150 ], which is the list of prices after discount. The for loop runs 3 times and each time it will calculated the discounted price of one of the original prices and push to the new list 'discounted'. It is "return" and will not show on the screen since not call console.log or others to print out.
9. it will cause an error: since let cannot be reached out of the for loop(the block), then it is not defined in line 11.
10. it will output 3: since const length is defined in the function discountPrices, then it can be reached in line 12. Thus, it will just print out the lengh of prices list which is 3.
11. it will return the list [ 50, 100, 150 ], which is the list of prices after discount. The for loop runs 3 times and each time it will calculated the discounted price of one of the original prices and push to the new list 'discounted'. It is "return" and will not show on the screen since not call console.log or others to print out.
12. * A. student.name
    * B. student['Grad year']
    * C. student.greeting()
    * D. student['Favorite Teacher'].name
    * E. student.courseLoad[0]
13. * A. 32, since 2 will be automatically switch to String type.
    * B. 1, since it automatically switch '3' to number
    * C. 3, null will switch to 0
    * D. 3null, null will switch to String type
    * E. 4, true will switch to number 1
    * F. 0, both false and null become to 0
    * G. 3undefined, undefined will be switched to String type
    * H. NaN, both '3' and undefined will switch to number because of -, but undefined can only be switched to NaN. Thus, result is NaN.
14. * A. true. '2' will switch to number 2, since 2 > 1, it is true.
    * B. false. char '2' is greater than the first char '1' of '12'.
    * C. true. '2' will convert to 2, 2 == 2, then true.
    * D. false. === checks the equality without type conversion. Different types result in false.
    * E. false. true becomes 1, which does not equal to 2.
    * F. true. values that not intuitively "empty" becomes true, which functions to 2. Thus, true === true will no doubt results in true.
15. == will checks the equality with type conversion, but === checks the equality without type conversion.
16. 