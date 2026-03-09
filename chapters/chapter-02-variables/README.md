# Chapter 2 — Variables

[← Back to Chapters](../README.md)

This chapter introduced variables, data types, and user input.

---

## My Take

Variables in Python feel very loose compared to what I was used to. In VB.NET and C++ you declare the type first. In Python you just assign and go. It took some getting used to but it makes the code a lot faster to write.

The input() function was interesting. The fact that you can take something a user types and immediately store it and use it felt more powerful than expected for something this simple.

---

## Exercises

### Exercise 6 — Data Types

This one was an explanation exercise. No code to write, just an introduction to the different data types in Python: strings, integers, floats, and booleans.

### Exercise 7 — Temperature
```python
Fahrenheit = 39
Celsius = (Fahrenheit - 32) / 1.8
print(Celsius)
```

### Exercise 8 — BMI
```python
mass = 91
height = 6
bmi = mass / (height ** 2)
print(bmi)
```

### Exercise 9 — Pythagorean Theorem
```python
a = int(input('Enter a: '))
b = int(input('Enter b: '))
c = int((a**2) + (b**2))**0.5
print(c)
```

### Exercise 10 — Currency
```python
pesos = int(input('What do you have left in pesos? '))
soles = int(input('What do you have left in soles? '))
reais = int(input('What do you have left in reais? '))
total = int((pesos*0.00026) + (soles*0.29) + (reais*0.19))
print(total)
```
