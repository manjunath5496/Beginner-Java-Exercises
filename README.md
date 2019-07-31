# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
System.out.println("Hello, World!");
}
}
```
----------------------------------------


# Question 2

### **Question:**

> ***Write a program to find the area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main (String [] args) {
int r, area;
r = 2;
area = 4 * 3.14 * r * r;
System.out.println("The area of the circle = " + area);
}
}
```
----------------------------------------

# Question 3

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b, sum;
a=1;
b=2;
sum = a + b;
System.out.println("The sum of a and b = " + sum);
}
}
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b;
a=2;
b = a * a;
System.out.println("The square of a = " + b);
}
}
```
----------------------------------------

# Question 5

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b;
a=2;
b =3;
if(a>b)
{
System.out.println("a is greater than b");
}
else
{
System.out.println("b is greater than a");
}
}
}
```
----------------------------------------

# Question 6

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String[] args) {
int i, avg, sum = 0;
int [] num = {16, 18, 20, 25, 36};
for(i=0; i<5; i++)
sum = sum + num[i];
avg = sum/5;
System.out.println("Sum of the Elements in the array = " + sum);
System.out.println("Average of the Elements in the array = " + avg);
}
}
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program such that a Switch (case) allows to make a decision from the number of choices, i.e., from the number of cases.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
char ch;
printf("Enter any character:");
scanf("%c", &ch);
switch(ch)
{
case 'R':
printf("Red");
break;
case 'W':
printf("White");
break;
case 'Y':
printf("Yellow");
break;
case 'G':
printf("Green");
break;
default:
printf("Error");
break;
}
return 0;
} 
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program to find the greatest of two numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int x, y, *p, *q;
printf("Enter any integer:");
scanf("%d", &x);
printf("Enter any integer:");
scanf("%d", &y);
p = &x;
q = &y;
if(*p>*q)
{
printf("x is greater than y");
}
if(*q>*p)
{
printf("y is greater than x");
}
return 0;
}
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to print the address of x and the value assigned to x.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include <stdio.h>
int main()
{
int x, *p;
x = 1;
p = &x;
printf("The address of the variable x =%d", p);
printf("The value of the variable x =%d", *p);
return 0;
} 
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String[] args) throws Exception {
int i;
for( i=1; i<=10; i++)
System.out.println(" \n number = " + i + " its square = " + i*i + " its cube = " + i*i*i);
}
}
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
char M;
printf("Enter any character:");
scanf("%c", &M);
printf("ch=%c", M);
return 0;
} 
```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to print the multiplication table of a number.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int n, i;
Scanner scan = new Scanner(System.in);
System.out.println("Enter a number: ");
n = scan.nextInt();
for( i=1; i<=5; i++)
System.out.println (n + " * " + i + " = " + n * i);
}
}
```
----------------------------------------


# Question 13

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int i, product = 1;
for( i=1; i<=10; i++)
product = product * i;
System.out.println("The product of the first 10 digits = " + product);
}
}
```
----------------------------------------

# Question 14

### **Question:**

> ***Write a program to print whether the given number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a;
a = -35;
if(a>0)
{
System.out.println("Number is positive");
}
else
{
System.out.println(" Number entered is negative");
}
}
}
```
----------------------------------------

# Question 15

### **Question:**

