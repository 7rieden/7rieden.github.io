---
layout: post
title: Data Type 
date: 2020-06-17
permalink: /C_Lang/C
tags: [C]
comments: true
---
## Data Type
#### 1.Primitive
 `char`/`int`/`float`/`double`/`void`
#### 2.Derivied
 `Array`/`Pointer`/`Function`
#### 3.User defined
 `Enum`/`Structure`/`Union`
<br>

## Variables Data Types
 `Integer`/`Character`/`Float`/`Double`

---

## Calculating annual salary with <b>double</b>

```c
#include <stdio.h>
#define MONTHS 12

int main(){
    double monthSalary = 3000.50;
    printf("$ %.2f", monthSalary * MONTHS);

    return 0;
}
```

`#define MONTHS 12` is <b>Constants</b>

---

## ASCII

```c
#include <stdio.h>

int main(){
    char x = 'A';
    printf("%c", x);
    int y = 'A';
    printf("%c", y);
    char z = 'B';
    printf("%c", z);

    return 0;
}
```
---

## Printing with Decimal,Octal,Hexadecimal Numbers
```c
#include <stdio.h>

int main(){
    int x = 100;
    printf("Decimal Number : %d\n", x);
    printf("Octal Number: %o\n", x);
    printf("Hexadecimal Number: %x", x);

    return 0;
}
```