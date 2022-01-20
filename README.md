# C-Language

What is Operating System?
- Simply OS
- Just interface between User and the Machine
- Text to BCD -> BCD to Text
- C, C++, Java, .net, Python, Android, Ruby, JSON
- i/p -> o/p
-> C Language


. -> dot
/ -> forward slash
\ -> backward slash
' -> single quote/quotations
" -> double quote/quotations

String - a collection of characters
	|-> 
number - a collection of digits (0-9)
	|-> int
	|-> float
	|-> double
	|-> 
	
Variable, Values, Operands, Operators
-------------------------------------

Variable: Which stores some value
eg: Consider a jar/plate

Value	: which is having some data/info
eg: water or rice or jantikalu or biryani

Operands : 

Operator: which performs the operation on 2 or more operands
eg: 2+3, 2+3+5 so on

notations:
---------

integer 

Sample Calculator:
-----------------
#include<stdio.h>

int main()
{
    int num1, num2, result; //declaration
    
    printf("Enter value of num1: ");
    scanf("%d", &num1);
    
    printf("Enter value of num2: ");
    scanf("%d", &num2);
    
    //printf("The value of num1 is: %d", num2);
    
    //addition of 2 numbers
    //sum of 1000 and 430 is: 143
    //printf("%d",num1+num2\n);
    //printf("sum of 1000 and 430 is",num1+num2);
    
    result=num1+num2;
    printf("Sum of %d and %d is: %d", num1, num2, result);
    
    result=num1*num2;
    printf("\nProduct of %d and %d is: %d", num1, num2, result);
    
    result=num1-num2;
    printf("\nDifference of %d and %d is: %d", num1,num2,result);
    
    //Homework division
}

Circle:
------

#include<stdio.h>

int main()
{
    int radius; 
    float area, circumference;
    
    printf("Enter the radius: ");
    scanf("%d", &radius);
    
    area = 3.14*radius*radius;
    printf("Area of circle with radius %d is: %f", radius, area);
    
    circumference = 2*3.14*radius;
    printf("\ncircumference of circle with radius %d is:  %f", radius, circumference);
    
    //Homework Square and Rectangle
}
