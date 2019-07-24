This readme provides details about the REST api to compute and return the sum of numbers.
Currently , the input is hardcoded to range(1000000).

The code is organized in following directory structure - 
SampleApp
	==> DLGApp
		==> templates --> home.html
		==> tests --> test_myApp.py
		__init__.py
 		myApp.py

myApp.py : this is the main program, developed using flask framework with endpoint /total calling print_total() function.
print_total() provides the total for given input range, currently hardcoded to range(10000001)

templates/home.html : is the main landing page of the application, and is used to demonstrate use of html pages if required.

tests/test_myApp.py : is the test pack with following 3 test cases
1) test_sum - test function to confirm sum function works on list and resuts are as expected.
2) test_print_total_positive - test to assert/confirm that the total of input is as expected.
3) test_print_total_negative - negative test case to confirm that actual sum of input seqence is not as expected.

Please note : Ideally, I would prefer packaging this code as distribution using setuptools , but since I dont have the setup and IDE on my local machine, I developed and tested the code in restricted environment which cannot be accessed from outside. Therefore, I had to type the code in notepad and send across. However this code has been tested and works as expected.

