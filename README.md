# Python coding questions frombasics to advanced
<1> PYTHON PROGRAM TO PRINT A GIVEN NUMBER IS EVEN OR ODD
            a=int(input())
            if a%2==0:
               print("Given numbr is even")
            else:
                print("Given number is oddd")

 <2> PYTHON PROGRAM TO CHECK GIVEN NUMBER IS POSITIVE OR NEGATIVE
          a=int(input())
           if a==0:
              print("Given number is zero")
           elif a<0:
               print("Givennumber is negative")
           else:
               print("Given number is positive")

   <3> PYTHON PRORAMTO FIND SUM OF TWO NUMBERS
           a=int(input())
           b=int(input())
           print(a+b)

   <4> PYTHON  PROGRAM TOCHECK GIVEN NUMBER IS PRIME OR NOT:

            num=int(input())
            count=False
            for i in range(2,num):
            if num%i==0:
               count=True
               break
            if count==False:
                print("Given number is prime")
            else:
                print("given number is not prime")
      <5>PYTHON PROGRAM TO CHECK GIVEN NUMBER IS PALINDROME OR NOT:
              num=int(input())
              temp=num
              rev=0
              whilenum>0:
                remainder=n%10
                rev=(rev*10)+remainder
                num=num//10
              if temp==num:
                 print("palindrome")
              else:
                  print("not palindrome")
<6>PYTHON PROGRAM TO CHECK GIVEN NUMBER IS AN ARMSTRONG NUMBER OR NOT
            num=int(input())
             temp=num
             sum=0
             while num>0:
                 remainder=num%10
                 sum=remainder**3
                 num=num//10
             if num==remp:
                 print("Given number is an armstrong")
             else:
             print("Given number is not an armstrong number")
<7>  PYTHON PROGRAM TO CHECK GIVEN STRING IS ANAGRAM OR NOT
             s1=input()
             s2=input()
             a=sorted(s1)
             b=sorted(s2)
             if a==b:
                print9"Given number is an anagram")
             else:
             print("Given number is not an anagram")
<8>PYTHON PROGRAM TO PRINT MAXIMUM OF TWO NUMBERS
       a=int(input())
       b=int(input())
       if a>b:
         print(a," is greater")
      else:
          print(b,"is greater")
 <9>PYTHON PROGRAM TO FIND MAXIMUM OF THREE NUMBERS
          a=int(input())
          b=int(input())
          c=int(input())
          if a>b and a<c:
              print(a," is greater")
          elif b>a and b>c:
               print(b," is greater")
          else:
          print(c,"is greater")

<10> PYTHON PROGRAM TO FIND FACTORIAL OF A NUMBER
        def factorial(a):
             if num<1:
               return 1
             else:
             return a*factorial(a-1)
        num=int(input())
        print(factorial(num))
