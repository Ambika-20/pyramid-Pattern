# pyramid-Pattern
#To arrange the numbers in a pyramid pattern
n=int(input("Enter number of rows to be printed:"))
for i in range(0,n):
    for j in range(0,n-i-1):
        print(end=" ")
    for j in range(0,i+1):
        print(j,end=" ")
    print()
