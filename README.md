# assignment-1-23.02.2022
Write  a program to range of maximum and minimum 
l=[]
n=int(input('enter n'))
for i in range(n):
   c=int(input())
   l.append(c)
min=l[0]
for i in range(1,n):
   if l[i]<min:
     min=l[i]
max=l[0]
for i in range(1,n):
   if l[i]>max:
     max=l[i]
 
print(min) 
print(max)
Output
Enter number:4
23
25
36
63
Minimum value:63
Maximum value:23
