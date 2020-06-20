---
layout: post
title: Variables & Constants
date: 2020-06-17
permalink: /C_Lang/C
tags: [C],[Syntax]
comments: true
---
## sizeof
```c
#include <stdio.h>

int main(){
    int x;
    x = 10;
    printf("%d", x);
    printf("Memory size of variable x is %d", sizeof(x));

    return 0;
}
```
<br>

## Learning Data Types (int,float,double)
```c
#include <stdio.h>

int main() {
    int x = 100;
    float y = 123456789.123456789;
    double z = 123456789.123456789;
    print("x = %d \n", x);
    printf("y = %.2f\n", y);
    printf("z = %.2f\n", z);

    return 0;
}
```

<br>

## Overflow with <limits.h>
```c
#include <stdio.h>
#include <limits.h>

int main(){
    int x = INT_MAX;
    print("Integer x's Max is %d.\n", x);
    print("x + 1 = %d\n", x + 1);

    return 0;
}
```
<br>
`Interger x's Max is 2147483647.`
`x + 1 = -2147483648`

<br>

## Artithmetic operations
```c
#include <stdio.h>

int main(){
    int a = 2;
    int b = 3;

    printf("a = %d\n", a);
    printf("b = %d\n", b);
    printf("a + b = %d", a + b);
    printf("a - b = %d", a - b);
    printf("a * b = %d", a * b);
    printf("a / b = %d", a / b);
    printf("a % b = %d", a % b);
    
    return 0;
}
```