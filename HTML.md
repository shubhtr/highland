# HTML Reference
## by Shubhrendu Tripathi

<br><br>

## Basic HTML

Tag                 | Description
---                 | ---
`<!DOCTYPE>`        | defines the document type
`<html>`            | defines an html document
`<head>`            | metadata/information for the document
`<title>`           | title of the document
`<body>`            | defines the document body
`<h1>` to `<h6>`    | html headings
`<p>`               | paragraph
`<br>`              | inserts a single line break
`<hr>`              | thematic change in the content
`<!-- ... -->`      | a comment

## Formatting

Tag                     | Description 
---                     | ---
`<abbr>`                | an abbreviation or an acronym
`<addr>`                | contact information for the author/owner of a document/article
&nbsp;                  |   
`<b>`                   | bold text
`<bdi>`                 | isolates a part of text that might be formatted in a different direction from other text outside it
`<bdo>`                 | overrides the current text direction
`<blockquote>`          | a section that is quoted from another source
&nbsp;                  |
`<cite>`                | the title of a work
`<code>`                | a piece of computer code
&nbsp;                  |
`<del>`                 | text that has been deleted from a document
`<dfn>`                 | specifies a term that is going to be defined within the content
&nbsp;                  |
`<em>`                  | emphasized text
&nbsp;                  |
`<i>`                   | a part of text in an alternate voice or mood
`<ins>`                 | a text that has been inserted into a document
&nbsp;                  |
`<kdb>`                 | keyboard input
&nbsp;                  |
`<mark>`                | defines marked/highlighted text
`<meter>`               | defines a scalar measurement within a known range (a guage)
&nbsp;                  |
`<pre>`                 | preformatted text
`<progress>`            | represents the progress of a task 
&nbsp;                  |
`<q>`                   | a short quotation
&nbsp;                  |
`<rp>`                  | defines what to show in browsers that do not support ruby annotations
`<rt>`                  | defines an explanation/pronounciation of characters (for East Asian typography)
`<ruby>`                | defines a ruby annotation (for East Asian typography)
&nbsp;                  |
`<s>`                   | defines text that is no longer correct
`<samp>`                | defines sample output from a computer program
`<small>`               | defines smaller text
`<strong>`              | defines important text
`<sub>`                 | defines subscripted text
`<sup>`                 | defines superscripted text
&nbsp;                  |
`<template>`            | defines a container for content that should be hidden when the page loads
`<time>`                | define a specific time (or datetime)
&nbsp;                  |
`<u>`                   | defines some text that is unarticulated and styled differently from normal text
&nbsp;                  | 
`<var>`                 | defines a variable
&nbsp;                  |
`<wbr>`                 | defines a possible line-break

## Forms and Input

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

<ins>Tip:</ins> Always use the `<label>` tag to define labels for the following:

`<input type="text">`\
`<input type="checkbox">`\
`<input type="radio">`\
`<input type="file">`\
`<input type="password">`

