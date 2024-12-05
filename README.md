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
Follow [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/ "A quick reference to the Markdown syntax!")
#### URLs and Email Addresses
<https://www.markdownguide.org/>  
<lt.anh197@gmail.com>
#### Formatting Links
I love supporting ***[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)***
#### Reference-style Links
Follow [Markdown Cheat Sheet][label-1]
## Extended Syntax

[label-1]: <https://www.markdownguide.org/cheat-sheet/> "A quick reference to the Markdown syntax!"
