# Second-largest-number

a=[]
n=int(input("Enter the number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter the element:"))
    a.append(b)
a.sort()
print("Second largest element is:",a[n-2])

Output-

Enter the number of elements:5
Enter the element:24
Enter the element:35
Enter the element:71
Enter the element:52
Enter the element:68
Second largest element is: 68
