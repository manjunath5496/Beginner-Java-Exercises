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


# Question 53

### **Question:**

> ***Write a program to compare two strings.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {

    public static void main(String[] args) {

        String style = "Bold";
        String style2 = "Bold";

        if(style == style2)
            System.out.println("Equal");
        else
            System.out.println("Not Equal");
    }
}
```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to Create Directories.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.io.File;

class MyClass {
  public static void main(String[] args) {

    // creates a file object with specified path
    File file = new File("Java Example\\directory");

    // tries to create a new directory
    boolean value = file.mkdir();
    if(value) {
      System.out.println("The new directory is created.");
    }
    else {
      System.out.println("The directory already exists.");
    }
  }
}
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to Rename File.***

---------------------------------------

<strong>Solution: </strong>

```Java

import java.io.File;

class MyClass {
  public static void main(String[] args) {

    // create a file object
    File file = new File("oldName");
      
    // create a file
    try {
      file.createNewFile();
    }
    catch(Exception e) {
      e.getStackTrace();
    }

    // create an object that contains the new name of file
    File newFile = new File("newName");

    // change the name of file
    boolean value = file.renameTo(newFile);

    if(value) {
      System.out.println("The name of the file is changed.");
    }
    else {
      System.out.println("The name cannot be changed.");
    }
  }
}
```
----------------------------------------

# Question 56

### **Question:**

> ***Write a program to Get all Files Present in a Directory.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.io.File;

class MyClass {
  public static void main(String[] args) {

    // creates a file object
    File file = new File("C:\\Users\\Guest User\\Desktop\\Java File\\List Method");

    // returns an array of all files
    String[] fileList = file.list();

    for(String str : fileList) {
      System.out.println(str);
    }
  }
}
```
----------------------------------------



# Question 57

### **Question:**

> ***Write a program to Copy File.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.io.FileInputStream;
import java.io.FileOutputStream;

class MyClass {
  public static void main(String[] args) {

    byte[] array = new byte[50];
    try {
      FileInputStream sourceFile = new FileInputStream("input.txt");
      FileOutputStream destFile = new FileOutputStream("newFile");

      // reads all data from input.txt
      sourceFile.read(array);

      // writes all data to newFile
      destFile.write(array);
      System.out.println("The input.txt file is copied to newFile.");

      // closes the stream
      sourceFile.close();
      destFile.close();
    }
    catch (Exception e) {
      e.getStackTrace();
    }
  }
}
```
----------------------------------------


# Question 58

### **Question:**

> ***Write a program to Implement Bubble Sort algorithm.***

---------------------------------------

<strong>Solution: </strong>

```Java
// import the Class
import java.util.Arrays;
import java.util.Scanner;

class MyClass {

  // create an object of scanner
  // to take input from the user
  Scanner input = new Scanner(System.in);

  // method to perform bubble sort
  void bubbleSort(int array[]) {
    int size = array.length;

    // for ascending or descending sort
    System.out.println("Choose Sorting Order:");
    System.out.println("1 for Ascending \n2 for Descending");
    int sortOrder = input.nextInt();

    // run loops two times
    // first loop access each element of the array
    for (int i = 0; i < size - 1; i++)

      // second loop performs the comparison in each iteration
      for (int j = 0; j < size - i - 1; j++)

        // sort the array in ascending order
        if (sortOrder == 1) {
          // compares the adjacent element
          if (array[j] > array[j + 1]) {

            // swap if left element is greater than right
            int temp = array[j];
            array[j] = array[j + 1];
            array[j + 1] = temp;
          }
        }

        // sort the array in descending order
        else {
          // compares the adjacent element
          if (array[j] < array[j + 1]) {

            // swap if left element is smaller than right
            int temp = array[j];
            array[j] = array[j + 1];
            array[j + 1] = temp;
          }
        }

  }

  // driver code
  public static void main(String args[]) {

    // create an array
    int[] data = { -2, 45, 0, 11, -9 };

    // create an object of Main class
    Main bs = new Main();

    // call the method bubbleSort using object bs
    // pass the array as the method argument
    bs.bubbleSort(data);
    System.out.println("Sorted Array in Ascending Order:");

    // call toString() of Arrays class
    // to convert data into the string
    System.out.println(Arrays.toString(data));
  }
}
```
----------------------------------------

# Question 59

### **Question:**

> ***Write a program to Implement Quick Sort Algorithm.***

---------------------------------------

<strong>Solution: </strong>

```Java

