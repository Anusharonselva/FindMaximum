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

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large=max(marks)
    return large
    

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max= i
    return max
            

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (206)](https://github.com/Anusharonselva/FindMaximum/assets/119405600/b1e4feb7-e0c5-4c63-acaf-58a4511c5ce0)

![Screenshot (207)](https://github.com/Anusharonselva/FindMaximum/assets/119405600/aa5ecd78-add2-413c-8abe-479bc3a79522)

![Screenshot (208)](https://github.com/Anusharonselva/FindMaximum/assets/119405600/a9c454ca-ccbb-4e3d-b261-a1efa809fda5)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
