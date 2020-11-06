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
area = 3.14 * r * r;
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

# Question 33

### **Question:**

> ***Write a program to Find ASCII Value of a character.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        char ch = 'a';
        int ascii = ch;
        // You can also cast char to int
        int castAscii = (int) ch;

        System.out.println("The ASCII value of " + ch + " is: " + ascii);
        System.out.println("The ASCII value of " + ch + " is: " + castAscii);
    }

```
----------------------------------------


# Question 34

### **Question:**

> ***Write a program to Swap Two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        float first = 12.0f, second = 24.5f;

        System.out.println("--Before swap--");
        System.out.println("First number = " + first);
        System.out.println("Second number = " + second);

        first = first - second;
        second = first + second;
        first = second - first;

        System.out.println("--After swap--");
        System.out.println("First number = " + first);
        System.out.println("Second number = " + second);
    }
}
```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program to Display Fibonacci Series.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        int n = 10, t1 = 0, t2 = 1;
        System.out.print("First " + n + " terms: ");

        for (int i = 1; i <= n; ++i)
        {
            System.out.print(t1 + " + ");

            int sum = t1 + t2;
            t1 = t2;
            t2 = sum;
        }
    }
}
```
----------------------------------------

# Question 36

### **Question:**

> ***Write a program to Find GCD of two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        int n1 = 81, n2 = 153, gcd = 1;

        for(int i = 1; i <= n1 && i <= n2; ++i)
        {
            // Checks if i is factor of both integers
            if(n1 % i==0 && n2 % i==0)
                gcd = i;
        }

        System.out.printf("G.C.D of %d and %d is %d", n1, n2, gcd);
    }
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program to Find LCM of two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {
  public static void main(String[] args) {

    int n1 = 72, n2 = 120, lcm;

    // maximum number between n1 and n2 is stored in lcm
    lcm = (n1 > n2) ? n1 : n2;

    // Always true
    while(true) {
      if( lcm % n1 == 0 && lcm % n2 == 0 ) {
        System.out.printf("The LCM of %d and %d is %d.", n1, n2, lcm);
        break;
      }
      ++lcm;
    }
  }
}
```
----------------------------------------

# Question 38

### **Question:**

> ***Write a program to Count Number of Digits in an Integer.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        int count = 0, num = 3452;

        while(num != 0)
        {
            // num = num/10
            num /= 10;
            ++count;
        }

        System.out.println("Number of digits: " + count);
    }
}
```
----------------------------------------

# Question 39

### **Question:**

> ***Write a program to Reverse a Number.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        int num = 1234, reversed = 0;

        while(num != 0) {
            int digit = num % 10;
            reversed = reversed * 10 + digit;
            num /= 10;
        }

        System.out.println("Reversed Number: " + reversed);
    }
}
```
----------------------------------------

# Question 40

### **Question:**

> ***Write a program to Display Prime Numbers Between Two Intervals.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        int low = 20, high = 50;

        while (low < high) {
            boolean flag = false;

            for(int i = 2; i <= low/2; ++i) {
                // condition for nonprime number
                if(low % i == 0) {
                    flag = true;
                    break;
                }
            }

            if (!flag && low != 0 && low != 1)
                System.out.print(low + " ");

            ++low;
        }
    }
}
```
----------------------------------------

# Question 41

### **Question:**

> ***Write a program to Check Armstrong Number.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        int number = 371, originalNumber, remainder, result = 0;

        originalNumber = number;

        while (originalNumber != 0)
        {
            remainder = originalNumber % 10;
            result += Math.pow(remainder, 3);
            originalNumber /= 10;
        }

        if(result == number)
            System.out.println(number + " is an Armstrong number.");
        else
            System.out.println(number + " is not an Armstrong number.");
    }
}
```
----------------------------------------

# Question 42

### **Question:**

> ***Write a program to Find G.C.D Using Recursion.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        int n1 = 366, n2 = 60;
        int hcf = hcf(n1, n2);

        System.out.printf("G.C.D of %d and %d is %d.", n1, n2, hcf);
    }

    public static int hcf(int n1, int n2)
    {
        if (n2 != 0)
            return hcf(n2, n1 % n2);
        else
            return n1;
    }
}
```
----------------------------------------

# Question 43

### **Question:**

> ***Write a program to Reverse a Sentence Using Recursion.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

  public static void main(String[] args) {
    String sentence = "Go work";
    String reversed = reverse(sentence);
    System.out.println("The reversed sentence is: " + reversed);
  }

  public static String reverse(String sentence) {
    if (sentence.isEmpty())
      return sentence;

    return reverse(sentence.substring(1)) + sentence.charAt(0);
  }
}
```
----------------------------------------



# Question 44

### **Question:**

