# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a java program to calculate the number of tokens present in the tokenizer string.
## ALGORITHM :
1: Start program

2: Import the required classes: import java.util.* for Scanner and StringTokenizer.

3: Create the Main class.

4: Inside the main method:

a. Create a Scanner object to read user input.

b. Read a full line of text input from the user using nextLine().

c. Create a StringTokenizer object with the input string as its argument.

d. Use countTokens() method to count the number of tokens (words separated by whitespace by default).

e. Print the total number of tokens.

5: End


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by:Nivetha A
RegisterNumber:212222230101  
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main
{
    public static void main(String[]args)
  {
        Scanner scan = new Scanner(System.in);
        String name = scan.nextLine();
        StringTokenizer st = new StringTokenizer(name);
        System.out.println("Total number of Tokens: "+st.countTokens());
   }
}
```

## OUTPUT:

![437526667-d9e530aa-7f1f-4ce1-9845-c4a69c78b3d1](https://github.com/user-attachments/assets/0e69171e-ee16-44ca-b8ae-817cac285557)


## RESULT:
Thus the Java program successfully has calculate the number of tokens present in the tokenizer string.
