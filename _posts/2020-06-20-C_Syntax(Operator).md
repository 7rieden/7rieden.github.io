---
layout: post
title: Operator
date: 2020-06-20
permalink: /C_Lang/C
tags: [C]
comments: true
---

## Converting Seconds to Minutes

```c
#include <stdio.h>
#define SECOND_PER_MINUTE 60

int main(){
    int input;
    int min = input / SECOND_PER_MINUTE;
    int sec = input % SECOND_PER_MINUTE;
    printf("How many seconds?\n")
    scanf("%d\n",&input);
    printf("%d seconds = %d minutes %d seconds. \n", input, min, sec);

    return 0;
}
```
<br>
---

## Increment and Decrement Operators

```c
#include <stdio.h>

int main(){
    int x = 0;
    printf("Now x is %d.\n", x);
    x++;
    printf("Now x is %d.\n", x);
    x += 100; // x = x + 100
    printf("Now x is %d.\n", x);
    x -= 50; //x = x - 50
    printf("Now x is %d.\n", x);
    x *= 5; // x = x * 5
    printf("Now x is %d.\n", x);
    x %= 3; 
    printf("Now x is %d.\n", x);
    printf("Now x is %d.\n", x);

    return 0;
}
```

! `printf("Now x is %d.\n", x--);` decrease after printing
<br>
---

## Relations
```c
#include <stdio.h>

int main(){
    int x = 20, y = 30;
    printf("x = y ? %d\n", x == y ); // false = 0, true = 1
    printf("Is it different x from y? %d\n", x != y); // 1
    printf("x is bigger than y ? %d\n", x > y ); // 0
    printf("x is smaller than y ? %d\n", x < y ); // 1

    return 0;
}
```
<br>
---

## Logic Operators

```c
#include <stdio.h>

int main(){
    int x = 50, y = 30;
    printf("x is bigger than y, and y is less than 40? %d\n", (x > y) && (y < 40)); // 1
    printf("x is smaller than y, or y is 30? %d\n", (x < y) || (y == 30)); // 1
    printf("x is not 50? %d\n", x != 50); // 0

    return 0;
}
```
<br>
---

## Condition

```c
#include <stdio.h>

int main(){
    int x = -50, y = 30;
    int absoluteX= (x > 0) ? x : -x;
    int max = (x > y) ? x : y;
    int min = (x < y) ? x : y;
    printf("The absolute value is %d.\n", absoluteX);
    printf("The Maximum in x, y is %d.\n", max);
    printf("The Minimum in x, y is %d.\n", min);


    return 0;
}
```
<br>
---

## pow()

```c
#include <stdio.h>
#include <math.h> //pow(), abs()

int main(){
    double x = pow(2.0, 20.0);
    printf("2 ^20 = %.0f\n.", x); // 1048576

    return 0;
}
```