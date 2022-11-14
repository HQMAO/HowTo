To preview a markdown file, like xxx.md, in VScode:

hold command + k,then v;
or press the Preview button in the top-right of the toolbar.


## Sections
- [Headers](#headers)
<!-- [displayed name](#header-name)-->
- [Quotes](#quotes)
- [Emphasis](#emphasis)
- [Horizontal Rule](#horizontal-rule)
- [Links](#links)
- [Lists](#lists)
- [Images](#images)
- [Code](#code)
- [Tables](#tables)
- [Equations](#equations)
- [Custom HTML](#custom-html)
- [Custom CSS](#custom-css)
- [Additional Resource](#additional-resource)

---
## Headers

>**TODO**. Create a H1
# Header1
>**TODO**. Create a H2
## Header2

---
## Quotes

>**TODO**. Create a quote

> This is my quote

>**TODO**. Create a H4 quote

> #### Header4

---
## emphasis
**Bold Sentence** (enclosed with ** or __ on each side)

__Bold with italics__

*Italics sentence*

_Italics sentence_


--- 
## Horizontal Rule
three '-' divide sections.

---
## Lists
Create unordered lists '-','*','+',

- Item
- Plus item
+ One more item
* Last item

Sublist by indenting
- list
  - sublist
     - subsublist

create ordered lists using a number prefix
1. ItemA
1. ItemB
1. ItemC

---
## Links
Create a link with text in [] and link in ()

[github website](http://www.github.com)

[key]: http://www.github.com
<!-- key is a variable defined by the string.-->
[my web][key]

[section link](#links)
<!-- #links is a link to header Links, lower-case replacing ' ' with '-' -->

---
## Images
[img-vscode]: https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/150px-Visual_Studio_Code_1.35_icon.svg.png

![vscode][img-vscode]

---
## Code
Here is code inline `var item ={};`
```javascript
    var item1 ={};
    var item2 ={};
```

```fortran
    int a
    real b=2.
    a = 2*b
```
## Tables

| HEADER 1 | header 2 | Header 3 |
| -------- | :-------- | --------: | 
| colume 1 | colume 2 | colume 3 |
| colume 1 | colume 2 | colume 3 |
| colume 1 | colume 2 | colume 3 |


--
## Equations
   $$ E = m c^2 $$

---
## Custom HTML
```html
<p>Sample HTML Div</p>
```
<p>Sample HTML Div</p>

---
## Custom CSS
```css
<style>
body{
    color:blue;

}</style>
```
<style>
body{
    color:green;

}</style>

---
## Additional resources
[Adam P on Github](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

