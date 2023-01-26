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
Developed by: BEJIN.B
RegisterNumber: 22001908
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: B.BEJIN
RegisterNumber: 22001908
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: B.Bejin
RegisterNumber: 22001908
'''
def max_marks(list1):
    maximum=list1[0]
    for i in  list1:
        if i>maximum:
            maximum=i
    return maximum


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i,
![image](https://user-images.githubusercontent.com/118367518/214829766-7bc5bd62-d701-4c22-824d-b93ea03de915.png)
ii,
![image](https://user-images.githubusercontent.com/118367518/214829836-fff711d5-7610-4e66-a500-608f270d56d8.png)

iii,

![image](https://user-images.githubusercontent.com/118367518/214829897-3c62dab6-5901-4585-8aa0-3cc7e37dd5a4.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
