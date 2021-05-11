# TRIVIA Q/As

## Trivia #1
### Code
```
num = 1.3E4
print(num)
```
## Answers
* a) 1.3E4
* b) 13000.0
* c) SyntaxError: invalid syntax
* d) 1.33333
## Solution
**B**

float literals in Python can be represented with an exponent.


## Trivia #2
### Code
```
num = 2_455_122
print(num)
```
## Answers
* a) SyntaxError: invalid syntax
* b) 2_455_122
* c) [2, 455, 122]
* d) 2455122
## Solution
**D**

You can use an underscore for both integer and float literals to group digits together.


## Trivia #3
### Code
```
s = "women who code python"
c = s.capitalize()
print(c)
```
## Answers
* a) Women who code python
* b) Women Who Code Python
* c) WOMEN WHO CODE PYTHON
* d) women who code Python
## Solution
**A**

The str.capitalize() method will change the first character in a string to a titlecase (starting from python 3.8) or an uppercase (prior to python 3.8).


## Trivia #4
### Code
```
s = "women who code python"
print(s[::-1])
```
## Answers
* a) women who code pytho
* b) ["w","o","m","e","n"," ","w","h","o"," ","c","o","d","e"," ","p","y","t","h","o"]
* c) nohtyp edoc ohw nemow
* d) w
## Solution
**C**

Python slicing syntax support a third argument (step or stride) that can be used to make a copy of the same list in reverse order


## Trivia #5
### Code
```
import difflib
a = ["bee", "tobe", "ornottobe", "bees", "bebebe"]
matches = diffli* b)get_close_matches("be", a, n=1)
print(matches)
```
## Answers
* a) ["tobe"]
* b) ["bee"]
* c) "bebebe"
* d) "tobe"
## Solution
**B**

The get_close_matches() function in the difflib module can be used to return a list of the best "good enough" matches. We set the optional "n" parameter to 1 in order to only return the word with the highest similarity score to the word "be". The order of the resulting matches are determined by the heapq.nlargest() function using the measure of each word similarity where T is the total number of elements in both words, and M is the number of matches (2.0*M / T).


## Trivia #6
### Code
```
a = ["women", "who", "code", "python"]
j = "\t".join(a)
print(j)
```
## Answers
* a) women\twho\tcode\tpython
* b) ["\t", "women", "who", "code", "python"]
* c) women	who	code	python
* d) womentwhotcodetpython
## Solution
**C**

The str.join() method can be used to return a string which concatenate all the strings of an iterable separated by the the string provided to it. In this specific case, we use the \t escape sequence to separate each string by a ta* b)


## Trivia #7
### Code
```
import datetime
a = datetime.date(2021, 5, 23)
b = datetime.date(2020, 6, 13)
c = a-b
print(c.days)
```
## Answers
* a) 344
* b) 344 days, 0:00:00
* c) 344 days
* d) TypeError: unsupported operand type(s) for -: 'datetime.date' and 'datetime.date'
## Solution
**A**

You can use the subtraction operator between two datetime.date() objects to return a datetime.timedelta() object which contain the number of days between them.


## Trivia #8
### Code
```
#!/usr/bin/env python
import argparse

if __name__ == "__main__":
    parser = argparse.ArgumentParser()
    parser.add_argument('-n', '--names', nargs='+')

    args = parser.parse_args()
    print(args.names)
```
```    
my_cmd --names "Franz Martell" "Regina Hunt" "Christophe Cousineau" "Aarushi Ravel"
```
## Answers
* a) SyntaxError: invalid syntax
* b) ["Franz Martell" "Regina Hunt" "Christophe Cousineau" "Aarushi Ravel"]
* c) Franz Martell Regina Hunt Christophe Cousineau Aarushi Ravel
* d) Franz Martell
## Solution
**B**

You can set the nargs parameter of the parser.add_argument() method to + to gather all the argument in a list. But unlike using *, it will throw an error message if not at least one argument is provide* d)


## Trivia #9
### Code
```
import os
p = os.path.join("/", "home", "me", "documents", "work", "reports/report.ppt")
print(p)
```
## Answers
* a) SyntaxError: invalid syntax
* b) /homemedocumentsworkreports/report.ppt
* c) /homemedocumentswork/reports/report.ppt
* d) /home/me/documents/work/reports/report.ppt
## Solution
**D**

the join() method of the os.path module can concatenate a given path with any number of subsequent paths given. Those paths can be a partial path, a directory name and/or a filename.


## Trivia #10
### Code
```
import datetime
d = datetime.datetime(1912, 6, 23)
fd = "{:%Y-%m-%d}".format(d)
print(fd)
```
## Answers
* a) 12-6-23
* b) 1912623
* c) 1912-06-23
* d) :1912-6-23
## Solution
**C**

You can format a datetime.date() object in a string literal or when using the str.format() metho* d)

## Trivia #11
### Code
```
import json
a = json.loads('[0.1, 0.4, 2.99, 4.5]')
print(a)
```
## Answers
* a) [0.1, 0.4, 2.99, 4.5]
* b) '[0.1, 0.4, 2.99, 4.5]'
* c) <function loads at 0xDEADC0DE>
* d) 0.1, 0.4, 2.99, 4.5
## Solution
**A**

You can use the loads() function of the json module to deserialize a string to a python object. it's a safer alternative to the eval() function when you want to convert a string into a data-type.

## Trivia #12
### Code
```
d = {"language":"python","version":"3.9.5"}
dd = {d[i]: i for i in d}
print(dd)
```
## Answers
* a) ["language", "version"]
* b) ["python", "3.9.5"]
* c) {"language":"python","version":"3.9.5"}
* d) {'python': 'language', '3.9.5': 'version'}
## Solution
**D**

A dictionary can have its key:value pair reversed by doign a dictionary comprehension (PEP274) at the condition that each value is unique.