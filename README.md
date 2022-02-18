# 18-02-2022-assignment--2

#assignment 2 write a program to print sum of n factorial of a given number

fno=1
sum=0
n=int(input("Enter the n:"))
for i in range(1,n+1):
    fno=fno*i
    sum=sum+fno
print("factorial of a given number :",fno)
print('sum of factorial is :',sum)



output:
=================== RESTART: C:/Python37/factorial sum.py ===================
Enter the n:4
factorial of a given number : 24
sum of factorial is : 33
>>> 
