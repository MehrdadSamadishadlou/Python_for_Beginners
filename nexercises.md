---
title: Exercises
layout: template
filename: nexercises
--- 

> **IMPORTANT**  
> Large language models like ChatGPT can be highly useful, but relying on them to solve exercises can significantly hinder your learning process. Therefore, please refrain from using them to directly solve exercises. Instead, try to solve the exercises on your own first. Once you have attempted to solve them, you can ask the models for their solutions and compare them to your own. This way, you can identify areas where they wrote better codes and learn from them.


# 1. First Session

1. What is the output of each line of code? 

      ```
      4 ** 3
      42 // 12
      17 % 6
      print('b'*2 + 'a'*1 + 'c'*3 )
      ```

2. What would the following code print?

      ```
      x = 5
      x = x + 1
      x = 5 * 2
      x * 3
      print( x )
      ```

3. Write a program that utilizes the input function to ask the user for their name, then deliver a personalized welcome message as follows.

      ```
      Enter your name: Mehrdad
      Hello Mehrdad
      ```

4. Write a program that uses the input function to ask the user for the number of hours he/she worked and the hourly payment, and then calculate the gross pay based on this information.

      ```
      Work Hours: 32
      Hourly payment: 100000
      Pay: 3200000
      ```
5. If we are sure that the variable 'num' is a two-digit number, which line of code would cause the output to be the reverse of the value of 'num'? (For example, if 'var' equals 23, the output would be 32.)

      a. `print( str(var // 10) + str(var % 10) )`
      
      b. `print( str(var % 10) + str(var // 10) )`
      
      c.`print( str(var / 10) + str(var % 10) )` 
      
      d.`print( str(var % 10) + str(var / 10) )`


# 2. Second Session

1. Write a program that takes an input number and outputs the next multiple of 10 that is greater than the given number. For instance, if the input is 11, the program should print 20. If the input is 40, it should print 50.

2. Write a program that takes two input numbers and prints the larger number as the output. The first line of input should contain the first number, while the second line should contain the second number. The input numbers are guaranteed to be positive integers. If the two input numbers are equal, you can print either one of them.

3. Write a program that prompts the user to enter their age and prints their corresponding age group.

      - If the age is between zero and six (exclusive), the program should output "preschooler".
      - If the age is between six (inclusive) and ten (exclusive), the program should output "child".
      - If the age is between ten (inclusive) and fourteen (exclusive), the program should output "adolescent".
      - If the age is between fourteen (inclusive) and twenty-four (exclusive), the program should output "youth".
      - If the age is between twenty-four (inclusive) and forty (exclusive), the program should output "adult".
      - If the age is forty or above, the program should output "middle-aged".

4. Write a program that prompts the user to enter three numbers: A, B, and C. If A is even or both B and C are even, the program should print "good". Otherwise, it should print "bad". Try to achieve this using the OR and AND operators.

5. Write a program that prompts the user to enter four numbers and prints the maximum value among them.

6. Write a program that assists consumers in deciding whether to consume a food product based on the colors of the health guide labels. If a product meets the following conditions, print the message "Do not consume." Otherwise, print the message "Safe to consume":
      - It has at least three red labels.
      - It has at least two red labels and at least two yellow labels.
      - All labels are either yellow or red (meaning we don't have any green labels!).      

      <p align="center">
        <img id="Hist" src="https://github.com/MehrdadSamadishadlou/Python_for_Beginners/assets/95024166/114a81c4-2d80-4f6f-9d65-982f3fbf635f" width="300" />
      </p>


# 3. Third Session

> **IMPORTANT**  
> The purpose of the exercises that require you to determine the output of a code is to encourage you to execute the code in your mind rather than relying on the Python interpreter.

1. What will the following Python program print out?

      ```
      def print_double(x):
      print(2 * x)


      print_double(3)
      ```

2. What will the following Python program print out?

      ```
      def shout(word):
            return word + "!"

      
      speak = shout
      output = speak("shout")
      print(output)
      ```

 3. What will the following Python program print out?

      ```
      def add(x, y):
            return x + y

 
      def do_twice(func, x, y):
            return func(func(x, y), func(x, y))


      a = 5
      b = 10

      print(do_twice(add, a, b))
      ```
     
4. Write a program that converts a student's numerical score into a corresponding letter grade (A-F) according to the following table.

      ```
       Score   Grade
      >= 18     A
      >= 16     B
      >= 14     C
      >= 12     D
       < 12     F
      ```

# 4. Fourth Session

1. Please write a program that takes a positive number as input and determines whether it is a prime number or not.
   
   Definition of a prime number: It is only divisible by 1 and itself, with no other divisors. For example, 7 is a prime number because it    can only be divided by 1 and 7. However, 6 is not a prime number because it can be divided by 1, 2, 3, and 6.

   If the number is prime, output the word "prime." If the number is not prime, output the phrase "not prime."

   example input:
   ```
   32
   ```
   
   example output:  
   ```
   not prime
   ```

2. In this program, input the score achieved by Sepidrood Rasht team in the matches of the Premier League and print the total score of Sepidrood Rasht along with the number of victories they have obtained this season. Sepidrood plays 10 games in the Premier League, so the scores of this team will be provided to you in 10 lines. For each game, Sepidrood can gain zero, one, or three points. A loss corresponds to zero points, a draw corresponds to one point, and a win corresponds to three points.

   example input:
   ```
   1
   0
   3
   1
   1
   3
   0
   0
   3
   1
   ```

   example input:
   ```
   3 13
   ```
