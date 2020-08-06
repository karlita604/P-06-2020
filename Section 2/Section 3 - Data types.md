


# Basic Data Types

| NAME | TYPE |DESCRIPTION|EXAMPLE
|:--:|:------:|:--:|:-:|
| Integers | Int | whole numbers| 1 2 300 |
|Floating Points| float| decimal points| 2.3 0.0 14.6|
|Strings| str| ordered sequence of characters between quotations|"hello" "goodbye123"|
|Lists|list|ordered sequence of objects| [10,"h3llo", 30.4]|
|Dictionaries| dict| unordered key:value pairs| ("key":"value", "name":"Karla")
|Tuples| tup| unordered immutable sequence of objects| (10,"Lady")|
|Sets| set| unordered collection of unique objects| ("a","b")
|Boolean| bool| Logic values| True, False|

Data structures: everything including and below "Lists" in the table


# Numbers
Two main number types: Integers and Floating Points

Addition +
Subtraction -
Mult*
Div /
Mod %
Exponent **
Parantheses

**Why doesn't 0.1+0.2-0.3 equal 0.0 ?**

This has to do with floating point accuracy and computer's abilities to represent numbers in memory. For a full breakdown, check out: https://docs.python.org/2/tutorial/floatingpoint.html

# Variable Assignments

* Names cannot start with a number
* No spaces in the name
* Can only use alphanumeric symbols
* Best practice: lowercase only
* No key words

**Dynamic Typing**: you can reassign variables to different datatypes
(vs. **Statically-Typed**)

  
```python
my_dog=1;
my_dog="LC";
```

This allows you to not have. towrite out any data types 
--> faster dev time.
-->may result in bugs when we have unexpected datatypes.

In order to check the type `type(x)`

** if you ever have an error you can restart the kernel and that will erase every variable assignment so you can start again**


# Strings
Because strings are ordered sequence, we can use **indexing** and **slicing**

**Indexing:** 
* allows you tp grab a single bit of the string
* []
* index starts at 0
* reverse indexing ! -1 = last letter always
* white spaces count as characters in the string

```python
mystring = "Hello World"
mystring[0]
--> 'H'
mystring[-2]
-->'l'
```

**Slicing:**
* allows you to grab a whole section of a string
* [start:stop:step]
	* start is the numerical index for the slice part
	* stop is the index you will go up to (NOT included)
	* step is the size of the "jump"

```python
astring = "abcdefghijk"
astring[2:]
---> 'cdefghijk'
astring[:3]
---> 'abc'
astring[::]
---> 'abcdefghijk'
astring[2:7:2]
-->'ceg'


astring[::-1]
--->'kjihgfedcba'
```

**Escape sequences:** 
\n : new line
\t : tab
len("x") : returns length of string x
#comment


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0OTUzMDQ5ODQsLTE2NjIyMTcyODYsMT
kzNzE4MzUwMywtMTUxNTAzMTYyLDE3Njg3OTY3NTksMjIwODQw
MTk0LC0xNzIyNjk1OTkzLDg1NjYxNTYwMSwyOTA0NTYyODYsMT
Q4NzIzMzQ1LDEzODM2NDY3OTIsLTM2NjI4OTA1NSwtNTM2MjQ1
MzQzLC04NDc4Nzk0MDAsMTk5NDA1NCwyMDQwMjk3NjIyXX0=
-->