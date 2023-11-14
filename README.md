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


Program to mark the maximum of marks using the list method sort

Developed by: mahalakshmi.k

RegisterNumber: 212222240057


def max_marks(marks):

   marks.sort()
   
   large=marks[-1]
   
   return large





ii)	# To find the maximum marks using the list method max().


Program to find the maximum marks using the list method max().

Developed by: mahalakshmi.k

RegisterNumber: 212222240057


def max_marks(marks):

    large=max(marks)
    
    return large


iii) # To find the maximum marks without using builtin functions.


Program to the maximum marks without using builtin functions.

Developed by:mahalakshmi.k 

RegisterNumber:212222240057 


def max_marks(list1):

    max1=list1[0]
    
    for i in list1:
    
        if i > max1:
        
            max1=i
            
    return max1

 

## Output:

![Screenshot (23)](https://github.com/maha712/FindMaximum/assets/121156360/2fb6fca6-a201-4808-9a24-936564b60502)

![Screenshot (24)](https://github.com/maha712/FindMaximum/assets/121156360/5a207904-10f5-4292-b051-f280cf49939f)


![Screenshot (25)](https://github.com/maha712/FindMaximum/assets/121156360/fa0ee7cc-f95d-460a-a24f-199aeb121149)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
