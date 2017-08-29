## 4.2 If-else

If-else statements helps in decision control of a programme.

```java
    
    if(boolean expression){
        // Task 1
    }else{
        // Task 2
    }

```

If the boolean expression is `true` Task 1 will be executed, otherwise Task 2.

##### Example

```java

    int a = 4;
    int b = 12;
    
    if(a > b){
        System.out.println("A is greater");
    }else{
        System.out.println("B is greater");
    }
    
    // "B is greater" gets printed.
```

We can have a ladder of If-else statements.

```java
    
    
    if(condition 1){
        // Task 1
    } else if(condition 2){
        // Task 2
    }else if(condition 3){
        // Task 3
    }else if(condition 4){
        // Task 4   
    }else{
        // Task 5
    }
```