> ***Write a program to check the equivalence of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int x, y;
Scanner scan = new Scanner(System.in);
System.out.println("Enter a number: ");
x = scan.nextInt();
System.out.println("Enter a number: ");
y = scan.nextInt();
if(x-y==0)
{
System.out.println("The two numbers are equivalent");
}
else
{
System.out.println("The two numbers are not equivalent");
}
}
}
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to print the remainder of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int a, b, c;
Scanner scan = new Scanner(System.in);
System.out.println("Enter a number: ");
a = scan.nextInt();
System.out.println("Enter a number: ");
b = scan.nextInt();
c = a%b;
System.out.println("The remainder of a and b = " + c);
}
}
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to print the given number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int a;
Scanner scan = new Scanner(System.in);
System.out.println("Enter a number: ");
a = scan.nextInt();
if(a%2 == 0)
{
System.out.println("The number is even");
}
else
{
System.out.println("The number is odd");
}
}
}
```
----------------------------------------

# Question 18

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
char a;
for( a='A'; a<='Z'; a++)
System.out.println("\n " + a);
}
}
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int a, b, c, d, e, f;
a = 10;
b=12;
c=a+1;
d=b+1;
e=a-1;
f=b-1;
System.out.print("The incremented value of a = "+ c);
System.out.print("The incremented value of b = "+ d);
System.out.print("The decremented value of a = "+ e);
System.out.print("The decremented value of b = "+ f);
}
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to calculate the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int P,T, R, SI;
P = 1000;
T = 2;
R = 3;
SI = P*T*R/100;
printf("The simple interest = %d", SI);
return 0;
}
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int a, b, c;
printf("Enter any number:");
scanf("%d", &a);
printf("Enter any number:");
scanf("%d", &b);
printf("Enter any number:");
scanf("%d", &c);
if(a>b&&a>c)
{
printf("%d is greater than %d and %d", a, b, c);
}
else if (b>a&&b>c)
{
printf("%d is greater than %d and %d", b, a, c);
}
else
{
printf("%d is greater than %d and %d", c, b, a);
}
return 0;
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the factorial of the entered number.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int i, n, fact=1 ;
printf("Enter any number:");
scanf("%d", &n);
for(i=1; i<=n; i++)
fact = fact *i;
printf("\n Entered number is: %d", n);
printf("\n The factorial of the entered number %d is: %d", n, fact);
return 0;
}
```
----------------------------------------

# Question 23

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
#include<string.h>
int main()
{
char ch[4];
printf("Enter any word: ");
scanf("%c", &ch);
printf("The length of the string = %d", strlen(ch));
return 0;
}
```
----------------------------------------

# Question 24

### **Question:**

> ***Write a program to print the ASCII value of the entered character.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
char ch ='A';
printf("The ASCII value of ch is: %d", ch);
return 0;
}
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to check whether the entered character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
char ch = 'a';
if(islower(ch))
printf("you have entered the lower case letter");
else
printf("you have entered the upper case letter");
return 0;
}
```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to check whether the entered character is a upper case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
char ch = 'a';
if(isupper(ch))
printf("you have entered the upper case letter");
else
printf("you have entered the lower case letter");
return 0;
}
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to convert the lower case letter to upper case letter.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
char ch = 'a';
char b = toupper(ch);
printf("lower case letter %c is converted to upper case letter %c", ch, b);
return 0;
}
```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int i;
char name [8] = {' E' , ' I', ' N', ' S', ' T ', ' E', ' I', ' N'};
for(i=0; i<8; i++)
printf("\n Element [%d] = %c", i, name[i]);
return 0;
}
```
----------------------------------------

# Question 29

### **Question:**

> ***Write a program to print the output:</br>
Name of the book = B</br>
Price of the book = 135.00</br>
Number of pages = 300</br>
Edition = 8</br>
using structures.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
struct book {
char name;
float price;
int pages;
int edition;
};
struct book b1;
b1.name = 'B';
b1.price = 135.00;
b1.pages = 300;
b1.edition = 8;
printf("\n Name of the book = %c", b1.name);
printf("\n Price of the book = %f", b1.price);
printf("\n Number of pages = %d", b1.pages);
printf("\n Edition of the book = %d", b1.edition);
return 0;
}
```
----------------------------------------

# Question 30

### **Question:**

> ***Write a program to find square of a number using functions.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int square();
int main()
{
int answer;
answer = square();
printf("Square of the given number=%d", answer);
return(0);
}
int square()
{
int x;
printf("Enter any integer:");
scanf("%d", &x);
return x*x;
}
```
----------------------------------------

# Question 31

### **Question:**

