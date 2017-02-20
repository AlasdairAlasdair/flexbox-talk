# FLEXBOX

Flexbox has been around for a while, but I've come across a few people that haven't really used it before.

Hopefully I'm not wasting your time.

Things I think about flexbox:
1. it's great!
2. it should be the default choice when you're positioning something.

## Why is flexbox so great?

### 1. It isn't a grid system.
I've used Bootstrap, Skeleton in the past and here's my workflow:
 - Define rows.
- Split them into twelfths.
- Start defining columns by width.
- Modify column layout for different device sizes.
- Fix problems with clearfixes and offsetting and hiding columns on some devices.

Trying to reason about the layout of an app in multiple configurations is a lot to hold in your head.

You naturally define Bootstrap classes in your html. 
Understandable given how this is how it appears in the docs.
Ties you to an implementation.
Pollutes html with layout concerns, blurring responsibilites.

### 2. Simplifies complexity
1. It’s native css so no libraries
2. Everything is a div
3. Better separation of concerns
4. It does sensible things by default (!!!)
5. Makes it easier to do mobile first (yes, you should always be doing mobile first).

## What actually is flexbox?
[This isn't helpful.](https://developer.mozilla.org/en/docs/Web/CSS/flex)

[This is a bit helpful.](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)

[This is more helpful.](http://codepen.io/justd/pen/yydezN)


### What can you do with it?
Everything.

### How do I get started?
[css flexbox tutorial](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
[flexbox froggy](http://flexboxfroggy.com/)
[solved by flexbox](https://philipwalton.github.io/solved-by-flexbox/)
