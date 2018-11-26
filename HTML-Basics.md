# HTML basics

## Introduction
HTML stands for ```Hypertext-Markup-Language```.

Same principle in editors with highlighting e.g. bold, font size, color:  
Plain text is highlighted with special **surrounding tags** in source e.g. ```<b> </b>``` (bold), ```<h1> </h1>``` (headline).

Ending of an tag is defined with ```</tag>```. Some tags can be directly closed e.g. ```<meta charset="utf-8"/>```

Browsers render the website depending on ```HTML/CSS``` source.

**Note:** ```<tags> </tags>``` should be used in tree structures for encapsulated relationships and properties.

**Example:**

```HTML
<html>
|  <head>
|  (  <title>My Website</title>
|  </head>
|
|  <body>
|  (  <h1>A headline</h1>
|  (  <p><a href="path/to/file">encapsulated url, surrounded by paragraph</a></p>
|  </body>
</html>
```

<hr>

```HTML
<!-- Tag usage -->
<html>
</html>

<!-- Highlight Lorem ipsum as h1 -->
<h1>Lorem ipsum</h1>

<!--
   -    Don't need to be closed
   -    predefined properties e.g. thematic break, manual line break
   -->
<hr> <br>

<div id="foo">
  Text inside div foo
</div>


<!--
   -    <head> is used for meta data properties and relationships to stylesheets and scripts
   -    title – browser tab name, meta - charset, description …
   -->
  <head>
    <title>My Website</title>
    <meta charset="utf-8"/>
    <link rel="stylesheet" type="text/css" href="css/style.css"/>
  </head>
```
