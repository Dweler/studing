# Описание языка Markdown
Text surrounded by *  | _ - *italics*  
Text surrounded by ** | ** - **bold**
# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six
Inline link - [Search for it.](https://www.google.com)

Reference link - Do you want to [see something fun][a fun place]?

Reference link - Well, do I have [the website for you][another fun place]!

[a fun place]:https://www.zombo.com
[another fun place]:https://www.stumbleupon.com

Image - ![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

Reference image - [Black cat][Black]
[Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

Blockquote -

I read this interesting quote the other day:
>Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!

Unordered list -
* Flour,
* Cheese, 
* Tomatoes

Ordered list -
1. Cut the cheese 
1. Slice the tomatoes
1. Rub the tomatoes in flour

Nest one list within another
1. Cut the cheese 
1. Slice the tomatoes
   * Flour,
   * Cheese, 
   * Tomatoes
1. Rub the tomatoes in flour

Hard break - insert new line.  
Soft break - inserting two spaces after each new line.

table - 

| Command | Description |
| --- | --- |
| Open Developer Tools | F12,Ctrl + Shift + I |
| Open Developer Tools and bring focus to the console | Ctrl + Shift + J |

## <i>Example</i>

Here's a useful method. Should produce clickable references in any MarkDown editor.

# Table of contents
1. [Introduction](#introduction)
2. [Some paragraph](#paragraph1)
    1. [Sub paragraph](#subparagraph1)
3. [Another paragraph](#paragraph2)

## This is the introduction <a name="introduction"></a>
Some introduction text, formatted in heading 2 style

## Some paragraph <a name="paragraph1"></a>
The first paragraph text

### Sub paragraph <a name="subparagraph1"></a>
This is a sub paragraph, formatted in heading 3 style

## Another paragraph <a name="paragraph2"></a>
The second paragraph text

