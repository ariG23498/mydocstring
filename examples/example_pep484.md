
# example_function
```python
def example_function(arg1: int, arg2: int =1) -> bool:
```

---


This is an example of a docstring that conforms to the Google style guide. 
The indentation uses four spaces (no tabs). Note that each section starts
with a header such as `Arguments` or `Returns` and its contents is indented.

## Arguments
* **arg1**  : This description for this argument fits on one line.
* **arg2**  : This description is too long to fit on a
    single line. Note that it is continued by being indented. 

## Returns
* Stating the return type here is optional.

We can continue putting explanations in this section as long as the text
is indented.

---
This text is no longer indented and therefore not part of the `Returns`
section.

## Raises
* **ValueError**  : This is exception is raised when arg1 and arg2 are equal.

## Examples

Code block 1.

```python

>>> a
0

```
Code block 2.

```python

>>> b
1

```


## Source
```python
def example_function(arg1: int, arg2: int =1) -> bool:bool
    if arg1 == arg2:
        raise ValueError("`arg1` and `arg2` cannot be equal.")
    if arg1 > arg2:
        return True
    else: 
        return False

```

