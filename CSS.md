# CSS Reference
## by Shubhrendu Tripathi

<br><br>

## Background

Term                            |   Term 1
---                             |   ---
background                      |   <em>background-image</em>
&nbsp;                          |   <em>background-position</em>
&nbsp;                          |   <em>background-size</em>
&nbsp;                          |   <em>background-repeat</em>
&nbsp;                          |   <em>background-attachment</em>
&nbsp;                          |   <em>background-origin</em>
&nbsp;                          |   <em>background-clip</em>
&nbsp;                          |   <em>background-color</em>
&nbsp;                          |   &nbsp;
background-attachment           |   scroll \|\| fixed
&nbsp;                          |   &nbsp;
background-break                |   bounding-box \| each-box \| continuous
background-clip                 |   length
&nbsp;                          |   %
&nbsp;                          |   border-box \| padding-box \| content-box \| no-clip
&nbsp;                          |   &nbsp;
background-color                |   <em>color</em>
&nbsp;                          |   transparent
background-image                |   <em>url</em>
&nbsp;                          |   none
background-origin               |   border-box \| padding-box \| content-box
&nbsp;                          |   &nbsp;
background-position             |   top left \| top center \| top right \| center left \| center center \| center right \| bottom left \| bottom center \| bottom right
&nbsp;                          |   <em>x-% y-%</em>
&nbsp;                          |   <em>x-pos y-pos</em>
&nbsp;                          |   &nbsp;
background-repeat               |   repeat \| repeat-x \| repeat-y \| no-repeat
&nbsp;                          |   &nbsp;
background-size                 |   <em>length</em>
&nbsp;                          |   <em>%</em>
&nbsp;                          |   auto \| cover \| contain

## Table

Term                            |   Term 1
---                             |   ---
border-collapse                 |   collapse \| separate
border-spacing                  |   <em>length length</em>
caption-side                    |   top \| bottom \| left \| right
empty-cells                     |   show \| hide
table-layout                    |   table-layout-auto \| fixed

## Border

Term                            |   Term 1
---                             |   ---
border                          |   <em>border-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-break                    |   <em>border-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>color</em>
&nbsp;                          |   close
border-bottom                   |   <em>border-bottom-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-bottom-color             |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-bottom-style             |   <em>border-style</em>
&nbsp;                          |   &nbsp;
border-bottom-width             |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-collapse                 |   collapse \| separate
&nbsp;                          |   &nbsp;
border-image                    |   <em>image</em>
&nbsp;                          |   [ <em>number / % border-width </em> stretch \| repeat \| round ]
&nbsp;                          |   none
border-left                     |   <em>border-left-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
border-left-color               |   <em>border-color</em>
&nbsp;                          |   &nbsp;
border-left-style               |   <em>border-style</em>
&nbsp;                          |   &nbsp;
border-left-width               |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-right                    |   <em>border-right-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
border-right-color              |   <em>border-right-color</em>
&nbsp;                          |   &nbsp;
border-right-style              |   border-style
&nbsp;                          |   &nbsp;
border-right-width              |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
&nbsp;                          |   &nbsp;
border-top                      |   <em>border-top-width</em>
&nbsp;                          |   <em>border-style</em>
&nbsp;                          |   <em>border-color</em>
border-top-color                |   <em>border-color<em>
&nbsp;                          |   &nbsp;
border-top-style                |   <em>border-style</em>
&nbsp;                          |   &nbsp;
border-top-width                |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-width                    |   thin \| medium \| thick
&nbsp;                          |   <em>length</em>
border-radius                   |   <em>border-top-right-radius</em>
&nbsp;                          |   <em>border-bottom-right-radius</em>
&nbsp;                          |   <em>border-bottom-left-radius</em>
&nbsp;                          |   <em>border-top-left-radius</em>
border-top-right-radius         |   <em>length</em>
&nbsp;                          |   &nbsp;
border-bottom-right-radius      |   <em>length</em>
&nbsp;                          |   &nbsp;
border-bottom-left-radius       |   <em>length</em>
&nbsp;                          |   &nbsp;
border-top-left-radius          |   <em>length</em>
&nbsp;                          |   &nbsp;
box-shadow                      |   inset \|\| [ <em>length</em>, <em>length</em>, <em>length</em>, <em>length</em> || `<color>` ]
&nbsp;                          |   none
border-style                    |   none \| hidden \| dotted \| dashed \| solid \| double \| groove \| ridge \| inset \| outset

