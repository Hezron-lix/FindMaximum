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
Developed by: Hezron Belix
RegisterNumber: 23009905
'''
def max_marks(marks):
    marks.sort()
    a=marks[-1]
    return a
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Hezron Belix
RegisterNumber: 23009905
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Hezron Belix
RegisterNumber: 23009905
'''
def max_marks(list1):
    m=0
    for i in list1:
        if i>m:
            m=i
    return m  
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output](/one.png)
![output](/two.png)
![output](/three.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.