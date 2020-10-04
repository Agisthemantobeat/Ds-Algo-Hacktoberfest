## Python Cheatsheet

- [Python Basics](#python-basics)
    - [Math Operators](#math-operators)
    - [Data Types](#data-types)
    - [Variables](#variables)
    - [Comments](#comments)
 ## Python Basics

### Math Operators

From **Highest** to **Lowest** precedence:

| Operators | Operation        | Example         |
| --------- | ---------------- | --------------- |
| **        | Exponent         | `2 ** 3 = 8`    |
| %         | Modulus/Remainder| `22 % 8 = 6`    |
| //        | Integer division | `22 // 8 = 2`   |
| /         | Division         | `22 / 8 = 2.75` |
| *         | Multiplication   | `3 * 3 = 9`     |
| -         | Subtraction      | `5 - 2 = 3`     |
| +         | Addition         | `2 + 2 = 4`     |

Examples of expressions in the interactive shell:

```python
>>> 2 + 3 * 6
20
```

```python
>>> (2 + 3) * 6
30
```

```python
>>> 2 ** 8
256
```

```python
>>> 23 // 7
3
```

```python
>>> 23 % 7
2
```

```python
>>> (5 - 1) * ((7 + 1) / (3 - 1))
16.0
```

### Data Types

| Data Type              | Examples                                  |
| ---------------------- | ----------------------------------------- |
| Integers               | `-2, -1, 0, 1, 2, 3, 4, 5`                |
| Floating-point numbers | `-1.25, -1.0, --0.5, 0.0, 0.5, 1.0, 1.25` |
| Strings                | `'a', 'aa', 'aaa', 'Hello!', '11 cats'`   |

[*Return to the Top*](#python-cheatsheet)


### Variables

You can name a variable anything as long as it obeys the following rules:

* It can be only be a single word.
* Use combination of letters, numbers, and the underscore (`_`) character only.
* It can’t begin with a number.

Example:

```python
>>> abc = 'Hello'
>>> abc
'Hello'
```

### Comments

Inline comment:

```python
# This is a comment
```

Multiline comment:

```Python
# This is a
# multiline comment
```


[_Return to the Top_](#python-cheatsheet)




