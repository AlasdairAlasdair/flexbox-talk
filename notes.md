# What is flexbox?

Flexbox has been around for a [while](https://css-tricks.com/old-flexbox-and-new-flexbox).

I've come across a few people that haven't really used it before (I hadn't until a couple of years ago).

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.
If you've used it plenty and you're already a fan: I'm about to waste your time. Sorry.


.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.
If you don't think css positioning is as interesting as I do: I'm not sorry. If anything, you should apologise to me for wasting my time with your incorrect and ridiculous opinion.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.
# What is flexbox?
It's great!

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.         
# What is flexbox?

It should be the default choice for positioning everything with CSS.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
# What is flexbox?
![mk](https://raw.githubusercontent.com/AlasdairAlasdair/flexbox-talk/master/mk.jpg)
## It isn't a grid system.

Grid systems are intuitive but quickly become cumbersome.

I've used [Bootstrap](http://getbootstrap.com/css/#grid), [Skeleton](http://getskeleton.com/) in the past and here's my workflow:
- Define rows.
- Start describing columns by width as twelfths.
- Modify column layout for different device sizes (xs, sm, md, lg). Combination of multiple definitions per column.
- Fix problems on some devices.
    - clearfixes
    - offset columns
    - hide columns
- Cry about the layout near the boundaries of the media queries.
- Try to move on with your life.
- Fail.
- Fantasise about one day giving a lightning talk about a superior system.

Trying to reason about the layout of an app is a lot to hold in your head at the best of times. Trying to reason about the layout of an app in multiple configurations is really hard.

Grid systems don't make intelligent choices, you frequently need to hold its hand to create a sensible layout for each device size.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
# What is flexbox?
# :) It’s native css so no libraries

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
# O: Everything is just a div with a class name saying what it is, not how it should work.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
# :O It does sensible things by default. 

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
# Ö You can centre things easily.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
## What is flexbox?
[This isn't helpful.](https://developer.mozilla.org/en/docs/Web/CSS/flex)

[This is a bit helpful.](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)

### Parent child relationship
![parentchild](https://raw.githubusercontent.com/AlasdairAlasdair/flexbox-talk/master/parentchild.jpg)

Parent = flex container

Child = flex item

### Recursion
![turtles](https://raw.githubusercontent.com/AlasdairAlasdair/flexbox-talk/master/turtles.jpg)

[This is more helpful.](http://codepen.io/justd/pen/yydezN)

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
## What is flexbox?
It's versatile. It’s equally good at big site structural things and little fiddly components.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
## What is flexbox?
It's a way of simplifying complexity.
It makes me write cleaner, simpler, less hacky css. 
- Fewer elements using absolute / relative positioning.
- Fewer hardcoded values.
- Easier to make pages mobile friendly !important;

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
### You won't want to use Bootstrap
When using Bootstrap you naturally fall into defining Bootstrap classes in your html, which is understandable given how this is how it appears in the docs but it's not a great idea. 

If you're using vanilla css you'll have to do this because you need to combine multiple classes per element (but really you should be using sass or less or something).

This not only ties you to an implementation but pollutes html with layout concerns, blurring responsibilites.

You'll never need to understand (misunderstand) floats.

(Bootstrap 4 is going to have flex support. Although it seems to mostly be wrappers around flexbox itself, so you can easily lose some of the benefits)

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
### How do I get started?
[css flexbox tutorial](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

[flexbox froggy](http://flexboxfroggy.com/)

[solved by flexbox](https://philipwalton.github.io/solved-by-flexbox/)

I like using this stuff so I'm happy to help out.

.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
.  
# ?