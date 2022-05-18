# SASS Reference
## by Shubhrendu Tripathi

<br><br>

## Introduction

SASS (Syntactically Awesome Style Sheets) in an extension of CSS. It is also known as CSS pre-processor. SCSS was introduced in SASS version 3.

SCSS Syntax

    ```css
    nav {
        ul {
        margin: 0;
        padding: 0;
        list-style: none;
        }
        li {
        display: inline-block;
        }
        a {
        display: block;
        padding: 6px 12px;
        text-decoration: none;
        }
    }
    ```

Corresponding CSS Syntax

    ```css
    nav ul {
        margin: 0;
        padding: 0;
        list-style: none;
    }
    nav li {
        display: inline-block;
    }
    nav a {
        display: block;
        padding: 6px 12px;
        text-decoration: none;
    }
    ```

SASS to CSS - Transpilation (one human-readable format is converted into another human-readable format)

Sass supports two different file extensions, namely, `.sass` and `.scss`, one is for SASS code and the other is for SCSS syntax. As we already mentioned in our introduction tutorial, Sass became Scss from version 3 which has a syntax which is very much similar to CSS as compared to Sass which has a very different syntax.

## Benefits of SCSS

<ul>
<li>It uses the nested syntax, which is more readable.</li>
<li>It offers the use of variables, as seen in the examples above.</li>
<li>The syntax is similar to CSS, hence the learning curve is easier.</li>
<li><b>Functions(mixins)</b> can be created with SCSS.</li>
<li>It allows Inheritance too.</li>
</ul>

## Installation

<ul>
<li><u>GitHub</u>: https://github.com/sass/sass</li>
<li><u>NPM</u>:
    $ npm install -g sass
</ul>

<ins>Using VS Code for Sass</ins>

Live Sass compiler
https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass

## Variables

Sass allows variables to be defined. Variables begin with a dollar sign ($). Variable assignment is done with a colon (:).

SassScript supports four data types:
<ul>
<li>Numbers (including units)</li>
<li>Strings (with quotes or without)</li>
<li>Colors (name, or names)</li>
<li>Booleans</li>
</ul>

Variables can be arguments to or results from one of several available functions. During translation, the values of the variables are inserted into the output CSS document.

SCSS

    $primary-color: #3bbfce;
    $margin: 16px;
    .content-navigation {
        border-color: $primary-color;
        color: darken($primary-color, 10%);
    }
    .border {
        padding: $margin / 2;
        margin: $margin / 2;
        border-color: $primary-color;
    }

Compiled CSS

    .content-navigation {
        border-color: #3bbfce;
        color: #2b9eab;
    }

    .border {
        padding: 8px;
        margin: 8px;
        border-color: #3bbfce;
    }

## Nesting

CSS does support logical nesting, but the code blocks themselves are not nested. Sass allows the nested code to be inserted within each other.

SCSS

    table.h1 {
        margin: 2em 0;
        td.in {
            text-align: right;
        }
    }

    li {
        font: {
            family: serif;
            weight: bold;
            size: 1.3em;
        }
    }

Compiled CSS

    table.h1 {
        margin: 2em 0;
    }
    table.h1 td.ln {
        text-align: right;
    }

    li {
        font-family: serif;
        font-weight: bold;
        font-size: 1.3em;
    }

More complicated types of nesting including namespace nesting and parent references are discussed in the Sass documentation.

SCSS

    @mixin table-base {
        th {
            text-align: center;
            font-weight: bold;
        }
        td, th {
            padding: 2px;
        }
    }

    #data {
        @include table-base;
    }

Compiled CSS

    #data th {
        text-align: center;
        font-weight: bold;
    }
    #data td, #data th {
        padding: 2px;
    }

## Loops
Sass allows for iterating over variables using @for, @each and @while, which can be used to apply different styles to elements with similar classes or ids.

Sass

    $squareCount: 4
    @for $i from 1 through $squareCount 
        #square-#{$i} 
        background-color: red
        width: 50px * $i
        height: 120px / $i

Compiled CSS

    #square-1 {
        background-color: red;
        width: 50px;
        height: 120px;
    }

    #square-2 {
        background-color: red;
        width: 100px;
        height: 60px;
    }

    #square-3 {
        background-color: red;
        width: 150px;
        height: 40px;
    }

## Arguments

Mixins also support arguments.

Sass

    =left($dist)
        float: left
        margin-left: $dist

    #data
        +left(10px)

Compiled CSS

    #data {
        float: left;
        margin-left: 10px;
    }

In combination

Sass

    =table-base 
        th 
            text-align: center
            font-weight: bold
        td, th
            padding: 2px

    =left($dist)
        float: left
        margin-left: $dist

    #data
        +left(10px)
        +table-base


Compiled CSS

    #data {
        float: left;
        margin-left: 10px;
    }

    #data th {
        text-align: center;
        font-weight: bold;
    }

    #data td, #data th {
        padding: 2px;
    }

Selector inheritance

CSS3 does not allow selector inheritance. In Saas, inheritance is achieved by inserting a line inside of a code block that uses the @extend keyword and references another selector. The extended selector's attributes are applied to the calling selector. 

Sass

    .error 
        border: 1px #f00
        background: #fdd

    .error.intrusion
        font-size: 1.3em
        font-weight: bold

    .badError
        @extend .error
        border-width: 3px


Compiled CSS

    .error, .badError {
        border: 1px #f00;
        background: #fdd;
    }

    .error.intrusion, 
    .badError.intrusion {
        font-size: 1.3em;
        font-weight: bold;
    }

    .badError {
        border-width: 3px;
    }

# References

* https://www.studytonight.com/sass
* https://en.wikipedia.org/wiki/Sass_(stylesheet_language)

