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

### It isn't a [grid system](https://www.google.co.uk/search?q=milton+keynes&espv=2&biw=697&bih=673&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjv8d6fzJ_SAhUrL8AKHZobA6UQ_AUICCgD#imgrc=2pxcLrOnPAMIFM:).
I've used Bootstrap, Skeleton etc in the past and here's my workflow:
- Define rows.
- Split rows into twelfths.
- Start describing columns by width.
- Modify column layout for different device sizes.
- Fix problems with clearfixes and offsetting and hiding columns on some devices.

Trying to reason about the layout of an app in multiple configurations is a lot to hold in your head a the best of times. Grid system does not make intelligent choices, you need to hold its hand through lots of configurations.

You naturally define Bootstrap classes in your html. 
Understandable given how this is how it appears in the docs.
This not only ties you to an implementation but pollutes html with layout concerns, blurring responsibilites.

### 2. Simplifies complexity
1. It’s native css so no libraries
2. Everything is a div
3. No encouragement to pollute html with layout, better separation of concerns
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