<11> PYTHON PROGRAM TO PRINT FIBONACCI SERIES
      n1=0
      num=int(input()
      n2=1
      print(n1,n2)
      for i in range(0,num+1):
           n3=n1+n2
           print(n3 ,end=",")
           n1=n2
           n2=n3
<12>   PYTHON PROGRAAM TO PRINT  APATTERN
       n=int(input())
       for i in range(0,n):
           for j in range(0,i+1):
                print("*" ,end=" ")
      
<13>PYTHON PROGRAM TO PRINT SPECIAL PASCAL TRIANGLE
from math import factorial
rows=int(input("enter the number of rows")
 for n in range(rows):
    for j in range(1,rows-n):
        print(end=" ")
    for n range(n+1):
        ncr=factorial(n)//(factorial(r)*factroial(n-r))
        print(ncr,emd=" ")
    print('')
<13> C PROGRAM TO FIND GEOMETRIC SEQUENCE OF TWO SERIES:
           #include<stdio.h>
#include<math.h>
int main(){
    int n;
    scanf("%d",&n);
    if (n%2!=0){
        int a=1;
        int r=2;
        int term =(n+1)/2;
        int result=a*pow(2,term-1);
        printf("%d",result);
    }
    else{
        int a=1;
        int r=3;
        int term=n/2;
        int result=a*pow(3,term-1);
        printf("%d",result);
    }
}

<14> PYTHON PROGRAM TO FIND ANGLE IN DEGREES WITH TWO INPUT SIDES
    # Enter your code here. Read input from STDIN. Print output to STDOUT
from math import atan2,degrees
a=int(input())
b=int(input())
c=str(round(degrees(atan2(a,b))))
print(f'{c}\xb0')

<15> HACKER RANK PROBLEM ..INTRODUCTION TO SETS

       def average(array):
    # your code goes here
    array1=set(array)
    a=sum(array1)
    b=len(array1)
    c=a/b 
    return c
if __name__ == '__main__':
    n = int(input())
    arr = list(map(int, input().split()))
    result = average(arr)
    print(result)

<16> python program for minf d game
    import random
a=random.randint(1,10)
b=int(input())
c=a+a
d=c+b
e=d/2
f=e-a
print(int(f))
<17> python program to print palindrome triangle:
for i in range(1,int(input())+1): 
    print((((10**i)-1)//9)**2)
    
<18> PYTHON PROGRAM TO PRINT CLOSET NUMBER AND DIVISIBLE TO ANOTHER NUMBER
      n,m=map(int,input().split())
a=(n//m)*m
b=a+m
if((b-n)<=(n-a)):
    print(b)
else:
    print(a)
    
<19> python program to find the return change:

      n=int(input())
a=(n//10)*10
b=a+10
if((b-n)<=(n-a)):
    print(100-b)
else:
    print(100-a)
   <20> PYTHON PROGRAM WITH USING SUPER KEYWORD

   class parent:
    def show(self):
        print("this is parent class")
class child(parent):
    def display(self):
        print("this is a child class")
    def show(self):
        super().show()
child=child()
child.display()
child.show()

<21> PYTHON PROGRAM HECK WETHER THE TWO RECTANGLES ARE OVERLAP OR NOT:
     import math
ax1,ay1,ax2,ay2=map(int,input().split())
bx1,by1,bx2,by2=map(int,input().split())
cx1=max(ax1,bx1)
cx2=min(ax2,bx2)
cy1=max(ay1,by1)
cy2=min(ay2,by2)
d1=cx2-cx1
d2=cy2-cy1
if (d1>0 and d2>0):
    print("1")
else:
    print("0")

<22>PYTHON PROGRAM TO FOR HACKER MAN 

  a,b=map(int,input().split())
c=a+b
l1=[2,3,5,7,11]
if c in l1:
    print("Alice")
else:
    print("Bob")

 <23>PYTHON PROGRAM FOR DRAWING BOOK

  n=int(input())
p=int(input())
a=p//2
b=(n//2)-(p//2)
if (a<b):
    print(a)
else:
    print(b)

   <24>PYTHON PROGRAM FOR CHEF AND CHACOLATE

     x,y,z=map(int,input().split())
a=x*5
b=y*10
c=a+b
d=c//z
print(d)

<25>PYTHON PROGRAM FOR CLOSEST NUMBER

  n,m=map(int,input().split())
a=(n//m)*m
b=a+m
if((b-n)<=(n-a)):
    print(b)
else:
    print(a)
    <26> PYTHON PROGRAM FOR ONLINE OR OFFLINE

        n,m=map(int,input().split())
a=n*0.1
b=n-a
if(m<b):
    print("offline")
else:
    print("online")

   <27>PYTHON PROGRAM FOR RETURN THE CHANGE

    n=int(input())
a=(n//10)*10
b=a+10
if((b-n)<=(n-a)):
    print(100-b)
else:
    print(100-a)

<28>PYTHON PROGRAM FOR HACKER MAN

 a,b=map(int,input().split())
c=a+b
l1=[2,3,5,7,11]
if c in l1:
    print("Alice")
else:
    print("Bob")

  <29>PYTHON PROGRAM TO FIND ATTENDANCE ARWS FOR STUDENTS:
  
class Solution:
    def checkRecord(self, s: str) -> bool:
        count_absent=s.count("A")
        count_late=s.count("L")
        if(count_absent<2 and 'LLL' not in s):
            return True
        else:
            return False    
      <30>program to print the pattern given below
      
            *
            * *
            * * *
            *  * * *

     num=int(input())
     for i in range(1,num+1):
        for j in range(1,i+1):
           print("*",end=" )
        print()
     <31> program toprint the pattern given below
           * * * *
           * * *
           * *
           *
       n=int(input())
       for i in range(num,0,-1):
            for j in range(1,i):
                print("*",end=" ")
           print() 
           
<32>python program to print stars in heart shape

#python program to print the heart shape 
for i in range(6):
    for j in range(7):
        if(i==0 and j%3!=0)or (i==1 and j%3==0) or (i-j==2) or (i+j==8):
            print("*",end=" ")
        else:
            print(end=" ")
    print()        

    <33> pythonprogram t print full triangle
        *
       * *
      * * * 
     * * * * 

     #python program to print the heart shape 
#python program to print the heart shape 
 n=6
for i in range(n):
    for j in range(i,n):
        print(" ",end=" ")
    for j in range(i):
        print("*",end=" ")
    for j in range(i+1):
        print("*",end=" ")
    print()       
    










       
