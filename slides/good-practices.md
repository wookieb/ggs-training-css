--- 
layout: fact
---

# Good practices

---

# Button vs link

* Link `<a>`
  * navigating to other pages
  * opening in a new tab
* Button `<button>`
  * performing action at a page that does not require navigation
  * submitting a form


--- 

# Button vs link

Don't do it
```html
<a href="javascript:void(0)">Action</a>
```

Do this instead
```html
<button>Action</button>
```

---

# Devtools is your friend

* Modifying styles in browser
* Use computed tab
* Enforce element state
