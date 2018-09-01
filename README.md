# Mastering Markdown Examples

To test some basic markdown syntax, based on [Mastering Markdown](https://www.gitbook.com/book/roachhd/master-markdown/details).

Useful links:

* GitHub **official** document of [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* Online Markdown Cheatsheet (PDF version) https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

## <a name='TableOfContent'></a> Table of Content

[Anchors](#Anchors)  
[Blockquotes](#Blockquotes)  
[Code Blocks](#CodeBlocks)  
[Horizontal Rules](#HorizontalRules)  
[Images](#Images)  
[Links](#Links)  
[Lists](#Lists)  
[Special Character](#SpecialCharacter)  
[Tables](#Tables)  
[Titles](#Titles)  
[GFM](#GFM)  
[Writing on GitHub](#WritingOnGitHub)

## <a name="Anchors"></a> Anchors

See [Table of Content](#TableOfContent) above.

## <a name="Block Elements"></a> Block Elements

### Paragraph

A paragraph is simple one or more consecutive lines of text, separated by one or more blank lines.

### Line Breaks

End a line with 2 spaces, rather than a `<br/>`.

## <a name="Blockquotes"></a> Blockquotes

> This is a blockquote with two paragraphs.
>
> This is the second paragraph, under one blank line.

## <a name="CodeBlocks"></a> Code Blocks

To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

    This is a code block.

### Inline code blocks

This is a `inline code block`

### Syntax highlighting

```python
import tensorflow as tf
```

## <a name="HorizontalRules"></a> Horizontal Rules

***

## <a name="Images"></a> Images

![Alternative text when cannot load image.](invalid_path)

![Alternative text when cannot load image.](https://avatars1.githubusercontent.com/u/8685355?v=3&s=96 "Optional title")

## <a name="Links"></a> Links

[I'm an inline-style link.](https://www.google.com/ncr)

[I'm an inline-style link with title.](https://www.google.com/ncr "Google's Homepage")

[I'm a reference-style link.][Arbitrary case-insensitive reference text]

[Arbitrary case-insensitive reference text]: https://www.perphyyoung.github.io "PerphyYoung's Homepage"

[I'm a relative reference to a repository file.](LICENSE)

## <a name="Lists"></a> Lists

### Unordered lists (asterisks recommended)

* Asterisk

### Ordered lists (numbers followed by period and a space)

1. Bird
2. McHale
3. Parish

## <a name="SpecialCharacter"></a> Special Character

Inside Markdown code spans and blocks, angle brackets(<>) and ampersands(&) are **always** encoded automatically.

## <a name="Tables"></a> Tables

Tables aren't part of the core Markdown spec, but they are part of GFM (GitHub Flavored Markdown).

| Tables | Are | Cool |
| :------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

## <a name="Titles"></a> Titles

> ## This is an H2
> ### This is an H3
> #### This is an H4

## <a name="GFM"></a> GitHub Flavored Markdown (GFM)

Some differences from traditional Markdown:

### URL autolinking

GFM will autolink standard URLs:

* http://example.com

### Strikethrough text

GFM adds syntax to create strikethrough text

* ~~Mistaken text.~~

### Fenced code blocks

Just wrap your code in \`\`\` `some code` \`\`\`

```javascript
function test() {
    console.log("Notice the blank line before this function?");
}
```

### Tables

See [Tables](#Tables) section.

## <a name="WritingOnGitHub"></a> Writing on GitHub

### Markup

#### Task lists

* [x] @mentions, #refs, [links](fake_path), **formatting**, and tags are supported
* [x] list syntax is required (any unordered or ordered list supported)
* [x] this is a complete item
* [ ] this is an incomplete item

#### References

Certain references are auto-inked:

* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26

### Features

1. Name and Team @mentions autocomplete
2. Emoji autocomplete, check out http://www.emoji-cheat-sheet.com
3. Issue autocomplete (Typing # will bring up)
4. Zen Mode (fullscreen) writing

### Emoji

:smile:

The top 5 used Emojis on GitHub are:

1. :shipit: `:shipit:`
2. :sparkles: `:sparkles:`
3. :-1: `:-1:`
4. :+1: `:+1:`
5. :clap: `:clap:`
