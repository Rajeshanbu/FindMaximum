# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.

# Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm:
Get the list of marks as input
Use the sort() function or max() function or use the for loop to find the maximum mark.
Return the maximum value
# Program:
# i) To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: Rajesh A
RegisterNumber: 22008551
```
```
def max_marks(marks):
    marks.sort()
    return marks[-1]
 ```
# ii) To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Rajesh A
RegisterNumber: 22008551
```
```
def max_marks(marks):
    return (max(marks))
 ```
# iii) To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Rajesh A
RegisterNumber: 22008551
```
```
def max_marks(list1):
    max_value=0
    for i in list1:
        if i>max_value:
            max_value=i
    return max_value
 ```
    
# Sample Input and Output
![sampleinput](https://user-images.githubusercontent.com/118924713/214592204-b72ffdd8-44da-4152-99b0-f46ec17d50d3.jpg)


# Output:
i) To find the maximum of marks using the list method sort.
![MAX1](https://user-images.githubusercontent.com/118924713/214592066-7b131185-8378-459a-9e65-f240f1dfc996.png)


ii) To find the maximum marks using the list method max().

![MAX2](https://user-images.githubusercontent.com/118924713/214592085-8c382783-37d6-4875-a91b-3017ac781e5d.png)

iii) To find the maximum marks without using builtin functions.

![MAX3](https://user-images.githubusercontent.com/118924713/214592111-91941ea7-c552-439b-b47a-cf951a260878.png)

# Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
