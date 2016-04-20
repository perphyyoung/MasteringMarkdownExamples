# Mastering Markdown Examples
To test some basic markdown syntax, based on [Mastering Markdown](https://www.gitbook.com/book/roachhd/master-markdown/details)

Bonus: GitHub **official** document of [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

# <a name="Table of Content"></a> Table of Content
[Anchors](#Anchors)  
[Blockquotes](#Blockquotes)  
[Code Blocks](#Code Blocks)  
[Horizontal Rules](#Horizontal Rules)  
[Images](#Images)  
[Links](#Links)  
[Lists](#Lists)  
[Special Character](#Special Character)  
[Tables](#Tables)  
[Titles](#Titles)  
[GFM](#GFM)  
[Writing on GitHub](#Writing on GitHub)


# <a name="Anchors"></a> Anchors
See [Table of Content](#Table of Content) above.


# <a name="Block Elements"></a> Block Elements
### Paragraph
A paragraph is simple one or more consecutive lines of text, separated by one or more blank lines.

### Line Breaks
End a line with 2 or more spaces, rather than a `<br/>`.


# <a name="Blockquotes"></a> Blockquotes
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.


# <a name="Code Blocks"></a> Code Blocks
To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

    This is a code block.

### Inline code blocks
This is a `inline code block`

### Syntax highlighting
```js
var a = {};
```


# <a name="Horizontal Rules"></a> Horizontal Rules
***
---
___


# <a name="Images"></a> Images
### Inline
![Alternative text](https://avatars1.githubusercontent.com/u/8685355?v=3&s=96 "Optional title")

### Reference
![Alternative text][imageId]
[imageId]: https://avatars1.githubusercontent.com/u/8685355?v=3&s=96 "Optional title"


# <a name="Links"></a> Links
[I'm an inline-style link](https://www.google.com/ncr)

[I'm an inline-style link with title](https://www.google.com/ncr "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](LICENSE)


# <a name="Lists"></a> Lists
### Unordered lists (use asterisks, pluses, and hyphens)
* Asterisk
+ Plus
- Hyphen

### Ordered lists (numbers followed by period)
1. Bird
2. McHale
3. Parish


# <a name="Special Character"></a> Special Character
Inside Markdown code spans and blocks, angle brackets(<>) and ampersands(&) are **always** encoded automatically.


# <a name="Tables"></a> Tables
Tables aren't part of the core Markdown spec, but they are part of GFM (GitHub Flavored Markdown).

| Tables | Are | Cool |
| :------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |


# <a name="Titles"></a> Titles
> # This is an H1
> ## This is an H2
> ###### This is an H6


# <a name="GFM"></a> GitHub Flavored Markdown (GFM)
Some differences from traditional Markdown:

### Multiple underscore in words
GFM ignores underscores in words:
* wow_great_stuff

### URL autolinking
GFM will autolink standard URLs:
* http://example.com

### Strikethrough text
GFM adds syntax to create strikethrough text
* ~~Mistaken text.~~

### Fenced code blocks
Just wrap your code in \`\`\` `some code` \`\`\`

```
function test() {
    console.log("Notice the blank line before this function?");
}
```

### Syntax highlighting
This is a further step of *code block*

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

### Tables
See [Tables](#Tables) section.

### HTML
You can use a subset of HTML within your READMEs, issues, and pull requests.


# <a name="Writing on GitHub"></a> Writing on GitHub
## Markup
### Task lists
- [x] @mentions, #refs, [links](), **formatting**, and tags are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### References
Certain references are auto-inked:

* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26

## Features
1. Name and Team @mentions autocomplete
2. Emoji autocomplete, check out http://www.emoji-cheat-sheet.com
3. Issue autocomplete (Typing # will bring up)
4. Zen Mode (fullscreen) writing


## Emoji
:smile:

The top 5 used Emojis on GitHub are:

1. :shipit: `:shipit:`
2. :sparkles: `:sparkles:`
3. :-1: `:-1:`
4. :+1: `:+1:`
5. :clap: `:clap:`


[Arbitrary case-insensitive reference text]: https://www.perphyyoung.github.io "PerphyYoung's Homepage"