import java.util.Arrays;

class MyClass {

  // divide the array on the basis of pivot
  int partition(int array[], int low, int high) {

    // select last element as pivot
    int pivot = array[high];

    // initialize the second pointer
    int i = (low - 1);

    // Put the elements smaller than pivot on the left and
    // greater than pivot on the right of pivot
    for (int j = low; j < high; j++) {

      // compare all elements with pivot
      // swap the element greater than pivot
      // with element smaller than pivot
      // to sort in descending order
      // if (array[j] >= pivot)
      if (array[j] <= pivot) {

        // increase the second pointer if
        // smaller element is swapped with greater
        i++;
        int temp = array[i];
        array[i] = array[j];
        array[j] = temp;
      }
    }

    // put pivot in position
    // so that element on left are smaller
    // element on right are greater than pivot
    int temp = array[i + 1];
    array[i + 1] = array[high];
    array[high] = temp;
    return (i + 1);
  }

  void quickSort(int array[], int low, int high) {
    if (low < high) {

      // Select pivot position and put all the elements smaller
      // than pivot on the left and greater than pivot on right
      int pi = partition(array, low, high);

      // sort the elements on the left of the pivot
      quickSort(array, low, pi - 1);

      // sort the elements on the right of pivot
      quickSort(array, pi + 1, high);
    }
  }

  // Driver code
  public static void main(String args[]) {

    // create an unsorted array
    int[] data = { 8, 7, 2, 1, 0, 9, 6 };
    int size = data.length;

    // create an object of the Main class
    Main qs = new Main();

    // pass the array with the first and last index
    qs.quickSort(data, 0, size - 1);
    System.out.println("Sorted Array: ");
    System.out.println(Arrays.toString(data));
  }
}
```
----------------------------------------

# Question 60

### **Question:**

> ***Write a program to Implement Merge Sort Algorithm.***

---------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Arrays;


class MyClass {

  // Merge two sub arrays L and M into array
  void merge(int array[], int p, int q, int r) {

    int n1 = q - p + 1;
    int n2 = r - q;

    int L[] = new int[n1];
    int M[] = new int[n2];

    // fill the left and right array
    for (int i = 0; i < n1; i++)
      L[i] = array[p + i];
    for (int j = 0; j < n2; j++)
      M[j] = array[q + 1 + j];

    // Maintain current index of sub-arrays and main array
    int i, j, k;
    i = 0;
    j = 0;
    k = p;

    // Until we reach either end of either L or M, pick larger among
    // elements L and M and place them in the correct position at A[p..r]
    // for sorting in descending
    // use if(L[i] >= <[j])
    while (i < n1 && j < n2) {
      if (L[i] <= M[j]) {
        array[k] = L[i];
        i++;
      } else {
        array[k] = M[j];
        j++;
      }
      k++;
    }

    // When we run out of elements in either L or M,
    // pick up the remaining elements and put in A[p..r]
    while (i < n1) {
      array[k] = L[i];
      i++;
      k++;
    }

    while (j < n2) {
      array[k] = M[j];
      j++;
      k++;
    }
  }

  // Divide the array into two sub arrays, sort them and merge them
  void mergeSort(int array[], int left, int right) {
    if (left < right) {

      // m is the point where the array is divided into two sub arrays
      int mid = (left + right) / 2;

      // recursive call to each sub arrays
      mergeSort(array, left, mid);
      mergeSort(array, mid + 1, right);

      // Merge the sorted sub arrays
      merge(array, left, mid, right);
    }
  }

  public static void main(String args[]) {

    // created an unsorted array
    int[] array = { 6, 5, 12, 10, 9, 1 };

    Main ob = new Main();

    // call the method mergeSort()
    // pass argument: array, first index and last index
    ob.mergeSort(array, 0, array.length - 1);

    System.out.println("Sorted Array:");
    System.out.println(Arrays.toString(array));
  }
}

```
----------------------------------------


# Question 61

### **Question:**

> ***Write a program to Implement Binary Search Algorithm.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.util.Scanner;

class MyClass {
  int binarySearch(int array[], int element, int low, int high) {

    // Repeat until the pointers low and high meet each other
    while (low <= high) {

      // get index of mid element
      int mid = low + (high - low) / 2;

      // if element to be searched is the mid element
      if (array[mid] == element)
        return mid;

      // if element is less than mid element
      // search only the left side of mid
      if (array[mid] < element)
        low = mid + 1;

      // if element is greater than mid element
      // search only the right side of mid
      else
        high = mid - 1;
    }

    return -1;
  }