## Transitions

Term                            |   Term 1
---                             |   ---
transition                      |   transition-property
&nbsp;                          |   transition-duration
&nbsp;                          |   transition-timing-function
&nbsp;                          |   transition-delay
&nbsp;                          |   &nbsp;
transition-delay                |   time
&nbsp;                          |   &nbsp;
transition-duration             |   time
&nbsp;                          |   &nbsp;
transition-property             |   none | all
&nbsp;                          |   &nbsp;
transition-timing-function      |   ease \| linear \| ease-in \| ease-out \| ease-in-out \| cubic-Bezier (number, number, number, number)
&nbsp;                          |   &nbsp;

## Box Model

|Term                               |   Term 1 |
|---                                |   ---    |
clear                               |   left \| right \| both \| none
display                             |   none \| inline \| block \| inlineblock \| list-item \| run-in \| compact \| table \| inlinetable \| \|table-row-group \| table-header-group \| tablefooter-group \| table-row \| table-column-group \| tablefooter-group \| table-row \| table-column-group \| tablecolumn \| table-cell \| tablecaption \| ruby \| ruby-base \| ruby-text \| ruby-base-group \| ruby-text-group
float                               |   left \| right \| none
height                              |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
max-height                          |   none
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
max-width                           |   none
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
min-height                          |   none \| inherit
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
min-width                           |   none
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
width                               |   auto
&nbsp;                              |   <em>%</em>
&nbsp;                              |   <em>length</em>
margin                              |   <em>margin margin-top</em>
&nbsp;                              |   <em>margin-right</em>
&nbsp;                              |   <em>margin-bottom</em>
&nbsp;                              |   <em>margin-left</em>
margin-bottom                       |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
margin-left                         |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
margin-right                        |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
margin-top                          |   auto
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding                             |   <em>padding padding-top</em>
&nbsp;                              |   <em>padding-right</em>
&nbsp;                              |   <em>padding-bottom</em>
&nbsp;                              |   <em>padding-left</em>
padding-bottom                      |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding-left                        |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding-right                       |   <em>length</em>
&nbsp;                              |   <em>%</em>
padding-top                         |   <em>length</em>
&nbsp;                              |   <em>%</em>
marquee-direction                   |   forward \| reverse
marquee-loop                        |   infinite
&nbsp;                              |   <em>number</em>
marquee-play-count                  |   infinite
&nbsp;                              |   <em>integer</em>
marquee-speed                       |   slow \| normal \| fast
marquee-style                       |   scroll \| slide \| alternate
overflow                            |   visible \| hidden \| scroll \| auto \| no-display \| nocontent
&nbsp;                              |   <em>overflow-x</em>
&nbsp;                              |   <em>overflow-y</em>
overflow-style                      |   auto \| marquee-line \| marqueeblock
overflow-x                          |   visible \| hidden \| scroll \| auto \| no-display \| nocontent
overflow-y                          |   visible \| hidden \| scroll \| auto \| no-display \| nocontent
rotation                            |   <em>angle</em>
rotation-point                      |   <em>position (paired value offset)</em>
visibility                          |   visibility visible \| hidden \| collapse

## Font

|Term                               |   Term 1 |
|---                                |   ---    |
font                                |   font-style
&nbsp;                              |   font-variant
&nbsp;                              |   font-weight
&nbsp;                              |   font-size/line-height
&nbsp;                              |   font-family
&nbsp;                              |   caption \| icon \| menu \| message-box \| smallcaption \| status-bar
font-family                         |   <em>family-name</em>
&nbsp;                              |   <em>generic-family</em>
&nbsp;                              |   inherit
font-size                           |   xx-small \| x-small \| small \| medium \| large \| x-large \| xx-large \| smaller \| larger \| inherit
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
font-size-adjust                    |   none \| inherit
&nbsp;                              |   <em>number</em>
font-stretch                        |   normal \| wider \| narrower \| ultra-condensed \| extracondensed \| condensed \| semi-condensed \| semiexpanded \| expanded \| extra-expanded \| ultraexpanded \| inherit
font-style                          |   normal \| italic \| oblique \| inherit
font-variant                        |   normal \| small-caps \| inherit
font-weight                         |   normal \| bold \| bolder \| lighter \| 100 \| 200 \| 300 \| 400 \| 500 \| 600 \| 700 \| 800 \| 900 \| inherit

