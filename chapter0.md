### Programming Basics

We will start with the very basics of programming. Please ensure your virtual machine from the previous two chapters is up and running. Open the XTerm application. If none of this makes sense please revisit the first two chapters to get comfortable. One of Python's most useful tools is the *Interactive Shell*. 

You can start your interactive shell by typing `python` in your XTerm application. 

```bash
python
Python 2.7.8 (default, Oct 18 2014, 12:50:18)
[GCC 4.9.1] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

The `>>>` (also chevron prompt) is the interactive shell. Enter *21 + 21* at the prompt and let Python do some simple arithmetic. 

```python
>>> 21 + 21
42
>>>
```

Interactive Shell:
![interactive shell](images/chapter101.png)

In Python, 21 + 21 is an _expression_, which is the smallest and most basic kind of instruction in the language. Expressions will have _values_ (in this case 21) and will have _operators_ (in this case +) which will _evaluate_ to a single value (in this case 42). Expressions are used anywhere in your code that you could use a value. 

In our second example enter the value *42* with no operators. This is also an expression which just evaluates to itself.

```python
>>> 42
42
```

We have seen the use of the addition operator above. Python uses others that we will demonstrate below.

```python
>>> 2 + 8 * 5
42
>>> (2 + 8) * 5
50
>>> 234567 * 456789
107147625363
>>> 2 ** 4
16
>>> 42 / 5
8
>>> 42.0 / 5
8.4
>>> 42.0 // 5
8.0
>>> 42 % 5
2
>>> (8 - 2) * ((3 + 4.0) / (5 - 2))
14.0
```