  public static void main(String args[]) {

    // create an object of Main class
    Main obj = new Main();

    // create a sorted array
    int[] array = { 3, 4, 5, 6, 7, 8, 9 };
    int n = array.length;

    // get input from user for element to be searched
    Scanner input = new Scanner(System.in);

    System.out.println("Enter element to be searched:");

    // element to be searched
    int element = input.nextInt();
    input.close();

    // call the binary search method
    // pass arguments: array, element, index of first and last element
    int result = obj.binarySearch(array, element, 0, n - 1);
    if (result == -1)
      System.out.println("Not found");
    else
      System.out.println("Element found at index " + result);
  }
}
```
----------------------------------------

# Question 62

### **Question:**

> ***Write a program to Load File as Input Stream.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.io.InputStream;
import java.io.FileInputStream;

public class MyClass {

  public static void main(String args[]) {

    try {

      // file input.txt is loaded as input stream
      // input.txt file contains:
      // This is a content of the file input.txt
      InputStream input = new FileInputStream("input.txt");

      System.out.println("Data in the file: ");

      // Reads the first byte
      int i = input.read();

      while(i != -1) {
        System.out.print((char)i);

        // Reads next byte from the file
        i = input.read();
      }
      input.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
----------------------------------------

# Question 63

### **Question:**

> ***Write a program to Create File and Write to the File.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.io.File;

class MyClass {
  public static void main(String[] args) {

    // create a file object for the current location
    File file = new File("JavaFile.java");

    try {

      // create a new file with name specified
      // by the file object
      boolean value = file.createNewFile();
      if (value) {
        System.out.println("New Java File is created.");
      }
      else {
        System.out.println("The file already exists.");
      }
    }
    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
----------------------------------------

 
# Question 64

### **Question:**

> ***Write a program to Read the Content of a File Line by Line.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.io.BufferedInputStream;
import java.io.FileInputStream;

class MyClass {
  public static void main(String[] args) {
    try {

      // Creates a FileInputStream
      FileInputStream file = new FileInputStream("input.txt");

      // Creates a BufferedInputStream
      BufferedInputStream input = new BufferedInputStream(file);

      // Reads first byte from file
      int i = input .read();

      while (i != -1) {
        System.out.print((char) i);

        // Reads next byte from the file
        i = input.read();
      }
      input.close();
    }

    catch (Exception e) {
      e.getStackTrace();
    }
  }
}
```
----------------------------------------

 
# Question 65

### **Question:**

> ***Write a program to Delete File.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.io.File;

class MyClass {
  public static void main(String[] args) {

    // creates a file object
    File file = new File("JavaFile.java");

    // deletes the file
    boolean value = file.delete();
    if(value) {
      System.out.println("JavaFile.java is successfully deleted.");
    }
    else {
      System.out.println("File doesn't exit");
    }
  }
}
```
----------------------------------------
# Question 66

### **Question:**

> ***Write a program to Get the File Extension.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.io.File;

class MyClass {

  public static void main(String[] args) {
    File file = new File("Test.java");

    // convert the file name into string
    String fileName = file.toString();

    int index = fileName.lastIndexOf('.');
    if(index > 0) {
      String extension = fileName.substring(index + 1);
      System.out.println("File extension is " + extension);
    }
  }
}
```
----------------------------------------

# Question 67

### **Question:**

> ***Write a program to Count number of lines present in the file.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.io.File;
import java.util.Scanner;

class MyClass {
  public static void main(String[] args) {

    int count = 0;

    try {
      // create a new file object
      File file = new File("input.txt");

      // create an object of Scanner
      // associated with the file
      Scanner sc = new Scanner(file);

      // read each line and
      // count number of lines
      while(sc.hasNextLine()) {
        sc.nextLine();
        count++;
      }
      System.out.println("Total Number of Lines: " + count);

      // close scanner
      sc.close();
    } catch (Exception e) {
      e.getStackTrace();
    }
  }
}
```
----------------------------------------
# Question 68

### **Question:**

> ***Write a program to Merge two lists.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.util.ArrayList;
import java.util.List;

class MyClass {
  public static void main(String[] args) {

    // create first list
    List<Integer> prime = new ArrayList<>();
    prime.add(2);
    prime.add(3);
    prime.add(5);
    System.out.println("First List: " + prime);

    // create second list
    List<Integer> even = new ArrayList<>();
    even.add(4);
    even.add(6);
    System.out.println("Second List: " + even);

    // create merged list
    List<Integer> numbers = new ArrayList<>();
    numbers.addAll(prime);
    numbers.addAll(even);

    System.out.println("Merged List: " + numbers);

  }
}
```
----------------------------------------

