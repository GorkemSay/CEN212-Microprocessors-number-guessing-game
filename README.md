# CEN212 Microprocessors Number Guessing Game
## Main Goal
In this game, the user will try to find a number randomly selected by the computer between one and ninety-nine. The randomly selected number will be compared with the number entered by the user. If the number entered by the user is low, the program will say that the number entered is lower. If the number entered by the user is greater, the program will say that the number entered is higher. This process will continue until the user guesses the number correctly. If the user guesses the number correctly, the program will tell the user that your guess is correct.

### Algorithm
In this program, we need two integer variables for random generated number and user's number. We need to compara theese two values and return a message for user. The code has a data part, a starting part and a loop part. In addition, there are 4 result labels, depending on the result that will be returned after comparing the numbers received from the user.

#### Data section
1. Declare a variable that store number received from user.
2. Welcoming message and other result messages.

#### Start label
1. Generate a random number and convert to ASCII code.

#### Loop label
1. Read user's input.
2. Check the digits.
3. Compare the user's input and random number.

#### Low, high, correct and other labels
1. If the number is low, go to low label.
2. If the number is high, go to high label.
3. If the number is correct, go to correct label.
4. If the number out of range, go to input_out_of_range label.
5. Print the result and exit.

#### Screenshot of the program
<a href="https://ibb.co/NmgQDLP"><img src="https://i.ibb.co/xfKP9M0/Whats-App-Image-2024-04-09-at-23-13-28.jpg" alt="Whats-App-Image-2024-04-09-at-23-13-28" border="0"></a>
