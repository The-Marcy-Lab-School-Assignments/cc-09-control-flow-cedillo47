# Code Challenge: Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Create a function `betweenFiveAndTen` that takes in an integer, and if that integer is between 5 and 10, it will return true or false.
```
betweenFiveAndTen(5) //returns true
betweenFiveAndTen(15) //returns false 
```

2. Create a function `betweenTenAndThirty` that takes in an integer, and if that integer is between 10 and 30 it will return true or false.
 
 same idea as the last question, Except now we will change the range in the if statment. The statmenrt before the && will check to see if num is less than 10 and the statment after will check if num is less than 30. 
```

betweenTenAndThirty(10) //returns false
betweenTenAndThirty(15) //returns true
```

3. Create a function `betweenThirtyAndFifty` that takes in an integer, and if that integer is between 30 and 50 it will return true or false.
 Yet again the same idea as before. Thus time we will change the peramiter so that the argument before the && will check to see iof the number if less than 30 and the later statment will check if its less than 50. 
```
betweenThirtyAndFifty(30) //returns true
betweenThirtyAndFifty(55) //returns false
```

4. Create a function `betweenThirtyFiftySeventy` that takes in an integer, and if that integer is between 0 and 30 or between 50 and 70 it will return true or false.
 the same concept as before but now i will include the || that will check to see if the interger is between 0 and 30 and the next argument checks to see if the integer passed is between 50 - 70. 
```
betweenThirtyFiftySeventy(0) //returns true
betweenThirtyFiftySeventy(44) //returns false
betweenThirtyFiftySeventy(55) //returns true
betweenThirtyFiftySeventy(71) //returns false
```

5. Create a function `betweenTwentyFiftySixty` that takes in an integer, and if that integer is between 0 and 20 or between 50 and 60 it will return true or false.
 
same idea as before but now the the arguments will have the vlaue that interger is being compared to will chnage. in the first argument one we are checking to see if the interger is greater than or equal to 0, and that is is less than 20. in between the two peramiters we will place a || to check if either or afrgument is correct.  In the secound argument we are checking to see if the interger is greater than or equal to 50, and that is is less than or equal to 60.  
```
betweenTwentyFiftySixty(12) //returns true
betweenTwentyFiftySixty(44) //returns false
betweenTwentyFiftySixty(55) //returns true
betweenTwentyFiftySixty(61) //returns false
```

6. Create a function `betweenTenTwentyThirty` that takes in an  integer, and if that integer is between 0 and 10 or between 20 and 30 it will return true or false

    same idea as before but now the the arguments will have the vlaue that interger is being compared to will chnage. in the first argument one we are checking to see if the interger is greater than or equal to 0, and that is is less than 10. in between the two peramiters we will place a || to check if either or afrgument is correct.  In the secound argument we are checking to see if the interger is greater than or equal to 20, and that is is less than or equal to 30.
```
betweenTenTwentyThirty(0) //returns true
betweenTenTwentyThirty(9) //returns true
betweenTenTwentyThirty(22) //returns true
betweenTenTwentyThirty(31) //returns false
```