Tag                                     | Description                       | Output
---                                     | ---                               | ---
`<form>`                                |                                   | <form>
&nbsp;                                  | &nbsp;                            | &nbsp;
`<input>`                               |                                   | <input>
`<input type="button">`                 | input - button                    | <input type="button">
`<input type="checkbox">`               | input - checkbox                  | <input type="checkbox">
`<input type="color">`                  | input - color                     | <input type="color">
`<input type="date">`                   | input - date                      | <input type="date">
`<input type="datetime-local">`         | input - datetime - local          | <input type="datetime-local">
`<input type="email">`                  | input - email                                 | <input type="email">
`<input type="file">`                   | input - file                                  | <input type="file">
`<input type="hidden">`                 | input - hidden                                | <input type="hidden">
`<input type="image">`                  | input - image                                 | <input type="image">
`<input type="month">`                  | input - month                                 | <input type="month">
`<input type="number">`                 | input - number                                | <input type="number">
`<input type="password">`               | input - password                              | <input type="password">
`<input type="radio">`                  | input - radio                                 | <input type="radio">
`<input type="range">`                  | input - range                                 | <input type="range">
`<input type="reset">`                  | input - reset                                 | <input type="reset">
`<input type="search">`                 | input - search                                | <input type="search">
`<input type="submit">`                 | input - submit                                | <input type="submit">
`<input type="tel">`                    | input - tel                                   | <input type="tel">
`<input type="text">`                   | input - text (default value)                  | <input type="text">
`<input type="time">`                   | input - time                                  | <input type="time">
`<input type="url">`                    | input - url                                   | <input type="url">
`<input type="week">`                   | input - week                                  | <input type="week">
&nbsp;                                  | &nbsp;                                        | &nbsp;
`<textarea>`                            | a multiline input control (text area)         | <textarea></textarea>
`<button>`                              | a clickable button                            | <button></button>
`<select>`                              | a drop-down list                              | <select></select>
`<optgroup>`                            | a group of related options in a drop-down list    | <optgroup></optgroup>
`<option>`                              | an option in a drop-down list                     | <option></option>
`<label>`                               | a label for an `<input>` element                  | <label></label>
`<fieldset>`                            | group related elements in a form                  | <fieldset></fieldset>
`<legend>`                              | a caption for a `<fieldset>` element              | <legend></legend>
`<datalist>`                            | a list of pre-defined options for input controls  | <datalist></datalist>
`<output>`                              | defines a result of a calcuation                  | 

<br><br>

## Examples

Radio Buttons

    <!DOCTYPE html>
    <html>
    <body>

    <h1>Display Radio Buttons</h1>

    <form action="/action_page.php">
    <p>Please select your gender:</p>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br>
    <input type="radio" id="other" name="gender" value="other">
    <label for="other">Other</label>

    <br>  

    <p>Please select your age:</p>
    <input type="radio" id="age1" name="age" value="30">
    <label for="age1">0 - 30</label><br>
    <input type="radio" id="age2" name="age" value="60">
    <label for="age2">31 - 60</label><br>  
    <input type="radio" id="age3" name="age" value="100">
    <label for="age3">61 - 100</label><br><br>
    <input type="submit" value="Submit">
    </form>

    </body>
    </html>

select

    <!DOCTYPE html>
    <html>
    <body>

    <h1>The select element</h1>

    <p>The select element is used to create a drop-down list.</p>

    <form action="/action_page.php">
    <label for="cars">Choose a car:</label>
    <select name="cars" id="cars">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
        <option value="opel">Opel</option>
        <option value="audi">Audi</option>
    </select>
    <br><br>
    <input type="submit" value="Submit">
    </form>

    <p>Click the "Submit" button and the form-data will be sent to a page on the 
    server called "action_page.php".</p>

    </body>
    </html>

checkbox

    <!DOCTYPE html>
    <html>
    <body>

    <h1>Show Checkboxes</h1>

    <form action="/action_page.php">
    <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
    <label for="vehicle1"> I have a bike</label><br>
    <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
    <label for="vehicle2"> I have a car</label><br>
    <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
    <label for="vehicle3"> I have a boat</label><br><br>
    <input type="submit" value="Submit">
    </form>

    </body>
    </html>

textarea

    <label for="w3review">Review of W3Schools:</label>

    <textarea id="w3review" name="w3review" rows="4" cols="50">
    At w3schools.com you will learn how to make a website. They offer free tutorials in all web development technologies.
    </textarea>

## Frames

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                           | Output
---                 | ---                                   | ---
`<iframe>`          | defines an inline frame               | <iframe></iframe>

## Images

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                           | Output
---                 | ---                                   | ---
`<img>`             | image                                 | <img></img>
`<map>`             | a client-side image map               | <map></map>
`<area>`            | an area inside an image map           | <area></area>
`<canvas>`          | used to draw graphics, on the fly, via scripting (usually JavaScript)     | <canvas></canvas>
`<figcaption>`      | a caption for a `<figure>` element                                        | <figcaption></figcaption>
`<figure>`          | specifies self-contained content                                          | <figure></figure>
`<picture>`         | a container for multiple image resources                                  | <picture></picture>
`<svg>`             | a container for SVG graphics                                              | <svg></svg>

