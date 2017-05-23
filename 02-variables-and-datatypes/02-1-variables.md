## 2.1 Variables

When we declare a variable in Java, the compiler allocates empty space in the memory to store its value. The amount of space allocated depends on the data type of the variable.

```java
int x = 32;
```

In this case, an integer variable **x** is declared to store the value **32**. The value given to a variable is mutable ie it can change over the course of a program.

```java
int x = 32;

... // More code

x = 51;

```

The variable **x** used to store **32** initially which was then changed to **51**

Notice how we don't write ```int``` when changing the value. We only mention the datatype when the variable is declared for the first time.

We can do simple algebraic operations on variables such as : 

```java
int a = 2;
int b = 5;

int c = a + b; // c = 7
```

