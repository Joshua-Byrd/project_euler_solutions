# Project Euler Problem 1

## Javascript
```
let sum = 0;

for (i = 1; i < 1000; i++) {
    if (i % 3 === 0 || i % 5 === 0) {
        console.log(i);
        sum += i;

    }
}

```

## Python

```
answer = sum([x for x in range(1000) if (x % 3 == 0) or (x % 5 == 0)])


```