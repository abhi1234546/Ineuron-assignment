## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans-We call python as a general purpose and high level language because we can do multipke things like data related activities like analysis using python language.

Q2. Why is Python called a dynamically typed language?

Ans-Because this language provides you to specify the type of variable.

Q3. List some pros and cons of Python programming language?

Ans-Pros-1)Smooth learning curve,2)High speed development,3)Portability to other languages
    Cons-1)Speed limitation,2)No multithreading.

Q4. In what all domains can we use Python?

Ans-It is a popular choice for building web apps, gaming applications, enterprise-grade apps, e-commerce applications, ML and AI applications, and much more.

Q5. What are variable and how can we declare them?

Ans-Variable are reffered to envelop where information can be stored. Variable are declared by name or an alphabate like a,aa,aaa etc.

Q6. How can we take an input from the user in Python?

Ans-String input this method is used to take string input from user. The unser can enter the numeric value but as well it can be treated as string.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans-It may be integer,float.

Q8. What is type casting?

Ans- The conversion of one data type into other data type is called casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans-Yes,we have to provide seperate input line for each input parameter.

Q10. What are keywords?

Ans-Keywords are the reserve words they have specific menaning and also restriction.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans-We can not use the keywords as a variable because they are used to syntax and structure in language.

Q12. What is indentation? What's the use of indentaion in Python?

Ans-Indentation is the space which is given before to write the code And its use is to indicate block of code.

Q13. How can we throw some output in Python?

Ans-By using the print()function.

Q14. What are operators in Python?

Ans-1)Logical operator,2)Arithmatic operator,3)Comparison operator.

Q15. What is difference between / and // operators?

Ans-/ this operator devides left hand operand by right hand and ans may be in the decimal form but in case of // there is no any decimal point in the answer.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Ans-str=input()
    print(str*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans-n=int(input())
    if n%2==0:
        print("Number is even")
    else:
        print("Number is odd")

Q18. What are boolean operator?

Ans-Boolean operators are specific words that are used to expand your search.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Ans- 1

Q20. What are conditional statements in Python?

Ans-If else,elif,For,While

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans-It allowes to user to execute specific blok of code depending on the input parameter.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans- age=int(input())
     if age>=18:
        print("I can vote")
     else:
        print("I can not vote")
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans-numbers = [12, 75, 150, 180, 145, 525, 50]
    sum=0
    for element in range(0,len(numbers)):
        sum=sum+numbers[element]
    print("Sum of all element:",sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans-a=int(input())
    b=int(input())
    c=int(input())
    if a>b:
        print(a)
    elif a>c:
        print(b)
    else:
        print(c)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```