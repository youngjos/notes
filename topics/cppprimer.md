# C++ Primer

## Compound Types

![](../img/references.png)

### References

A reference is a type that refers to another type 

```c++
int ival = 1024;
int &refval = ival; // refers to ival
```

A reference is an alias (another name) and is NOT an object

```c++
refval = 2; // assigns 2 to ival
int ii = refval; // equivalent to ii = ival;
int &refval2 = refval; // bounds refval2 to ival
int &refval3 = 10; // error: must initialize to an object
double dval;
int &refval4 = dval // error: must initialize to an object of same type
```

### Pointers

A pointer points to another type

```c++
int *ip1; // integer pointer
int ival = 42;
int *ip2 = &ival; // integer pointer holding the address of ival
double dval;
double *dp1 = &dval; // double pointer holding the address of dval
double *dp2 = dp1; // double pointer
int *ip3 = dp1; // error: bad types
ip3 = &dval; // error: double address can not be assigned to int points

myvar == 25; // true
&myvar == 1776; // true
foo == 1776; // true
*foo == 25; // true
```
