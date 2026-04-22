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
```
real_part = int(input("Enter the real part: "))
imag_part = int(input("Enter the imaginary part: "))
z = complex(real_part, imag_part)
print("Complex number:", z)
print("Real part:", z.real)
print("Imaginary part:", z.imag)
```
## Output
<img width="418" height="262" alt="image" src="https://github.com/user-attachments/assets/051fab95-7b2f-49e3-8a06-f0dd70db9d6d" />

## Result
