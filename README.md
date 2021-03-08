# chapter 3 worksheet
1. What is missing from this code?     
    temperature = float(input("Temperature: ")
    if temperature > 90:
        print("It is hot outside.")
    else:
        print("It is not hot out.")
     add another parenthesis after temperature: temperature = float(input("Temperature: "))
 
 2. Write a Python program that will take in a number from the user and print
    if it is positive, negative, or zero. Use a proper if/elif/else chain, don't
    just use three if statements.

num = int(input("Enter a number: "))
if num > 0:
   print("Positive number")
elif num == 0:
   print("Zero")
else:
   print("Negative number")

 3. Write a Python program that will take in a number from a user and print
    out ``Success'' if it is greater than -10 and less than 10, inclusive. (1 pt)

num = int(input("Enter a number: "))
if num < 10 and num > -10:
    print("Success")

 4. This runs, but there is something wrong. What is it? (1 pt)
     
    user_input = input("A cherry is a: ")
    print("A. Dessert topping")
    print("B. Desert topping")
    if user_input.upper() == "A":
        print("Correct!")
   else:
        print("Incorrect.")
This program prints the options only after an input is given.
     
 5. There are two things wrong with this code that tests if x is set to a
    positive value. One prevents it from running, and the other is subtle.
    Make sure the if statement works no matter what x is set to.
    Identify both issues. (2 pts)
     
    x == 4
    if x >= 0:
        print("x is positive.")
    else:
        print("x is not positive.")

first, instead of two equal signs ("==") we need only one ("="). Second, x is not defined. 
     
 6. What three things are wrong with the following code? (3 pts)
     
    x = input("Enter a number: ")
    if x = 3
        print("You entered 3")
  
The first mistake: it needs to have a colon after the if statement. Second, it needs two equal signs ("=="), in other words x== 3. The third one is that it needs int fundtion: x = int(input("Enter a number: ")) 
   
 7. There are four things wrong with this code. Identify all four issues. (4 pts)
     
    answer = input("What is the name of Dr. Bunsen Honeydew's assistant? ")
    if a = "Beaker":
        print("Correct!")
        else
        print("Incorrect! It is Beaker.")

first mistake: a is not defined, a has to be replaced with answer. Second mistake, if statement needs two equal signs ("=="). in oder words, if answer == "Beaker":
Third mistake: after else statement, we need colon. Forth mistake: else statement has indentation error.
     
 8. This program doesn't work correctly. What is wrong? (1 pt)
     
    x = input("How are you today?")
    if x == "Happy" or "Glad":
        print("That is good to hear!")

Regardless of the input, This program prints “That is good to hear!”. Even when you answer for instance " I am bad today", it prints: that is good to hear.
     
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

GUESS : x=5
y=Fizz
z = Buzz

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
True

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
False
True
True
False
False
False
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

The occupations are not assigned to variables.