## Color
|Term                               |   Term 1 |
|---                                |   ---    |
color                               |   inherit
&nbsp;                              |   <em>color</em>
opacity                             |   inherit
&nbsp;                              |   <em>number</em>

## Text
|Term                               |   Term 1 |
|---                                |   ---    |
direction                           |   ltr \| rtl \| inherit
hanging-punctuation                 |   none \| [ start \| end \| endedge ]
letter-spacing                      |   normal
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
punctuation-trim                    |   none \| [start \| end \| adjacent]
text-align                          |   start \| end \| left \| right \| center \| justify
text-align-last                     |   start \| end \| left \| right \| center \| justify
text-decoration                     |   none \| underline \| overline \| line-through \| blink
text-emphasis                       |   none \| [ [ accent \| dot \| circle \| disc] [ before \| after ]? ]
text-indent                         |   <em>length</em>
&nbsp;                              |   <em>%</em>
text-justify                        |   auto | inter-word | interideograph | inter-cluster | distribute | kashida | tibetan
text-outline                        |   none
&nbsp;                              |   <em>color</em>
&nbsp;                              |   <em>length</em>
text-shadow                         |   none
&nbsp;                              |   <em>color</em>
&nbsp;                              |   <em>length</em>
text-transform                      |   none \| capitalize \| uppercase \| lowercase
text-wrap                           |   normal \| unrestricted \| none \| suppress
unicode-bidi                        |   normal \| embed \| bidioverride
white-space                         |   normal \| pre \| nowrap \| prewrap \| pre-line
white-space-collapse                |   preserve \| collapse \| preservebreaks \| discard
word-break                          |   normal \| keep-all \| loose \| break-strict \| break-all
word-spacing                        |   normal
&nbsp;                              |   <em>length</em>
&nbsp;                              |   <em>%</em>
word-wrap                           |   normal \| break-word

## Column
|Term                               |   Term 1 |
|---                                |   ---    |
column-count                        |   auto
&nbsp;                              |   <em>number</em>
column-fill                         |   auto \| balance
column-gap                          |   normal
&nbsp;                              |   <em>length</em>
column-rule                         |   <em>column-rule-width</em>
&nbsp;                              |   <em>column-rule-style</em>
&nbsp;                              |   <em>column-rule-color</em>
column-rule-color                   |   <em>color</em>
column-rule-style                   |   <em>border-style</em>
column-rule-width                   |   thin \| medium \| thick
&nbsp;                              |   <em>length</em>
columns                             |   <em>column-width</em>
&nbsp;                              |   <em>column-count</em>
column-span                         |   1 \| all
column-width                        |   auto
&nbsp;                              |   <em>length</em>


## Animations
|Term                               |   Term 1 |
|---                                |   ---    |
animation                           |   animation-name
&nbsp;                              |   animation-duration
&nbsp;                              |   animation-timing-function
&nbsp;                              |   animation-delay
&nbsp;                              |   animation-iteration-count
&nbsp;                              |   animation-direction
animation-delay                     |   time
animation-direction                 |   normal \| alternate
animation-duration                  |   time
animation-iteration-count           |   inherit
&nbsp;                              |   number
animation-name                      |   none \| IDENT
animation-play-state                |   running \| paused
animation-timing-function           |   ease \| linear \| ease-in \| ease-out \| ease-in-out \| cubic-Bezier (number, number, number, number)

