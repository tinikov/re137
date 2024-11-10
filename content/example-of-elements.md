+++
title = "Example of elements"
date = 2000-01-01T00:00:00+00:00
description = "Post showcasing elements"
[taxonomies]
categories = ["samples"]
[extra]
toc_gen = true
+++

## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

## Horizontal Rules

___

---

***

## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~

## Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
    + Facilisis in pretium nisl aliquet
      - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

Block code "fences"

```
Sample text here...
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. extension to be used for dest files. extension to be used for dest files. extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

## Links

[link text](http://github.com)

[link with title](http://github.com "title text!")

## Images

!["Still Life with Peaches and Grapes" by Auguste Renoir](https://images.metmuseum.org/CRDImages/ep/original/DT1877.jpg)

![Mille-fleurs tapestry with three medallions](https://images.metmuseum.org/CRDImages/es/original/DP360507.jpg "Mille-fleurs tapestry with three medallions")

Like links, Images also have a footnote style syntax

![The Unicorn is Attacked (from the Unicorn Tapestries][id]

With a reference later in the document defining the URL location:

```
[id]: https://images.metmuseum.org/CRDImages/cl/original/DP101128.jpg  "The Unicorn is Attacked"
```

[id]: https://images.metmuseum.org/CRDImages/cl/original/DP101128.jpg  "The Unicorn is Attacked"

### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

and multiple paragraphs.

[^second]: Footnote text.
