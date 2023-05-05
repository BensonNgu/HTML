# HTML INTRODUCTION
[<kbd>WHAT IS HTML</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#what-is-html)
[<kbd>TAGS</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#tags)
[<kbd>CHARACTER ENTITIY</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#character-entity)
[<kbd>BLOCKQUOTE</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#blockquote)
[<kbd>FORMATTING TEXT</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#formatting-text)
[<kbd>PREFORMATTED TEXT</kbd>](Html-intro#preformatted)
## WHAT IS HTML?
- **H**yper **T**ext **M**arkuo **L**anguage
- Markup language for describing web documents
- described by html tags
- Each tag described different document content

```
<html>
    <head>
        <title>JT</title>
    </head>
    <body>
        Hello World!
    </body>
</html>
```
![example 1](https://github.com/BensonNgu/HTML-notes/blob/main/Html-intro/src/Screenshot_20230427_014814.png)

***A html document***
- start with: \<html> tag
- follow by : \<head> tag   
- follow by : \<body> tag  (visible part in the browser)  
[<kbd>Back to top</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)
## Tags
- most of the tag goes in pair, a start tag and an end tag  
```
<tagname> content </tagname>
```
| **Tags** | **Example** |
|---------|--------|
| Heading | ```<h1> <h2> <h3> <h4> <h5> <h6>``` |
| Paragraph | ```<p>``` |
| Line break | ```<br/> or <bt />``` |
| Horizontal line(divider) | ```<hr/>``` |

[<kbd>Back to top</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)

## Character entity
- Enable the browser to print some character that has been **reserved** by html

| **Character entity** | **Example** |
|---|---|
| Non-breaking space | ```&nbsp``` |
| < | ```&lt``` |
| > |```&gt```|
| & |```&amp```|
| " |```&quot```|
| ' |```&apos```|
| &deg; |```&deg```|
| &copy; |```&copy```|

[<kbd>Back to top</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)
## Blockquote
```
<body>
    <p>This is a normal paragraph</p>
    <blockquote>
        <p>This is a paragraph in a block quote</p>
    </blockquote>
</body>
```
![blockquote](https://github.com/BensonNgu/HTML-notes/blob/main/Html-intro/src/Screenshot_20230427_021435.png)

[<kbd>Back to top</kbd>](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)

## Formatting text
```
<body>
    <i>italic text</i> <br />
    <b>italic text</b> <br />
    <mark>italic text</mark> <br />
    <del>italic text</del> <br />
    <ins>italic text<ins> <br />
</body>
```
![text formatting](https://github.com/BensonNgu/HTML-notes/blob/main/Html-intro/src/Screenshot%202023-05-06%20001053.png)
---
```
<body>
    <h2>HTML <small>small</small> formatting</h2>
    <p>Lorem ipsum dolor sit, <small>amet consectetur adipisicing elit</small>. Iure corrupti.</p>
</body>
```
![small tag](https://github.com/BensonNgu/HTML-notes/blob/main/Html-intro/src/small-formatting.png)
---
```
<body>
    <h2>Math</h2>
    <h3><ins>Exponential</ins></h3>
    x<sup>2</sup> <br />
    <h3><ins>Equation</ins></h3>
    x<sub>1</sub><sup>n</sup> + x<sub>2</sub><sup>n</sup> 
</body>
```
![math](https://github.com/BensonNgu/HTML-notes/blob/main/Html-intro/src/math.png)

[<kbd>Back to top</kbd>](Html-intro#html-introduction)

## Preformatted text
- <span style="color:#ccb67b">pre</span> element show in [<kbd>monospace</kbd>](https://fonts.google.com/knowledge/glossary/monospaced)
- it preserved the character and the line spacing

```
<body>
   <pre>
       test
                on
 pre
    tag
   </pre>
   <br />
   <p>
       test
                on
 p
    tag
   </p>
</body>
```
><body>
![pre-tag](src/pre-tag.png)

[<kbd>Back to top</kbd>](Html-intro#html-introduction)