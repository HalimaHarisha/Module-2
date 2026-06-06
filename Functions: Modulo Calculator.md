# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```
def result(a, b):
    mod = a % b
    print("Modulo is:", mod)


a = int(input("Enter first number: "))
b = int(input("Enter second number: "))


result(a, b)
```

## Output

<img width="515" height="286" alt="image" src="https://github.com/user-attachments/assets/485c4138-ad71-4ede-9cf8-6ef4ae258f37" />


## Result

The program successfully defines a function to calculate the modulo of two numbers using the % operator and prints the result.
