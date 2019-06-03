# Week 1

#### Communication Accts
- Slack
    - channels
    - direct messages
    - edit/delete messages
- professional Email Address

#### fs basics
- intro folders
    - Drive folders
    - User folder
    - Important Sub Folders (Desktop, Documents, Downloads)

#### CLI Basics
- CRUD file system (fs)
    - what does CRUD stand for
- navigate fs
- CRUD fs
    - i.e. `touch echo rm pwd cd ls tab mkdir rmdir rm -rf cat nano`

#### Editor (VS Code)
- fs manipulation with VS Code
- Folder/file naming conventions
- VS Code Specifics
    - Command Palette
    - Keyboard Shortcuts cheat sheet

## Resources
- [Learn enough command line to be dangerous](https://www.learnenough.com/command-line-tutorial/basics#sec-our_first_command)
- [Explain Shell](https://explainshell.com/)

## Exercise
*Complete using CLI*
1. Make a directory on your Desktop folder and name it `cbc6`.
2. Navigate in that folder and create another folder and name it `first_project`.
2. In that folder create a file called something like `hey-there.txt`
3. Open that file and add some text

#### Git Basics
- setup Github acct
- diff b/w GitHub & git
- basic Git workflows
    - `clone -> add -> commit -> push/pull`
    - `status`

## Resources
- [Basic Git Workflow Tutorial](http://rogerdudler.github.io/git-guide/)
- [Basic Git cheat sheet](http://rogerdudler.github.io/git-guide/)

## Exercise
1. Create a new repository on Github.
2. CLI: navigate to the folder **inside** your `cbc-6` folder.
3. CLI: `git add .`
4. CLI: `git commit -m "[...]"`
    - Write a message in the `[...]`
5. Copy from Github the line that says `git remote add [...]`
6. CLI: Paste what you copied and press enter
7. CLI: `git push -u origin master`
8. Refresh Github to see if it worked.

#### Markdown Basics
- importance for jobs
- headings `# - ######`
- bold
- italics
- links/images
- lists (ordered/unorder)
- task lists
- code blocks
- emojis
- table

## Resources
- [Github Flavored Markdown](https://guides.github.com/features/mastering-markdown/)

## Exercise
1. Add a `readme.md` file to your project
2. Use 6 of the above concepts to explain your text file.

#### HTML Basic Terms
- elements
- tags
- attributes
- HTML document structure
    - `html head body`
- self closing elements

#### CSS Basic Terms
- selectors
- properties
- values
- type selectors
- class selectors
- id selectors
- additional selectors
    - psuedo-selectors
    - children

#### CSS Basic Concepts
- Referencing CSS
- CSS Resets
- Cross Browser Compatibility

#### HTML Basic Concepts
- block vs. inline (div vs span)
- comments
- headings
- bold/italics
- HTML5
    - `header, nav, article, section, footer, aside`

## Resources
- [First Web Page](https://learn.shayhowe.com/html-css/building-your-first-web-page/)
- [HTML/CSS Basics](https://learn.shayhowe.com/html-css/getting-to-know-html/)
- 

## Exercise
1. Make a web page.
2. Add html, head, and body tags
3. In the body add a header, article, section, footer
4. In each of those add some divs, paragraphs, and spans of text.
5. Apply classes and ids to html elements.

#### HTML Basic Concepts II
- creating hyper links
    - relative vs absolute path
    - wrapping elements with anchors
    - link to new window
    - link to part of same page
- mailto
    - special character encoding
    - URL encoding

#### CSS Basic Concepts II
- Calculating Specificity
- combing Selectors
- Layering styles with multiple classes

#### CSS Colors
- rgb
- hsl
- keyword
- hexadecimal
- rgba
- hsla

#### CSS Lengths
- Absolute Lengths
    - pixels
- Relative Lengths
    - percentages
    - em/rem 

#### CSS Box Model
- display
    - block
    - inline
    - inline-block
    - none
- width/height
- margin
- padding
- borders
    - border-width
    - border-style
    - border-color
    - border-radius
    - _box-sizing_
        - vendor prefixing
            - -moz- : Firefox
            - -ms- : IE
            - -webkit- : Chrome/Safari

## Resources
- [Hyperlink Basics](https://learn.shayhowe.com/html-css/getting-to-know-html/)
- [CSS Basics](https://learn.shayhowe.com/html-css/getting-to-know-css/)
- [CSS Box Model](https://learn.shayhowe.com/html-css/opening-the-box-model/)

## Exercise
1. add an anchor tag that links to your favorite website.
2. wrap a div of text that links to your text document you created.
3. use an anchor to link to an id somewhere else on the page.
4. put a style tag in the head of your html and color an element using rgb, hex color, and a key word.
5. set the height/width, padding, border, and margin for some of your elements.
6. for an element that has a child:
    - put a px width/height on the parent.
    - on the child put a percentage width/height

#### HTML/CSS Developer Tools Basics
- how to open
- elements tab
    - html
    - styles
    - box-model

#### CSS Positioning
- floats
- clearing
- containing
    - `:before` and `after`
- inline-block
- relative
- absolute
- fixed

## Resources
- [Developer Tool Basics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools)
- [CSS Positioning](https://learn.shayhowe.com/html-css/positioning-content/)

## Exercise
1. add an html `aside` element and put it above your `section`
2. float the `aside` to the side of the section
3. use `inline-block` to make a 2 column layout (2 elements side by side)

#### CSS Typography
- typeface vs. font
- color
- font properties
    - font-family
    - font-size
    - font-style
    - font-variant
    - font-weight
- line-height
- text properties
    - text-align
    - text-decoration
    - text-indent
    - text-shadow
    - text-transform
- web safe fonts
- web fonts
- citations & quotes

#### CSS backgrounds & gradients
- background-color
- background-image
    - background-repeat
    - background-position
- designing gradient backgrounds
    - linear background gradient
    - radial background gradient
- background-size
    - cover
    - contain

## Resources
- [Typography](https://learn.shayhowe.com/html-css/working-with-typography/)
- [Backgrounds and Gradients](https://learn.shayhowe.com/html-css/setting-backgrounds-and-gradients/)

## Exercise
1. set your paragraphs to be a web safe font.
2. load a font from Google that you like and set that for your anchor tags.
3. mess with font/text properties
4. set your divs to a certain background color.
5. load a background image to something
6. set a background-gradient to something

#### HTML lists
- unordered lists
- ordered lists
    - start
    - reversed
    - value
- description lists
- nesting lists
- list item styling
    - list-style-type

#### HTML/CSS adding media
- images
    - supported image formats (gif, jpg, png) 
    - background-image vs img tag   
- audio
- video
- inline frames
- figure
- caption

#### HTML form
- form tag
    - `method`
    - `action`
- input types
    - `text`      
    - `color`
    - `email`
    - `range`
    - `time`
    - `date`
    - `month`
    - `search`
    - `url`
    - `datetime`
    - `number`
    - `tel`
    - `week`
- textarea
- `name`
- multiple choice
    - type
        - `radio`
        - `checkbox`
- drop down list
    - `select > option`
- submit button
- hidden input
- form organization
    - label
        - `for`
    - fieldset
        - legend
- placeholder

#### HTML tables
- table tag
- table row
- table data
- table head
- table structure
    - caption tag
    - table head
    - table body
    - table footer
- combining multiple cells
    - `scope`
    - `colspan`
    - `rowspan`
- table borders
    - border-collapse
    - border-spacing
- aligning text
    - text-align
    - vertical-align

## Resources
- [Lists](https://learn.shayhowe.com/html-css/creating-lists/)
- [Media](https://learn.shayhowe.com/html-css/adding-media/)
- [Forms](https://learn.shayhowe.com/html-css/building-forms/)
- [Tables](https://learn.shayhowe.com/html-css/organizing-data-with-tables/)

## Exercise
1. add an unordered list of at least 3 items
2. add an ordered list of at least 3 items
3. create a table
4. nest the unordered list in a cell
5. nest the ordered list in another cell
6. give the table a heading and footer 
7. add an image tag
8. give it a caption
9. make a form with some different types of inputs