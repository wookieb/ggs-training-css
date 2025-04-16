---
layout: fact
---
# Responsive Web Design (RWD)

---

# Mobile first

Simple: Always start with styles for smallest possible screen that needs to be supported (mobile, table, desktop).

```css
/* full width column on mobile */
.layout {
    width: 100%;
    margin-left: 16px;
    margin-right: 16px;
}

/* 2 columns on tablet */
@media (min-width: 768px) {
    display: grid;
    grid-template-columns: 1fr 1fr;
}

/* 4 columns on desktop */
@media (min-width: 1024px) {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
}
```

--- 

# Why mobile first?

* To keep it consistent and intuitive
* Mobile styles looks OK on desktop but desktop styles on mobile aren't
* Overriding desktop styles to mobile is usually harder
  * try to revert css styles from previous slides for mobile only
