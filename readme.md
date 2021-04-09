# HTML and CSS clone of The Next Web (TNW)

## About

This is a clone of [The Next Web](https://thenextweb.com/)'s home page. The objective of this exercise was to practice responsive design. My approach was to focus on making containers responsive (so I did the entire layout first without content), and then as far as possible I made content fit responsively to its container (e.g. making contents size as a percentage of the container).

### Live Demo

[GitHub Pages](https://kath-ldn.github.io/thenextweb-clone/)

### Built with

HTML & CSS

For the responsive design specifically I used:
- Media queries
- CSS units - particularly %, vw, vh
- Display: none to hide parts of the layout on resize
- CSS grid for overall layouts, refining columns and rows as the screen resizes
- Flexbox for grid cells/navbars

## Prerequisites & Installation

No special requirements.

## Roadmap

None planned - this was a learning project. I may update in future in line with the below.

### Known Issues

* Although I used Dev Tools for getting specific colors, images and icons, I didn't use them to inspect and copy the overall layout. Therefore things like margins, gradients, padding, positining, and sizings are not pixel perfect! The reason I did this was to practice (and get errors) so that I could learn how to do the responsive design rather than copying and pasting.
* I hadn't covered animations in the HTML/CSS module, and haven't added hovers etc. Therefore the page doesn't feel as interactive as the original. I may update this in future, but have other examples where I have done this effectively.
* Some of the visual effects (such as the way the logo resizes when scrolling down at 768px wide) are only achievable with JS (I think!). As this is part of the HTML/CSS module I haven't integrated JS. If I were doing this outside of the learning exercise I would have done more of it with JS as I think it would have been more efficient - e.g. adding HTML elements via JS rather than all individually.
* The CSS could likely be rationalised to reduce repetition.

## Acknowledgements

* Google Fonts
* CSS-Tricks
* GitHub Pages
* MeyerWeb (reset sheet)

ALL CONTENT MAY BE COPYRIGHT THENEXTWEB - THIS IS JUST FOR MY LEARNING PURPOSES.