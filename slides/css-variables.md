## CSS Variables

Variables defined that you define and that contain specific values to be reused throughout a document

```css
element {
  --primary-color: blue;
}

element {
  color: var(--primary-color, red);
}
```

And you can change with JS too!

```javascript
document.documentElement.style.
  setProperty('--primary-color', 'green');
```
