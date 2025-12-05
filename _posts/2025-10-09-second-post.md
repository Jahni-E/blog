Welcome to my Second Blog Post!

<img src="/blog/images/secondpost2.jpeg" alt="Picture of Emoji"> <img src="/blog/images/secondpost.jpeg" alt="Picture of Emoji">


# What is Debugging and Why is it important?
Debugging is a procces of analyzing,realizing problems and resolving errors or bugs in your code.Their can be different type of errors in ur code like syntax index,indentation Runtime,and other errors that can stop ur code from running.Debuggung could be useful for different proggramming laungages like Javascript,Python and etc.
Here listed below will be 3 different codes in python that debugging was needed and i will guide you to understand why debugging was needed and how we solve the problem in code 

# Task 1
```python
temperature = 75

if temperature > 80:
    print("It's hot")
elif temperture > 50:
    print("It's temperate")
elif temperture < 0:
    print("It's cold")
```
 This code is incorrect and needs to be Debug because the code doesnt account for numbers 0 and 50.In order to fix this code you would have to Debug this code.If you Debug this code you would have to  Change the final elif to an else statement, this will make sure any temperature less than 50 is determined to be cold

# Task 2
 ```python
 text = "Hello,World,my name is"
 count = 0 
 
 for char in text:
    if char == "":
        count += 1

        print(count)
```
This code is incorrect and needs to be Debug because The if statement does not have a space causing the count to stay at 0 and not increase.To fix this  code you will have to Change the if statement to have spaces instead of 0 spaces so the count could increase by 1.

# Task 3
```python
print("give me a number")
n = input()

for num in range(1, n):
    if num % 2 < 0:
        print(num, "is even.")
    else:
        print(num, "is odd.")
```
This code is incorrect and needs to be Debug because the  Integer data type  is not included in The variable n.In order to fix/Debug this code you will have to Change the variable n  including an integer because users are entering numbers.

These are all different ways on how you can debug code and why debugging is useful when dealing with programming languages.
