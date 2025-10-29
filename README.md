# goal of this project in the advanced HTML and CSS course

- In the previous lessons I was taught about responsive HTML and CSS techniques and media queries.
- Ideally, it said that most of the natural responsiveness is using correct semantic HTML tags and attributes. Of course using css built-in formating like grid and flexbox is also encouraged as well.

# recommendations by the project author

- He recommends to go from top to bottom, starting with the larger sections of the layouts. 
- Also notes that it doesn't matter where I start or how I do the responsiveness (such as starting with a mobile layout then using media queries to expand the layout to tablet and PC, or the other way around) as long as it is responsive.


# notes to self: 

- (10/29/2025) When I was working on the main header card of the website, I was trying to make a caption on top of the image similar to the desktop example image, but I was having trouble overlaying the text on top of the image with position: absolute, but I saw that in order to contain the position where it moves with the image itself, I needed to define a "position context" which provides html elements that are position: absolute to move relative to a parent element that isn't position: static, so I made the image container position: relative to contain the position: absolute caption. I also need to remind myself that position: absolute is relative to the parent that isn't static, and position: fixed is relative to the viewport.