## Speech
|Term                               |   Term 1 |
|---                                |   ---    |
cue                                 |   <em>cue-before</em>
&nbsp;                              |   <em>cue-after</em>
cue-before                          |   uri [ silent \| x-soft \| soft \| medium \| loud \| x-loud] \| none \| inherit ]
&nbsp;                              |   <em>number</em>
&nbsp;                              |   <em>%</em>
cue-after                           |   uri [ silent | x-soft | soft | medium | loud | x-loud] | none | inherit ]
&nbsp;                              |   <em>number</em>
&nbsp;                              |   <em>%</em>
mark                                |   <em>mark-before</em>
&nbsp;                              |   <em>mark-after</em>
mark-before                         |   <em>string</em>
mark-after                          |   <em>string</em>
pause                               |   <em>pause-before</em>
&nbsp;                              |   <em>pause-after</em>
pause-before                        |   none | x-weak | weak | medium | strong | x-strong | inherit
&nbsp;                              |   <em>time</em> 
pause-after                         |   none | x-weak | weak | medium | strong | x-strong | inherit
&nbsp;                              |   time
phonemes                            |   <em>string</em>
rest                                |   rest-before
&nbsp;                              |   rest-after
rest-before                         |   none | x-weak | weak | medium | strong | x-strong | inherit
&nbsp;                              |   time
rest-after                          |   none | x-weak | weak | medium | strong | x-strong | inherit
&nbsp;                              |   time
speak                               |   none | normal | spell-out | digits | literal-punctuation | no-punctuation | inherit
voice-balance                       |   left | center | right | leftwards | rightwards | inherit
&nbsp;                              |   <em>number</em>
voice-duration                      |   <em>time</em>
voice-family                        |   inherit | [ <specific-voice, age, generic-voice, number> ]
voice-rate                          |   x-slow | slow | medium | fast | x-fast | inherit
&nbsp;                              |   %
voice-pitch                         |   x-low | low | medium | high | x-high | inherit
&nbsp;                              |   <em>number</em>
&nbsp;                              |   <em>%</em>
voice-pitch-range                   |   x-low | low | medium | high | x-high | inherit
&nbsp;                              |   <em>number</em>
voice-stress                        |   strong | moderate | none | reduced | inherit
voice-volume                        |   silent | x-soft | soft | medium | loud | x-loud | inherit
&nbsp;                              |   <em>number</em>
&nbsp;                              |   <em>%</em>

## Template Layout
|Term                               |   Term 1 |
|---                                |   ---    |
box-align                           |   start \| end \| center \| base
box-direction                       |   start \| end \| center \| base
box-flex                            |   <em>number</em>
box-flex-group                      |   <em>integer</em>
box-lines                           |   single \| multiple                    
box-orient                          |   horizontal \| vertical \| inlineaxis \| block-axis
box-pack                            |   start \| end \| center \| justify
box-sizing                          |   content-box \| padding-box \| border-box \| margin-box
tab-side                            |   top \| bottom \| left \| right

## List & Markers
|Term                               |   Term 1 |
|---                                |   ---    |
list-style                          |   <em>list-style-type</em>
&nbsp;                              |   <em>list-style-position</em>
&nbsp;                              |   <em>list-style-image</em>
list-style-image                    |   none
&nbsp;                              |   <em>url</em>
list-style-position                 |   Inside \| outside
list-style-type                     |   none \| asterisks \| box \| check \| circle \| diamond \| disc \| hyphen \| square \| decimal \| decimal-leadingzero \| lower-roman \| upperroman \| lower-alpha \| upperalpha \| lower-greek \| lower-latin \| upper-latin \| hebrew \| armenian \| georgian \| cjk-ideographic \| hiragana \| katakana \| hiraganairoha \| katakana-iroha \| footnotes
marker-offset                       |   auto
&nbsp;                              |   <em>length</em>

## Grid Positioning
|Term                               |   Term 1 |
|---                                |   ---    |
grid-columns                        |   none \| inherit
&nbsp;                              |   <em>[ length percentage relative length ]</em>
grid-rows                           |   none \| inherit
&nbsp;                              |   <em>[ length percentage relative length ]</em>

## Outline
|Term                               |   Term 1 |
|---                                |   ---    |
outline | <i>outline-color</i>
&nbsp; | <i>outline-style</i>
&nbsp; | <i>outline-width</i>
&nbsp; | &nbsp;
outline-color | <i>color</i>
&nbsp; | invert
&nbsp; | &nbsp;
outline-offset | inherit
&nbsp; | length
&nbsp; | &nbsp;
outline-style | None \| dotted \| dashed \| solid \| double \| groove \| ridge \| inset \| outset
&nbsp; | &nbsp;
outline-width | thin \| medium \| thick \| length

