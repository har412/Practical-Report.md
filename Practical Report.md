
# **PROGRAMMING FOR PROGRAM SOLVING ESC-18105**
## NAME-*HARKIRAT SINGH*
## ROLL NO-*1915031*
## BRANCH-*COMPUTER SCIENCE*
![LOGO](                     

# 1.Program to display a welcome message using puts  

```C
#include<stdio.h>     
int main()                                                                                                 
{  
puts("\nHELLO TO BUDDING ENGINEERS\n");  
return 0;  
}  
```     
## Output of program  

```C
HELLO TO BUDDING ENGINEERS  
```

# 2.Program to display address using puts  

```C
#include<stdio.h>  
int main()  
{  
puts("HARKIRAT SINGH \n CSE A1\n 1915031\n\
44/40 G Shaheed Bhagat Singh Nagar Pakhowal road ludhiana");  
return 0;  
}  

```
## Output of program

```C
HARKIRAT SINGH 
 CSE A1
 1915031
44/40 G Shaheed Bhagat Singh Nagar Pakhowal road ludhiana
```
# 3.Program to calculate sum of two numbers

```C
include<stdio.h>  
int main()  
{  
int a,b,c;  
printf("Enter the two no which you want to add : ");  
scanf("%d %d",&a,&b);  
c = a + b;  
printf("sum of given numbers is %d\n",c);  
return 0;  
}  
```

## Output of program

```C
Enter the two no which you want to add : 20 35
sum of given numbers is 55
```

# 4.Program to convert farenhiet to celcius

```C
#include<stdio.h>  
int main()  
{  
float f,c;   
printf(" Enter degree of farenhiet:  ");  
scanf("%f",&f);  
c=(f-32)*5/9;  
printf("The coverted value of  %f farenhiet is : %f Celsius\n",f,c);  
return 0;  
}  
```

## Output of the program

```C
Enter degree of farenhiet:  45
The coverted value of  45.000000 farenhiet is : 7.222222 Celsius
```

# 5.Program to find area and perimeter of circle

```C
include<stdio.h>
# define pi 3.141
int main()
{
float a,r,b; 
printf("Enter the magnitude of radius of circle :");
scanf("%f",&r);
a=pi*r*r;
b=2*pi*r;
printf("Area of the circle is %f \n",a);
printf("perimeter of  the circle is %f \n ",b);
return 0;
}
```

## Output of the program

```C
Enter the magnitude of radius of circle :3
Area of the circle is 28.268999  
perimeter of  the circle is 18.846001 
```

# 6.Program to find number is odd or even

```C
include<stdio.h>
int main()
{
int n;
printf("Enter the no : ");
scanf("%d",&n);
if(n%2==0)
printf(" no is even\n");                                                                                 
else
printf("no is odd\n");      
return 0;                                                                                              
}                                                                                                                                                                          
```

## Output of the program

```C
Enter the no : 45
no is odd
```

# 7.Program to find factorial of a number
                                                                      
```C
include<stdio.h>
int main()
{
int i,ans=1,n;                                                                                         
printf("Enter the no:  ");
scanf("%d",&n);
for(i=1;i<=n;i++)
ans=ans*i;
printf("factorial of given no is : %d\n",ans);
return 0;
}
 ```
 
 ## Output of the program
 
 ```C
 Enter the no:  5
factorial of given no is : 120
 ```
 
 # 8.Program to reverse a number
 
 ```C
 include<stdio.h>

int main()
{
int n,ans=0,r;
printf("Enter the no : ");
scanf("%d",&n);                                                                                        
while(n>0)
{
r=n%10;
ans=ans*10+r;
n=n/10;
}
printf("Reverse of the given no is : %d\n",ans);
return 0;
} 
```

## Output of the program

```C
Enter the no : 56234
Reverse of the given no is : 43265
 ```
# 9.Prgram for fizz buzz game

```C
 #include<stdio.h>

int main()
{
int i,n;
printf("Enter the limit: ");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if(i%3==0&&i%5!=0)
printf("fizz\n");
if(i%5==0&&i%3!=0)
printf("buzz\n");
if(i%3==0&&i%5==0)
printf("fizzbuzz\n");
if(i%3!=0&&i%5!=0)
printf("%d\n",i);
}
return 0;
}                                                                   
```

## Output of the program

```C
Enter the limit: 20
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
16
17
fizz
19
buzz
```

# 10.Program to display days of week using switch case

```C
#include<stdio.h>

int main()
{
int n;
printf(" Enter m for monday t for tuesday w for wednesday h for thursday f for friday s for saturday  : ");
scanf("%c",&n);
switch(n)
{
case 'm':printf("monday\n");
break;
case 't':printf("tuesday\n");
break;
case 'w':printf("wednseday\n");
break;
case 'h':printf("thursday\n");
break;
case 'f':printf("friday\n");
break;
case 's':printf("saturday\n");
break;
}
return 0;
}
```

## Output of the program
```C
 Enter m for monday t for tuesday w for wednesday h for thursday f for friday s for saturday  : t
tuesday
```

# 11.Program to make a simple arithmetic calculator
```C
#include<stdio.h>

int main()
{
char op;
float  num1,num2,result;
printf("Enter [num1] [+ - * /] [num2]\n");
scanf("%f %c %f",&num1,&op,&num2);

switch (op)
{
case '+':
result=num1+num2;
break;
case '-':
result=num1-num2;
break;
case '*':
result=num1*num2;
break;
case '/':
result=num1/num2;
break;
default:
printf("not valid operation");
}
printf("%.2f %c %.2f= %.3f",num1,op,num2,result);
return 0;
}
```

## Output of the program
```C
Enter [num1] [+ - * /] [num2]
56/2
56.00 / 2.00= 28.000
```
# 12.Program to check whether year is leap or not

```C 
#include<stdio.h>

int main()
{
int n; 
printf("Enter the year u want to check it for leap :");
scanf("%d",&n);
if(n%4==0)
printf("it is a leap year\n");
else
printf(" not a leap year\n");
return 0;
}
```

## Output of the program
```C
Enter the year u want to check it for leap :2016 
it is a leap year
```

# 13.Program to check whether number is palindrome or not

```C
#include<stdio.h>

int main()
{
int temp,n,r,ans=0;
printf("Enter the no : " );
scanf("%d",&n);
temp=n;
while(n>0)
{
r=n%10;
ans=ans*10+r;
n=n/10;
}
if(ans==temp)
printf("it is a palindrome no\n");
else
printf("it is not a palindrome no\n");
return 0;
}
```

## Output of the program

```C
Enter the no : 121
it is a palindrome no
```

# 14.Program to display fibonacchi series

```C
#include<stdio.h>

int main()
{
int n,a=0,b=1,c,i;
printf(" Enter the  no of fibonachi terms u want to print: ");
scanf("%d",&n);
printf("%d\t%d\t",a,b);
for(i=1;i<=n-2;i++)
{
c=a+b;
printf("%d\t",c);
a=b;
b=c;
}
return 0;
}
```

## Output of the program

```C
Enter the  no of fibonachi terms u want to print: 10
0       1       1       2       3       5       8       13      21      34 
```

# 15.Program to enter and display 1D array

```C
#include<stdio.h>

int main()
{
  int array[6],i;   //array declaration
printf("Enter the 6 elments of array :\n ");
for(i=0;i<6;i++)
{
  scanf("%d",&array[i]);
}
printf("Elements of array inputted by you are:\n ");

for(i=0;i<6;i++)
{
   printf("%d\t",array[i]);
}
return 0;
}
```

## Output of the program
```C
Enter the 6 elments of array :
 1
2
3
4
5
6
Elements of array inputted by you are:
 1      2       3       4       5       6  
 ```
 # 16.Program to enter and display 2D array
 ```C
 #include<stdio.h>

int main()
{
  int arr[3][5],i,j;
printf("Enter the elements of array : \n");

for(i=0;i<3;i++)
{
   for(j=0;j<5;j++)
   scanf("%d",&arr[i][j]);
}

printf("2D array entered by you is : \n");

for(i=0;i<3;i++)
{
   for (j=0;j<5;j++)
    printf("%d\t",arr[i][j]);
printf("\n");
}

return 0;
}
```

## Output of the program

```C
Enter the elements of array : 
1
2
3
4
5
6
7
8
9
12
12
2
32
6
8
2D array entered by you is : 
1       2       3       4       5
6       7       8       9       12
12      2       32      6       8
```

# 17.Program for addition of two matrices

```C
#include<stdio.h>

int main()

{ int a[3][3],b[3][3],c[3][3],i,j;

printf("Enter the elements of matrix A : \n");

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d\n",&a[i][j]);
}

printf(" enter the elements of matrix B\n");

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d\n",&b[i][j]);
}

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[i][j]=a[i][j]+b[i][j];
}
printf("matix A + B = \n");

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d\t",c[i][j]);
printf("\n");
}
return 0;
}
```

## Output of the program

```C
Enter the elements of matrix A : 
1
2
3
4
5
6
7
8
9
1
 enter the elements of matrix B
12
3
4
2
35
6
9
65
4
matix A + B = 
2       14      6
8       7       41
13      17      74
```

# 18.Program of subtraction of two matrices

```C
#include<stdio.h>

int main()
{
int a[3][3],b[3][3],c[3][3],i,j;

 printf("Enter the elements of array A : \n");

for(i=0;i<3;i++)
{
  for(j=0;j<3;j++)
   scanf("%d",&a[i][j]);
}

printf("Enter the elements of array B : \n");

for(i=0;i<3;i++)
{
  for(j=0;j<3;j++)
   scanf("%d",&b[i][j]);
}

for(i=0;i<3;i++)
{
  for(j=0;j<3;j++)
  c[i][j]=a[i][j]-b[i][j];
}

printf("result A - B = :\n");
for(i=0;i<3;i++)
{
  for(j=0;j<3;j++)
  printf("%d\t",c[i][j]);
printf("\n");
}
return 0;
}
 ```
 
 ## Output of the program
 
 ```C
 Enter the elements of array A : 
1
2
3
4
5
6
93
6
5
Enter the elem.Pents of array B : 
57
3
612
2
3
1
1
5
8
result A - B = :
-56     -1      -609
2       2       5
92      1       -3
```

# 19.Progarm of matrix transpose

```C
#include<stdio.h>

int main()

{ int a[3][3],c[3][3],i,j;

printf("Enter the elements of matrix A : \n");

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d\n",&a[i][j]);
}

for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[j][i]=a[i][j];
}

printf(" transpose of matrix A :\n");


for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d\t",c[i][j]);
printf("\n");
}
return 0;
}
```

## Output of the program

```C
2
3
456
6
96
4
2
7
8
 transpose of matrix A :
1       456     4
2       6       2
3       96      7
```

# 20.Progarm of matrix multiplication

```C
#include<stdio.h>

int main()
{
int a[3][3],b[3][3],c[3][3],i,j;

printf("Enter the values of matrix a : \n");

for(i=0;i<3;i++)
{
   for(j=0;j<3;j++)
   scanf("%d",&a[i][j]);
}
printf("Enter the values of matrix b:\n ");
for(i=0;i<3;i++)
{
    for(j=0;j<3;j++)
        scanf("%d",&b[i][j]);
}
for(i=0;i<3;i++)
{
     for(j=0;j<3;j++)
     c[i][j]=a[i][0]*b[0][j]+a[i][1]*b[1][j]+a[i][2]*b[2][j];
}
printf("matrix a * b = \n");
for(i=0;i<3;i++)
{
    for(j=0;j<3;j++)
     printf("%d\t",c[i][j]);
    printf("\n");
}
return 0;
}
```
## Output of the program

```C
Enter the values of matrix a : 
1
2
3
4
5
6
1
1
2
Enter the values of matrix b:
 5
5
63
12
8
5 
9
4
3
matrix a + b = 
56      33      82
134     84      295
35      21      74
```

# 21.Program to find square of a number using function

```C
#include<stdio.h>
int square(int n);   // function declaration  or  function prototype
int main()
{
int ans,n;
printf("Enter the no : ");
scanf("%d",&n);
ans=square(n);     //function call
printf("square of given no is : %d\n",ans);
return 0;
}
int square(int n)  // function defination
{
  n=n*n;
return n;
}
```

## Output of the program

```C
Enter the no : 5
square of given no is : 25
```
# 22.Program of swapping of two numbers using call by value

```C
#include<stdio.h>

void swap(int a,int b);
void swap(int a,int b)
{
  int c;
c=a;
a=b;
b=c;
}

int main()
{

   int a,b;
printf("Enter two numbers :");
scanf("%d %d",&a,&b);
printf("value of a and b before swapping :%d %d\n ",a,b);
swap(a,b);
printf("value of a and b after swap :%d %d\n",a,b);
return 0;
}
```
## Output of the program

```C
Enter two numbers :5 6
value of a and b before swapping :5 6
 value of a and b after swap :5 6
```

# 23.Program to swap two numbers using call by reference

```C
#include<stdio.h>

void swap(int *a,int*b);
void swap(int *a,int*b)
{
int temp;
temp=*a;
*a=*b;
*b=temp;
}
int main()
{
int a,b;
printf("Enter the two numbers :");
scanf("%d %d",&a,&b);
printf("Values of a and b before swap: %d  %d\n",a,b);
swap(&a,&b);
printf("values of a and b after swap: %d  %d\n",a,b);
return 0;
}
```

## Output of the program

```C
Enter the two numbers :5 6
Values of a and b before swap: 5  6
values of a and b after swap: 6  5
```

# 24.Program to find factorial of a number using recursion 
 
 ```C
 
#include<stdio.h>
int fact(int n);
int fact(int n)
{
int ans;
if(n==0)
ans=1;
else
ans=n*fact(n-1);
return ans;
}

int main()
{
int n,result;
printf("Enter the no whose factorial you want to get : ");
scanf("%d",&n);
 result=fact(n);
printf("factorial of %d is: %d \n",n,result);
return 0;
}
```

## Output of the program
```C
Enter the no whose factorial you want to get : 5
factorial of 5 is: 120 
```

# 25.Program to display fibonacchi series using recursion

```C
#include<stdio.h>

 int fibonacchi(int n);

int main()
{
int i,n,c=0;
printf("Enter the no of fibonacchi terms you want to print: ");
scanf("%d",&n);
for(i=1;i<+n;i++)
{
  printf("%d\n",fibonacchi(c));
     c++;
}
return 0;
}

int fibonacchi(int n)
{
    if(n==0)
   return 0;
   if(n==1)
    return 1;
else
    return(fibonacchi(n-1) + fibonacchi(n-2));
}
```

## Output of the program
```C
Enter the no of fibonacchi terms you want to print: 10
0
1
1
2
3
5
8
13
21
```

# 26.Program to enter and  display elements of structure

```C
#include<stdio.h>

struct data
{
 char name[20];
 char branch[10];
  int roll_no;
};

int main()
{
struct data c;   //declared data type and variable
printf("Enter your name,branch,roll no :\n");
scanf("%s %s %d",&c.name,&c.branch,&c.roll_no);
printf("YOUR DATA\n name : %s\nbranch : %s\nroll no : %d\n",c.name,c.branch,c.roll_no);
return 0;
}
```

## Output of the program
```C
Enter your name,branch,roll no :
harkirat
cse
1915031
YOUR DATA
 name : harkirat
branch : cse
roll no : 1915031
```

# 27.Program to enter data of 5 students using array in structures

```C
#include<stdio.h>

struct record
{
int roll_no;
char name[20];
int marks;
long contact_no;
};

int main()
{
int i;
struct record r[5];
for(i=1;i<6;i++)
{
  printf("STUDENT %d \nEnter roll no,name,marks,contact no: ",i);
scanf("%d %s %d %ld",&r[i].roll_no,&r[i].name,&r[i].marks,&r[i].contact_no);
}
for(i=1;i<6;i++)
{
   printf("for student %d \n roll no :%d \n name: %s  \n marks: %d \n contact no: %ld \n\n ",i,r[i].roll_no,r[i].name,r[i].marks,r[i].conta$
}
return 0;
}
```

## Output of the program 
```C

Enter roll no,name,marks,contact no: 1
harkirat
56
5494656313
Enter roll no,name,marks,contact no: 2
gursewak
62
264654656563
STUDENT 3 
Enter roll no,name,marks,contact no: 3
jasjot
95
56556556562
STUDENT 4 
Enter roll no,name,marks,contact no: 4
harjit
75
651626323123
STUDENT 5 
Enter roll no,name,marks,contact no: 5     
harjot
65
56565262526352
for student 1 
 roll no :1 
 name: harkirat  
 marks: 56 
 contact no: 5494656313 

 for student 2 
 roll no :2 
 name: gursewak  
 marks: 62 
 contact no: 264654656563 

 for student 3 
 roll no :3 
 name: jasjot  
 marks: 95 
 contact no: 56556556562 

 for student 4 
 roll no :4 
 name: harjit  
 marks: 75 
 contact no: 651626323123 

 for student 5 
 roll no :5 
 name:   
 marks: 65 
 contact no: 56565262526352 
```

***
***

                                       
