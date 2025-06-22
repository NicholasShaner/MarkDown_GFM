<h1><code style="color: red">GitHub Flavored Markdown Reference Material</code></h1>

<br>

---


<!--Headings -->


<h2 style="color: blue">Headings</h2>

_\*Work like header tags in HTML (h1, h2, h3, etc)_

- # Header 1 (\# \<text>)
- ## Header 2 (\#\# \<text>)
- ### Header 3 (\#\#\# \<text>)
- #### Header 4 (\#\#\#\#\# \<text>)
- ##### Header 5 (\#\#\#\#\#\# \<text>)
- ###### Header 6 (\#\#\#\#\#\#\# \<text>)

---
<br>



<!--Horizonal Rules/Page Breaks -->


<h2 style="color: blue">Horizonal Rule/ Page Break</h2>

(\-\-\-) \*when used directly under line of text, creates horizontal rule and transitions above text to h2 heading
---
(\-\-\-) \*when double spaced below text line, creates horizontal rule without any text transformation

---

(\=\=\=) \*when used directly under line of text, creates horizontal rule and transitions above text to h1 heading
===

<br>



<!--Italics -->


<h2 style="color: blue">Italics</h2>

_Italics_ (\*\<Text\>\* or \_\<Text\>\_)

\*single asteric or underline

<br>



<!--Bold -->


<h2 style="color: blue">Bold</h2>

**BOLD** \-\> NOT BOLD (\*\*\<Text\>\*\* or \_\_\<Text\>\_\_) 

\*double asteric or double underline

<br>



<!--Strike Through -->


<h2 style="color: blue">Strike Through</h2>

~~Strike Through Text~~ (\~\~\<Text\>\~\~) 

\*double tilde before and after text, very useful for making inline edits to preserve corrected text for reference

<br>



<!--Underline -->


<h2 style="color: blue">Underline</h2>

### \*\* _There is no direct method in markdown to underline text as it is typically saved for links_ \*\*

<br>



<!--Block Quote -->


<h2 style="color: blue">Block Quote</h2>

Using the '\>' character at the head of a line of text creates indented block of text
> This is block quotes  
> The window size will determine the width of lines and vertical sizing. To force newline, add two spaces at end of line

<br>



<!--Code Block -->


<h2 style="color: blue">Code Block</h2>

To create an inset box of directly iterate code/text:  
\- add triple tilde (\`\`\`), add code/text, then newline and add three closing tilde

_\*someones need to double space after opening tildes depending on redering_

```
This is a code block, it will take any text verbatim without the need for escape characters
```
\* _can declare code language after opening tilde and get color coded scripts_  
```python

def add(x, y):
    return x + y

```

<br>



<!--Inline Code -->


<h2 style="color: blue">Inline Code</h2>

Using single tilde before and after text allows you to add verbatim code/text within a line of text like **` '(**) creates bold' `**  
\` \<Text\> \`

<br>



<!--External Link -->


<h2 style="color: blue">External Link</h2>

_Used to create hyperlink to external URL_

` [<Text>]( https:// URL) `  
Example link to google: &nbsp;&nbsp;&nbsp;&nbsp; [Google](https://www.google.com)

_Can reuse link by creating link reference at bottom of page:_  
` [Google]: (https://www.google.com) ` &nbsp;&nbsp;\*allows for only needing ` [Google] ` call within text

<br>



<!--Internal Link -->


<h2 style="color: blue">Internal Link</h2>

_Used to link to internal content_  
\* mostly used within table of content
<br>
_\* all headers in Markdown inherintly rendered with HTML ID of Header name, hashtag, all lowercase and dash for spaces (ie. #internal-link)_

Here is a link back to [Headings](#headings)

<br>



<!--Image -->


<h2 style="color: blue">Images</h2>

` !['alternative text'](image_link) `  
<br>
ie.  

![Super Mario](https://purepng.com/public/uploads/large/purepng.com-mariomariofictional-charactervideo-gamefranchisenintendodesigner-1701528634653vywuz.png)

` ![Super Mario](mario.jpg) `

<br>



<!--Image With Link -->


<h2 style="color: blue">Images With Links</h2>

_Combination of Link and Image syntax_  
` [!['Alternative Text'](image_link)]( https:// URL ) `
<br>
ie.  

[![Super Mario](https://purepng.com/public/uploads/large/purepng.com-mariomariofictional-charactervideo-gamefranchisenintendodesigner-1701528634653vywuz.png)](https://www.google.com)

`[![Super Mario link to Google](mario.jpg)](https://www.google.com) `  

<br>



<!--List -->


<h2 style="color: blue">List</h2>

<h3 style="color: orange">Unordered List (Bullet Points)</h3>

_To create list use hyphen, space, then text_  
Can be nested by spacing down and tab over.
- Point 1
    - Point 1.1
        - Point 1.1.1
    - Point 1.2
- Point 2

<h3 style="color: orange">Ordered List (Numbered List)</h3>

_To create performed same way but user numbered lines (ie. ` 1. , 2. , etc ` )_  
Can be nested with either ordered or unordered items
1. Item One
    - Item One part 1
    1. Item One Sub One
2. Item Two

<br>



<!--Task List -->


<h2 style="color: blue">Task List (Check Box List)</h2>

_To create same as unordered list but include ` [ ] ` before text. \* MAY NOT RENDER IN VSCODE_
<br>
- [ ] Bread _` " - [ ] Bread " `_
    - [ ] White _` " - [ ] White " `_
    - [ ] Wheat _` " - [ ] Wheat " `_
- [ ] Fruit _` " - [ ] Fruit " `_
    - [ ] Apple _` " - [ ] Apple " `_
    - [ ] Orange _` " - [ ] Orange " `_
    - [ ] Banana _` " - [ ] Banana " `_

<br>



<!--Table -->


<h2 style="color: blue">Table</h2>

` |  <text>    |  <text>    |  <text>    | ` \*header row, inherintly bold  
` |------------|------------|------------| ` \*table break  
` | <Row Text> | <Row Text> | <Row Text> | ` \*table row  
<br>
|Mom    | Dad | Child 1 | Child 2 |  
|:-------|:-----:|---------:|:---------:|
|Steph  | Nick| Nora    | Elsie   |  

\*text is default left aligned:  
- to center add colon on either end of table break columns  
- right adjust add single colon on right end of table break column  

\*can mix and match alignments

<br>



<!--Misc. -->


<h2 style="color: green">Misc.</h2>

- <h3 style="color: orange">Centering</h3>

_<div align="center">To center text on page, can use typical HTML center syntaxing </div>_
<div align="center">

```html
<div align="center">  <"Text">  </div>
```

</div>

<br>

- <h3 style="color: orange">External links defaul to open new tab in default/current browser</h3>
