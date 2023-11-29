# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: SUDHARSAN RAM M
RegisterNumber: 212222110048
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: SUDHARSAN RAM M
RegisterNumber: 212222110048
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: SUDHARSAN RAM M
RegisterNumber: 212222110048
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
# To find the maximum of marks using the list method sort.
![image](https://github.com/Sudharsanram/FindMaximum/assets/119393980/d196430b-3124-4f49-afb4-ecb590ad0134)

# To find the maximum marks using the list method max().
![image](https://github.com/Sudharsanram/FindMaximum/assets/119393980/7883555c-520f-4a8c-b000-3fa85cfc8e61)

# To find the maximum marks without using builtin functions.
![image](https://github.com/Sudharsanram/FindMaximum/assets/119393980/f8a1526a-a5d9-451d-90ad-2b7cf23bb98f)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