# Question 69

### **Question:**

> ***Write a program to Remove duplicate elements from Array List.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.util.ArrayList;
import java.util.Arrays;
import java.util.LinkedHashSet;
import java.util.Set;

class MyClass {
  public static void main(String[] args) {

    // create an arraylist from the array
    // using asList() method of the Arrays class
    ArrayList<Integer> numbers = new ArrayList<>(Arrays.asList(1, 2, 3, 4, 1, 3));
    System.out.println("ArrayList with duplicate elements: " + numbers);

    // convert the arraylist into a set
    Set<Integer> set = new LinkedHashSet<>();
    set.addAll(numbers);

    // delete al elements of arraylist
    numbers.clear();

    // add element from set to arraylist
    numbers.addAll(set);
    System.out.println("ArrayList without duplicate elements: " + numbers);
  }
}
```
----------------------------------------

# Question 70

### **Question:**

> ***Write a program to Calculate union of two sets.***

----------------------------------------

<strong>Solution: </strong>

```Java
import java.util.HashSet;
import java.util.Set;

class MyClass {
  public static void main(String[] args) {

    // create the first set
    Set<Integer> evenNumbers = new HashSet<>();
    evenNumbers.add(2);
    evenNumbers.add(4);
    System.out.println("Set1: " + evenNumbers);

    // create second set
    Set<Integer> numbers = new HashSet<>();
    numbers.add(1);
    numbers.add(3);
    System.out.println("Set2: " + numbers);

    // Union of two sets
    numbers.addAll(evenNumbers);
    System.out.println("Union is: " + numbers);
  }
}
```
----------------------------------------

# Question 71

### **Question:**

> ***Write a program to determine whether one string is a rotation of another.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {    
    public static void main(String[] args) {    
        String str1 = "abcde", str2 = "deabc";    
            
        if(str1.length() != str2.length()){    
            System.out.println("Second string is not a rotation of first string");    
        }    
        else {    
            //Concatenate str1 with str1 and store it in str1    
            str1 = str1.concat(str1);    
             //Check whether str2 is present in str1    
            if(str1.indexOf(str2) != -1)    
                System.out.println("Second string is a rotation of first string");    
            else    
                System.out.println("Second string is not a rotation of first string");    
        }    
    }    
}
```
----------------------------------------

# Question 72

### **Question:**

> ***Write a program to find the duplicate characters in a string.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {    
     public static void main(String[] args) {    
        String string1 = "Great responsibility";    
        int count;    
            
        //Converts given string into character array    
        char string[] = string1.toCharArray();    
            
        System.out.println("Duplicate characters in a given string: ");    
        //Counts each character present in the string    
        for(int i = 0; i <string.length; i++) {    
            count = 1;    
            for(int j = i+1; j <string.length; j++) {    
                if(string[i] == string[j] && string[i] != ' ') {    
                    count++;    
                    //Set string[j] to 0 to avoid printing visited character    
                    string[j] = '0';    
                }    
            }    
            //A character is considered as duplicate if count is greater than 1    
            if(count > 1 && string[i] != '0')    
                System.out.println(string[i]);    
        }    
    }    
}     

```
----------------------------------------


# Question 73

### **Question:**

> ***Write a program to find the duplicate words in a string.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {    
    public static void main(String[] args) {    
        String string = "Big black bug bit a big black dog on his big black nose";    
        int count;    
            
        //Converts the string into lowercase    
        string = string.toLowerCase();    
            
        //Split the string into words using built-in function    
        String words[] = string.split(" ");    
            
        System.out.println("Duplicate words in a given string : ");     
        for(int i = 0; i < words.length; i++) {    
            count = 1;    
            for(int j = i+1; j < words.length; j++) {    
                if(words[i].equals(words[j])) {    
                    count++;    
                    //Set words[j] to 0 to avoid printing visited word    
                    words[j] = "0";    
                }    
            }    
                
            //Displays the duplicate word if count is greater than 1    
            if(count > 1 && words[i] != "0")    
                System.out.println(words[i]);    
        }    
    }    
}    
```
----------------------------------------

