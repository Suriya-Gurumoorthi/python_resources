# 🧠 NumPy Worksheet – Practice (With Answers)

## 1. Create a 1-D NumPy array with values from 5 to 25 (step = 5)

```python
import numpy as np
arr = np.arange(5, 30, 5)
```

## 2. Create a 2x3 NumPy array filled with ones

```python
arr = np.ones((2, 3))
print(arr)
```
## 3. Generate 6 evenly spaced numbers between 0 and 1

```python
arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])
print(arr[1, 2])

```
## 4. Create the following array and access the element at 2nd row, 3rd column from this array:

|---|---|---|
| 1 | 2 | 3 |
| 4 | 5 | 6 |
| 7 | 8 | 9 |

```python

```

## 5. Create a 1-D array `[10, 20, 30, 40, 50]` and slice the last 3 elements. Print the result.
```python
import numpy as np
array = np.array([10, 20, 30, 40, 50])
sliced = array[-3:]
print(sliced)
```
## 6. Find max, min, mean, std of this array: `[10, 20, 30, 40, 50]`
```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print("Max:", np.max(arr))       
print("Min:", np.min(arr))       
print("Mean:", np.mean(arr))     
print("Standard Deviation:", np.std(arr)) 

```
## 7. Create a 5x5 random matrix and find elements > 0.5
```python
import numpy as np

mat = np.random.rand(5, 5)
print("Matrix:\n", mat)

greater_than_half = mat > 0.5
print("\nValues > 0.5:\n", mat[greater_than_half])

```
## 8. Create two 3X3 random matrics and perform matrix addition, subtraction, multiplication
```python
import numpy as np

A = np.random.randint(1, 10, (3, 3))
B = np.random.randint(1, 10, (3, 3))

print("Matrix A:\n", A)
print("Matrix B:\n", B)

print("\nAddition:\n", A + B)
print("Subtraction:\n", A - B)
print("Multiplication (Dot Product):\n", np.dot(A, B))

```
## 9. Create a 2-D array [[1, 2, 3], [4, 5, 6]]. Change the element at 1st row, 3rd column to 10 and print the updated array.
```python
import numpy as np

arr = np.array([[1, 2, 3], [4, 5, 6]])
arr[0, 2] = 10  # Change 3 to 10
print("Updated array:\n", arr)
# Output:
# [[ 1  2 10]
#  [ 4  5  6]]
```
## 10. Create two 2-D NumPy arrays `[[1, 2], [3, 4]] and [[5, 6], [7, 8]].` Use `np.concatenate()` to stack them vertically (row-wise). Print the result. `(Hint: Use axis=0.)`
```python
import numpy as np
array1 = np.array([[1, 2], [3, 4]])
array2 = np.array([[5, 6], [7, 8]])
combined = np.concatenate((array1, array2), axis=0)
print(combined)
```
