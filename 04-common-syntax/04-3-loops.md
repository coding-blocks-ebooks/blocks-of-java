## 4.3 Loops

Loops are used to execute some statements multiple times. There are 3 loop-constructs available in Java.


### 4.3.1 While loop

This is the simplest type of loop.

```java
    while(condition){
        // statement
    }
```

As long as the condition is true, the statement gets executed again and again.

##### Example

```java
    int count = 0;
    
    while(count<5){
        System.out.println("Hello");
        count = count + 1;
    }
```

##### Output
`Hello
Hello
Hello
Hello
Hello`

An important point to note whenever using a while loop is to have a *Terminating condition*. That is to make sure that the condition becomes false at some point or else the programme will be stuck in an infinite loop.

### 4.3.2 For loop