# Question 74

### **Question:**

> ***Write a program to find maximum and minimum occurring character in a string.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {    
   
   public static void main(String[] args) {    
      String str = "grass is greener on the other side";    
      int[] freq = new int[str.length()];    
      char minChar = str.charAt(0), maxChar = str.charAt(0);    
      int i, j, min, max;            
          
      //Converts given string into character array    
      char string[] = str.toCharArray();    
          
      //Count each word in given string and store in array freq    
      for(i = 0; i < string.length; i++) {    
          freq[i] = 1;    
          for(j = i+1; j < string.length; j++) {    
              if(string[i] == string[j] && string[i] != ' ' && string[i] != '0') {    
                  freq[i]++;    
                      
                  //Set string[j] to 0 to avoid printing visited character    
                  string[j] = '0';    
              }    
          }    
      }    
          
      //Determine minimum and maximum occurring characters    
      min = max = freq[0];    
      for(i = 0; i <freq.length; i++) {    
              
          //If min is greater than frequency of a character     
          //then, store frequency in min and corresponding character in minChar    
          if(min > freq[i] && freq[i] != '0') {    
              min = freq[i];    
              minChar = string[i];    
          }    
          //If max is less than frequency of a character     
          //then, store frequency in max and corresponding character in maxChar    
          if(max < freq[i]) {    
              max = freq[i];    
              maxChar = string[i];    
          }    
      }    
          
      System.out.println("Minimum occurring character: " + minChar);    
      System.out.println("Maximum occurring character: " + maxChar);    
  } 
}  
```
----------------------------------------

# Question 75

### **Question:**

> ***Write a program to separate the Individual Characters from a String.***

---------------------------------------

<strong>Solution: </strong>

```Java
public class MyClass {  
    public static void main(String[] args) {  
        String string = "characters ";  
  
        //Displays individual characters from given string  
        System.out.println("Individual characters from given string: ");  
  
        //Iterate through the string and display individual character  
        for(int i = 0; i < string.length(); i++){  
            System.out.print(string.charAt(i) + " ");  
        }  
    }  
}  
```
----------------------------------------



</br>

<h2> Papers  </h2>

<ul>

 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(1).pdf" style="text-decoration:none;">J-Orchestra: Enhancing Java Programs with Distribution Capabilities</a></li>


 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(2).pdf" style="text-decoration:none;">A New Approach for Java Based Kernel</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(3).pdf" style="text-decoration:none;">Proactive Empirical Assessment of New Language Feature Adoption via Automated Refactoring: The Case of Java 8 Default Methods</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(4).pdf" style="text-decoration:none;">Trace-based Debloat for Java Bytecode</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(5).pdf" style="text-decoration:none;">Java Applications Development Based on Component and Metacomponent Approach</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(6).pdf" style="text-decoration:none;">A comparison of three programming languages for a full-edged next-generation sequencing tool</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(7).pdf" style="text-decoration:none;">Java Web Design Frameworks: Review of Java Frameworks For Web Applications</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(8).pdf" style="text-decoration:none;"> Reflection Analysis for Java</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(9).pdf" style="text-decoration:none;">
New Software Development Methodology for Student of Java Programming Language </a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(10).pdf" style="text-decoration:none;">e JAVA Chatbot for Learning Programming</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(11).pdf" style="text-decoration:none;">Eclipse Platform Technical Overview</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(12).pdf" style="text-decoration:none;">Study on Design and Implementation of JAVA Programming Procedural Assessment Standard</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(13).pdf" style="text-decoration:none;">Making the future safe for the past: Adding Genericity to the Java Programming Language</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(14).pdf" style="text-decoration:none;">Java Applet</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(15).pdf" style="text-decoration:none;">Java Basics</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(16).pdf" style="text-decoration:none;">Writing Robust Java Code:
The AmbySoft Inc. Coding Standards for Java</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(17).pdf" style="text-decoration:none;">
Differences between Java Concepts</a></li>   
  
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(18).pdf" style="text-decoration:none;">Exception handling in java</a></li> 

  
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(19).pdf" style="text-decoration:none;">Teach yourself Java module</a></li> 

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(20).pdf" style="text-decoration:none;"> Java programming for C/C++ developers</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(21).pdf" style="text-decoration:none;">The Java Language
Specification</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(22).pdf" style="text-decoration:none;">Kotlin Language Documentation</a></li> 
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(23).pdf" style="text-decoration:none;"> Language Oriented Programming: The Next Programming Paradigm</a></li> 
 

   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(24).pdf" style="text-decoration:none;">Automatic Source Code Summarization of Context for Java Methods</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(25).pdf" style="text-decoration:none;">Transparent Acceleration of Java-based Deep Learning Engines</a></li>                              
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(26).pdf" style="text-decoration:none;">Neural Network Implementation in Java</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(27).pdf" style="text-decoration:none;">C++ for Java Programmers</a></li>
   
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(28).pdf" style="text-decoration:none;">The Scratch Programming Language
and Environment</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(29).pdf" style="text-decoration:none;">The benefits of using Java as a
high-performance language for mission critical financial applications</a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(30).pdf" style="text-decoration:none;">Challenges for Static Analysis of Java Reflection – Literature Review and Empirical Study</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(31).pdf" style="text-decoration:none;">A Simple Application ProgramInterface for Saving Java Program Data on a Wiki</a></li> 
    <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(32).pdf" style="text-decoration:none;">The Java Memory Model is Fatally Flawed</a></li> 

   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(33).pdf" style="text-decoration:none;">Comparative Study of C, C++, C# and Java Programming Languages</a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(34).pdf" style="text-decoration:none;">C# Versus Java</a></li> 
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(35).pdf" style="text-decoration:none;">JAVA for
Beginners</a></li> 

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(36).pdf" style="text-decoration:none;">New Learning Methodology for Student of Java Programming Language</a></li> 
 
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(37).pdf" style="text-decoration:none;">A Java Fork/Join Framework</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(38).pdf" style="text-decoration:none;">Study of Development of Java Applications in Eclipse Environment and Development of Java Based Calendar Application with Email Notifications</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(39).pdf" style="text-decoration:none;">Introduction to Programming Using Java</a></li> 
 
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(40).pdf" style="text-decoration:none;">A Large Scale Study of Programming Languages and Code Quality in Github</a></li> 

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(41).pdf" style="text-decoration:none;">Automatic Source Code Summarization of Context for Java Methods</a></li> 
 
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(42).pdf" style="text-decoration:none;">Using Memory Errors to Attack a Virtual Machine</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(43).pdf" style="text-decoration:none;">Polymorphism in the Spotlight: Studying Its Prevalence in Java and Smalltalk</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(44).pdf" style="text-decoration:none;">Object-Oriented Programming Basics With Java</a></li> 
 
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(45).pdf" style="text-decoration:none;">Performance analysis and optimization of the Java memory system</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(46).pdf" style="text-decoration:none;">Dynamic Metrics for Java</a></li>

 
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(47).pdf" style="text-decoration:none;">Java in the High Performance Computing Arena: Research, Practice and Experience</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/jva(48).pdf" style="text-decoration:none;">Loop Recognition in C++/Java/Go/Scala</a></li>













</ul>

</br>
<h2>Source Codes: </h2>
<ul>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/JavaFX animated login and sign up form.rar" style="text-decoration:none;">JavaFX animated login and sign up form</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Payroll System.rar" style="text-decoration:none;">Payroll System</a></li>

 
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Phone Book App.rar" style="text-decoration:none;">Phone Book Application</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Simple Banking System.rar" style="text-decoration:none;">Simple Banking System</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Text to Morse Code and Binary.rar" style="text-decoration:none;">Text to Morse Code and Binary</a></li>
 
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Baby Care Project.rar" style="text-decoration:none;">Baby Care Project</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Broadcasting Chat Server Project.rar" style="text-decoration:none;">Broadcasting Chat Server Project</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/City Classified and Search.rar" style="text-decoration:none;">City Classified and Search</a></li>
  
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Company Mailer Project.rar" style="text-decoration:none;">Company Mailer Project</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Connect Globe.rar" style="text-decoration:none;">Connect Globe</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Fee Management.rar" style="text-decoration:none;">Fee Management</a></li>
  
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Library Management System.rar" style="text-decoration:none;">Library Management System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Mailcasting Project.rar" style="text-decoration:none;">Mailcasting Project</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Pharmacy Project.rar" style="text-decoration:none;">Pharmacy Project</a></li>
  
  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-Java-Exercises/blob/master/Transport Company.rar" style="text-decoration:none;">Transport Company</a></li>   
  
  
  
  
</ul>
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
	


 
