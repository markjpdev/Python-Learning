# Chapter 3 — Control Flow

[← Back to Chapters](../README.md)

---

## My Take

_Write this when you finish the chapter._

---

## Exercises

_Add exercises here as you complete them._

## Exercises

### Exercise 11 — Coin Flip
```python
import random
num = random.randint(0, 1)
if num > 0.5:
  print('Heads')
else:
  print('Tails')
```

### Exercise 12 — Grades
```python
grade = 59
if grade >= 55:
  print('You passed.')
else:
  print('You failed.')
```

### Exercise 13 — pH Levels
```python
ph = 9
if ph > 7:
  print('Basic')
elif ph < 7:
  print('Acidic')
else:
  print('Neutral')
```

### Exercise 14 — Magic 8 Ball
```python
import random
num = random.randint(1, 9)

print(input('Enter your Question: '))
if num == 1:
  print('Magic 8 Ball: Yes - Definitely')
elif num == 2:
  print('Magic 8 Ball: It is decidedly so.')
elif num == 3:
  print('Magic 8 Ball: Without a doubt')
elif num == 4:
  print('Magic 8 Ball: Reply hazy, try again')
elif num == 5:
  print('Magic 8 Ball: Ask again later.')
elif num == 6:
  print('Magic 8 Ball: Better not tell you now.')
elif num == 7:
  print('Magic 8 Ball: My sources say no.')
elif num == 8:
  print('Magic 8 Ball: Outlook not so good.')
else:
  print('Very doubtful.')
```

### Exercise 15 — The Cyclone
```python
min_height = 137
cost = 10

height = int(input("What is your height (cm)? "))
credits = int(input("How many credits do you have? "))

if height >= min_height and credits >= cost:
  print("Enjoy the ride!")
elif height < min_height and credits >= cost:
  print("You are not tall enough to ride.")
elif height >= min_height and credits < cost:
  print("You don't have enough credits.")
else:
  print("You haven't met either requirements")
```

### Exercise 15 — The Cyclone
```python
min_height = 137
cost = 10

height = int(input("What is your height (cm)? "))
credits = int(input("How many credits do you have? "))

if height >= min_height and credits >= cost:
  print("Enjoy the ride!")
elif height < min_height and credits >= cost:
  print("You are not tall enough to ride.")
elif height >= min_height and credits < cost:
  print("You don't have enough credits.")
else:
  print("You haven't met either requirements")
```
