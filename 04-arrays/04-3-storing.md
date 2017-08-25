## Storing values

We can store values in the array by using a similar syntax as before.

```java
    int[] arr = new int[10];
    
    arr[0] = 43;
    arr[1] = 2;
    arr[2] = -5;
    
    ...
    
    arr[9] = 86;
    arr[10] = 14; // This statement will throw Exception    
    
    
    System.out.println(arr[9]) // 86
    System.out.println(arr[2]) // -5
```