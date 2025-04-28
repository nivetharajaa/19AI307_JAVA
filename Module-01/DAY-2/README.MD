# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
Develop a java program to check and print whether given input is vowel or consonant using if..else statement.

## ALGORITHM :
1. Start the program.
2. Import the java.util package for Scanner input.
3. Create a class named VowelConsonantChecker.
4. Define the main method.
5. Create a Scanner object (sc) to read user input.
6. Prompt the user: "Enter a single alphabet character:"
7. Read the input character using sc.next().charAt(0) and store it in a variable (ch).
8. Convert the character to lowercase (to handle both uppercase and lowercase inputs).
9. Check if the character is a vowel (a, e, i, o, u):
    If yes, print "[character] is a vowel."
    Else if the character is between 'a' to 'z' (valid alphabet), print "[character] is a consonant."
    Else, print "Invalid input! Please enter an alphabet letter.
10. Close the Scanner object.
11. End the program.

## PROGRAM:
 ```
Program to implement a variable and operators using Java
Developed by: Pavithra R
RegisterNumber: 212222230106
```

## Sourcecode.java:

```java
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        char ch=input.next().charAt(0);
        if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U')
         System.out.print(ch+" is vowel");
        else
         System.out.print(ch+" is consonant");
    }
}
```
## OUTPUT:

## RESULT:
Thus, the Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true is created successfully.
