## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?

ans - Python is a general purpose programming language because it cane be used for multiple type of developments and differnt domains . Its called high level languange because the logic building in python does not requires one to know binary or assembly languages .

Q2. Why is Python called a dynamically typed language?

ans -Python is dynamically typed language because python interpreter is capable of identifying the data type of variable at run time and the programmer need to decalre the data type of variables .

Q3. List some pros and cons of Python programming language?

ans - pros of python 
    1. It is easy to use .
    2. It is dynamically typed so the programmers needs not to worry about declartion of varible data type.
    3. It provides support in terms of different libraries and frameworks that are used in web develeopment ,data domain etc.

    cons of python 
    1. It is comparitively slower to other languanges like c++,java etc.
    2. Memory consumption is higher .

Q4. In what all domains can we use Python?

ans - Python is a versatile language that is used in various domains for its ease of use . The different domains that uses python are data domain because of the support provided with the libraries , also python can be used for full stack web development using django and flask framework , testing and app development. 

Q5. What are variable and how can we declare them?

ans - variables are names given to memory locations that may store some value . Since the memory locations are represented as hexadecimal numbers so it becomes difficult to access the values stored there and that is why we use variables . 

```
x="123"   // string variable 
t=123     // integer variable 
z=123.54  // double variable  
```
Q6. How can we take an input from the user in Python?

ans - Input in python from the user is taken using the input() function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

ans - The default datatype of input function is string . Typecasting is used to change string to a different data type.

Q8. What is type casting?

ans - Type casting is a method to change data type of a object or a variable . For e.g A integer to a string . In python it can   be done using functions like str(), int(),float(). 

```
        x=123   ## this is a integer
        s=str(x)  ## s is a string which stores the value as "123" 
```
 
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

ans - yes , we can take multiple inputs using a single input function by using the split function with defining a separator . for e.g -
      
```
      s1,s2,s3 = input().split(" ")

      if we give input as --  ABC DEF GHI 
      it will get stored as s1= "ABC", s2="DEF" , s3="GHI"
```  
Q10. What are keywords?

ans - keywords are reserved name in a programming languages . These keywords have a specific meaning and use . These cannot be used to be named as variables.

Q11. Can we use keywords as a variable? Support your answer with reason.

ans - The keywords in a programming language have a specific meaning and use . They cannot be used as a varaible as they have predefined functionality . for e.g  int,str, input etc 

Q12. What is indentation? What's the use of indentaion in Python?

ans -Indentation in python is used to tell the interpreter that the statments belong to a single block. Indentation is used to define the block spaces in python.

Q13. How can we throw some output in Python?

ans - In python output is thrown using the print function that displays the output in terminal . for e.g 
        print ("This is the output ")

Q14. What are operators in Python?

ans - operators in python are used to perform operation on values and variables for building logic . for eg . additon (+),subtraction (-) .

Q15. What is difference between / and // operators?

