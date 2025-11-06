------------------------------------------------------------------------
Super Calculator
Author: Hacker T. Largebrain
------------------------------------------------------------------------

This program implements a highly efficient calculating engine for
a pocket calculator. It includes a complete test rig to demonstrate
that the engine works as it should.

Lab III

22.
Testing the addition operation.
The result is: 7
Testing the subtraction operation.
The result is: 5
All tests passed.

The results are correct as the addition operation is 3+4 and the substraction operation is 9-4. 
So yes, all tests have indeed passed.

23. Calling testPlus() would normally return 7 because the 
operation is 3+4. However, if I call testPlus() AFTER calling testPlus(), then it returns 1, an 
error. It should return 7 too because 3 and 4 are hard-coded into the method.

24. Repeating the same thing for testMinus() also produces an error. Instead of returning 5, it 
returns -13 AFTER calling testAll(). testMinus() should return 5 too because 9 and 4 are 
hard-coded into the method.

25. Whenever I call testAll(), that method seems to affect the result of both testPlus() and 
testMinus(). Doing some back-and-forth calling can make both tests return the correct answer.