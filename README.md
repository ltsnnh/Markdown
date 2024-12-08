The Markdown Guide
===
Basic Syntax
---
### Headings
#### Heading level 4
##### Heading level 5
###### Heading level 6
### Paragraphs
To create paragraphs, use a blank line to separate one or more lines of text.

You should not indent paragraphs with spaces or tabs.
### Line Breaks
To create a line break  
end a line with two or more spaces  
and then type return.
### Emphasis
#### Bold
To **bold** text, add **two asterisks** or underscores before and after a word or phrase.
#### Italic
To *italicize* text, add *one asterisk* or underscore before and after a word or phrase.
#### Bold and Italic
To ***emphasize*** text with **bold** and *italics* at the same time, add ***three asterisks*** or underscores before and after a word or phrase.
### Blockquotes
> To create a blockquote, add a > in front of a paragraph.
#### Blockquotes with Multiple Paragraphs
> This the first paragraph.
>
> And this is the second paragraph.
#### Nested Blockquotes
> This the first paragraph.
>
>> And this is the nested paragraph.
#### Blockquotes with Other Elements
> ##### Blockquotes can contain other Markdown formatted elements
>
> - Not all elements can be used.
> - You’ll need to experiment to see which ones work.
>
> *Everything* is going **well**.
### Lists
#### Ordered Lists
1. First item
4. Second item
2. Third item
3. Fourth item
##### Nesting List Items
1. First item
1. Second item
1. Third item
    1. Indented item
    1. Indented item
1. Fourth item
#### Unordered Lists
- First item
+ Second item
* Third item
- Fourth item
##### Nesting List Items
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
#### Adding Elements In Lists
##### Paragraphs
- This is the first list item.
- Here's the second list item.
  
    I need to add another paragraph below the second list item.

- And here's the third list item.
##### Blockquotes
- This is the first list item.
- Here's the second list item.

    > A blockquote would look great here.

- And here's the third list item.
##### Code Blocks
- Open the file.
- Find the following code block on line 21:

        main()
        {
            return 0;
        }

- Write code in main() function.
##### Images
- Open the file.
- Marvel at its beauty.
  
    ![Markdown flowchart](/markdown-flowchart.png)

- Close the file.
### Code
To denote a *word or phrase* as `code`, enclose it in tick marks (`).
#### Escaping Tick Marks
If the *word or phrase* you want to denote as code *includes one or more tick marks*,
``you can escape it by enclosing the `word or phrase` in double tick marks`` (``).
#### Code Blocks
    <html>
        <head>
        </head>
    </html>
### Horizontal Rules
***
---
___
### Links
Follow [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
#### Adding Titles
[Dillinger](https://dillinger.io/ "The best online Markdown editors") which you can use to try writing in Markdown.
#### URLs and Email Addresses
<https://daringfireball.net/projects/markdown/>  
<lt.anh197@gmail.com>
#### Formatting Links
A list of Markdown tools and learning resources: ***[Awesome Markdown](https://github.com/mundimark/awesome-markdown)***
#### Reference-style Links
Check out [Jekyll][label-1]
### Images
![Markdown Logo](/markdown.jpg "Markdown watermark")
### Escaping Characters
\*To display a literal character that would otherwise be used to format text in a
Markdown document, add a backslash (\\) in front of the character.
#### Characters You Can Escape
| Syntax | Description |
| ------ | ----------- |
| \ | backslash |
| ` | tick mark |
| * | asterisk |
| _ | underscore |
| {} | curly braces |
| [] | brackets |
| () | parentheses |
| # | pound sign |
| + | plus sign |
| - | minus sign |
| . | dot |
| ! | exclamation mark |
| \| | pipe |
## Extended Syntax
### Tables
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
#### Alignment
| Syntax | Description | Test Text |
| :--- | :---: | ---: |
| Header | Title | Here's this |
| Paragraph | Text | And more |
### Fenced Code Blocks
```json
{
    "firstName": "Tuan Anh",
    "lastName": "Le",
    "age": 27
}
```
### Footnotes
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

### Heading IDs {#custom-id}
#### Linking to Heading IDs
You can link to headings with custom IDs in the file by creating a [standard link](#custom-id) with
a number sign (#) followed by the custom heading ID.

### Definition Lists
First Term  
: This is the definition of the first term.

Second Term  
: This is one definition of the second term.  
: This is another definition of the second term.  

### Strikethrough
The world is ~~flat~~ round.

### Task Lists
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

---

[label-1]: <https://jekyllrb.com/> "A site generator that takes Markdown files and builds an HTML website"
