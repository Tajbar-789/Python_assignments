Assignment Part-1


Q1. Why do we call Python as a general purpose and high-level programming language?

ans - Python is a general purpose programming language because it cane be used for multiple type of developments and differnt domains . Its called high level languange because the logic building in python does not requires one to know binary or assembly languages .

Q2. Why is Python called a dynamically typed language?

ans -Python is dynamically typed language because python interpreter is capable of identifying the data type of variable at run time and the programmer need to decalre the data type of variables .

Q3. List some pros and cons of Python programming language?

ans - pros of python 1. It is easy to use . 2. It is dynamically typed so the programmers needs not to worry about declartion of varible data type. 3. It provides support in terms of different libraries and frameworks that are used in web develeopment ,data domain etc.

cons of python 
1. It is comparitively slower to other languanges like c++,java etc.
2. Memory consumption is higher .
Q4. In what all domains can we use Python?

ans - Python is a versatile language that is used in various domains for its ease of use . The different domains that uses python are data domain because of the support provided with the libraries , also python can be used for full stack web development using django and flask framework , testing and app development.

Q5. What are variable and how can we declare them?

ans - variables are names given to memory locations that may store some value . Since the memory locations are represented as hexadecimal numbers so it becomes difficult to access the values stored there and that is why we use variables .

t=123     // integer variable 
z=123.54  // double variable  
Q6. How can we take an input from the user in Python?

ans - Input in python from the user is taken using the input() function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

ans - The default datatype of input function is string . Typecasting is used to change string to a different data type.

Q8. What is type casting?

ans - Type casting is a method to change data type of a object or a variable . For e.g A integer to a string . In python it can be done using functions like str(), int(),float().

    ```x=123   ## this is a integer
    s=str(x)  ## s is a string which stores the value as "123" 
    ```
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

ans - yes , we can take multiple inputs using a single input function by using the split function with defining a separator . for e.g -

  ```s1,s2,s3 = input().split(" ")

  if we give input as --  ABC DEF GHI 
  it will get stored as s1= "ABC", s2="DEF" , s3="GHI"
  ```  
Q10. What are keywords?

ans - keywords are reserved name in a programming languages . These keywords have a specific meaning and use . These cannot be used to be named as variables.

Q11. Can we use keywords as a variable? Support your answer with reason.

ans - The keywords in a programming language have a specific meaning and use . They cannot be used as a varaible as they have predefined functionality . for e.g int,str, input etc

Q12. What is indentation? What's the use of indentaion in Python?

ans -Indentation in python is used to tell the interpreter that the statments belong to a single block. Indentation is used to define the block spaces in python.

Q13. How can we throw some output in Python?

ans - In python output is thrown using the print function that displays the output in terminal . for e.g print ("This is the output ")

Q14. What are operators in Python?

ans - operators in python are used to perform operation on values and variables for building logic . for eg . additon (+),subtraction (-) .

Q15. What is difference between / and // operators?

ans - the first operator (/) is used to give the division output between two numbers while the second operator (//) is used to give the division output but with just the quotient part or the output before the decimal point .

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron
ans -

```for i in range(0,4):
    print("iNeuron",end='')
```  
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

ans- num=int(input("Enter a number")) if(num%2==0): print("Even number") else: print("Odd number ") Q18. What are boolean operator? ans - the operators used in boolean expressions that results into boolean values true or false are boolean operators . for e.g AND , OR and NOT .

Q19. What will the output of the following?

1 or 0

0 and 0

True and False and True

1 or 0 or 0
ans -

  ```true 
  false
  false
  true
  ```  
Q20. What are conditional statements in Python?

ans - conditional statements are those statements that are used to build a logic based on some logic. This can be done using if ,else statements. 
Q21. What is use of 'if', 'elif' and 'else' keywords?

ans - if ,elif ,else keywords in python are used to check for conditons . if keywords is used for the first condition that is to be checked and elif is used for subsequent conditions that are to be checked and else is used for the case when all conditions are not met . 
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

ans -

```age=int(input(Enter the age of the person"))
if(age>=18):
    print("I can vote")
elif(age<18):
    print("I can't vote")  
```
Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]
ans -

```sum = 0
    for i in numbers:
        if(i%2==0):
            sum+=i
    print(sum)
```
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

ans -

     if(a>=b):
       if(a>=c):
           print(a)
       else:
           print(c)
     else:
       if(b>=c):
           print(b)
       else:
           print(c)
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
ans -

     for num in numbers :
        if(num%5==0):
          if(num>500):
              break
          elif(num>150):
              continue
          else:
              print(num) 
