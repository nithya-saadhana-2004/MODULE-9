# 🧮 SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.

---

## 🎯 Aim

To develop a Python class with functions to:
- Create a list of integers
- Sort it using the **Insertion Sort** algorithm
- Display the sorted list

---

## 🧠 Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**

---

## 💻 PROGRAM:
```
  def create_matrix(n,m):
      M=[]
      for i in range(n):
          row=[]
          for j in range(m):
              x=int(input())
              row.append(x)
          M.append(row)
      return M 
  r,c=input().split()
  A=create_matrix(int(r),int(c))
  B=create_matrix(int(r),int(c))
  C=[]
  for i in range(int(r)):
      R=[]
      for j in range(int(c)):
          item=A[i][j]-B[i][j]
          R.append(item)
      C.append(R)
  print(A)
  print(B)
  print(C)
```
## OUTPUT:
<img width="752" height="802" alt="image" src="https://github.com/user-attachments/assets/c0c5e3d0-9076-4dd4-994c-3b1282ed0ec7" />

## RESULT:
<img width="752" height="802" alt="image" src="https://github.com/user-attachments/assets/9d0e5d92-1dbb-4266-94bc-1907faa835f5" />