> ***Write a program To print "hello world" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int i;
for (i =1; i<=10; i ++)
printf("hello world \n");
return 0;
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int i =1;
do
{
printf("%d\n", i++);
} while (i<=5);
return 0;
}
```
----------------------------------------

# Question 33

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```Java
#include <stdio.h>
int main()
{
char i;
char body [4] = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
printf("\n body[%c] = %c", body[i] , body[i]);
return 0;
}
```
----------------------------------------


# Question 34

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```Java
#include<stdio.h>
#include<stdlib.h>
int main () {
printf("linux\n");
exit (0);
printf("php\n");
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
linux
```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include <stdio.h>
#include <ctype.h>
int main()
{
int a =2;
if( isalpha(a) )
{
printf(" The character a is an alphabet");
}
else
{
printf("The character a is not an alphabet");
}
return 0;
}
```
----------------------------------------

# Question 36

### **Question:**

> ***Write a program to calculate the discounted price and the total price after discount</br>
Given:</br>
If purchase value is greater than 1000, 10% discount</br>
If purchase value is greater than 5000, 20% discount</br>
If purchase value is greater than 10000, 30% discount.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
double PV;
printf("Enter purchased value:");
scanf("%lf", &PV);
if(PV>1000)
{
printf("\n Discount=%lf", PV* 0.1);
printf("\n Total=%lf", PV - PV* 0.1);
}
else if(PV>5000)
{
printf("\n Discount =%lf", PV* 0.2);
printf("\n Total=%lf", PV - PV* 0.1);
}
else
{
printf("\n Discount=%lf", PV* 0.3);
printf("\n Total=%lf", PV - PV* 0.1);
}
return 0;
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int i = 1;
while (i<=10)
{
printf("%d\n", i++);
}
return 0;
}
```
----------------------------------------

# Question 38

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```Java
#include <stdio.h>
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
continue;
}
printf("%d\n ", i);
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
1
2
4
5
```
----------------------------------------

# Question 39

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```Java
#include <stdio.h>
int main()
{
   int num [] = {11, 22, 33, 44, 55, 66};
    int n;

    /* Calculating the size of the array with this formula.
     * n = sizeof(array_name) / sizeof(array_name[0])
     * This is a universal formula to find number of elements in
     * an array, which means it will work for arrays of all data
     * types such as int, char, float etc.
     */
    n = sizeof(num) / sizeof(num [0]);
    printf("Size of the array is: %d\n", n);
    return 0;
}
```
----------------------------------------

# Question 40

### **Question:**

> ***What would be the output of the following programs:***

----------------------------------------

```Java
#include <stdio.h>
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
break;
}
printf("%d\n", i);
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
1
2
```
----------------------------------------

```Java
#include <stdio.h>
int main()
{
int i;
for(i=1;i<=5;i++)
{
if(i==3)
{
goto HAI;
}
printf("\n %d ",i);
}
HAI : printf("\n Linux");
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
1
2
Linux
```
----------------------------------------

```Java
#include<stdio.h>
int main()
{
int i = 54;
int y = i<<1;
printf("The value of y = %d", y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
The value of y = 108
```
----------------------------------------

```Java
#include<stdio.h>
int main()
{
int i = 54;
int y = i>>1;
printf("The value of y = %d", y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
The value of y = 27
```
----------------------------------------

```Java
#include<stdio.h>
int main()
{
char ch [5];
printf( "Enter the name: ");
scanf("%s", &ch);
printf( "The name you entered = %s", ch);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
Enter the name:
Dennis
The name you entered = Denni
```
----------------------------------------

```Java
#include <stdio.h>
int main()
{
for( ; ; ) 
{
printf("This loop will run forever.\n");
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever. ......... 
```
----------------------------------------


```Java
#include<stdio.h>
int main()
{
printf("Hello,world!");
return 0;
printf("Hello,world!");
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
Hello,world! 
```
----------------------------------------

# Question 41

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```Java
#include<stdio.h>
int main()
{
int age;
printf("Enter age:");
scanf("%d", &age);
if(age>=60)
{
printf("senior citizen");
}
else
{
printf("not a senior citizen");
}
return 0;
}
```
----------------------------------------

 
 
