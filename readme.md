# HTMl and CSS clone of The Next Web (TNW)

Original website: https://thenextweb.com/

The objective of this exercise was to practice responsive design. My approach was to focus on making containers responsive (so I did the entire layout first), and as far as possible I made contents fit to the container (e.g. making contents size as a percentage of the container).

## How

For the responsive design specifically I used:
- Media queries
- CSS units - particularly %, vw, vh
- Display: none to hide parts of the layout on resize
- CSS grid for overall layouts, refining columns and rows as the screen resizes
- Flexbox for grid cells/navbars

## Known issues
- Although I used DevTools for things like getting specific colors, getting images and icons, I didn't use them to inspect and copy the overall layout.
- Therefore things like margins, gradients, padding, positining, and sizings are not pixel perfect!
- The reason I did this was to practice (and get errors) so that I could learn how to do the responsive design rather than copying and pasting.
- Animations - I haven't covered these at the point of developing this, so will add them in future.
- Some of the visual effects (such as the way the logo resizes when scrolling down at 768px wide) are only achievable with JS (I think!). As this is part of the HTML/CSS module I haven't integrated JS. Therefore some of the visuals (e.g. the Header) aren't quite the same as the original TNW. However, I have incorporated the relevant HTML/CSS so I am ok with this.
- If I were being picky I'd go through again and ensure that margins/padding/font sizes/colors are really consistent.
- I would also go through the style sheet and see if there are any more areas I could rationalise/avoid repetition.
- If I were doing this outside of the learning exercise I would have done more of it with JS as I think it would have been quicker - e.g. adding HTML elements via JS rather than all individually.


### ALL CONTENT MAY BE COPYRIGHT THENEXTWEB - THIS IS JUST FOR LEARNING PURPOSES.