## Audio / Video

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<audio>`           | sound content                                                                         | <audio></audio>
`<source>`          | multiple media resources for media elements (`<video>`, `<audio>` and `<picture>`)    | <source></source>
`<track>`           | text tracks for media elements (`<video>` and `<audio>`)                              | <track></track>
`<video>`           | a video or movie                                                                      | <video></video>

## Links

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<a>`               | a hyperlink                                                                           | <a></a>
`<link>`            | relationship between a documents and an external resource                             | <link></link>
`<nav>`             | navigation links                                                                      | <nav></nav>


### Open in a new window
Use `target="_blank"`

`<a href="www.google.com" target="_blank">`

## Lists

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<ul>`              | an unordered list                                                                     | <ul></ul>
`<ol>`              | an ordered list                                                                       | <ol></ol>
`<li>`              | a list item                                                                           | <li></li>
`<dl>`              | a description list                                                                    | <dl></dl>
`<dt>`              | term/name in a description list                                                       | <dt></dt>
`<dd>`              | a description of a term/name in a description list                                    | <dd></dd>

## Tables

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<table>`           | a table                                                                               | <table></table>
`<caption>`         | a table caption                                                                       | <caption></caption>
`<th>`              | a header cell in a table                                                              | <th></th>
`<tr>`              | a row in a table                                                                      | <tr></tr>
`<td>`              | a cell in a table                                                                     | <td></td>
`<thead>`           | groups the header content of a table                                                  | <thead></thead>
`<tbody>`           | groups the body content of a table                                                    | <tbody></tbody>
`<tfoot>`           | groups the footer content of a table                                                  | <tfoot></tfoot>
`<col>`             | specifies column properties for each column within a `<colgroup>` element             | <col></col>
`<colgroup>`        | specifies a group of one or more columns in a table for formatting                    | <colgroup></colgroup>

## Styles and Semantics

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<style>`           | a style information for a document                                                    | <style></style>
`<div>`             | a section in a document                                                               | <div></div>
`<span>`            | a section in a document                                                               | <span></span>
`<header>`          | a header for a document or section                                                    | <header></header>
`<footer>`          | a footer for a document or section                                                    | <footer></footer>
`<main>`            | the main content of a document                                                        | <main></main>
`<section>`         | a section in a document                                                               | <section></section>
`<article>`         | an article                                                                            | <article></article>
`<aside>`           | content aside from the page content                                                   | <aside></aside>
`<details>`         | additional details that the user can view or hide                                     | <details></details>
`<dialog>`          | a dialog box or window                                                                | <dialog></dialog>
`<summary>`         | a visible heading for a `<details>` document                                          | <summary></summary>
`<data>`            | adds a machine-readable translation of a given content                                | <data></data>

## Meta Info

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<head>`            | information about the document                                                        | <head></head>
`<meta>`            | metadata about an HTML document                                                       | <meta></meta>
`<base>`            | based url/target for all relative URLS in a document                                  | <base></base>


## Programming

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description                                                                           | Output
---                 | ---                                                                                   | ---
`<script>`          | a client-side script                                                                  | <script></script>
`<noscript>`        | an alternate content for users that do not support client-side scripts                | <noscript></noscript>
`<embed>`           | a container for an external (non-HTML) application                                    | <embed></embed>
`<object>`          | an embedded object                                                                    | <object></object>
`<param>`           | a parameter for an object                                                             | <param></param>

## Special Characters

<ins>Note:</ins> The Output column shows some elements when previewed in Visual Studio Code. It does not show this on GitHub.com

Tag                 | Description            | Output
---                 | ---                    | ---
`&ensp;`            | half point size of the current font | &ensp;
`&emsp;`            | tab                    | &emsp;  
`&nbsp;`            | space                  | &nbsp;

<br><br>

## Status Codes

### Status Code Classes

