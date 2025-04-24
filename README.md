# Experiment-7

## Write a python program for sorting and inspect for failures. 

## Algorithm:

1. Start the program.

2. Get the number of elements from user

3. Get the elements to be sorted

4. Traverse the array and sort the elements one by one

5. Print the sorted array

6. Stop the program. 

# Program:
```
n = int(input("Enter the number of elements: "))  
arr = []  

try:  
    for i in range(n):  
        a = float(input("Enter the element: "))  
        arr.append(a)  

    # Bubble sort (corrected)
    for i in range(n):  
        for j in range(n - i - 1):  
            if arr[j] > arr[j + 1]:  # Compare adjacent elements  
                temp = arr[j]  
                arr[j] = arr[j + 1]  
                arr[j + 1] = temp  

    print("The array after sorting: ", end="")  
    for i in range(n):  
        print(arr[i], end=" ")  

except ValueError:  
    print("Enter a valid number")
```
# Output

![Screenshot 2025-03-29 103507](https://github.com/user-attachments/assets/5e014d98-c2d2-420e-8b20-1edc26c33954)

![Screenshot 2025-03-29 103605](https://github.com/user-attachments/assets/e51902cd-8049-4fc2-b715-1798cb1c5c32)

![Screenshot 2025-03-29 103707](https://github.com/user-attachments/assets/857f2cbb-bfda-45a4-9b3d-ff2497ca4a3a)

![Screenshot 2025-03-29 103913](https://github.com/user-attachments/assets/4765f124-9cc1-4eba-9db8-ee76ae448a87)

![Screenshot 2025-03-29 103957](https://github.com/user-attachments/assets/32a8649c-f734-49cd-b818-a4475b45cba0)

![Screenshot 2025-03-29 104057](https://github.com/user-attachments/assets/b83c85a6-4004-41cb-b4e9-e994fc8382db)

![Screenshot 2025-03-29 104325](https://github.com/user-attachments/assets/d19d7838-7021-4490-9f90-89158e8b53d6)

![Screenshot 2025-03-29 104431](https://github.com/user-attachments/assets/ca30b0ff-286e-4fc6-93d2-a8ef2e700afb)

![Screenshot 2025-03-29 104529](https://github.com/user-attachments/assets/4f053bd7-5db2-4c6d-ba3c-9d86e93c01dc)

![Screenshot 2025-03-29 104621](https://github.com/user-attachments/assets/570759a3-369f-49b4-b42b-e213890ce0a4)

# Result
Thus, a program to check sorting has been written and test cases have been written and verified 
successfully.
