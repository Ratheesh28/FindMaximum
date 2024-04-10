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
 # Program Name :  Find the maximum of a list of numbers
 # Name : RATHEESHKUMAR B R
 # Register Number : 212223110040
def max_marks(m):
    m.sort()
    high=m[-1]
    return high



```

ii)	# To find the maximum marks using the list method max().
```
 # Program Name : To find the maximum marks using the list method max().
 # Name : RATHEESHKUMAR B R
 # Register Number : 212223110040
def max_marks(m):
    large=max(m)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
 # Program Name :To find the maximum marks without using builtin functions.
 # Name : RATHEESHKUMAR B R
 # Register Number : 212223110040

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```



## Output:
![Screenshot 2024-04-10 134049](https://github.com/Ratheesh28/FindMaximum/assets/138849186/1678abb8-d6a9-4175-b340-1c7d18edd693)
![Screenshot 2024-04-10 134141](https://github.com/Ratheesh28/FindMaximum/assets/138849186/507b0540-2119-4d92-9310-27849385994a)
![Screenshot 2024-04-10 134817](https://github.com/Ratheesh28/FindMaximum/assets/138849186/5dc5d868-550a-4455-ba1c-bc5b0ea73b19)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
