Glipdown - Glip Flavored Markdown
=================================

This is the library to render Glip Flavored Markdown.

## Formatting

| Markdown | Output |
|----------|--------|
| `\*italics\*` | *italics* |
| `\*\*bold\*\*` | **bold** |
| `\[a link\]\(http://google.com\)` | [a link](http://google.com) |


```
*italics*	italics
**bold**	bold
[a link](http://google.com)	a link
> quote	
quote
~~strikethrough~~	strikethrough
_underline_	underline
* list item 1
* list item 2
* list item 3	
list item 1
list item 2
list item 3
|three|column|table|	
three	column	table
```

## Running the Tests

```bash
$ git clone https://github.com/jstrinko/glipdown
$ npm install
$ npm test/markdown.js
```