> ***Write a program to Calculate Standard Deviation.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        double[] numArray = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };
        double SD = calculateSD(numArray);

        System.out.format("Standard Deviation = %.6f", SD);
    }

    public static double calculateSD(double numArray[])
    {
        double sum = 0.0, standardDeviation = 0.0;
        int length = numArray.length;

        for(double num : numArray) {
            sum += num;
        }

        double mean = sum/length;

        for(double num: numArray) {
            standardDeviation += Math.pow(num - mean, 2);
        }

        return Math.sqrt(standardDeviation/length);
    }
}
```
----------------------------------------

# Question 45

### **Question:**

> ***Write a program to Add Two Matrix Using Multi-dimensional Arrays.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        int rows = 2, columns = 3;
        int[][] firstMatrix = { {2, 3, 4}, {5, 2, 3} };
        int[][] secondMatrix = { {-4, 5, 3}, {5, 6, 3} };

        // Adding Two matrices
        int[][] sum = new int[rows][columns];
        for(int i = 0; i < rows; i++) {
            for (int j = 0; j < columns; j++) {
                sum[i][j] = firstMatrix[i][j] + secondMatrix[i][j];
            }
        }

        // Displaying the result
        System.out.println("Sum of two matrices is: ");
        for(int[] row : sum) {
            for (int column : row) {
                System.out.print(column + "    ");
            }
            System.out.println();
        }
    }
}
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to Multiply to Matrix Using Multi-dimensional Arrays.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        int r1 = 2, c1 = 3;
        int r2 = 3, c2 = 2;
        int[][] firstMatrix = { {3, -2, 5}, {3, 0, 4} };
        int[][] secondMatrix = { {2, 3}, {-9, 0}, {0, 4} };

        // Mutliplying Two matrices
        int[][] product = new int[r1][c2];
        for(int i = 0; i < r1; i++) {
            for (int j = 0; j < c2; j++) {
                for (int k = 0; k < c1; k++) {
                    product[i][j] += firstMatrix[i][k] * secondMatrix[k][j];
                }
            }
        }

        // Displaying the result
        System.out.println("Sum of two matrices is: ");
        for(int[] row : product) {
            for (int column : row) {
                System.out.print(column + "    ");
            }
            System.out.println();
        }
    }
}
```
----------------------------------------

# Question 47

### **Question:**

> ***Write a program to Find Transpose of a Matrix.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        int row = 2, column = 3;
        int[][] matrix = { {2, 3, 4}, {5, 6, 4} };

        // Display current matrix
        display(matrix);

        // Transpose the matrix
        int[][] transpose = new int[column][row];
        for(int i = 0; i < row; i++) {
            for (int j = 0; j < column; j++) {
                transpose[j][i] = matrix[i][j];
            }
        }

        // Display transposed matrix
        display(transpose);
    }

    public static void display(int[][] matrix) {
        System.out.println("The matrix is: ");
        for(int[] row : matrix) {
            for (int column : row) {
                System.out.print(column + "    ");
            }
            System.out.println();
        }
    }
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program find the occurrence (Frequency) of a character in a given string.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        String str = "This website is awesome.";
        char ch = 'e';
        int frequency = 0;

        for(int i = 0; i < str.length(); i++) {
            if(ch == str.charAt(i)) {
                ++frequency;
            }
        }

        System.out.println("Frequency of " + ch + " = " + frequency);
    }
}
```
----------------------------------------

# Question 49

### **Question:**

> ***Write a program to Remove All Whitespaces from a String.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {
        String sentence = "T    his is b  ett     er.";
        System.out.println("Original sentence: " + sentence);

        sentence = sentence.replaceAll("\\s", "");
        System.out.println("After replacement: " + sentence);
    }
}
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to Get Current Date/Time.***

---------------------------------------

<strong>Solution: </strong>

```Java

public class MyClass {

    public static void main(String[] args) {
        LocalDateTime current = LocalDateTime.now();

        System.out.println("Current Date and Time is: " + current);
    }
}
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to Get Current Working Directory.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        String path = System.getProperty("user.dir");
        
        System.out.println("Working Directory = " + path);

    }
}
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to Append Text to an Existing File.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.io.IOException;
import java.nio.file.Files;
import java.nio.file.Paths;
import java.nio.file.StandardOpenOption;

public class MyClass {

    public static void main(String[] args) {

        String path = System.getProperty("user.dir") + "\\src\\test.txt";
        String text = "Added text";

        try {
            Files.write(Paths.get(path), text.getBytes(), StandardOpenOption.APPEND);
        } catch (IOException e) {
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


   <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(1).pdf" style="text-decoration:none;">Learn Java for Web Development: Modern Java Web Development</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(2).pdf" style="text-decoration:none;">Data Structures and Problem Solving Using Java</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(3).pdf" style="text-decoration:none;">Data Structures and Algorithms in Java</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(4).pdf" style="text-decoration:none;">Java for Absolute Beginners </a></b></li>                              
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(6).pdf" style="text-decoration:none;">Java Interview Notes </a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(7).pdf" style="text-decoration:none;">Java Coding Interview</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(8).pdf" style="text-decoration:none;">Java: The Complete Reference</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(9).pdf" style="text-decoration:none;">Java: Easy Java Programming for Beginners, Your Step-
By-Step Guide to Learning Java Programming</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(10).pdf" style="text-decoration:none;">Java All-in-One For Dummies</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(11).pdf" style="text-decoration:none;"> Sams Teach Yourself Java in 24 Hours</a></b></li>
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(13).pdf" style="text-decoration:none;">Java Design Patterns</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(14).pdf" style="text-decoration:none;">Java Programming Interviews Exposed</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(15).pdf" style="text-decoration:none;">Java For Testers: Learn Java fundamentals fast</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(16).pdf" style="text-decoration:none;">Microservices Patterns: With Examples in Java</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(17).pdf" style="text-decoration:none;">Modern Compiler Implementation in Java</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(18).pdf" style="text-decoration:none;"> Object-Oriented Programming (OOP) with Java</a></b></li>
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(19).pdf" style="text-decoration:none;">Objects First with Java: A Practical Introduction Using BlueJ</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(20).pdf" style="text-decoration:none;">OCA Java SE 8 Programmer I Certification Guide</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(21).pdf" style="text-decoration:none;">Software Architecture Design Patterns in Java</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(22).pdf" style="text-decoration:none;">Fundamentals of Computer Science Using Java</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(5).pdf" style="text-decoration:none;">Java Puzzlers: Traps, Pitfalls, and Corner Cases</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/ava(12).pdf" style="text-decoration:none;">Java in a Nutshell</a></b></li>

 </ul>
	


 
