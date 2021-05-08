# Tests in python
Unit tests are some pieces of code to exercise the input, the output and the behavior of your code. 

Test syntax :
`Def test_name():`
    `actual =< actual_output>`
    `expected = < expected _output>`
    `assert expected == actual`



The name of the test should describe the test and the expected results .

The test file name should follow the same name of module name  , for example :
File.py  the test unit name : test_file.py

separating the tests folder from production code is good practice

The steps of create test unit :
Arrange, Act and Assert (AAA) :
Arrange: you need to organize the data needed to execute that piece of code (input);
Act: here you will execute the code being tested (exercise the behaviour);
Assert: after executing the code, you will check if the result (output) is the same as you were expecting.


The cycle is made by three steps:
Write a unit test and make it fail
Write the feature and make the test pass
Refactor the code to improve the performance

Test-driven development (TDD) :
The aim of this method is to create tests before writing the code and then validate the code

The tests save your time !
Maybe you will spend some time in writing units of test but you will encounter fewer pugs

Test-driven development (TDD) :
The aim of this method is to create tests before writing the code and then validate the code

The tests save your time !
Maybe you will spend some time in writing units of test but you will encounter fewer pugs

**Recursion**
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function.  (Like for loop)

Example on Recursion that fin out the sum of numbers from zero until num , The function will repeat itself until the base case 
`def sum (num):`
    `if (num > 0 ):` 
       `num = num + sum(num-1)`
        `return num` 
   `else:` 
`return 0`


If the base case is not reached or not defined, then the stack overflow problem may arise  (infinity loop)

 direct recursion : the function calls itself directly 


indirect recursion : the function calls another function and the second function call first function agane 

