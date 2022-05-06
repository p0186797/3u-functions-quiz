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

Create a new file in this repo called **linear.py**. Within it, create 2 functions: **get_a_b_c** and **is_point_on_line**. **get_a_b_c** takes in a str in the form of ax + by = c and returns a tupple of ints: a, b, c. **is_point_on_quad** takes in a str in the form ax + by = c and 2 ints - x, y and returns True if (x, y) is on the line.

### Input Specification for get_a_b_c

The function takes a str in the from ax + by = c.

### Output Specification for get_a_b_c

A tupple of 3 ints: a, b, c.

**Sample Calls**
```
>>> get_a_b_c("-3x + 5y = 7")
(-3, 5, 7)
>>> get_a_b_c("12x - 7y = -5")
(12, -7, -5)
```

### Input Specification for is_point_on_line

The function takes 3 inputs: a str in the form ax + by = c and 2 ints: x, y.

### Output Specification for is_point_on_line

True or False

**Sample Calls**
```
>>> is_point_on_line("-3x + 5y = 7", 1, 2)
True
>>> is_point_on_line("12x - 7y = -5", 4, 3)
False
```
