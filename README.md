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

i) To find the maximum of marks using the list method sort.
```Python

def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])

```

ii) To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    a=max(marks)
    return a

```

iii) To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    
```
## Output:
i)
![output](./img/scr1.png) 
ii)
![output](./img/scr2.png) 
iii)
![output](./img/scr3.png) 

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.