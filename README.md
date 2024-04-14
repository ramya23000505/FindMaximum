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
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(array):
    return max(array)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```

## Output:

# To find the maximum of marks using the list method sort.
![Screenshot 2024-03-27 094132](https://github.com/ramya23000505/FindMaximum/assets/149370791/81070451-21ab-4309-b131-246742e66db4)
![Screenshot 2024-03-27 094138](https://github.com/ramya23000505/FindMaximum/assets/149370791/851f8e40-696d-40b4-9a33-6303b973e617)
# To find the maximum marks using the list method max().
![Screenshot 2024-03-27 094144](https://github.com/ramya23000505/FindMaximum/assets/149370791/d84daad0-be73-45b3-b4b7-b41ee66159a5)
![Screenshot 2024-03-27 094207](https://github.com/ramya23000505/FindMaximum/assets/149370791/54f00561-1eee-4e1f-b86b-420072bd15ad)
# To find the maximum marks without using builtin functions.
![Screenshot 2024-03-27 094213](https://github.com/ramya23000505/FindMaximum/assets/149370791/6fe387dd-70dc-42b2-afcc-4bbf23636354)
![Screenshot 2024-03-27 094218](https://github.com/ramya23000505/FindMaximum/assets/149370791/b9e59d04-3417-49ea-8907-8ffc60540ea2)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
