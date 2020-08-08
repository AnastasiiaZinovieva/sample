# Hello my dear friends!

## A python example

*average* is **sum** (bold) of elements devided by their **number** (bold)

To calculate the average we need to:
1. calculate sum (ordered list)
   1. initialize accumulator variable
   1. loop through elements
      * add each of them to the iterator
1. determine number of elements i.e. via `len(list)`
1. divide by the number of elements

### Note that:
* sum may be:
  * integer
  * float

* average is (bold) **always** float

```python
def average(list):
    sum = 0.0
    for e in list:
        sum += e
    return sum / len(list)
```

