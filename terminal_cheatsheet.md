# Markdown Cheatsheet
All markdown files end with .md

`ls` - this will show you all the files

# H1 
## H2
### H3

**bold text**

*italic font*

> this is a blockquote

## Ordered List
1. first item
2. second item
3. third item

`code`

## 3 ways to create horizontal lines
***
---
____

[hyperlink name of choice](https://www.example.com)

![alt text if image doesnt load ](image.jpg)

| Table title 1 | Table title 2 |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

## Fenced Code Blocks
####  use three backticks (```) or three tildes (~~~) on the lines before and after the code block. No line indentaion needed.
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

[^1]: This is the footnote.

## Heading ID

#### Adding custom IDs allows you to link directly to headings and modify them with CSS. To add a custom heading ID, enclose the custom ID in curly braces on the same line as the heading.
### My Great Heading {#custom-id}

## Definition Lists
#### Some Markdown processors allow you to create definition lists of terms and their corresponding definitions.

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough
~~The world is flat.~~ We now know that the world is round.

## Task Lists
#### Task lists (also referred to as checklists and todo lists) allow you to create a list of items with checkboxes.
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

control+command+space= 🐍 🐍 🐍 🐍

## Highlight
#### two methods to highlight depending on your markdown processors
I need to highlight these ==very important words==.
I need to highlight these <mark>very important words</mark>.

## Subscript
#### some Markdown processors allow you to use subscript to position one or more characters slightly below the normal line of type. Two methods based on processor.

H~2~O

H<sub>2</sub>O

## Superscript
#### some Markdown processors allow you to use superscript to position one or more characters slightly above the normal line of type. Two methods based on processor.
X^2^

X<sup>2</sup>