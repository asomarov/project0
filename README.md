My website is the first lesson of my online Excel course. The theme is reference types.
The website contains four webpages:
1. Index.html
2. R1C1options.html
3. ExcelCourseLesson1_1.html
4. ExcelCourseLesson1_2.html

Then there are two CSS files:
1. style.css
2. style_R1C1.css

I used also SASS file (style.scss), and it generated style.css.map file.
All webpages have a link to a CSS file, which defines their style. The second webpage has its own CSS file (style_R1C1.css).
Other webpages have another CSS file (style.css). These webpages use class selectors
like "text", "section". I use one id to 'ftable' to have a unique style for the contents section.
When you hover over h2 and h3 headings the color of these headings will change to lightblue (this color is defined by a sass variable).
In scss file I use two variables ($colorhover and $divbackcol). $divbackcol defines background color of a div.
This div has a nesting with p and ol. There is also an inheritance feature for the class "text" and "section" from t.
Tables have their own style. Selecting a text will result in another color of the text and of the selection. 
The third webpage has a link to Bootstrap CSS file, as it uses one Bootstrap feature collapse (more on this below).

The first 'index.html' has a contents section,
where you can navigate through the website. It continues with
the first reference type (Relative).
Inside the Relative section there is a link to R1C1options.html
(where I explain how to switch to R1C1 reference style via four images).
The second webpage (i.e. R1C1options.html) uses its own CSS file, where I use grid structure
of two columns, which change to a flex structure when the width a screen is below 700px (I am using here @media).
As I said earlier the third webpage uses Bootstrap. I use Bootstrap's feature 'Collapse'
to show an image of F4 button by pressing on it (Sometimes some people ask me how to find this button on a keyboard).
