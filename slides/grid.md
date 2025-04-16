---
layout: fact
---
# CSS Grid

---

# What is CSS Grid

Allows to display elements in a grid layout consisting of rows and columns. 
Similar to tables but more flexible and powerful.

Only few of possible options:
* [gap between elements](https://jsfiddle.net/rx13wzp2/2/)
* making all elements the same size
* auto-fitting size [based on available space]((https://gridbyexample.com/examples/example37/))
* [areas to move elements around](https://gridbyexample.com/examples/example11/) 


---
layout: statement
---
# Examples and patterns

It is very complex subject and requires practice to master.

https://gridbyexample.com/

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout


---
layout: statement
---
# Grid systems

Bootstrap's Flexbox grid system != Bootstrap CSS grid 

---

# Bootstrap Flexbox Grid system

* Uses flexbox to simulate grid in [one dimension](https://getbootstrap.com/docs/5.3/layout/grid/) (columns - multiple lines still allowed).
* Supports [gutters](https://getbootstrap.com/docs/5.3/layout/gutters/) 
  * gaps between column content and edges of the column
* Supports [responsive breakpoints](https://getbootstrap.com/docs/5.3/layout/breakpoints/)
* Shortcut to expose grid-like capabilities as utility classes with RWD


---
layout: statement
---

# When to use Bootstrap's flexbox grid systems

Probably never - Use [CSS grid system](https://getbootstrap.com/docs/5.3/layout/css-grid/) instead

--- 

# When to use Bootstrap's CSS Grid system

* For big layouts (sidebars, main content)
* Using many classes becomes unreadable therefore fallback to css grid
* Don't bother with components requiring [pixel perfect requirements](https://getbootstrap.com/docs/5.3/forms/input-group/) or if can be solved simpler with pure css

---

# How about Flex?

Still very useful for one-dimensional layouts (rows or columns) but not for two-dimensional layouts (rows and columns).
