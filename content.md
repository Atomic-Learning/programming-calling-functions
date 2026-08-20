A function is a reusable block of code that performs a specific task. Many programming languages include built-in (intrinsic) functions you can call right away. A function call runs the function and, if it returns a value, gives you a result you can use.

# Calling a Function

Exact syntax varies by programming language, but a function call commonly uses the function name followed by parentheses. Arguments (inputs) are data values passed to the function to be used in the execution of the function. These are often provided inside the parentheses:

```
print("Hello")
length("hello")
round(3.14)
```

When multiple arguments are provided as a sequence of values, their order usually matters - each function will know what to do with the the value of each argument based on its position in the argument list. As a result, arguments passed in this way are known as positional arguments.

```
count("hello", "l") # Counts how many times "l" appears in "hello"
modulo(7, 3) # Returns the remainder when 7 is divided by 3
```

In the examples above, swapping the order of the arguments would change the operation we are asking the function to perform.

# Return Values

Some functions return a value, which can be stored in a variable, or used as part of an expression:
    

```
count = length("hello") # Count the number of characters in "hello" and save in count
x = max(5, 10) + 3 # Get the maximum of 5 and 10, add 3 to it and save in x
```

Others do not return a value (or return a unimportant value) are called for their side effects (like printing output, writing to a file, etc.):

```
print("Hello, world!") # Print a message to the console.
```
