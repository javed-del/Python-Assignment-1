## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

A.Python is called high-level programming language because it can be used to easily write by humans and easy to understand and it has a great versatility because python can be used in many domains like data sciences,data engineering,machine learning and many other


Q2. Why is Python called a dynamically typed language?

A.Python is called Dynamically typed language because we can declare the variable on go in runtime and easy for type casting.
 
Q3. List some pros and cons of Python programming language?

A.Pros:
1.Python is Easy to Learn and Use Programming Language
2.Python has a reach library support 
3.Python has a great versatility
Cons:
1.Python is Dynamically typed 
2.Perfomance of Python is Slow


Q4. In what all domains can we use Python?

A.In Data Sciences,Data Analytics,Data Sciences,Data Engineering,Artificial Intelligence,Machine Learning And Many Other 


Q5. What are variable and how can we declare them?

A.Variable is location in memory that stores value,we can declare a variable directly equating it to some value.


Q6. How can we take an input from the user in Python?

A.by using input() function


Q7. What is the default datatype of the value that has been taken as an input using input() function?

A.String is the default datatype of the value that has been taken as input in input() function.


Q8. What is type casting?

A.Type Casting is converting data type of variable from one type to another datatype.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

A.Yes, by using loop functions such as for,while. 


Q10. What are keywords?

A.keywords are words in python which have a specific functionality and cannot be used as variable.


Q11. Can we use keywords as a variable? Support your answer with reason.

A.we cannot use keyword as variable as they have specific functionality to perform.


Q12. What is indentation? What's the use of indentaion in Python?

A.Indentation is Space given between the code after using this sign ":"


Q13. How can we throw some output in Python?

A.By Using print() function


Q14. What are operators in Python?

A.operators in python are used to perform operation on values stored in variables they are used for various tasks like comparing the variables ,assigning values and performing arthimetic operations 


Q15. What is difference between / and // operators?

A."/" operator gives float value as output "//" gives int value as output.


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
A.word="iNeuron"
print(word*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Anumber=int(input())
if number%2==0:
    print("number is Even")
else:
    print("number is Odd")
Q18. What are boolean operator?
A.Boolean operators in python are AND,OR,NOT and they are called Boolean Operators because they produce output whether true or false.
Q19. What will the output of the following?

1 or 0
A.1
0 and 0
A.False
True and False and True
A.False
1 or 0 or 0
A.1

Q20. What are conditional statements in Python?
A.Conditional Statemnts in Python are used to compile the code in condition of the code.
Q21. What is use of 'if', 'elif' and 'else' keywords?
A.if,elif and else are the conditional keywords 
Q22.Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
age = int(input())
if age>=18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
even_sum=0
for i in numbers:
    if i%2==0:
        even_sum+=i
    else:
        even_sum=even_sum
print(even_sum)

    


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
 numbers_list=[]
for i in range(3):
    numbers=int(input())
    numbers_list.append(numbers)
print(max(numbers_list))


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i%5==0:
        print(i)
    
- If the number is greater than 150, then skip it and move to the next number
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i>=150:
        continue 
    else:
        print(i)


- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i>500:
        print(i)