# Project Euler Problem 2

## Javascript
```
let num1 = 1;
let num2 = 2;
let num3 = 0;
let sum = 2;

while (num3 < 4000000){
  num3 = num1 + num2;
  num1 = num2;
  num2 = num3;

  if (num3 % 2 === 0){
    sum += num3;
  }
}

//sum = 4613732


```

## Python

```
num1 = 1
num2 = 2
num3 = 0
sum = 2

while num3 < 4000000:
    num3 = num1 + num2
    num1 = num2
    num2 = num3

    if num3 % 2 == 0:
        sum += num3

#sum = 4613732
```