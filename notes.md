# FLEXBOX

Flexbox has been around for a [while](https://css-tricks.com/old-flexbox-and-new-flexbox).

I've come across a few people that haven't really used it before (I hadn't until 18 months ago).

If you've used it plenty already: I'm about to waste your time. Sorry.

If you don't think css positioning is as interesting as I do: I'm not sorry. If anything, you should apologise to me for wasting my time with your incorrect and ridiculous opinion.

Things you need to know about flexbox:

1. it's great!

2. it should be the default choice for positioning everything.

Let's address these insighful points in a bit more detail:

## 1. Flexbox is great!

WHY?

### It isn't a grid system
![mk](https://raw.githubusercontent.com/AlasdairAlasdair/flexbox-talk/master/mk.jpg)
Grid systems are intuitive but quickly become cumbersome.

I've used [Bootstrap](http://getbootstrap.com/css/#grid), [Skeleton](http://getskeleton.com/) in the past and here's my workflow:
- Define rows.
- Start describing columns by width as twelfths.
- Modify column layout for different device sizes (xs, sm, md, lg). Combination of multiple definitions per column.
- Fix problems with clearfixes and offsetting and hiding columns on some devices.
- Cry about the layout near the boundaries of the media queries.
- Try to move on with your life.
- Fail.
- Fantasise about one day giving a lightning talk about a superior system.

Trying to reason about the layout of an app in multiple configurations is a lot to hold in your head a the best of times. Grid system does not make intelligent choices, you need to hold its hand through lots of configurations.

You naturally fall into defining Bootstrap classes in your html, which is understandable given how this is how it appears in the docs but it's not a great idea. 
If you're using vanilla css you'll have to do this because you need to combine multiple classes per element (but really you should be using sass or less or something).
This not only ties you to an implementation but pollutes html with layout concerns, blurring responsibilites.


### 2. Simplifies complexity
- It’s native css so no libraries
- Everything is just a div with a class name saying what it is, not how it should work.
- No encouragement to pollute html with layout, better separation of concerns.
- <blink>It does sensible things by default (!!!) </blink>
- Makes it easier to do mobile first (yes, you should always be doing mobile first).

## What actually is flexbox?
[This isn't helpful.](https://developer.mozilla.org/en/docs/Web/CSS/flex)

[This is a bit helpful.](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)

### Parent child relationship
![parentchild](https://raw.githubusercontent.com/AlasdairAlasdair/flexbox-talk/master/parentchild.jpg)

Parent = flex container
Child = flex item

### Recursive!
![turtles](https://raw.githubusercontent.com/AlasdairAlasdair/flexbox-talk/master/turtles.jpg)


[This is more helpful.](http://codepen.io/justd/pen/yydezN)

Scary at first but really never got lost with dev tools.

It’s equally good at big site structural things and little fiddly components.

This is biased but I find I write cleaner, less hacky css with fewer absolute / reative positioning.

### What can you do with it?
Everything.

### How do I get started?
[css flexbox tutorial](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

[flexbox froggy](http://flexboxfroggy.com/)

[solved by flexbox](https://philipwalton.github.io/solved-by-flexbox/)

### If get stuck, how do I get unstuck?
I like ~~fighting with~~ using this stuff so come and ask me.

## oh and Bootstrap 4 is going to have flex support. Although it seems to mostly be wrappers around flexbox itself, so you can easily lose some of the benefits.
