# JS + CSS Photo Editor

A vanilla JS simple photo editor with options to blur the image change the size and color of border.

## Concepts Used

### HTML

1. Custom Variable declaration.

```html
data-sizing=""
```

2. Accessing the data object.

### CSS

1. Variable declaration and usage.

```CSS
 --blur: 0px;
 filter: blur(var(--blur));
```

### JavaScript

1. Updating CSS variables using JS

```javaScript
document.documentElement.style.setProperty();
```

2. Getting and traversing the NodeList returned from querySelector

```javaScript
const inputs = document.querySelectorAll(".controls input");

 inputs.forEach((input) =>{}
```
