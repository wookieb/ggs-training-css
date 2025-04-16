---
layout: fact
---

# CSS Specificity

---

# CSS Specificity

Is the algorithm that the browser uses to determine which CSS rule to apply when multiple rules could apply to the same element.

<a href="https://jsfiddle.net/5c6grL4u/1/">Code sandbox (1)</a>

<a href="https://jsfiddle.net/5c6grL4u/2/">Code sandbox (2)</a>


 
---

# CSS Specificity

Specificity is calculated based on the types of selectors used in a rule. Selector with highest score wins.


Consist of values in 3 columns (from the most important one)
- ID Column - How many times ID selector ('#selector') is used
- Class Column - How many times class selector ('.selector'), attribute selector ('[attr]') and pseudo-class selector (':pseudo-class') is used.
- Element Column - How many times element selector ('element') and pseudo-element selector ('::before') is used


---
layout: statement
---

# Demo

https://specificity.keegan.st/


--- 

# CSS Specificity in PMG

Use class, attribute, and pseudo class selectors as much as possible for general styling. 
Lower the specificity the better.
```css
.button {
    font-size: 16px;
}
```

Use ID selectors for specific styling - for example overriding styles for certain component
```css
#widget-it-container .button {
    font-size: 20px;
}
```

---
# CSS Specificity hack

```css

.button {
    color: red;
}
/* Higher specificity */
.button.button {
    color: blue;
}
```

Avoid using `!important` as it is usually not necesssary.
