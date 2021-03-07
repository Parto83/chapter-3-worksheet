# chapter 3 worksheet
1. What is missing from this code?     
    temperature = float(input("Temperature: ")
    if temperature > 90:
        print("It is hot outside.")
    else:
        print("It is not hot out.")
     The second parenthesis after temperature on the first line
 
 2. Write a Python program that will take in a number from the user and print
    if it is positive, negative, or zero. Use a proper if/elif/else chain, don't
    just use three if statements.

    	number = int(input("Enter a number: "))
if number > 0:
    print("Your number is positive")
elif number = 0:
    print("Your number is zero")
elif number < 0:
    print("Your number is negative")

 3. Write a Python program that will take in a number from a user and print
    out ``Success'' if it is greater than -10 and less than 10, inclusive. (1 pt)

number = int(input("Enter a number: "))
if number < 10 and number > -10:
    print("Success")

 4. This runs, but there is something wrong. What is it? (1 pt)
     
    user_input = input("A cherry is a: ")
    print("A. Dessert topping")
    print("B. Desert topping")
    if user_input.upper() == "A":
        print("Correct!")
    else:
        print("Incorrect.")
The options will only print out after an input is given
     
 5. There are two things wrong with this code that tests if x is set to a
    positive value. One prevents it from running, and the other is subtle.
    Make sure the if statement works no matter what x is set to.
    Identify both issues. (2 pts)
     
    x == 4
    if x >= 0:
        print("x is positive.")
    else:
        print("x is not positive.")

The first thing wrong is that x is not defined. The second thing is that it uses “==” to assign the value of 4 to x when it should just read x = 4.
     
 6. What three things are wrong with the following code? (3 pts)
     
    x = input("Enter a number: ")
    if x = 3
        print("You entered 3")
  
The first mistake is that the int function should go in front of the input function to convert the input into an integer. The second mistake is that the if statement should use 2 equal signs otherwise is saying to assign x to a value of 3. The third mistake is that there should be a colon after the if statement.
   
 7. There are four things wrong with this code. Identify all four issues. (4 pts)
     
    answer = input("What is the name of Dr. Bunsen Honeydew's assistant? ")
    if a = "Beaker":
        print("Correct!")
        else
        print("Incorrect! It is Beaker.")

The first mistake is that the first if statement should have two equal signs instead of one. The second mistake is that there should be a colon after the else statement. The third mistake is that the else statement should not be imbedded into the if statement. The fourth statement is that the if statement is checking to see if a is equal to beaker when there is no a variable.
     
 8. This program doesn't work correctly. What is wrong? (1 pt)
     
    x = input("How are you today?")
    if x == "Happy" or "Glad":
        print("That is good to hear!")

This program prints “That is good to hear!” no matter what the user inputs. To fix this the if statment should read “ if x == “Happy” or x == “Glad”:”.
     
 9. Look at the code below. Write your best guess here on what it will print.
    Next, run the code and see if you are correct.
    Clearly label your guess and the actual answer.
    Also, if this or any other example results in an error, make sure to
    state that an error occurred.
    While you don't need to write an explanation, make sure you understand
    why the computer prints what it does. Don't get caught flat-footed when
    you need to know later. (2 pts)
     
    x = 5
    y = x == 6
    z = x == 5
    print("x=", x)
    print("y=", y)
    print("z=", z)
    if y:
        print("Fizz")
    if z:
        print("Buzz")

GUESS : nothing an error will occur
ACTUAL:
x = 5
y = False
z = True
Buzz

		
   
10. Look at the code below. Write you best guess on what it will print.
    Next, run the code and see if you are correct. (2 pts)
     
    x = 5
    y = 10
    z = 10
    print(x < y)
    print(y < z)
    print(x == 5)
    print(not x == 5)
    print(x != 5)
    print(not x != 5)
    print(x == "5")
    print(5 == x + 0.00000000001)
    print(x == 5 and y == 10)
    print(x == 5 and y == 5)
    print(x == 5 or y == 5)
     
GUESS : 
True
False
True
False
False
False
False
True
False
False

ACTUAL:
True
False
True
False
False
True
False
False
True
False
True

11. Look at the code below. Write you best guess on what it will print.
    Next, run the code and see if you are correct. (2 pts)
     
    print("3" == "3")
    print(" 3" == "3")
    print(3 < 4)
    print(3 < 10)
    print("3" < "4")
    print("3" < "10")
    print( (2 == 2) == "True" )
    print( (2 == 2) == True )
    print(3 < "3")
     
GUESS : 
True
True
True
True
False
False
True
True
False

ACTUAL: 
True
False
True
True
True
False
False
True
ERROR

12. What things are wrong with this section of code?
    The programmer wants to set the money variable according to
    the initial occupation the user selects. (1 pt)
     
    print("Welcome to Oregon Trail!")
 
    print("A. Banker")
    print("B. Carpenter")
    print("C. Farmer")
 
    user_input = input("What is your occupation? ")
 
    if user_input = A:
        money = 100
    else if user_input = B:
        money = 70
    else if user_input = C:
        money = 50
 
    print("Great! you will start the game with", money, "dollars.")

They didn't assign the occupations to a variable.

