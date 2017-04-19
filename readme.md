# Static Comp Challenge #3

## Requirements  
The objective of this project was to take the web page layout for a hiring manager's management system and recreate it as a responsive layout for screens between 320px and 2000px in width.  Minor customization in terms of design is allowed, as well as content theme if desired.

### Design Approach  
The design approach was to recreate the comp as faithfully as possible save for the flavor text in the various headings, tables, paragraphs, etc.  The theme chosen was inspired from the book Shōgun, which is great and should be read by everyone.

### Technical Approach  
The basic layout contains 2 main containing elements. 1. The sidebar navigation 2. The rest of the page.  Display:flex is then applied to the body.  This allows the two major sections to be controlled and stay together at all screen widths. The sidebar navigation is given a fixed width, while the main content section is given flex grow so that it always takes up the rest of the page.  This same technique is applied to the search bar and various other elements that are required to fill extra space next to neighboring fixed width elements. As the page shrinks elements begin to stack on top of each other, and buttons disappear that will have to be accessed through other display more type buttons.

### Difficulties
 * There weren't too many technical difficulties as the layout approach was very effective.  Keeping the CSS to a minimum and well organized is probably the biggest challenge.  It is organized in order of element appearance, which may not be the best approach.  
 * I possibly should have put divs within all the buttons in order to get the icons to fit better.  I used several pre-made sprites which was great but the spacing on the sprites was very tight and caused some headaches because borders were then used to cover up the preceding or following images.

#### Original Design composition
![Original Design](https://github.com/Ggoering/gg-comp-challenge-3/blob/master/assets/static-comp-challenge-3.jpg)

#### Link to hosted webpage
https://ggoering.github.io/gg-comp-challenge-3/
