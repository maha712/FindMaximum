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
def linearSearch(array,n,k):
    for i in range(0,n):
        if array [i] ==k:
            return i
    return-1
array=eval(input())
k=eval(input())
n=len(array)
array.sort()
result = linearSearch(array,n,k)
if result==-1:
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ",result)


```

ii)	# To find the maximum marks using the list method max().
```Python
def binarySearchIter(array,k,low,high):
    while low <= high:
        mid = low + (high-low)//2
        if array[mid]==k:
            return mid
        elif array[mid]<k:
            low=mid+1
        else:
            high = mid-1
    return-1
array=eval(input())
array.sort()
k=eval(input())
result= binarySearchIter(array,k,0,len(array)-1)
if result==-1:
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ",result)


```

iii) # To find the maximum marks without using builtin functions.
```Python
def BinarySearch(arr,k,low,high):
    if low<=high:
        mid=low+(high-low)//2
        if array[mid]==k:
            return mid
        elif array[mid]>k:
            return BinarySearch(arr,k,low,mid-1)
        else:
            return BinarySearch(arr,k,mid+1,high)
    else:
        return-1
array=eval(input())
array.sort()
k=eval(input())
result=BinarySearch(array,k,0,len(array)-1)
if result==-1:
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ",result)


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (115)](https://github.com/maha712/FindMaximum/assets/121156360/c3b1a907-4044-4f7c-b0e9-81cd5605122d)
![Screenshot (116)](https://github.com/maha712/FindMaximum/assets/121156360/b4f7d463-6d3b-46e6-a16e-77cd972a0ad7)
![Screenshot (117)](https://github.com/maha712/FindMaximum/assets/121156360/fa843369-881a-47a9-9477-ef38b290d604)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
