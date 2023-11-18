# CAP3_Test_Cases
Unit Test Case - description 

This set of unit tests is designed to assess the functionality of two classes ('Apple' and 'Basket') and their associated methods within a Pygame-based game. 
Below is a description of each test case:

# test_apple_update
This test case evaluates the 'update' method of the 'Apple' class. It does the following:
1. Setup: Creates an instance of the 'Apple' class.
2. Action: Retrieves the initial y-coordinate of the apple's rectangle.
3. Assertion: Calls the 'update' method and checks whether the y-coordinate of the apple's rectangle has increased by 4, as expected.

# test_basket_update
This test case assesses the 'update' method of the 'Basket' class. The steps are as follows:
1. Setup: Instantiates a 'Basket' object.
2. Action: Retrieves the initial x-coordinate of the basket's rectangle.
3. Assertion: Calls the 'update' method and verifies that the x-coordinate of the basket's rectangle remains unchanged, as expected.

# test_apple_reset_position
This test evaluates the functionality of resetting the apple's position in the 'Apple' class. The procedure includes:
1. Setup: Creates an instance of the 'Apple' class and sets the y-coordinate of its rectangle to 350.
2. Action: Calls the 'update' method to trigger the reset of the apple's position.
3. Assertion: Checks whether the y-coordinate of the apple's rectangle has been correctly reset to 0.

These unit tests help ensure that the core functionalities of the game, specifically the movement of the apple and the reset of its position, are working as intended. 
The tests are written using the 'unittest' framework, and they serve as a means to validate the expected behavior of the game logic in these specific scenarios.

# references
1. https://www.youtube.com/watch?v=JJ9zZ8cyaEk
2. https://www.youtube.com/watch?si=S12ryN5bv1VyYxj_&fbclid=IwAR3EglZae-
QalhJKiVTTNoNgAC8r1--dlFEw5jJbwKqri_zDAtKsu1WZ4tU&v=v1MtwCPTmB
I&feature=youtu.be
3. https://www.youtube.com/watch?si=8V9ULoW1nwVc8gxe&fbclid=IwAR2PbuO
p4PcRZH58C3yKuEWHB7Jm-NF-O4_I5IxBTolhVNIAqXLnNLJorM8&v=96mDQ
rlceEk&feature=youtu.be
4. https://www.youtube.com/watch?v=mzlH8lp4ISA
5. https://docs.python.org/3/library/unittest.html
6. https://www.dataquest.io/blog/unit-tests-python/
7. https://www.pythontutorial.net/python-unit-testing/

