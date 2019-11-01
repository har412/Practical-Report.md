
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

                                                                      
                                                                      
                                                                      
