# Portfilio

This website is a presentation of some of the concepts we learned in our front-end nanodegree.

## Installation

Clone the GitHub repository:

```
$ git clone https://github.com/dumulong/frontend-nanodegree-mobile-portfolio.git
$ cd frontend-nanodegree-mobile-portfolio
```

## How do I run this application?

Just open the index.html file.

You will be presented with the following links:

- Build Your Own 2048!
- Website Performance Optimization
- Mobile Web Development
- Cam's Pizzeria


### Build Your Own 2048!
This page is an implementation of the famous 2048 game.

### Website Performance Optimization
Just a sample page showing a profile.

### Mobile Web Development
Another sample page for a profile, geared toward mobile development.

### Cam's Pizzeria
This is the webpage for testing perfomance.  I show a ficticious pizzaria.  You can see a long list of randomly generated pizza name and ingrdients.

You can change the size of the pizzas by using a slider.  The size selection are small, medium and large.
### Modifications related to the performance

To improve the quality of our project, we've recently made the following changes:

- index.html:
Removing Google Fonts, Loding our javascript library asynchonously when possible and finally, "inlining" the css needed for this page.

- views/js/main.js:
in the function `changePizzaSizes`, we are reading the size of the first pizza only and reapplying the new size to all pizzas.
We also now keep a global variable containing all the "moving pizzas" that we fill at the beginning.  After that we are reusing them to move then to the right based on a pre-established "phase" when the user is scrolling (see `updatePositions`). We've also reduce the amount of "moving pizzas" based on the user's window size.

- pizza.html:
We have change the size of the image our pizzeria to a more nimble size.

## License

This project is distributed under the MIT license.
