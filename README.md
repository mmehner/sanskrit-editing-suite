# sanskrit editing suite
description

## Prerequisites

## Installation


## Preliminary considerations: text encoding and presentation
- text encoding is not to be confounded with character encoding, cf. [this site](https://scripts.sil.org/IWS-Chapter02) for a short introduction;
- text encoding is mostly done with a particular form of presentation (a printed book, web page, poster) in mind, the content is structured and differentiated according to the necessities of the processor (e.g. LaTeX commands separate content from presentational processing instructions), often inside a user interface that displays the encoded information as formatted text in a similar way to the intended result (WYSIWYG, e.g. office suites); the text encoding has to be converted if another form of presentation is desired
- textual content can also be encoded according to its function regardless of presentation, which is especially useful if:
  - various presentations should be generated from the same source file,
  - a subsequent use of the content by yourself or others is foreseeable/desirable,
  - you don't want to deal with formatting details (yet).
- general drawbacks of functional markup:
  - functional markup is usually more intrusive and less intuitive to read,
  - presentation has to be styled separately.

## Acronyms
- XML = Extensible Markup Language, for a crash course on XML cf. [this repo](https://github.com/radardenker/xml-crashcourse)
- XSLT = Extensible Stylesheet Language Transformations, 
- DTD = Document Type Definition, a validation scheme type
- TEI = Text Encoding Initiative
- NLP = Natural Language Processing

## Usage
- [general workflow](charts/editing-workflow-with-ekdosis.pdf) with [https://ctan.org/pkg/ekdosis](ekdosis), [https://de.wikipedia.org/wiki/LuaTeX](LuaLaTeX) and [https://www.w3.org/TR/xslt20/](XSLT 2.0)
  - text encoding: LaTeX
  - outputs:
    - pdf for publication
    - html for progress sharing
    - plain text for string search, text mining and NLP

## Known issues

## Examples 

```

```
