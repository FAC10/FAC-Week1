#CSS

##Responsive vs. mobile-first design:

###Responsive design:

- Contents _responsively_ adjusts to the type of the user's device.
- Contents remain the same, although can be hidden depends on user's device.

A responsive site displays identical content across all devices while conforming to the container with which a user interacts with.

###Why mobile-first design:

- Designed with mobile-first in mind, focuses on content first with limited extra features.
- Supposedly 25% of US mobile web users are _mobile only_, therefore by having a mobile friendly website you're catering to a larger group of audience.

Mobile-first design should still be “responsive” in the way images, text and menus work together to fit the device they’re viewed on. In addition, they should also adapt to the user’s behaviors.

##What is BEM?

BEM stands for Block, Element, Modifier

```
/* Block component */
.btn {}

/* Element that depends upon the block */
.btn__price {}

/* Modifier that changes the style of the block */
.btn--orange {}
.btn--big {}
```

[Codepen Example](http://codepen.io/team/css-tricks/pen/226a65c8f7d64615aabd45048d1d3b6d)

[Learn more here](https://css-tricks.com/bem-101/)
