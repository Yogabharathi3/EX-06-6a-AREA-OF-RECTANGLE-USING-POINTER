# EX-06-6a-AREA-OF-RECTANGLE-USING-POINTER
## AIM 
To write a C Program to find area of rectangle using pointer. 
## ALGORITHM 
1. Start the program. 
2. Read two numbers. 
3. Calculate the area of rectangle using the formula area=(*x)*(*y) 
4. Display the result. 
5. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
int main() 
{ 
float l,b,*x,*y,area; 
 scanf("%f%f",&l,&b); 
 x=&l; 
 y=&b; 
 area=(*x)*(*y); 
 printf("Area of rectangle = %.6f sq. units",area); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-06-6a-AREA-OF-RECTANGLE-USING-POINTER/assets/118899387/7eb162f4-6e58-443a-a8aa-8ef3233ae839)
## RESULT 
Thus the program to find area of rectangle using pointer has been executed 
successfully
