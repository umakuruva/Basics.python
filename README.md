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















       
