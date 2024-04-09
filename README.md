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
![Screenshot 2024-04-01 000612](https://github.com/Ratheesh28/FindMaximum/assets/138849186/51a072c0-7d99-450a-b58a-3568b97842f7)
![Screenshot 2024-04-01 000646](https://github.com/Ratheesh28/FindMaximum/assets/138849186/1b66f018-61e7-4e78-aa30-f4b1d01aa716)
![Screenshot 2024-04-01 000656](https://github.com/Ratheesh28/FindMaximum/assets/138849186/7116da0b-060c-473a-aca0-98293265ab5a)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
