---
title: Course Materials
layout: template
filename: materials
--- 

# 1. First Session

## An Introduction to Python Programming

You can download the introductory presentation file by following the link provided below.


<a href="https://drive.google.com/file/d/1CccpPF6sBml0l_dvmNUv2NnlsVDffva-/view?usp=sharing" target="_blank"><button>Presentation</button></a>


## Python Environment

### Installing Python

<p style='text-align: justify;'>
If you haven't installed Python on your computer yet, you can download it for free from the official Python website. Simply follow this link to the download page:
</p>

<a href="https://www.python.org/downloads/" target="_blank"><button>Python</button></a>

<p style='text-align: justify;'>
An IDE, or Integrated Development Environment, is a software application that provides a comprehensive environment for programmers to write, edit, and debug code. Visual Studio Code (VSCode) is a popular and powerful IDE developed by Microsoft that supports various programming languages and platforms. I recommend using VSCode as your primary IDE for Python programming tasks. Download VSCode for free from the official website at the following link (Unfortunately, you may use an anti-filter for downloading this):
</p>

<a href="https://code.visualstudio.com/download#" target="_blank"><button>VSCode</button></a>


### Online Python programming

<p style='text-align: justify;'>
To fully immerse yourself in learning Python, it is highly recommended that you install Python on your computer. However, if you do not have access to a computer with Python installed, you can still explore the language using online platforms such as Google Colab or online-python, which can execute Python code.
</p>

<a href="https://colab.research.google.com/notebooks/intro.ipynb" target="_blank"><button>Colab</button></a>    <a href="https://www.online-python.com/" target="_blank"><button>online-python</button></a>


## Python Reserved Words

<p style='text-align: justify;'>
Python reserved keywords are words that have special meanings and purposes in the Python programming language. These keywords cannot be used as variable names, function names, or any other identifiers because they are already reserved for specific programming constructs. Here is the full list of Python reserved keywords:
</p>

```
and     continue  finally  is        raise
as      def       for      lambda    return
assert  del       from     None      True
async   elif      global   nonlocal  try
await   else      if       not       while
break   except    import   or        with
class   False     in       pass      yield
```
<p style='text-align: justify;'>
It can be useful to keep this list of Python reserved keywords handy. If you encounter an error message from the interpreter related to a variable name, you can quickly check if the variable name is a reserved keyword by referring to this list.
</p>


## Session Codes

In the window below, you can view all the code I have written during this session.

