gulp-css-img-cachebust
======================

Appends cachebust query parameters to image URLs within CSS files.

Before:

```css
// BEFORE: style.css
body {
  background: url('../img/darudesandstorm.jpg');
}
```

After:

```css
// AFTER: style.css
body {
  background: url('../img/darudesandstorm.jpg?123456789');
}
```

Amazing.
