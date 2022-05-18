# Python Reference
## by Shubhrendu Tripathi

<br><br>

This repository contains a collection of sample code, recipes, snippets, etc for the Python 3 programming language.

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

# Author
Shubhrendu Tripathi
<br><br>
[![GitHub followers](https://img.shields.io/github/followers/shubhtr.svg?style=social&label=Follow%20shubhtr)](https://github.com/shubhtr) [![Twitter Follow](https://img.shields.io/twitter/follow/shubhtr.svg?style=social)](https://twitter.com/intent/follow?screen_name=shubhtr)

## Variables and Constants

### Defining Variables

### Types of Data

### Variable Scope

### Predefined Variables

### Variable-handling Functions

## For

## If-Else

## While

## Switch

### Ternary Operator

### Modules

### Constants

#### Default constants

Constant                | Description
---                     | ---
`__LINE__`              | denotes the number of the current line in a file
`__FILE__`              | is the full path and filename of the file
`__DIR__`               | directory of the file
`__FUNCTION__`          | name of the function
`__CLASS__`             | class name, includes the namespace it was declared in
`__TRAIT__`             | the trait name, also includes the namespace
`__METHOD__`            | the class method name
`__NAMESPACE__`         | name of the current namespace

## array

## return

## namespace

## require_once

## dirname(__FILE__)

## use

## function

## throw - try - catch - Exception

# Error reporting 

# OOP


## Class and Object


### class


### object


### $this


### change a property


### instanceof 


### Constructor


### call parent constructor in child class

    
### private

### public


## File Operations

### fopen

### fread

### fclose

## Keywords

    False
    None
    True

    and
    as
    assert
    async
    await

    break

    class
    continue

    def
    del

    elif
    else
    except

    finally
    for
    from

    global

    if
    import
    in
    is

    lambda

    nonlocal
    not

    or

    pass

    raise
    return

    try

    while
    with

    yield

## String

<ins>Note</ins>: All string methods returns new values. They do not change the original string.


Method | Description |
--- | --- |
capitalize() |	Converts the first character to upper case
casefold() |	Converts string into lower case
center() |	Returns a centered string
count()	| Returns the number of times a specified value occurs in a string
&nbsp; | &nbsp;
encode() |	Returns an encoded version of the string
endswith() |	Returns true if the string ends with the specified value
expandtabs() |	Sets the tab size of the string
&nbsp; | &nbsp;
find() |	Searches the string for a specified value and returns the position of where it was found
format() |	Formats specified values in a string
format_map() |	Formats specified values in a string
&nbsp; | &nbsp;
index()	| Searches the string for a specified value and returns the position of where it was found
isalnum() |	Returns True if all characters in the string are alphanumeric
isalpha() |	Returns True if all characters in the string are in the alphabet
isdecimal() |	Returns True if all characters in the string are decimals
isdigit() |	Returns True if all characters in the string are digits
isidentifier() |	Returns True if the string is an identifier
islower() |	Returns True if all characters in the string are lower case
isnumeric() |	Returns True if all characters in the string are numeric
isprintable() |	Returns True if all characters in the string are printable
isspace() |	Returns True if all characters in the string are whitespaces
istitle() |	Returns True if the string follows the rules of a title
isupper() |	Returns True if all characters in the string are upper case
&nbsp; | &nbsp;
join() |	Joins the elements of an iterable to the end of the string
&nbsp; | &nbsp;
ljust() |	Returns a left justified version of the string
lower() |	Converts a string into lower case
lstrip() |	Returns a left trim version of the string
&nbsp; | &nbsp;
maketrans() |	Returns a translation table to be used in translations
&nbsp; | &nbsp;
partition() |	Returns a tuple where the string is parted into three parts
&nbsp; | &nbsp;
replace() |	Returns a string where a specified value is replaced with a specified value
rfind() |	Searches the string for a specified value and returns the last position of where it was found
rindex() |	Searches the string for a specified value and returns the last position of where it was found
rjust() |	Returns a right justified version of the string
rpartition() |	Returns a tuple where the string is parted into three parts
rsplit() |	Splits the string at the specified separator, and returns a list
rstrip() |	Returns a right trim version of the string
&nbsp; | &nbsp;
split() |	Splits the string at the specified separator, and returns a list
splitlines() |	Splits the string at line breaks and returns a list
startswith() |	Returns true if the string starts with the specified value
strip() |	Returns a trimmed version of the string
swapcase() |	Swaps cases, lower case becomes upper case and vice versa
&nbsp; | &nbsp;
title() |	Converts the first character of each word to upper case
translate() |	Returns a translated string
&nbsp; | &nbsp;
upper() |	Converts a string into upper case
&nbsp; | &nbsp;
zfill() |	Fills the string with a specified number of 0 values at the beginning

<br>

## Format a number with leading zeros 



## Executing shell commands

### `os.system`

### `subprocess.run`

### `subprocess.Popen`


# References
* [The Python Language Reference](https://docs.python.org/3/reference/index.html)
* [The Python Standard Library](https://docs.python.org/3/library/index.html)

* https://www.w3schools.com/python/python_ref_string.asp
* https://stackabuse.com/executing-shell-commands-with-python/