<details>
  <summary>
    summary
  </summary>
  ```
  (base) ➜  ~ python3
  Python 3.9.7 (default, Sep 16 2021, 08:50:36) 
  [Clang 10.0.0 ] :: Anaconda, Inc. on darwin
  Type "help", "copyright", "credits" or "license" for more information.
  
  >>> print('Salam')
  Salam
  >>> x = 1
  >>> x
  1
  
  >>> # Talk about values
  >>> 2
  2
  >>> 4.5
  4.5
  
  >>> # Talk about strings
  >>> "salam"
  'salam'
  
  >>> type(12)
  <class 'int'>
  >>> #integer
  >>> #float
  >>> type(3.2)
  <class 'float'>
  >>> type('salam')
  <class 'str'>
  >>> type(-12)
  <class 'int'>
  
  >>> salam
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  NameError: name 'salam' is not defined
  
  >>> print(3)
  3
  >>> print("Hello world")
  Hello world
  
  >>> #?? type("3.5")
  >>> #?? type(salam)
  >>> type("3.5")
  <class 'str'>
  >>> type(salam)
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  NameError: name 'salam' is not defined
  
  
  >>> # Talk about variable. something that changes.
  >>> x = 2
  
  >>> # Talk about computer memory
  >>> X * 2
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  NameError: name 'X' is not defined
  
  >>> x * 2
  4
  >>> x = 6
  >>> x * 2
  12
  
  >>> pi = 3.14
  >>> r = 50
  >>> pi * r * r
  7850.0
  >>> pi = 3.141592
  >>> pi * r * r
  7853.98
  >>> area = pi * r * r
  >>> # memory talk
  >>> area
  7853.98
  
  >>> x = 1
  >>> x = x + 1
  >>> x
  2
  >>> # How x = x + 1 works. 
  
  >>> # Talk about naming
  >>> # a->z, A->Z, 0->9
  >>> # Mehrdad, mehrdad
  >>> # underscore _
  >>> # Good naming
  
  >>> # gheymate 234 jabe daskesh latex
  >>> gheymate_livan =  200000
  >>> tedad = 130
  >>> gheymate_kol = gheymate_livan * tedad
  >>> gheymate_kol
  26000000
  >>> print(gheymate_kol)
  26000000
  >>> # memory talk
  
  >>> # Case sensitivity
  >>> sen = 50
  >>> Sen
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  NameError: name 'Sen' is not defined
  
  >>> # Error reading
  >>> # number in the variable beginning
  
  >>> # reserved keywords in python
  >>> False = 2
    File "<stdin>", line 1
      False = 2
      ^
  SyntaxError: cannot assign to False
  >>> # ?? pps = 10, area = 20, tp = pps * area, area = 30, print(tp)
  
  >>> #Statement: A statement is a unit of code that the Python interpreter can execute.
  >>> x = 1
  >>> print(x)
  1
  
  >>> # Operators: + - * / ** // %
  >>> 2 ** 8
  256
  
  >>> 17 // 3
  5
  >>> 17 % 3
  2
  
  >>> # reminder by % 10 
  
  
  >>> # Expression: An expression is a combination of values, variables, and operators. A value all by itself is considered an expression.
  >>> x * 3 + 6 / 89 ** 2
  3.000757480116147
  >>> 3 + 2 - 1
  4
  
  >>> # () ** */ +-
  >>> 5 - 3 * 2
  -1
  >>> (5 - 3) * 2
  4
  
  >>> my_name = "mehrdad"
  >>> print("my_name")
  my_name
  >>> my_family = "shadlou"
  >>> print("my_family")
  my_family
  >>> print(my_name + my_family)
  mehrdadshadlou
  >>> print(my_name + ' ' +  my_family)
  mehrdad shadlou
  >>> 'python' * 5
  'pythonpythonpythonpythonpython'
  
  >>> 'm' * "v"
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  TypeError: can't multiply sequence by non-int of type 'str'
  
   
  >>> # taking input
  >>> input()
  6
  '6'
  >>> input('your age')
  your age12
  '12'
  >>> input('your age: ')
  your age: 12
  '12'
  >>> age = input('your age: ')
  your age: 12
  >>> age
  '12'
  >>> type(age)
  <class 'str'>
  >>> age + 2
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  TypeError: can only concatenate str (not "int") to str
  >>> int(age)
  12
  >>> int(age) + 1
  13
  >>> age = input('your age: ')
  your age: 33.5
  >>> int(age)
  Traceback (most recent call last):
    File "<stdin>", line 1, in <module>
  ValueError: invalid literal for int() with base 10: '33.5'
  >>> float(age)
  33.5
  
  >>> # about commenting
  
  >>> # Talk about Boolean
  >>> 
  >>> True
  True
  >>> False
  False
  >>> type(False)
  <class 'bool'>
  
  >>> type(True)
  <class 'bool'>
  >>> 5 < 6
  True
  >>> 5 > 6
  False
  >>> x = 5
  >>> x > 10
  False
  >>> a = 3
  >>> b = -5
  >>> a > b
  True
  >>> # < > <= >= 
  >>> 5 >= 5
  True
  >>> # ==
  >>> a = 3
  >>> a == 3
  True
  >>> # !=
  >>> 4 <= 4
  True
  
  >>> 4 = 4
    File "<stdin>", line 1
      4 = 4
      ^
  SyntaxError: cannot assign to literal
  >>> a = 6
  >>> b= 7
  >>> a != b
  True
  >>> # not, and, or
  >>> not a != b
  False
  >>> # making sentensec
  >>> # sen > 10 , ghad > 1m
  >>> # hassan 3y, 2m
  >>> (3>4) and (4>1)
  False
  >>> (3<4) and (4>1)
  True
  >>> (3>4) or (4>1)
  True
  ```
</details>

