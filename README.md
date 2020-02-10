# Big-Thief-Tour-Swiss-Style

A swiss style website for Big Thief North America Tour 2020

![final poster](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/poster_final.png);

Big Thief Tour website mock up is inspired from the Swiss Style Poster design. It is for Dynamic Web Development Assignment 2 Making & Breaking the Grid - Swiss Poster Design

## Build With
- VS Code
- Githubb
- Figma

##  Author
- Zeyao Li, ITP First-year @ NYU Tisch


## Design Process

My design process always starts with creating a mood board and finding the inspiration that I really like. I went on Pintrest and Dribble to look for "Swiss Style Poster" and found some posters that I really like and thought that potentially I can use for my design. Eventually I picked the one on left bottom corner thinking that one is good for having a lot of texts on it. Some other posters that I liked did not allow me to put texts like "tour dates" on it with those layout.

![moodboard](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/moodboard.png)

Then I followed a few steps to mock the poster:

1: Find my poster source and lock down the width and height of the website that I want to create.

![source](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/01_source.png)

2. Identify each column on the poster. Column also includes the gutter in between each. So measure out the number of columns and the pixels of the gutter. 

![columns](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/02_layout_columns.png)

3. Adding on up of the column, I identified the row on the poster and measure the pixel of each with no margin. I also measure the rows that the backgrounnd texts take place of. In this step I created the whole grid system of the poster

![rows](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/03_layout_rows.png)

4. After creating the grid system, I moved on to create a style guide for the original poster. It helps me find the type of font that I need to use and the size of the font. I also picked the color pallette from the poster, with a detailed document of its layout. Writing all that down helps me to adapt the styleguide to my own design.

![og_styleguide](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/04_styleguide.png)

5. Final step. Find my own color pallette from the current Big Thief website and apply it to the poster, and make some small changes of other elements on the poster and I was good to go for development. 

![remix](https://github.com/zeyaoli/Big-Thief-Tour-Swiss-Style/blob/master/design/05_remix.png)


## Development

I like writing down all the text that I need first on a plain HTML page. It helps me to structure the whole website and makes my work later way easier. I used main tag to distinguish the poster from its background, then add a container div to place all content and set its margin. I manually created each tour date, however, in mind, I think using React will be a better way to do (or put all the info into a json file and update it with javascript). Then I created the background text and made it not selectable so it blends it into the ground. The triangle mask is a tricky div border. I set the div width and height to 0 and make the border super big for one side and another side to transparent. Then it became a triangle. 

One of the example of [triangle with CSS.](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_shapes_triangle-up)


