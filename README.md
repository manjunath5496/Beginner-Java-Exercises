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
public class MyClass {
public static void main(String[] args)throws Exception {
char ch;
System.out.print("Enter a character:");
ch = (char)System.in.read();
switch(ch)
{
case 'R':
System.out.print("Red");
break;
case 'W':
System.out.print("White");
break;
case 'Y':
System.out.print("Yellow");
break;
case 'G':
System.out.print("Green");
break;
default:
System.out.print("Error");
break;
}
}
}
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program to read 10 numbers from the keyboard and find their sum and average.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int N1, N2, N3, N4, N5, N6, N7, N8, N9, N10, sum;
float X;
Scanner scan = new Scanner(System.in);
System.out.println("Enter any ten Numbers: ");
N1 = scan.nextInt();
N2 = scan.nextInt();
N3 = scan.nextInt();
N4 = scan.nextInt();
N5 = scan.nextInt();
N6 = scan.nextInt();
N7 = scan.nextInt();
N8 = scan.nextInt();
N9 = scan.nextInt();
N10 = scan.nextInt();
sum = N1 + N2 + N3 + N4 + N5 + N6 + N7 + N8 + N9 + N10;
X = sum /10;
System.out.println("The sum of 10 numbers = " + sum);
System.out.println("The average of 10 numbers = " + X);
}
}
```
----------------------------------------

# Question 9

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

# Question 10

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String[] args) throws Exception {
char c;
System.out.print("Enter a character:");
c = (char)System.in.read();
System.out.println("ch= " + c);
}
}
```
----------------------------------------

# Question 11

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


# Question 12

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

# Question 13

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
System.out.println("Number entered is negative");
}
}
}
```
----------------------------------------

# Question 14

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

# Question 15

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

# Question 16

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

# Question 17

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

# Question 18

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

# Question 19

### **Question:**

> ***Write a program to calculate the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int P,T, R, SI;
P = 1000;
T = 2;
R = 3;
SI = P*T*R/100;
System.out.println("The simple interest = " + SI);
}
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
int a, b, c;
Scanner scan = new Scanner(System.in);
System.out.println("Enter any number:");
a = scan.nextInt();
System.out.println("Enter any number:");
b = scan.nextInt();
System.out.println("Enter any number:");
c = scan.nextInt();
if(a>b&&a>c)
{
System.out.println("a is greater than b and c");
}
else if(b>a&&b>c)
{
System.out.println("b is greater than a and c");
}
else
{
System.out.println("c is greater than b and a");
}
}
}    
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to print the factorial of the entered number.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String []args){
int i, n, fact=1 ;
Scanner scan = new Scanner(System.in);
System.out.println("Enter any number:");
n = scan.nextInt();      
for(i = 1; i <= n; i++)
        {
            fact = fact * i;
        }
        System.out.println("Factorial of " + n + " is: " + fact);
     }
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
String a;
Scanner scan = new Scanner(System.in);
System.out.print("Enter Your Name : ");
      a = scan.nextLine();
System.out.println("The length of the String is: " + a.length());
}
}
```
----------------------------------------

# Question 23

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
public class MyClass {
public static void main(String[] args) throws Exception{
int i;
char [] num = {'E' , 'I', 'N', 'S', 'T', 'E', 'I', 'N'};
for(i=0; i<8; i++)
System.out.println("Einstein [" + i + " ] = " + num[i]);
}
}
```
----------------------------------------

# Question 24

### **Question:**

> ***Write a program to find square of a number using method.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String[] args) {
int x;
Scanner scan = new Scanner(System.in);
System.out.println("Enter any number: ");
x = scan.nextInt();
System.out.println("Square of the number = " + square (x));
}
public static int square (int x){
return x*x;
}
}
```
----------------------------------------

# Question 25

### **Question:**

> ***Write a program To print "hello world" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int i;
for (i =1; i<=10; i ++)
System.out.println("\n hello world");
}
}
```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int i =1;
do
{
System.out.println(" \n " + i++);
} while (i<=5);
}
}
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String[] args) throws Exception{
int i;
char [] body = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
System.out.println("body [" + body [i] + " ] = " + body [i]);
}
}
```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int i = 1;
while (i<=10)
{
System.out.println("\n " + i++);
}
}
}

```
----------------------------------------

# Question 29

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```Java
public class MyClass {
public static void main(String []args) {
int i;
for (i=1; i<=5; i++) {
if (i==3) {
continue;
}
System.out.println("" + i);
}
}
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

# Question 30

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String[] args) {
   int num [] = {11, 22, 33, 44, 55, 66};
	System.out.println("Size of the array is: " + num.length);
}
}
```
----------------------------------------

# Question 31

### **Question:**

> ***What would be the output of the following programs:***

----------------------------------------

```Java
public class MyClass {
public static void main(String []args) {
int i;
for (i=1; i<=5; i++) {
if (i==3) {
break;
}
System.out.println("" + i);
}
}
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
public class MyClass {
public static void main(String [] args) {
int x = 2;
System.out.println(" Square of a number = " + Math.pow((x), 2));
}
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
Square of a number = 4.0
```
----------------------------------------

```Java
public class MyClass {
public static void main(String [] args) {
int i = 54;
int y = i<<1;
System.out.println("The value of y = " + y);
}
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
The value of y = 108
```
----------------------------------------

```Java
public class MyClass {
public static void main(String [] args) {
int i = 54;
int y = i>>1;
System.out.println("The value of y = " + y);
}
}

```
----------------------------------------

<strong>Solution: </strong>

```Java
The value of y = 27
```
----------------------------------------

```Java
import java.util.Scanner;
public class MyClass {
public static void main(String [] args) {
String m;
Scanner in = new Scanner(System.in);
System.out.print("Enter the name: ");
m = in.nextLine();
System.out.println("The name you entered = " + m);
}
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
Enter the name:
Dennis
The name you entered = Dennis
```
----------------------------------------

```Java
public class MyClass {
public static void main(String[] args) {
for( ; ; ) 
{
System.out.println("This loop will run forever.\n");
}
}
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
public class MyClass {
public static void main(String [] args) {
System.out.println("Hello, World!");
System.exit(0); 
System.out.println("Hello, World!");
}
}
```
----------------------------------------

<strong>Solution: </strong>

```Java
Hello,world! 
```
----------------------------------------

# Question 32

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
public static void main(String [] args) {
int age;
age=20;
if(age>= 60)
{
System.out.println("senior citizen");
}
else
{
System.out.println("not a senior citizen");
}
}
}
```
----------------------------------------

 </br>
<h3>Books:</h3>
<hr>

<ul>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(11).pdf" style="text-decoration:none;">Thinking in Java </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(12).pdf" style="text-decoration:none;">The Elements of Java Style</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(13).pdf" style="text-decoration:none;">Beginning Programming with Java For Dummies</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(14).pdf" style="text-decoration:none;">Effective Java </a></b></li>                              
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(15).pdf" style="text-decoration:none;">Java: How To Program </a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(16).pdf" style="text-decoration:none;">Java For Dummies</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(17).pdf" style="text-decoration:none;">Java Threads </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(18).pdf" style="text-decoration:none;">Java Cookbook</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(19).pdf" style="text-decoration:none;">Java Generics and Collections</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(20).pdf" style="text-decoration:none;">The Well-Grounded Java Developer</a></b></li>
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/pb(21).pdf" style="text-decoration:none;">Think Java: How to Think Like a Computer Scientist</a></b></li>
 </ul>
	


 
