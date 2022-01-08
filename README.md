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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Sowmiya N 
RegisterNumber: 21500134
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    maxnum=marks[-1]
    return maxnum


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Sowmiya N 
RegisterNumber: 21500134
'''
def max_marks(marks):
    # write your code here
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Sowmiya N 
RegisterNumber: 21500134
'''
def max_marks(list1):
    # write your code here
    max_value=0
    for i in list1:
        if i>max_value:
            max_value=i
    return (max_value)


```

## Output:

i)	# To find the maximum of marks using the list method sort.

![output](./img/PY7I.png) 

ii)	# To find the maximum marks using the list method max().

![output](./img/PY7II.png)

iii) # To find the maximum marks without using builtin functions.

![output](./img/PY7III.png) 

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.