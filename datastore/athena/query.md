# query

## Markdown Cheatsheet

## Heading 1 \#

```text
Markup :  # Heading 1 #

-OR-

Markup :  ============= (below H1 text)
```

### Heading 2 \#\#

```text
Markup :  ## Heading 2 ##

-OR-

Markup: --------------- (below H2 text)
```

#### Heading 3 \#\#\#

```text
Markup :  ### Heading 3 ###
```

**Heading 4 \#\#\#\#**

```text
Markup :  #### Heading 4 ####
```

Common text

```text
Markup :  Common text
```

_Emphasized text_

```text
Markup :  _Emphasized text_ or *Emphasized text*
```

~~Strikethrough text~~

```text
Markup :  ~~Strikethrough text~~
```

**Strong text**

```text
Markup :  __Strong text__ or **Strong text**
```

_**Strong emphasized text**_

```text
Markup :  ___Strong emphasized text___ or ***Strong emphasized text***
```

[Named Link](http://www.google.fr/) and [http://www.google.fr/](http://www.google.fr/) or [http://example.com/](http://example.com/)

```text
Markup :  [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>
```

[heading-1](query.md#heading-1)

```text
Markup: [heading-1](#heading-1 "Goto heading-1")
```

Table, like this one :

| First Header | Second Header |
| :--- | :--- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

```text
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

`code()`

```text
Markup :  `code()`
```

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

```text
Markup : ```javascript
         ```
```

* Bullet list
  * Nested bullet
    * Sub-nested bullet etc
* Bullet list item 2

```text
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2
```

1. A numbered list
   1. A nested numbered list
   2. Which is numbered
2. Which is numbered

```text
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
```

* [ ] An uncompleted task
* [x] A completed task

```text
 Markup : - [ ] An uncompleted task
          - [x] A completed task
```

* [ ] An uncompleted task
  * [ ] A subtask

```text
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
```

> Blockquote
>
> > Nested blockquote

```text
Markup :  > Blockquote
          >> Nested Blockquote
```

_Horizontal line :_

```text
Markup :  - - - -
```

_Image with alt :_

![Title is optional](http://via.placeholder.com/200x150)

```text
Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")
```

Foldable text:

Title 1

Content 1 Content 1 Content 1 Content 1 Content 1Title 2

Content 2 Content 2 Content 2 Content 2 Content 2

```text
Markup : <details>
           <summary>Title 1</summary>
           <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
         </details>
```

```markup
<h3>HTML</h3>
<p> Some HTML code here </p>
```

Hotkey:

⌘F

⇧⌘F

```text
Markup : <kbd>⌘F</kbd>
```

Hotkey list:

| Key | Symbol |
| :--- | :--- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1: Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

```text
Markup : Code appears between colons :EMOJICODE:
```

