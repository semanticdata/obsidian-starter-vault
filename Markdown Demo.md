---
title: Markdown Demo
tags:
  - markdown
  - reference
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc eu feugiat sapien. Aenean ligula nunc, laoreet id sem in, interdum bibendum felis.

# H1 Heading 1

## H2 Heading 2

### H3 Heading 3

#### H4 Heading 4

##### H5 Heading 5

###### H6 Heading 6

## Text Formatting

Text can be **bold**, _italic_, or ~~strikethrough~~.

You can [link](https://example.dom/) to external pages. and other internal [[Markdown|links]].

## Blockquotes

### Example 1

> This is a blockquote
> with several lines

### Example 2

> ## This is a header.
> 1. This is the first list item.
> 2. This is the second list item.
> 
> Here's some example code:
> 
>     Markdown.generate();

## Lists

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

* List item
* Another item
* And another item

### Nested List

* Item
	1. First Sub-item
	2. Second Sub-item

## Code

### Inline Code

Let us use some `inline code` and check out how it `looks`. Here's some `more`.

### Code Blocks

```html
<html>
	<head>
		<div style="background-color: #333;">
			<a href="https://example.com/">Example</a>
		</div>
	</head>
</html>
```

```css
.niceClass {
	color: blue;
	background-color: #fff;
}
```

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

## Tables

| head one     |     head two      | head three |
| ------------ | :---------------: | ---------: |
| ok           | good swedish fish |       nice |
| out of stock |  good and plenty  |       nice |
| ok           |   good `oreos`    |        hmm |
| ok           | good `zoute` drop |       yumm |

## Inline Markdown Within Tables

| Inline&nbsp;&nbsp;&nbsp; | Markdown&nbsp;&nbsp;&nbsp; | In&nbsp;&nbsp;&nbsp;                | Table  |
| ------------------------ | -------------------------- | ----------------------------------- | ------ |
| _italics_                | **bold**                   | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code` |

## Callouts

Callouts are great for highlighting important information.

> [!INFO] Custom Title Here
> This is an info callout with a custom title.

> [!TIP]
> This is a tip. Note the title defaults to the callout type.

> [!WARNING]
> This is a warning callout.

> [!NOTE] Collapsible Section
> This callout can be collapsed by clicking it.
>
> You can put multiple lines inside.
>
> > Even nested quotes work.

> [!QUESTION]- Can callouts be collapsed by default?
> Yes! Add a minus (-) or plus (+) after the type.
>
> - Minus (-) = collapsed by default
> - Plus (+) = expanded by default (default behavior)

> [!EXAMPLE]
> Here are the available callout types:
>
> - `note` (default, blue)
> - `info` (blue)
> - `todo` (blue)
> - `tip` (cyan, shows a lightbulb)
> - `success` (green)
> - `question` (yellow)
> - `warning` (orange)
> - `failure` (red)
> - `danger` (red)
> - `bug` (red)
> - `example` (purple)
> - `quote` (gray, no icon)

## Horizontal Rule

---

## Tasks and Todos

- [ ] Pending Task
- [x] Completed Task
* [-] Won't Do Task
* [/] In Progress Task
* [*] You are a star.
* [!] Exclamation Mark!
* [?] Question Mark?
* [<] Scheduled Task
* [>] Forwarded Task

## Images

![image](https://just-the-docs.com/assets/images/small-image.jpg)

## Other Elements — Abbr, Sub, Sup, Kbd, Mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
