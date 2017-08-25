## Accessing the values

```java
int[] arr = new int[10];
```

At this point all the 10 values in **arr** are 0. This is because the default value of _int_ is 0. We talk about default values in the next chapter.

We can access the values in the array using

```java
    System.out.println(arr[0];
    System.out.println(arr[1];
    System.out.println(arr[2];
    
    ...
    System.out.println(arr[9];
```

Every print statement will print a 0. Remember the indices of array starts from 0 and not 1.
Thus, the last index is 9 and not 10.

```java
    System.out.println(arr[10];
    // This will throw an Exception and the programme will crash.
```

