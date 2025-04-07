# Day 1 Worksheet with Answers


### **1. Digital ID Card**
Create a digital ID card using variables. Store and print:
   - Full name
   - Department
   - Year of study
   - University name <br>
##### **Solution**
```python
full_name = "Priya"
department = "Data Analytics"
year = 2
university = "VIT University"
print(f"I’m {full_name} from the {department} department, year - {year} at {university}.")
```

### 2. **Salary with Increment**
A company has increased all employees’ base salary of ₹50,000 by 12%.
   - Store the base salary
   - Calculate the increment
   - Use assignment operator to update and print the new salary.

##### **Solution**
```python
salary = 50000
increment = salary * 0.12
salary += increment
print("Updated salary:", salary)
```

### 3. **Programming Languages List**
Create a list of five programming languages.
   - Print the third language
   - Replace the last language with 'Python' and print the list.
##### **Solution**
```python
languages = ['Java', 'C', 'JavaScript', 'Ruby', 'Go']
print(languages[2])  # Output: JavaScript
languages[-1] = 'Python'
print(languages)     # Updated list: ['Java', 'C', 'JavaScript', 'Ruby', 'Python']
```

### 4. **Student Dictionary**
Create a dictionary for a student:
   {'name': 'Arun', 'reg_no': '21CS001', 'course': 'ML'}
   - Add a 'cgpa' key with value 9.1
   - Print the dictionary
##### **Solution**
```python
student = {'name': 'Arun', 'reg_no': '21CS001', 'course': 'ML'}
student['cgpa'] = 9.1
print(student)
# Output: {'name': 'Arun', 'reg_no': '21CS001', 'course': 'ML', 'cgpa': 9.1}
```

### 5. **Sales Report**
Store five months' revenue in a list: [25000, 27000, 26000, 31000, 29500]
   - Calculate and print total and average revenue.
##### **Solution**
```python
sales = [25000, 27000, 26000, 31000, 29500]
total = sum(sales)
average = total / len(sales)
print("Total Revenue:", total)    # 138500
print("Average Revenue:", average)  # 27700.0
```
### 6. **Candy Sharing**  
   You have 25 candies and 6 friends. Use arithmetic operators (`//` and `%`) to calculate how many each friend gets and how many are left over. Print both results.
##### **Solution**
```python
# Total candies and friends
candies = 25
friends = 6

# Calculate how many candies each friend gets (integer division)
each_friend = candies // friends

# Calculate how many candies are left over (modulus)
leftover = candies % friends

# Print the results
print(f"Each friend gets: {each_friend} candies")
print(f"Candies left over: {leftover}")
```

### 7. Fixing Variable Naming Errors
Identify and fix variable naming errors:
   - user-name = "Meena"
   - 2location = "Mumbai"
   - from = "India"
   - emp Name = "Raj"
   - _id = 1001
##### **Solution**
```python
   - user_name = "Meena"
   - location = "Mumbai"
   - from1 = "India"
   - empName = "Raj"
   - id_ = 1001
```