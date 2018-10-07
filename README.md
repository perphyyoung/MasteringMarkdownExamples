# Mastering Markdown Examples
Showing some basic markdown syntax, based on [Mastering Markdown on gitbook](https://www.gitbook.com/book/roachhd/master-markdown/details).

Useful links:  
* GitHub **official** document of [Mastering Markdown guides](https://guides.github.com/features/mastering-markdown/)
* Online markdown cheatsheet (PDF version) https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

## Table of Content
[1. Anchors](#1-anchors)  
[2. Block Elements](#2-block-elements)  
[3. Blockquotes](#3-blockquotes)  
[4. Code Blocks](#4-code-blocks)  
[5. Horizontal Rules](#5-horizontal-rules)  
[6. Images](#6-images)  
[7. Links](#7-links)  
[8. Lists](#8-lists)  
[9. Special Character](#9-special-character)  
[10. Tables](#10-tables)  
[11. Titles](#11-titles)  
[12. GFM](#12-gfm)  
[13. Writing on GitHub](#13-writing-on-github)

## 1. Anchors
See [Table of Content](#table-of-content) above.

## 2. Block Elements
### 2.1 Paragraph
A paragraph is simple one or more consecutive lines of text, separated by one or more blank lines.

### 2.2 Line Breaks
End a line with 2 spaces, rather than a `<br/>`.

## 3. Blockquotes
> This is a blockquote with two paragraphs.
>
> This is the second paragraph, under one blank line.

## 4. Code Blocks
To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

    This is a code block.

### 4.1 Inline code blocks
This is a `inline code block`

### 4.2 Syntax highlighting
By specify a language.

```python
import tensorflow as tf
```

## 5. Horizontal Rules
By three `*`, namely `***`.

***

## 6. Images
![Alternative text when cannot load image.](invalid_path)

![Alternative text when cannot load image.](https://avatars1.githubusercontent.com/u/8685355?v=3&s=96 "Optional title")

## 7. Links
[I'm an inline-style link.](https://www.google.com/ncr)

[I'm an inline-style link with title.](https://www.google.com/ncr "Google's Homepage")

[I'm a reference-style link.][Arbitrary case-insensitive reference text]

[Arbitrary case-insensitive reference text]: https://www.perphyyoung.github.io "PerphyYoung's Homepage"

[I'm a relative reference to a repository file.](LICENSE)

## 8. Lists
### 8.1 Unordered lists
> asterisks recommended

* Asterisk

### 8.2 Ordered lists
> numbers followed by period and a space

1. Bird
2. McHale
3. Parish

## 9. Special Character
Inside Markdown code spans and blocks, angle brackets(<>) and ampersands(&) are **always** encoded automatically.

## 10. Tables
Tables aren't part of the core Markdown spec, but they are part of GFM (GitHub Flavored Markdown).

| Tables | Are | Cool |
| :------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

## 11. Titles
> ## This is an H2
> ### This is an H3
>
> #### This is an H4

## 12. GFM
GitHub Flavored Markdown.  
Some differences from the standard Markdown:

### 12.1 Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

### 12.2 Strikethrough text
GFM adds syntax to create strikethrough text

* ~~Mistaken text.~~

### 12.3 Fenced code blocks
Just wrap your code in \`\`\` `some code` \`\`\` and specify a language

```javascript
function test() {
    console.log("Notice the blank line before this function?");
}
```

### 12.4 Tables
See [Tables](#Tables) section.

## 13. Writing on GitHub
### 13.1 Task lists
* [x] @mentions, #refs, [links](fake_path), **formatting**, and tags are supported
* [x] list syntax is required (any unordered or ordered list supported)
* [x] this is a complete item
* [ ] this is an incomplete item

### 13.2 References
Certain references are auto-inked:
* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: perphyyoung@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: perphyyoung/sample.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: perphyyoung#26
* User/Repository#Num: perphyyoung/sample.js#26

### 13.3 Features
1. Name and Team @mentions autocomplete
2. Emoji autocomplete, check out http://www.emoji-cheat-sheet.com
3. Issue autocomplete (Typing # will bring up)
4. Zen Mode (full-screen) writing

### 13.4 Emoji
1. :smile: `:smile:`
2. :sparkles: `:sparkles:`
3. :-1: `:-1:`
4. :+1: `:+1:`
5. :clap: `:clap:`
