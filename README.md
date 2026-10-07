# Day-120-Count-Element
# Python Day 120 - Count Element

## Description

This program demonstrates how to use the `count()` method in Python.

The `count()` method is used to find how many times a particular value appears in a list.

## Example

```text id="example120"
List: [10, 20, 10, 30, 10, 40, 20]
10 appears 3 times.
```

## Code

```python id="code120"
numbers = [10, 20, 10, 30, 10, 40, 20]

print("List:", numbers)

number = 10

count = numbers.count(number)

print(number, "appears", count, "times.")
```

## Concepts Used

* Lists
* `count()` method
* Variables
* Searching elements
* `print()`

## How It Works

1. A list named `numbers` is created.
2. The number `10` is stored in the variable `number`.
3. `numbers.count(number)` counts how many times `10` appears.
4. The result is stored in the `count` variable.
5. The result is displayed using `print()`.

## Important Note

```python id="note120"
numbers.count(10)
```

This returns the number of times `10` appears in the list.

For example:

```text id="count120"
[10, 20, 10, 30, 10]
 ↑       ↑       ↑
       3 times
```

## File Name

`count_element.py`

## Goal

The goal of this program is to understand how to count the occurrences of an element in a Python list using the `count()` method.
