---
id: Combining Selectors
---

SwordCSS provides simple properties to combine the CSS of certain selectors.

## Combining Classes

With `sw-class` you can copy the CSS of classes.

```css
.elem {
    sw-class: elem2;
}
.elem2 {
    width: 20px;
}
```

## Combining IDs

With `sw-id` you can copy the CSS of IDs.

```css
.elem {
    sw-id: elem2;
}
#elem2 {
    width: 20px;
}
```

## Combining With Queries

With `sw-query` you can copy the CSS of valid DOM queries.

```css
.elem {
    sw-query: #elem2 .elem3;
}
#elem2 {
    width: 20px;
}
.elem3 {
    height: 30px;
}
```