Class | Description | Details
--- | --- | ---
1xxs</b> | <b>Informational responses</b> | the server is thinking through the request.
2xxs</b> | <b>Success!</b> | The request was successfully completed and the server gave the browser the expected response.
3xxs</b> | <b>Redirection</b> | You got redirected somewhere else. The request was received, but there's a redirect of some kind.
4xxs</b> | <b>Client errors</b> | Page not found. The site or page couldn't be reached. (The request was made, but the page isn't valid - this is an error on the website's side of the conversation and often appears when a page doesn't exist on the site.)
5xxs</b> | <b>Server errors</b> | Failure. A valid request was made by the client but the server failed to complete the request.

### Common status codes

Code | Status | Description
--- | --- | ---
200 | <b>OK</b> | request was successfully carried out
&nbsp; | &nbsp; | &nbsp;
301 | <b>Moved Permanently</b> | data requested from the client cannot be found under the given address since it has been moved permanently
302 | <b>Moved Temporarily</b> | the requested data has temporarily been moved. remaining information is specified so that an automatic redirection can take place. the old address remains valid.
307 | <b>Temporary redirect</b> | a more specific redirect method than the 302 code and has the browser perform the redirect instead of the server. This is useful for sites served on HTTPS that are on an HTTP Strict-Transport-Security (HSTS) preload list.
&nbsp; | &nbsp; | &nbsp;
400 | <b>Bad Request</b> | something went wrong with the client request.
403 | <b>Forbidden</b> | the requested data is access protected and the request cannot performed due to client's lack of authorization. 
404 | <b>Not Found</b> | requested website information was not found on the server. it could be that the address no longer exists or the contents were moved to a new address without notice. any links to non-existing pages are known as 'dead links'
410 | <b>Gone</b> | a resource or URL is unavailable because it was deleted on purpose and was not redirected.
&nbsp; | &nbsp; | &nbsp;
500 | <b>Internal Server Error</b>| 500 server response functions as a collection status code for unexpected server errors. If an error occurs on the server’s part, which prevents the requested data from being retrieved, this HTTP status code will automatically be issued. As well as sending an answer to the client the webserver also creates an internal error report. 
502 | <b>Bad Gateway</b> | It’s delivered when the server, which is accessed via the main server, couldn’t forward the request. In this case, the first server functions only as a proxy or gateway.
503 | <b>Service Unavailable</b> | the relevant web server, which should deliver the requested information, is overloaded. The server response occasionally contains information about when the request can be processed at the earliest.
504 | <b>Gateway Timeout</b> | the cause of the failure was due to a timeout during the processing of a request.

<br><br>

## Img Data URIs

It is possible to encode content into a URI string. You then use the string as if it were a URL, and then the browser simply interprets it as if it were a file. It’s weird and kinda neat:

    <img height="44" title="CodeIgniter Logo"
        alt="Visit CodeIgniter.com official website!"
        src="data:image/png;base64,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"></a>

Data URIs are not usually a great solution. Most meaningful images are going to create insanely long strings (just see the example above), and they actually don’t load as fast as external files. They do cut down on HTTP requests to the server, which you may (or may not) care about. They can also be useful in situations where external images might not get loaded, such as in emails or in self-contained documents to be read offline.

<br><br>

## Colors

<ins>Note:</ins> The Color column shows the color when previewed in Visual Studio Code. It does not show color on GitHub.com

