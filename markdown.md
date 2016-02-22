---
layout: page
title:  "Markdown"
date:   2016-02-16 21:27:23
categories: tools
permalink: /tools/markdown/
---

Markdown Cheatsheet

Markdown ist eine Auszeichnungssprache, die das Schreiben und Strukturieren von HTML-formatierten Texten wesentlich erleichtert. Eine Reihe von Sonderzeichen werden automatisch in valide HTML Auszeichnunng konvertiert:

---

# Überschriften

	# Heading 1 		wird zu <h1>Heading 1</h1>
	## Heading 2 		wird zu <h2>Heading 2</h2>
	### Heading 3 		wird zu <h3>Heading 3</h3>
	#### Heading 4 		wird zu <h4>Heading 4</h4>
	##### Heading 5 	wird zu <h4>Heading 4</h4>
	

# Text
	
Common text


## Emphasized text

	*Emphasized text*

## Strong text

   **Strong text**

# Links

[Named Link](http://www.google.fr/) and http://www.google.fr/ or <http://example.com/>

    Markup :  [Named Link](http://www.google.fr/) and http://www.google.fr/ or <http://example.com/>

# Lists

* Bullet list
 * Nested bullet
  * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
           * Nested bullet
            * Sub-nested bullet etc
          * Bullet list item 2
~~~

1. A numbered list
 1. A nested numbered list
 2. Which is numbered
2. Which is numbered

~~~
 Markup : 1. A numbered list
           1. A nested numbered list
           2. Which is numbered
          2. Which is numbered
~~~


# Tables

Table, like this one :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

# Code


`code()`

    Markup :  `code()`

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    Markup : ```javascript
             ```


> Blockquote
>> Nested blockquote

    Markup :  > Blockquote
              >> Nested Blockquote

_Horizontal line :_
- - - -

    Markup :  - - - -

_Image with alt :_

![picture alt](http://www.brightlightpictures.com/assets/images/portfolio/thethaw_header.jpg "Title is optional")

    Markup : ![picture alt](http://www.brightlightpictures.com/assets/images/portfolio/thethaw_header.jpg "Title is optional")