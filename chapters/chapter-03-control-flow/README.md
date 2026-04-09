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

### Exercise 16 - Sorting Hat
```python
# Write code below 💖
gryffindor = 0
ravenclaw = 0
hufflepuff = 0
slytherin = 0

print("Q1) Do you like Dawn or Dusk?")
print("1) Dawn")
print("2) Dusk")
q1 = int(input())

if q1 == 1:
  gryffindor = gryffindor + 1
  ravenclaw = ravenclaw + 1
elif q1 == 2:
  hufflepuff = hufflepuff + 1
  slytherin = slytherin + 1
else:
  print("Wrong input.")

print("Q2) When I'm dead, I want people to remember me as:")
print("1) The Good")
print("2) The Great")
print("3) The Wise")
print("4) The Bold")
q2 = int(input())

if q2 == 1:
  hufflepuff = hufflepuff + 2
elif q2 == 2:
  slytherin = slytherin + 2
elif q2 == 3:
  ravenclaw = ravenclaw + 2
elif q2 == 4:
  gryffindor = gryffindor + 2
else:
  print('Wrong input.')

print("Q3) Which kind of instrument most pleases your ear?")
print("1) The violin")
print("2) The trumpet")
print("3) The piano")
print("4) The drum")
q3 = int(input())

if q3 == 1:
  slytherin = slytherin + 4
elif q3 == 2:
  hufflepuff = hufflepuff + 4
elif q3 == 3:
  ravenclaw = ravenclaw + 4
elif q3 == 4:
  gryffindor = gryffindor +4
else:
  print('Wrong input.')

print('gryffindor', gryffindor)
print('ravenclaw', ravenclaw)
print('hufflepuff', hufflepuff)
print('slytherin', slytherin)
```