Name                | Code          | Color
---                 | ---           | ---
AliceBlue           | #F0F8FF       | <span style="background-color:aliceblue; display:block; width: 100px">&nbsp;</span>
AntiqueWhite        | #FAEBD7       | <span style="background-color:antiquewhite; display:block; width: 100px">&nbsp;</span>
Aqua                | #00FFFF       | <span style="background-color:aqua; display:block; width: 100px">&nbsp;</span>
Aquamarine          | #7FFFD4       | <span style="background-color:aquamarine; display:block; width: 100px">&nbsp;</span>
Azure               | #F0FFFF       | <span style="background-color:azure; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Beige               | #F5F5DC       | <span style="background-color:beige; display:block; width: 100px">&nbsp;</span>
Bisque              | #FFE4C4       | <span style="background-color:bisque; display:block; width: 100px">&nbsp;</span>
Black               | #000000       | <span style="background-color:black; display:block; width: 100px">&nbsp;</span>
BlanchedAlmond      | #FFEBCD       | <span style="background-color:blanchedalmond; display:block; width: 100px">&nbsp;</span>
Blue                | #0000FF       | <span style="background-color:blue; display:block; width: 100px">&nbsp;</span>
BlueViolet          | #8A2BE2       | <span style="background-color:blueviolet; display:block; width: 100px">&nbsp;</span>
Brown               | #A52A2A       | <span style="background-color:brown; display:block; width: 100px">&nbsp;</span>
BurlyWood           | #DEB887       | <span style="background-color:burlywood; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
CadetBlue           | #5F9EA0       | <span style="background-color:cadetblue; display:block; width: 100px">&nbsp;</span>
Chartreuse          | #7FFF00       | <span style="background-color:chartreuse; display:block; width: 100px">&nbsp;</span>
Chocolate           | #D2691E       | <span style="background-color:chocolate; display:block; width: 100px">&nbsp;</span>
Coral               | #FF7F50       | <span style="background-color:coral; display:block; width: 100px">&nbsp;</span>
CornflowerBlue      | #6495ED       | <span style="background-color:cornflowerblue; display:block; width: 100px">&nbsp;</span>
Cornsilk            | #FFF8DC       | <span style="background-color:cornsilk; display:block; width: 100px">&nbsp;</span>
Crimson             | #DC143C       | <span style="background-color:crimson; display:block; width: 100px">&nbsp;</span>
Cyan                | #00FFFF       | <span style="background-color:cyan; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
DarkBlue            | #00008B       | <span style="background-color:darkblue; display:block; width: 100px">&nbsp;</span>
DarkCyan            | #008B8B       | <span style="background-color:darkcyan; display:block; width: 100px">&nbsp;</span>
DarkGoldenRod       | #B8860B       | <span style="background-color:darkgoldenrod; display:block; width: 100px">&nbsp;</span>
DarkGray            | #A9A9A9       | <span style="background-color:darkgray; display:block; width: 100px">&nbsp;</span>
DarkGrey            | #A9A9A9       | <span style="background-color:darkgrey; display:block; width: 100px">&nbsp;</span>
DarkGreen           | #006400       | <span style="background-color:darkgreen; display:block; width: 100px">&nbsp;</span>
DarkKhaki           | #BDB76B       | <span style="background-color:darkkhaki; display:block; width: 100px">&nbsp;</span>
DarkMagenta         | #8B008B       | <span style="background-color:darkmagenta; display:block; width: 100px">&nbsp;</span>
DarkOliveGreen      | #556B2F       | <span style="background-color:darkolivegreen; display:block; width: 100px">&nbsp;</span>
DarkOrange          | #FF8C00       | <span style="background-color:darkorange; display:block; width: 100px">&nbsp;</span>
DarkOrchid          | #9932CC       | <span style="background-color:darkorchid; display:block; width: 100px">&nbsp;</span>
DarkRed             | #8B0000       | <span style="background-color:darkred; display:block; width: 100px">&nbsp;</span>
DarkSalmon          | #E9967A       | <span style="background-color:darksalmon; display:block; width: 100px">&nbsp;</span>
DarkSeaGreen        | #8FBC8F       | <span style="background-color:darkseagreeen; display:block; width: 100px">&nbsp;</span>
DarkSlateBlue       | #483D8B       | <span style="background-color:darkslateblue; display:block; width: 100px">&nbsp;</span>
DarkSlateGray       | #2F4F4F       | <span style="background-color:darkslategray; display:block; width: 100px">&nbsp;</span>
DarkSlateGrey       | #2F4F4F       | <span style="background-color:darkslategrey; display:block; width: 100px">&nbsp;</span>
DarkTurquoise       | #00CED1       | <span style="background-color:darkturqoise; display:block; width: 100px">&nbsp;</span>
DarkViolet          | #9400D3       | <span style="background-color:darkviolet; display:block; width: 100px">&nbsp;</span>
DeepPink            | #FF1493       | <span style="background-color:deeppink; display:block; width: 100px">&nbsp;</span>
DeepSkyBlue         | #00BFFF       | <span style="background-color:deepskyblue; display:block; width: 100px">&nbsp;</span>
DimGray             | #696969       | <span style="background-color:dimgray; display:block; width: 100px">&nbsp;</span>
DimGrey             | #696969       | <span style="background-color:dimgrey; display:block; width: 100px">&nbsp;</span>
DodgerBlue          | #1E90FF       | <span style="background-color:dodgerblue; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
FireBrick           | #B22222       | <span style="background-color:firebrick; display:block; width: 100px">&nbsp;</span>
FloralWhite         | #FFFAF0       | <span style="background-color:floralwhite; display:block; width: 100px">&nbsp;</span>
ForestGreen         | #228B22       | <span style="background-color:forestgreen; display:block; width: 100px">&nbsp;</span>
Fuchsia             | #FF00FF       | <span style="background-color:fuchsia; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Gainsboro           | #DCDCDC       | <span style="background-color:gainsboro; display:block; width: 100px">&nbsp;</span>
GhostWhite          | #F8F8FF       | <span style="background-color:ghostwhite; display:block; width: 100px">&nbsp;</span>
Gold                | #FFD700       | <span style="background-color:gold; display:block; width: 100px">&nbsp;</span>
GoldenRod           | #DAA520       | <span style="background-color:goldenrod; display:block; width: 100px">&nbsp;</span>
Gray                | #808080       | <span style="background-color:gray; display:block; width: 100px">&nbsp;</span>
Grey                | #808080       | <span style="background-color:grey; display:block; width: 100px">&nbsp;</span>
Green               | #008000       | <span style="background-color:green; display:block; width: 100px">&nbsp;</span>
GreenYellow         | #ADFF2F       | <span style="background-color:greenyellow; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
HoneyDew            | #F0FFF0       | <span style="background-color:honeydew; display:block; width: 100px">&nbsp;</span>
HotPink             | #FF69B4       | <span style="background-color:hotpink; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
IndianRed           | #CD5C5C       | <span style="background-color:indianred; display:block; width: 100px">&nbsp;</span>
Indigo              | #4B0082       | <span style="background-color:indigo; display:block; width: 100px">&nbsp;</span>
Ivory               | #FFFFF0       | <span style="background-color:ivory; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Khaki               | #F0E68C       | <span style="background-color:khaki; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Lavender            | #E6E6FA       | <span style="background-color:lavender; display:block; width: 100px">&nbsp;</span>
LavenderBlush       | #FFF0F5       | <span style="background-color:lavenderblush; display:block; width: 100px">&nbsp;</span>
LawnGreen           | #7CFC00       | <span style="background-color:lawngreen; display:block; width: 100px">&nbsp;</span>
LemonChiffon        | #FFFACD       | <span style="background-color:lemonchiffon; display:block; width: 100px">&nbsp;</span>
LightBlue           | #ADD8E6       | <span style="background-color:lightblue; display:block; width: 100px">&nbsp;</span>
LightCoral          | #F08080       | <span style="background-color:lightcoral; display:block; width: 100px">&nbsp;</span>
LightCyan           | #E0FFFF       | <span style="background-color:lightcyan; display:block; width: 100px">&nbsp;</span>
LightGoldenRodYellow| #FAFAD2       | <span style="background-color:lightgoldenrodyellow; display:block; width: 100px">&nbsp;</span>
LightGray           | #D3D3D3       | <span style="background-color:lightgray; display:block; width: 100px">&nbsp;</span>
LightGrey           | #D3D3D3       | <span style="background-color:lightgrey; display:block; width: 100px">&nbsp;</span>
LightGreen          | #90EE90       | <span style="background-color:lightgreen; display:block; width: 100px">&nbsp;</span>
LightPink           | #FFB6C1       | <span style="background-color:lightpink; display:block; width: 100px">&nbsp;</span>
LightSalmon         | #FFA07A       | <span style="background-color:lightsalmon; display:block; width: 100px">&nbsp;</span>
LightSeaGreen       | #20B2AA       | <span style="background-color:lightseagreen; display:block; width: 100px">&nbsp;</span>
LightSkyBlue        | #87CEFA       | <span style="background-color:lightskyblue; display:block; width: 100px">&nbsp;</span>
LightSlateGray      | #778899       | <span style="background-color:lightslategray; display:block; width: 100px">&nbsp;</span>
LightSlateGrey      | #778899       | <span style="background-color:lightslategrey; display:block; width: 100px">&nbsp;</span>
LightSteelBlue      | #B0C4DE       | <span style="background-color:lightsteelblue; display:block; width: 100px">&nbsp;</span>
LightYellow         | #FFFFE0       | <span style="background-color:lightyellow; display:block; width: 100px">&nbsp;</span>
Lime                | #00FF00       | <span style="background-color:lime; display:block; width: 100px">&nbsp;</span>
LimeGreen           | #32CD32       | <span style="background-color:limegreen; display:block; width: 100px">&nbsp;</span>
Linen               | #FAF0E6       | <span style="background-color:linen; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Magenta             | #FF00FF       | <span style="background-color:magenta; display:block; width: 100px">&nbsp;</span>
Maroon              | #800000       | <span style="background-color:maroon; display:block; width: 100px">&nbsp;</span>
MediumAquaMarine    | #66CDAA       | <span style="background-color:mediumaquamarine; display:block; width: 100px">&nbsp;</span>
MediumBlue          | #0000CD       | <span style="background-color:mediumblue; display:block; width: 100px">&nbsp;</span>
MediumOrchid        | #BA55D3       | <span style="background-color:mediumorchid; display:block; width: 100px">&nbsp;</span>
MediumPurple        | #9370DB       | <span style="background-color:mediumpurple; display:block; width: 100px">&nbsp;</span>
MediumSeaGreen      | #3CB371       | <span style="background-color:mediumseagreen; display:block; width: 100px">&nbsp;</span>
MediumSlateBlue     | #7B68EE       | <span style="background-color:mediumslategreen; display:block; width: 100px">&nbsp;</span>
MediumSpringGreen   | #00FA9A       | <span style="background-color:mediumspringgreen; display:block; width: 100px">&nbsp;</span>
MediumTurquoise     | #48D1CC       | <span style="background-color:mediumturquoise; display:block; width: 100px">&nbsp;</span>
MediumVioletRed     | #C71585       | <span style="background-color:mediumvioletred; display:block; width: 100px">&nbsp;</span>
MidnightBlue        | #191970       | <span style="background-color:midnightblue; display:block; width: 100px">&nbsp;</span>
MintCream           | #F5FFFA       | <span style="background-color:mintcream; display:block; width: 100px">&nbsp;</span>
MistyRose           | #FFE4E1       | <span style="background-color:mistyrose; display:block; width: 100px">&nbsp;</span>
Moccasin            | #FFE4B5       | <span style="background-color:moccasin; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
NavajoWhite         | #FFDEAD       | <span style="background-color:navajowhite; display:block; width: 100px">&nbsp;</span>
Navy                | #000080       | <span style="background-color:navy; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
OldLace             | #FDF5E6       | <span style="background-color:oldlace; display:block; width: 100px">&nbsp;</span>
Olive               | #808000       | <span style="background-color:olive; display:block; width: 100px">&nbsp;</span>
OliveDrab           | #6B8E23       | <span style="background-color:olivedrab; display:block; width: 100px">&nbsp;</span>
Orange              | #FFA500       | <span style="background-color:orange; display:block; width: 100px">&nbsp;</span>
OrangeRed           | #FF4500       | <span style="background-color:orangered; display:block; width: 100px">&nbsp;</span>
Orchid              | #DA70D6       | <span style="background-color:orchid; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
PaleGoldenRod       | #EEE8AA       | <span style="background-color:palegoldenrod; display:block; width: 100px">&nbsp;</span>
PaleGreen           | #98FB98       | <span style="background-color:palegreen; display:block; width: 100px">&nbsp;</span>
PaleTurquoise       | #AFEEEE       | <span style="background-color:paleturquoise; display:block; width: 100px">&nbsp;</span>
PaleVioletRed       | #DB7093       | <span style="background-color:palevioletred; display:block; width: 100px">&nbsp;</span>
PapayaWhip          | #FFEFD5       | <span style="background-color:papayawhip; display:block; width: 100px">&nbsp;</span>
PeachPuff           | #FFDAB9       | <span style="background-color:peachpuff; display:block; width: 100px">&nbsp;</span>
Peru                | #CD853F       | <span style="background-color:peru; display:block; width: 100px">&nbsp;</span>
Pink                | #FFC0CB       | <span style="background-color:pink; display:block; width: 100px">&nbsp;</span>
Plum                | #DDA0DD       | <span style="background-color:plum; display:block; width: 100px">&nbsp;</span>
PowderBlue          | #B0E0E6       | <span style="background-color:powderblue; display:block; width: 100px">&nbsp;</span>
Purple              | #800080       | <span style="background-color:purple; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
RebeccaPurple       | #663399       | <span style="background-color:rebeccapurple; display:block; width: 100px">&nbsp;</span>
Red                 | #FF0000       | <span style="background-color:red; display:block; width: 100px">&nbsp;</span>
RosyBrown           | #BC8F8F       | <span style="background-color:rosybrown; display:block; width: 100px">&nbsp;</span>
RoyalBlue           | #4169E1       | <span style="background-color:royalblue; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
SaddleBrown         | #8B4513       | <span style="background-color:saddlebrown; display:block; width: 100px">&nbsp;</span>
Salmon              | #FA8072       | <span style="background-color:salmon; display:block; width: 100px">&nbsp;</span>
SandyBrown          | #F4A460       | <span style="background-color:sandybrown; display:block; width: 100px">&nbsp;</span>
SeaGreen            | #2E8B57       | <span style="background-color:seagreen; display:block; width: 100px">&nbsp;</span>
SeaShell            | #FFF5EE       | <span style="background-color:seashell; display:block; width: 100px">&nbsp;</span>
Sienna              | #A0522D       | <span style="background-color:sienna; display:block; width: 100px">&nbsp;</span>
Silver              | #C0C0C0       | <span style="background-color:silver; display:block; width: 100px">&nbsp;</span>
SkyBlue             | #87CEEB       | <span style="background-color:skyblue; display:block; width: 100px">&nbsp;</span>
SlateBlue           | #6A5ACD       | <span style="background-color:slateblue; display:block; width: 100px">&nbsp;</span>
SlateGray           | #708090       | <span style="background-color:slategray; display:block; width: 100px">&nbsp;</span>
SlateGrey           | #708090       | <span style="background-color:slategrey; display:block; width: 100px">&nbsp;</span>
Snow                | #FFFAFA       | <span style="background-color:snow; display:block; width: 100px">&nbsp;</span>
SpringGreen         | #00FF7F       | <span style="background-color:springgreen; display:block; width: 100px">&nbsp;</span>
SteelBlue           | #4682B4       | <span style="background-color:steelblue; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Tan                 | #D2B48C       | <span style="background-color:tan; display:block; width: 100px">&nbsp;</span>
Teal                | #008080       | <span style="background-color:teal; display:block; width: 100px">&nbsp;</span>
Thistle             | #D8BFD8       | <span style="background-color:thistle; display:block; width: 100px">&nbsp;</span>
Tomato              | #FF6347       | <span style="background-color:tomato; display:block; width: 100px">&nbsp;</span>
Turquoise           | #40E0D0       | <span style="background-color:turquoise; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Violet              | #EE82EE       | <span style="background-color:violet; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Wheat               | #F5DEB3       | <span style="background-color:wheat; display:block; width: 100px">&nbsp;</span>
White               | #FFFFFF       | <span style="background-color:white; display:block; width: 100px">&nbsp;</span>
WhiteSmoke          | #F5F5F5       | <span style="background-color:whitesmoke; display:block; width: 100px">&nbsp;</span>
&nbsp;              | &nbsp;        | &nbsp;
Yellow              | #FFFF00       | <span style="background-color:yellow; display:block; width: 100px">&nbsp;</span>
YellowGreen         | #9ACD32       | <span style="background-color:yellowgreen; display:block; width: 100px">&nbsp;</span>


# References

* https://html.com/attributes/img-src/
