## 3.2 Output

As discussed previously in [1.2 First Program](01-getting-started/01-2-first-program.md), we use `System.out.println("Output message")` to show output.

##### Difference between println() and print()

`println()` will print the message and automatically put the cursor in the next line.
    
However, `print()` will leave the cursor just after the output message.

`print("This is a test message\n")` and `println("This is a test message")` will produce the same output.

#### Printing values of variables

```java
public class OutputTest {

    public static void main(String[] args) {
        int x = 42;
        System.out.println(x); // This prints 42 to the console. 
    }
}

```