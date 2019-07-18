# C++ Primer

## Compound Types

### References

A reference is a types that refers to another type 

```c++
int ival = 1024;
int &refval = ival; // refers to ival
```

A reference is an alias (another name) and is NOT an object

```c++
refval = 2; // assigns 2 to ival
int ii = refval; // equivalent to ii = ival;
int &refval2 = refval; // bounds refval 2 to ival
int &refval3 = 10; // error: must initialize to an object
double dval;
int &refval4 = dval // error: must initialize to an object of same type
```
