# `for` loops

## Iterate over list
```python
fruit = ["apple", "orange", "grape", "banana", "kiwi"]
for f in fruit:
    print(f)
```

## Iterate over list with index
```python
fruit = ["apple", "orange", "grape", "banana", "kiwi"]
for i, f in enumerate(fruit):
    print(f"{i}: {f}")
```

## Iterate over two lists in parallel
```python
fruit = ["apple", "orange", "grape", "banana", "kiwi"]
veggie = ["carrot", "tomato", "bean", "pea"]
for f, v in zip(fruit, veggie):
    print(f"{f}, {v}")
```

# Types

Python is dynamically typed. That means the types are evaluated at runtime. That is why type errors are
a kind of exception.

Adding type hint to your code just helps to clarify it. The interpreter actually does not look at them.

Example:
```python
def f(text: str, number: int) -> str:
    print(number)
    inner: int = number
    return str


```

