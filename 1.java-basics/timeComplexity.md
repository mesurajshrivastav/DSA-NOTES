What is time complexity?

- Rate of which the time taken increases with respect to the input size.

tc != time taken to the machine -- because it is depending on the system

code - old windows time take 2s.
code - new macbook time take 1s.

Tc - Big oh notation - O() inside this we write time taken

```java
    for(int i=0; i<5; i++){
        System.out.pritln("Ss");
    }

    //check, print , increase so 3*5 15 O(15)

    // whatever is the total no of steps, we write inside the big oh notation
```

- Time complexity to be computed in wrost case secanario
- Avoid constants
- avoid lower values

```java
  for(int i=0; i<N; i++){
        System.out.pritln("Ss");
    }

    // now it will run N times  3*N = O(3N)
```
