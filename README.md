# Simple_calculator.py
a = int(input("Enter 1st number :"))
b = int(input("Enter 2nd number :"))
c = input("Enter the Opertaion +,-,/,*:")
print("The result is :", end='')
if c=='+':
        print(a+b)
elif c=='-':
    print(a-b)
elif c=='/':
    print(a/b)
elif c=='*':
    print(a*b)
else:
    print("Error : Wrong operator entered")


Output:
Enter 1st number :20
Enter 2nd number :15
Enter the Opertaion +,-,/,*:*
The result is :300
