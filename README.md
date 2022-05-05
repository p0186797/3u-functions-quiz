# 3u-functions-quiz

Functions Quiz
---

For each exercise, create a function according to the specifications, complete with docstrings.

Use this site for reference:

https://capitalizemytitle.com/military-time/1201/

---------

## Exercise 1

Create a new file in this repo called **military_time.py**. Within it, create 2 functions: **to_military**, **to_standard**. **to_military** converts time in standard form to military form. **to_standard** converts time in military form to standard form.

### Input Specification for to_military

The function takes in a str in the form HH:MM and a str that is either "am" or "pm". HH will be 01 to 12 and MM will be 00 to 59.

### Output Specification for to_military

Military time as a str in the form HHMM where HH will be 00 to 23 and MM will be 00 to 59.

**Sample Calls**
```
>>> to_military("12:00", "am")
"0000"
>>> to_military("12:05", "am")
"0005"
>>> to_military("01:25", "am")
"0125"
>>> to_military("03:55", "pm")
"1555"
>>> to_military("11:59", "pm")
"2359"
```
### Input Specification for to_standard

The function takes a str representation of a military time in the form HHMM. HH will be 00 to 23 and MM will be 00 to 59.

### Output Specification for to_standard

Standard time as a str in the form HH:MM am or HH:MM pm where HH will be from 01 to 12 and MM will be from 00 to 59.

**Sample Calls**
```
>>> to_standard("0125")
"01:25 am"
>>> to_standard("2359")
"11:59 pm"
```

---------

## Exercise 2

Create a new file in this repo called **quadratics.py**. Within it, create 2 functions: **get_a_b_c** and **is_point_on_quad**. **get_a_b_c** takes in a str in the form of y = ax^2 + bx + c and returns a tupple of ints: a, b, c.

### Input Specification for get_a_b_c

The function takes a str in the from y = ax^2 + bx + c.

### Output Specification for gcd

A tupple of 3 ints: a, b, c.

**Sample Calls**
```
>>> get_a_b_c("y = -2x^2 + 4x - 5")
(-2, 4, -5)
>>> get_a_b_c("y = 3x^2 
12
```

### Input Specification for reduce_fraction

The function takes 2 positive integers greater than or equal to 1: **a** and **b**. They represent the numerator and denominator of a fraction.

### Output Specification for reduce_fraction

A tuple of 2 positive integers that represent numerator and denominator of the fraction a/b reduced.

**Sample Calls**
```
>>> reduce_fraction(10, 12)
(5, 6)
>>> reduce_fraction(16, 8)
(2, 1)
```
