# goal of this project in the advanced HTML and CSS course

- In the previous lessons I was taught about responsive HTML and CSS techniques and media queries.
- Ideally, it said that most of the natural responsiveness is using correct semantic HTML tags and attributes. Of course using css built-in formating like grid and flexbox is also encouraged as well.

# recommendations by the project author

- He recommends to go from top to bottom, starting with the larger sections of the layouts. 
- Also notes that it doesn't matter where I start or how I do the responsiveness (such as starting with a mobile layout then using media queries to expand the layout to tablet and PC, or the other way around) as long as it is responsive.


# notes to self: 

- (10/29/2025) When I was working on the main header card of the website, I was trying to make a caption on top of the image similar to the desktop example image, but I was having trouble overlaying the text on top of the image with position: absolute, but I saw that in order to contain the position where it moves with the image itself, I needed to define a "position context" which provides html elements that are position: absolute to move relative to a parent element that isn't position: static, so I made the image container position: relative to contain the position: absolute caption. I also need to remind myself that position: absolute is relative to the parent that isn't static, and position: fixed is relative to the viewport.

- (10/29/2025) the main section is finished, but the box shadows are a little off on the cards. It should be fine for now.

- (10/30/2025) I was having trouble handling the overflow that the diagonal shape caused on the header element. The shape is a diagonal 
rectangle that spans from the top to the middle of the header to create a design. I made the rectangle long and wide, but the browser wouldn't 
ignore the overflow of the rectangle being rotated, so I made it so that the <body> tag would hide any horizontal overflow by adding the 
overflow-x: hidden property which prevented an scroll bar being added.