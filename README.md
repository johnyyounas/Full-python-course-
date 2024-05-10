
```
# Lesson 1: Variables

Variables are objects containing specific values. They serve as names appointed to values or operations that we need to perform multiple times. Understanding variables is crucial for effective programming, as they facilitate efficient time management.

## Observing the Code:

```python
x = 5  # Numeric variable
print(x)

y = "we are learning with Sir Johny"  # String variable
print(y)

x = x + 156
print(x - 1)

# Identifying the type of variable
print(type(y))
```

## Rules for Assigning a Variable:

1. The variable should contain letters, numbers, or underscores.

```python
x_y = 5  # Example of a valid variable name
```

2. Do not start with a number.
3. Spaces are not allowed in variable names.
4. Avoid using Python keywords (e.g., print, input, break) as variable names.
5. Use lowercase words for better readability.
6. String literals should be enclosed in double or single quotes.

## Identifying the Type of Variable:

```python
fruit_basket = 'Mangoes', 'Oranges'
print(type(fruit_basket))
```

## Deleting a Variable:

```python
fruit_basket = 'apple', 'mango', 'banana'
del fruit_basket
fruit_basket = 2
print(fruit_basket)
```

Deleting variables may seem unnecessary, but understanding how to use the `del` function can be beneficial for managing memory and optimizing code.
```
