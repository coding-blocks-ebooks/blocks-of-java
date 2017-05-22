## 1.2 First Program

Lets start by a simple program that prints Hello World on the console.

```java
public class Test {

    public static void main(String[] args) {

        System.out.println("Hello World");

    }

}
```

Lets see what is going on here.

* The compiler starts reading our program from the main\(\) function. Therefore, anything meaningful has to be inside this main\(\) function.
* We write `System.out.println("Hello World");` to print Hello World on the console.
* Since java is purely object oriented, we need to write our programs inside a class. We will discuss more about this later.
* The class name and the file name should be same. In this case, you will have to make sure that you are writing this code in a file named _Test.java_