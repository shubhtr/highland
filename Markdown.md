# Markdown Reference
## by Shubhrendu Tripathi

<br><br>

## Code

#### Syntax 

    `This is code`

#### Output

`This is code`

***

## Code Block

#### Syntax #1

    ----
    This is a 
    piece of code 
    in a block
    ----

#### Output

----
This is a 
piece of code 
in a block
----

#### Syntax #2

    ```
    This too
    ```

#### Output

```
This too
```

***

## Line

#### Syntax
    ***

#### Output
***

***

## Table

#### Syntax

    Header 1 | Header 2 | Header 3
    ---|---|---
    Content 1 | Content 2 | Content 3
    Content 4 | Content 5 | Content 6
    Content 7 | Contetn 8 | Content 9

#### Output

Header 1 | Header 2 | Header 3
---|---|---
Content 1 | Content 2 | Content 3
Content 4 | Content 5 | Content 6
Content 7 | Contetn 8 | Content 9

***

## Headers

### Syntax
    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6

    Alt-H1
    ======

    Alt-H2
    ------

### Output

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alt-H1
======

Alt-H2
------

## Bullet Lists

### Syntax
    * Item
    * Item
    - Item
    - Item

### Ouptput
* Item
* Item
- Item
- Item

## Underline

### Syntax
    <ins>This is underlined.</ins>

### Output
<ins>This is underlined.</ins>



## Pipe

### Syntax
    ls \| wc –l

### Output
$ ls \| wc –l

## Line Breaks

Do this | DONT DO THIS
--- | ---
First line with two spaces after.  <br>And the next line. | First line with a backslash after. \ <br> And the next line.
&nbsp; | &nbsp; 
First line with the HTML tag after.`<br>`<br>And the next line. | First line with nothing after.<br> And the next line.
<br><br>
backslashes are not recommended for compatibility reasons
<br><br>
<ins>TLDR;</ins> Use `<br>` for line break.


# Creating and highlighting code blocks

create fenced code blocks by placing triple backticks ``` before and after the code block. can add an optional language identifier to enable syntax highlighting in your fenced code block.

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```


# Links

    [The Python Language Reference](https://docs.python.org/3/reference/index.html)

# References
* https://www.markdownguide.org/basic-syntax/#line-break-best-practices