ans - the first operator (/) is used to give the division output between two numbers while the second operator (//) is used to give the division output but with just the quotient part or the output before the decimal point .

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

ans - 
    
```
for i in range(0,4):
    print("iNeuron",end='')
```  
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

ans- 
```
num=int(input("Enter a number"))
if(num%2==0):
    print("Even number")
else:
    print("Odd number ")
```

Q18. What are boolean operator?
ans - the operators used in boolean expressions that results into boolean values true or false are boolean operators . for e.g AND , OR and NOT .

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

ans - 
      
 ```
true 
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
    
```
age=int(input(Enter the age of the person"))
if(age>=18):
    print("I can vote")
elif(age<18):
    print("I can't vote")  
```
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

ans -   
    
```
sum = 0
for i in numbers:
    if(i%2==0):
        sum+=i
print(sum)
```

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.


ans - 
    
```   
a,b,c=[int(i) for i in (input().split(" "))]
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
  ```

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


ans -
    
  ```  
    numbers = [12, 75, 150, 180, 145, 525, 50]
    for num in numbers :
        if(num%5==0):
            if(num>500):
                break
            elif(num>150):
                continue
            else:
                print(num) 
  ```   

Q26. What is a string? How can we declare string in Python?

ans - A string can be defined as a sequence of characters .for e.g. "Happy", "NEW",'year' etc. we can declare strings using the double quotes(" ") or single quotes(' ') .
str1="HELLO"
str2='world'

Q27. How can we access the string using its index?

ans - We can easily access the strings using its index as it maintains a order . The index of a string starts from 0 (first character ) to length of the string -1 (last character ).
for e.g.  str1="Hello" 
        print(str1[0])   // prints first character 'H'
        print (str1[len(str1)-1]) // prints last character 'o'

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```

ans - 
``` 
        str="Big Data iNeuron"
        print(str[9:])  // slicing the last portion of the string from index 9 
```    

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```

ans-
  ```
    str="Big Data iNeuron"
    print(str[-1:8:-1])
  ```
Q30. Resverse the string given in the above question.

ans-  
  ```
    str="Big Data iNeuron"
    print(str[-1::-1])
  ```
Q31. How can you delete entire string at once?
ans - 
    ```
    str1="heag" 
    del str1
    ```
Q32. What is escape sequence?

ans- escape sequences in programming languages are special characters or sequence that are used for different functionality . for e.g  "\n" is the newline character or "\t" is a tab character .

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
ans-
```
    str1='iNeuron\'s Big Data Course'  # making use of escape character to escape the ' in the string 
    print(str1)
```
Q34. What is a list in Python?

ans - A list is a data structure that is mutable,ordered and can store different type of objects like integer,float,bool , string 
etc . A list is defined with square brackets . for e.g . l1=['A',12,1.23,false]  

Q35. How can you create a list in Python?

ans - A list is created with the help of square brackets and by adding element one after the other . for e.g . l1=['A',12,1.23,false] . we can use insert ,append or extend function to add elements in a list . 

Q36. How can we access the elements in a list?

ans- List is a ordered data structure which means that the index can be used to acccess elements in the order they were inserted . 
To access the first element of a list we can use 0th index 
```
for e.g   l1=[1,2,3]
          print (l1[0]) # print the first element 
          print (l1[0:2]) # print the whole list

```

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
ans -
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])
```
Q38. Take a list as an input from the user and find the length of the list.
ans -
``` 
    l = [int(ele) for ele in input("Enter the list items : ").split()]
    print(len(l))
```
    
Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
ans - 
```
    lst = ["Welcome", "to", "Data", "course"]
    lst.insert(2,"Big")
    print(lst)
```
Q40. What is a tuple? How is it different from list?

ans- A tuple is a in built ordered immutable data structre in python . It is defined witin the round brackets . The difference between a list and a tuple is that a list is mutable in nature which means we can change the elements present in the list after the declartion whereas tuple does not allows the user to do so.


Q41. How can you create a tuple in Python?

ans- A tuple is created by using the tuple keyword or by using the round brackets in python. 
    for e.g   ```  t1=tuple([1,2,3])
                   t2=(1,2,3)  
              ```
Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

ans- The elements of a tuple needs to be provided while declaring it as it does not allows to add elements once it has been defined because of its immutability property .

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

ans- yes , two tuples can be appended by using the concatenation property of tuples but the result will be a new tuple . Tuples doesn't supports the append operation as it violates the immutability of the tuples.


Q44. Take a tuple as an input and print the count of elements in it.

ans-
```
t=tuple(int(num) for num in input("Enter the elements in the tuple").split())
print(len(t))
```

Q45. What are sets in Python?

ans- sets are mutable,unordered,unique collection of elements .sets can be defined with the help of curly brackets ({}) in python.
```
s={1,2,3}
print(type(s))
``` 

Q46. How can you create a set?

ans- sets are created with the help of curly brackets ({}) with elements in it or with the set constructor . 
``` 
s1=set()        ## first set
s1.add(1)
s1.add(2)
print(s1)
s2={1,2}         ## second set
print(s2)
```
Q47. Create a set and add "iNeuron" in your set.

ans-
```
s=set()      
s.add('iNeuron')
print(s)
```
Q48. Try to add multiple values using add() function.

ans-
```
s=set()
s.add('iNeuron')
l=['Big','Data','Course']
for i in l:
    s.add(i)
print(s)
```
Q49. How is update() different from add()?

ans -  Add() function is used to add a single element to the set whereas a update() function can add an entire iterable like a list in just one function call. 

Q50. What is clear() in sets?

ans- Clear() function is used to clear all the elements from the set that are added . 

Q51. What is frozen set?

ans- A frozen set is a set that is immutable in nature . It has all the properties of a set with a additon that it cannot be changed once declared.

Q52. How is frozen set different from set?

ans- A frozen set is immutable in nature while a set in not immutable in nature . 

Q53. What is union() in sets? Explain via code.

ans - A union() between two sets is a unique collection of elements from both the sets . 
```
s1={1,2,3}
s2={2,3,4}
s1=s1.union(s2)
print(s1)           # {1,2,3,4}
``` 
Q54. What is intersection() in sets? Explain via code.

ans- A intersection() between two sets is a unique collection of elements that are common in both the sets .
```
s1={1,2,3}
s2={2,3,4}
s1=s1.intersection(s2)
print(s1)           # {2,3,4}
``` 
Q55. What is dictionary in Python?

ans - A dictionary is a data structure that stores data in form of key value pairs . Each value is linked to a key with the help of hash function.

Q56. How is dictionary different from all other data structures.

ans - A dictionay is different from other data structures as it contains data in form of key value pairs which are linked using a hash function. Other data structures only contain the the elements in it .

Q57. How can we delare a dictionary in Python?

ans - A dicitonay can be defined using dict() function or with curly brackets({ }).The data is added in dictionary in key value pairs .
Q58. What will the output of the following?
```
var = {}
print(type(var))
```

ans - <class 'dict'>

Q59. How can we add an element in a dictionary?

ans- we can add elements in array using update () function and also by giving the key value pair as a input.for e.g. 
```
d=dict()
d.update({'Name':'Tajbar'})          # updating the dict with a new key value pair
d.update({'Age':23})
d['Gender']='Male'                  # setting the value of key in a dict by assignment operator
print(d)
```

Q60. Create a dictionary and access all the values in that dictionary.

ans-
```
d=dict()
d.update({'Name':'Tajbar'})          # updating the dict with a new key value pair
d.update({'Age':23})
d['Gender']='Male'                  # setting the value of key in a dict by assignment operator
print(d.values())
```
Q61. Create a nested dictionary and access all the element in the inner dictionary.

ans-
```
d=dict()
d.update({'Name':'Tajbar'})          # updating the dict with a new key value pair
d.update({'Age':23})
d['Gender']='Male'                  # setting the value of key in a dict by assignment operator
d['Marks']={'English':83,'Physics':85,'Chemistry':89,'Mathematics':92,'Computer Science':94}
for key,value in d['Marks'].items():
    print(value,"Marks in",key)
```
Q62. What is the use of get() function?

ans- The get() function is used to get the value associated with the key that is passed as a argument in the function . for e.g.
```
d={'A':1,
    'B':2}
print(d.get('A'))       # prints 1 which is the value associated with 'A'
```

Q63. What is the use of items() function?

ans- The items() function is used to get a list of the key value pairs in the dictionary . for e.g.
```
d={'A':1,
    'B':2}
print(d.items())       # prints  dict_items([('A', 1), ('B', 2)])
```

Q64. What is the use of pop() function?

ans-The pop() function is used to delete the key value pair for which the key is passed as a argument . for e.g. 
```
d={'A':1,
    'B':2}
print(d.pop('A'))       # prints 1 indicating that pop operation was successful  makind dictionary d={'B':2}
```

Q65. What is the use of popitem() function?

ans-The popitem() function for dictionary is used to delete last added key value pair that is stored in the dictionary.for e.g. 
```
d={'A':1,
    'B':2}
print(d.popitem())        ## prints the last key value pair and deletes it 
``` 

Q66. What is the use of keys() function?

ans-The keys() function for dictionary is used to get all keys that are stored in the dictionary in form of list . for e.g .
```
d={'A':1,
    'B':2}
print(d.keys())  ## prints dict_keys['A','B']
```
Q67. What is the use of values() function?

ans- The values() function for dictionary is used to get all values that are stored in the dictionary in form of list .
```
d={'A':1,
    'B':2}
print(d.values())  ## prints dict_values [1,2]
```

Q68. What are loops in Python?

ans- loops are statements that helps to run a certain block of code any number of times without rewriting the code . 

Q69. How many type of loop are there in Python?

ans - There are two type of loops in python i.e for loop and while loop .

Q70. What is the difference between for and while loops?

ans- The for loop in python is used to iterate over a range or a iterable object whereas in case of while loop the loop runs till a condition is satisfied . A while loop is usually used when the number of iterations  is not known and for loop is used when number of iterations is known . for e.g .

```
for i in range (0,5):  # for loop uses a iterable or a range function
    print(i)

x=0
while(x<5):         # while loop uses a conditon 
    print(i)

```

Q71. What is the use of continue statement?

ans- A continue statement is used to jump over to the next iteration in the loop .for e.g.
```
for i in range (0,5):  
    if(i==2):               # when i==2 the continue statement will skip the rest of the statements in the loop and jump to i=3
        continue
    else:
        print(i)
```


Q72. What is the use of break statement?

ans- A continue statement is used to jump over to the next iteration in the loop .for e.g.
```
for i in range (0,5):  
    if(i==2):          # when i==2 the break statement will skip the rest of the iterations in the loop and come out of the loop
        break
    else:
        print(i)
```

Q73. What is the use of pass statement?

ans- The pass statement is used to when the programmer doesnot want to execute any code and keep the code syntatically correct as well .
```
a = 10
b = 20

if(a<b):
pass
else:
print("b<a")

``` 
Q74. What is the use of range() function?

ans- The range function gives the output in form of a sequence starting from the start (first parameter ) to end-1(second parameter) by taking a increment (third parameter) at every step.
```
for c in range(1,10,2):
    print(c,end=" ")            ## prints 1 3 5 7 9 

```
Q75. How can you loop over a dictionary?

ans -
```
d={'A':1,
    'B':2}

for i in d:
    print("key:",i,"value:",d[i])
```

### Coding problems
Q76. Write a Python program to find the factorial of a given number.

ans - 
``` 
n=int(input("Enter the number:"))
ans=1
for i in range(n,1,-1):
    ans=ans*i
print(ans)
```
Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

ans- 
```
[p,r,t]=[int(i) for i in input("Enter the values of p , r and t respectively").split()]
print("simple interest is ",(p*r*t)/100)

```
Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

ans- 
```
p,r,t=(int(i) for i in input("Enter the values of p , r and t respectively").split())

coumpund_int=(p*(1+r/100)**t)

print(f"compound interest is {coumpund_int:.2f}")

```
Q79. Write a Python program to check if a number is prime or not.

ans- 
```
num=int(input("Enter a number"))
if(num==1):
    print("1 is not a prime number")
else:
    is_prime=True
    for i in range(2,num//2+1):
        if(num%i==0):
            is_prime=False
    if(is_prime):
        print(num,"is a prime number")
    else:
        print(num,"is not a prime number")

```
Q80. Write a Python program to check Armstrong Number.

ans-
```
num=int(input("Enter the number to be checked as a armstrong number"))
temp=num
number_of_digits=0

while(temp>0):                          ## finding the number of digits in the number 
    temp=temp//10                        ## reducing the number by one digit 
    number_of_digits=number_of_digits+1

temp=num
curr_sum=0

while (temp>0):
    rem=temp%10   ## the last digit of the number
    temp=temp//10
    curr_sum=curr_sum+(rem**number_of_digits)  ## calculating the running sum of digits raised to the power of number of digits

if(curr_sum==num):
    print(num," is a armstrong number")
else:
    print(num," is not a armstrong number")
```
Q81. Write a Python program to find the n-th Fibonacci Number.

ans-
```
num=int(input("Enter the nth index of fibonnaci series"))   ## index starts from 0  . 
if(num<=1):
    print(num,"is the",num,"th index fibonnaci number")
else:
    first=0
    second=1
    third=0
    i=2
    while(i<=num):
        third=first+second
        first=second
        second=third
        i=i+1
    print(third,"is the",num,"th index of fibonnaci series")
```
Q82. Write a Python program to interchange the first and last element in a list.

ans-
```
l=[int(num) for num in input("Enter the elements of the list").split(" ")]
print("first element and last element before the swap are ",l[0],l[len(l)-1])
l[0],l[len(l)-1]=l[len(l)-1],l[0]   ## swapping the two values 
print("first element and last element after the swap are ",l[0],l[len(l)-1])
```
Q83. Write a Python program to swap two elements in a list.

ans-
```
l=[int(num) for num in input("Enter the elements of the list").split(" ")]  
pos1=int(input("Enter the first element position"))      ## index starts from 0 to length -1
pos2=int(input("Enter the second element position"))
print("before the swap",l)
l[pos1],l[pos2]=l[pos2],l[pos1]
print("aftet the swap",l)

```

Q84. Write a Python program to find N largest element from a list.

ans-
```
l=[1,99,23,15,78,100,59,120]
l.sort(reverse=True)
n=int(input("Enter the value of n"))
print(l[0:n])

```

Q85. Write a Python program to find cumulative sum of a list.

ans-
```
l=[int(ele) for ele in  input("Enter the list elements").split(" ")]
sum=0
for i in range(0,len(l)+1):
    sum=sum+l[i]
print(sum)
```

Q86. Write a Python program to check if a string is palindrome or not.

ans-
``` 
str=input("Enter the string" )
is_palindrome=True
for i in range(0,len(str)//2):
    if(str[i]!=str[len(str)-i-1]):
        is_palindrome=False
        break
if(is_palindrome):
    print(str,"is a palindrome")
else:
    print(str,"is not a palindrome")
```

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

ans- the find() function of strings helps us to find the index of a substring that is present in the string. If the substring is present it gives the index of the starting point of substring and if its not present than it will give output as -1.
```
str1="My name is Tajbar"
str2="Taj"
str3="fads"
print(str1.find(str2))      # prints 11
print(str1.find(str3))      # prints -1
```

Q89. Write a Python program to find words which are greater than given length k.

ans-
```
l=input("Enter the words").split(" ")
k=int(input("Enter the value of k"))

words_greater_than_len_k=[]
for word in l:
    if(len(word)>k):
        words_greater_than_len_k.append(word)

print(words_greater_than_len_k)
```
Q90. Write a Python program to extract unquire dictionary values.

ans-
```
d={ 'A':1,
    'B':2,
    'C':3,
    'D':2,
    'E':1
}
ans=set(d.values())
print(ans)

```
Q91. Write a Python program to merge two dictionary.

ans-
```
d1={ 'A':1,
    'B':2,
    'C':3,
    'D':2,
    'E':1
}
d2={'F':12,
    'G':23,
    'A':12
    }
d1.update(d2)
print(d1)
```

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```

ans-
```
l=[('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
d=dict(l)
print(d)
```
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
ans-
```
l=[9,5,6]
new_list=[(i,i**3) for i in l]

print(new_list)
```
Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
ans-
```
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
l=[]
for i in test_tuple1:
    for j in test_tuple2:
        l.append((i,j))
       
for i in test_tuple2:
    for j in test_tuple1:
        l.append((i,j))     
print (l)
```
Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
ans-
```
l=[('for', 24), ('Geeks', 8), ('Geeks', 30)] 
l=sorted(l,key=lambda x : x[1])  ## using the sorted function and second element of a tuple as the key to sort 
print(l)
```
Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
ans-
```
for i in range(0,5):                ## loop for number of rows 
    for j in range(0,i+1):          ## loop for number of columns 
        print("*",end=" ")
    print()
```
Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
ans-
```
for i in range(0,5):                ## loop for number of rows
    for k in range(5-i-1,0,-1):      ## using the first inner loop to create the space as per the pattern 
        print(" ",end=" ")
    for j in range(0,i+1):          ## using the second inner loop to print the stars as per the pattern
        print("*",end=" ")
    print()
```

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
ans-
```
for i in range(0,5):                ## loop for number of rows
    for k in range(5-i-1,0,-1):      ## using the first inner loop to create the space as per the pattern 
        print(" ",end="")
    for j in range(0,i+1):          ## using the second inner loop to print the stars as per the pattern
        print("*",end=" ")
    print()
```
Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
ans-
```
for i in range(1,6):                ## loop for number of rows 
    for j in range(1,i+1):          ## loop for number of columns 
        print(j,end=" ")
    print()

```
Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
ans-
```
chars=['A','B','C','D','E']
for i in range(0,5):                ## loop for number of rows 
    for j in range(0,i+1):          ## loop for number of columns 
        print(chars[i],end=" ")
    print()

```
