# HTML INTRODUCTION
- [WHAT IS HTML](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#what-is-html)
- [TAGS](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#tags)
- [CHARACTER ENTITIY](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#character-entity)
- [BLOCKQUOTE](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#blockquote)
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
[Back to top](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)
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

[Back to top](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)

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

[Back to top](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)

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

[Back to top](https://github.com/BensonNgu/HTML-notes/tree/main/Html-intro#html-introduction)