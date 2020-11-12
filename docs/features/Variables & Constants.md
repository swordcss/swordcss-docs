---
id: Variables & Constants
---

SwordCSS allows variables and constants which can be used with their appropriate `@` rules.

```css
@sw-constants {
    width: 20px;
}
@sw-variables {
    height: 30px;
}
.elem {
    width: width;
    height: height;
}
```

## Difference Between Constants and Variables

Constants are as it is in the name, constant. They can never change because all references to those constants will be replaced at compile time.

On the other hand, variables become CSS custom properties, which can be changed at runtime by Javascript.