# Markdown Test
This document is a test to demonstrate that my knowledge of using markdown, developed while creating personal projects with a markdown-based graphic design site, can be effectively carried over to my role at the Wellcome Trust.

# Titles and headings 

Headings are made by preceding the text at the start of a line using a hash symbol, for example 

`# Title` would produce the following:

# Title

An increased number of hash symbols creates a smaller heading, as follows

# Title (`# Title`)

## Title (`## Title`)

### Title (`### Title`)

#### Title (`#### Title`)

##### Title (`##### Title`)

###### Title (`###### Title`)

While the last two appear as bold text and the same size as regular text, these may have different appearances on different markdown based programs. As a rule, hash symbols must be used at the start of a line to produce these results. Otherwise they come out like this: ## Title

___

## Bullet points

In a similar way to how a title or heading is added with a hash symbol, lines starting with an asterisk produce bullet points, such as `* Line 1`. The same result is produced by starting a line with a dash, such as `- Line 2`.

* Line 1
- Line 2
___

## Tables

##### Sample Table
| 1 | 2 | 3 |
|:----|:-----:|-----:|
| Left-aligned | Centred | Right-aligned |
| A | B | C |


Structuring a table such as the one above appears as follows: 

`| 1 | 2 | 3 |` - The top row of a table essentially designates the start of a table. This row will follow the alignment rules that appear in the 2nd row.

`|:----|:-----:|-----:|` - These desingate the alignment of each collumn.

`|:---|` for left-alighted, `|:---:|` for centred, and `|---:|` for right-aligned.

`| Left-aligned | Centred | Right-aligned |` - Following rows are structured in the same manner as the top row, and follow the alignment rules of the second row.

`| A | B | C |`

___

## Text Boxes

> ### Sample Text Box
> Where in my own projects a text box like this would be used for rules inserts, like quick references to related rulings, in this
> context the text box serves similar funtion in bringing an aside that can be treated separate to the main body of the text.
> With the style of this site, it would also be ideal for bringing attention to key quotes from the body of text, done using the hash symbol for the heading effect (starting with the appropriate number of hash symbols).

For example:

> ### *"(These blockquotes) would also be ideal for bringing attention to key quotes from the body of text."*

A text box is created by starting every line with the following: `> `. This symbol must be followed with a space to create a text box. After this space, one can start a new line as normal, such as with enlarged text using the hash symbol, or with an asterisk for bullet-points.

___

## Bold and Italic

**Bold**, *italics*, and ***the two combined*** are done through the use of asterisks. 
Asterisks either side of the text (with no space between the asterisk and the first and last characters, for example typing
`*Italic*` results in the word appearing as *Italic*) 
produce the following results, depending on the number used.

| Number of asterisks either side of text | Effect on Text |
|---|---:|
| One | *Italic* |
| Two | **Bold** |
| Three | ***Bold and Italic*** |
| Four or more | ******No further effect, reverts to bold****** |

---

## Dividing lines

Dividing lines can be produced with a row of three asterisks, dashes, or underscores. `***`, `---` or `___`.

***

## Hyperlinks

For hyperlinks, surround the word that you want to be the link with `[ ]`, then the url with `( )` immediately afterwards, so that there is no space between the second bracket of the first pair, and the first bracket of the second pair. 

`[Link](url of link)` 

For example, `[Wellcome](https://wellcome.ac.uk/)` will appear as [Wellcome](https://wellcome.ac.uk/), and link to https://wellcome.ac.uk/.

---

## Images

Inserting an image can vary with different versions of markdown-based software. In this format, there are two primary ways of insering an image. The first is `![]()`, in which the first pair of brackets is left empty, and the second pair contains the url for an image hosted online, or an image hosted within the same repository as the markdown document.

For example, `![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Wellcome_Trust_logo.svg/2000px-Wellcome_Trust_logo.svg.png)`
produces the following image.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Wellcome_Trust_logo.svg/2000px-Wellcome_Trust_logo.svg.png)

Images can also be added with the following method, for the same result. `<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Wellcome_Trust_logo.svg/2000px-Wellcome_Trust_logo.svg.png">` This method, where the image url is placed in as follows, `<img src="`Image URL`">` is preferable, as this allows the image to be resized.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Wellcome_Trust_logo.svg/2000px-Wellcome_Trust_logo.svg.png">

### Resizing Images

To resize an image added using the latter line of code, after the URL, add either `height="` or `width="`, followed by the intended height or width in pixels. The ideal value for this may not be obvious, so it's worth trying different values to work out the right size. For example, `<img src="`Image URL`" width="48">` produces an image with a width of 48 pixels, like the following:

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Wellcome_Trust_logo.svg/2000px-Wellcome_Trust_logo.svg.png" width="48">
