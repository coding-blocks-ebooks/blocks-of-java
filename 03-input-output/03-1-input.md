## 3.1 Input

#### Scanner

We will use Scanner class to take input from the user.

```java
import java.util.Scanner;

public class InputTest {
    
    public static void main(String[] args) {
        Scanner scrn = new Scanner(System.in);
        int x = scrn.nextInt();
    }

}

```

This program will wait for the user to enter an integer value. Once the user enters a value, it gets stored in the integer variable x.

`scrn` is an _object_ of class `Scanner` that has various functions. We use one such function `nextInt()` to get integer input.

Other commonly used functions - 

* `next()` for reading <b>String</b> upto the next space, `nextLine()` is used to read the whole line.
* `next().charAt(0)` for reading a <b>Character</b>.
* `nextByte()`, `nextBoolean()`, `nextFloat()`, etc for respective datatypes. 

It is a good practice to close the input stream by calling `scrn.close()` after you have used the Scanner object and you don't need it anymore. 
