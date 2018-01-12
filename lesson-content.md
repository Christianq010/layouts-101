## Flexbox

[![Mockup Preview](https://preview.ibb.co/gJM6hw/nike_mockup.jpg)](https://preview.ibb.co/gJM6hw/nike_mockup.jpg)


### The Basics
* When you turn a `div` to flexbox (`display: flex`) , all children in the `div` are `flex items`.
* Spacing around `flex items`:

```css

.flexbox {
    /* Equal space around each child */
    justify-content: space-around;
    /* Equal space between each child */
    justify-content: space-between;
    /* center all items to height of parent*/
    align-items: center;
}

.blue-fixed-item {
    /* grow, shrink , fixed at 25% */
    flex: 0 0 25%;
}

.purple-fixed-item {
    flex-grow: 1;
}

/* Allow items to go to a new line with flex wrap */
.flexbox {
    flex-wrap: wrap;
}


```

