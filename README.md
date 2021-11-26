# 3u-functions

Functions
---

For each exercise, create a function according to the specifications, complete with docstrings.

---------

## Exercise 1

Create a new file in this repo called **number_systems.py**. Within it, create 2 functions: **base_to_dec(n, b)** and **dec_to_base(n, b)**.

### Input Specification for base_to_dec

The function takes 2 positive integers: **n** and **b**. **n** represents a number written in base **b** - a number between 1 to 10.

### Output Specification for base_to_dec

A positive integer that represents the base **b** number **n** written as a decimal.

**Sample Calls**
```
>>> base_to_dec(101, 2)
5
    
>>> base_to_dec(576, 8)
382
```
### Input Specification for dec_to_base

The function takes 2 positive integers: **n** and **b**. **n** represents a decimal number and **b** is a number between 1 to 10 that represents the target base.

### Output Specification for dec_to_base

A positive integer that represents the decimal number **n** written in base **b**.

**Sample Calls**
```
>>> dec_to_base(5, 2)
101
>>> dec_to_base(382, 8)
576
```

---------

## Exercise 2

Create a new file in this repo called **fractions.py**. Within it, create 2 functions: **gcd(a, b)** and **reduce_fraction(a, b)**.

### Input Specification for gcd

The function takes 2 positive integers greater than or equal to 1: **a** and **b**.

### Output Specification for gcd

A positive integer that represents the greatest common divisor of **a** and **b**.

**Sample Calls**
```
>>> gcd(16, 18)
2
    
>>> gcd(24, 36)
12
```

### Input Specification for reduce_fraction

The function takes 2 positive integers greater than or equal to 1: **a** and **b**.

### Output Specification for reduce_fraction

A tuple of positive integers that represent the fraction a/b reduced.

**Sample Calls**
```
>>> dec_to_base(5, 2)
101
>>> dec_to_base(382, 8)
576
```
