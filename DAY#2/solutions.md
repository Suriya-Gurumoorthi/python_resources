# 📝 Answers

### 1. Write a program that checks if a number is positive or negative.
```python

num = int(input("Enter a number: "))
if num >= 0:
    print("Positive")
else:
    print("Negative")
```

### 2. Print all even numbers from 1 to 20 using a `for` loop.
```python
for i in range(1, 21):
    if i % 2 == 0:
        print(i)
```
### 3. Write a function that takes a name as input and prints a greeting.
```python
def greet(name):
    print(f"Hello, {name}!")
```
### 4. Use a `while` loop to print numbers from 10 to 1.
```python
i = 10
while i > 0:
    print(i)
    i -= 1
```
### 5. Write a program that skips printing multiples of 3 using `continue`.
```python
for i in range(1, 11):
    if i % 3 == 0:
        continue
    print(i)
```
### 6. Use `break` to stop printing numbers when the number reaches 7.
```python
for i in range(10):
    if i == 7:
        break
    print(i)
```
### 7. Write a lambda function to multiply a number by 10.
```python
multiply = lambda x: x * 10
print(multiply(5))
```
### 8. Create a function that returns the cube of a number.
```python
def cube(n):
    return n ** 3
```
### 9. Write a program to display the length of a user input string.
```python
text = input("Enter text: ")
print(len(text))
```
