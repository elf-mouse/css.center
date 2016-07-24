# Horizontally

## Is it inline or inline-* elements (like text or links)?

```css
.center-children {
  text-align: center;
}
```

This will work for `inline`, `inline-block`, `inline-table`, `inline-flex`, etc.

## Is it a block level element?

```css
.center-me {
  margin: 0 auto;
}
```

This will work no matter what the width of the block level element you're centering, or the parent.

> Note that you can't float an element to the center.

## Is there more than one block level element?

```css
.inline-block-center {
  text-align: center;
}
.inline-block-center div {
  display: inline-block;
  text-align: left;
}

.flex-center {
  display: flex;
  justify-content: center;
}
```
