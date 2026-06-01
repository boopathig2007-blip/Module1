# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
real = int(input("Enter the real part: "))
imag = int(input("Enter the imaginary part: "))

c = complex(real, imag)

print("Complex Number =", c)
print("Real Part =", c.real)
print("Imaginary Part =", c.imag)

## Output
Enter the real part: 5
Enter the imaginary part: 3
Complex Number = (5+3j)
Real Part = 5.0
Imaginary Part = 3.0

## Result
Thus, the Python program to read two integers, create a complex number, and display its real and imaginary parts was successfully executed and verified.
