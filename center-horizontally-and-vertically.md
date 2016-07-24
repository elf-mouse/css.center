# Both Horizontally and Vertically

## Is the element of fixed width and height?

```css
.parent {
  position: relative;
}

.child {
  width: 300px;
  height: 100px;
  padding: 20px;

  position: absolute;
  top: 50%;
  left: 50%;

  margin: -70px 0 0 -170px;
}
```

## Is the element of unknown width and height?

```css
.parent {
  position: relative;
}
.child {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

## Can you use flexbox?

```css
.parent {
  display: flex;
  justify-content: center;
  align-items: center;
}
```