## 3D / 2D Transform
|Term                               |   Term 1 |
|---                                |   ---    |
backface-visibility | visible \| hidden
&nbsp; | &nbsp;
perspective | none
&nbsp; | number
&nbsp; | &nbsp;
perspective-origin | [ [ [ percentage> \| <length> \|
left \| center \| right ] [
<percentage> \| <length> \| top
\| center \| bottom ]? ] <length> ]
\| [ [ [ left \| center \| right ] ||
[ top \| center \| bottom ] ]
<length> ]
&nbsp; | &nbsp;
transform | none \| matrix \| matrix3d \|
translate3d \| translateX \|
translateY \| translateZ \|
scale \| scale3d \| scaleX \\|
scaleY \| scaleZ \| rotate \|
rotate3d \| rotateX \| rotateY
\| rotateZ \| skewX \| skewY \|
skew \| perspective
&nbsp; | &nbsp;
transform-origin | [ [ [ <percentage> \|
<length> \| left \| center \|
right ] [ <percentage> \|
<length> \| top \| center \|
bottom ]? ] <length> ] \|
[ [ [ left \| center \| right ] ||
[ top \| center \| bottom ] ]
<length> ]
&nbsp; | &nbsp;
transform-style | flat \| preserve-3d
&nbsp; | &nbsp;

## Hyperlink
|Term                               |   Term 1 |
|---                                |   ---    |
target | <i>target-name</i>
&nbsp; | <i>target-new</i>
&nbsp; | <i>target-position</i>
&nbsp; | &nbsp;
target-name | current \| root \| parent \| new \| modal
&nbsp; | <i>string</i>
&nbsp; | &nbsp;
target-new | window \| tab \| none
&nbsp; | &nbsp;
target-position | above \| behind \| front \| back
&nbsp; | &nbsp;

## Generated Content
|Term                               |   Term 1 |
|---                                |   ---    |
bookmark-label | content
&nbsp; | <em>attr</em>
&nbsp; | <em>string</em>
&nbsp; | &nbsp;
bookmark-level | none
&nbsp; | <em>integer</em>
&nbsp; | &nbsp;
bookmark-target | self
&nbsp; | <em>uri</em>
&nbsp; | <em>attr</em>
&nbsp; | &nbsp;
border-length | auto
&nbsp; | <em>length</em>
&nbsp; | &nbsp;
content | normal \| none \| inhibit
&nbsp; | uri
&nbsp; | &nbsp;
counter-increment | none
&nbsp; | <em>identifier number</em>
&nbsp; | &nbsp;
counter-reset | none
&nbsp; | <em>identifier number</em>
&nbsp; | &nbsp;
crop | auto
&nbsp; | <em>shape</em>
&nbsp; | &nbsp;
display | normal \| none \| list-item
&nbsp; | &nbsp;
float-offset | <em>length length</em>
&nbsp; | &nbsp;
hyphenate-after | auto
&nbsp; | <em>integer</em>
&nbsp; | &nbsp;
hyphenate-before | auto
&nbsp; | <em>integer</em>
&nbsp; | &nbsp;
hyphenate-character | auto
&nbsp; | <em>integer</em>
&nbsp; | &nbsp;
hyphenate-lines | no-limit
&nbsp; | <em>integer</em>
&nbsp; | &nbsp;
hyphenate-resource | none
&nbsp; | <em>uri</em>
&nbsp; | &nbsp;
hyphens | none \| manual \| auto
&nbsp; | &nbsp;
image-resolution | normal \| auto
&nbsp; | dpi
&nbsp; | &nbsp;
marks | [ crop \|\| cross ] \| none
&nbsp; | &nbsp;
move-to | normal \| here
&nbsp; | identifier
&nbsp; | &nbsp;
page-policy | start \| first \| last
&nbsp; | &nbsp;
quotes | none
&nbsp; | <em>string string string string</em>
&nbsp; | &nbsp;
string-set | <em>identifier</em>
&nbsp; | <em>content-list</em>
&nbsp; | &nbsp;
text-replace | none
&nbsp; | <em>[<string> <string>]+</em>
&nbsp; | &nbsp;

## Positioning
|Term                               |   Term 1 |
|---                                |   ---    |
bottom
clip
left
position
right
top
z-index
auto
%
length
shape
auto
auto
%
length
static | relative | absolute | fixed
auto
%
length
auto
%
length
auto
number
