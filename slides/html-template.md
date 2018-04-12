## HTML Template

Declare fragments of markup which are parsed as HTML,
go unused at page load,
but can be instantiated later on at runtime.

```html
<template id="flower">
  <h2>Flower</h2>
  <img src="img_white_flower.jpg">
</template>
```
Then
```javascript
function showContent() {
  var template = document.getElementById("flower");
  var clone = template.content.cloneNode(true);
  document.body.appendChild(clone);
}
```

Notes:
- A standard DOM-based approach for client-side templating
- Holds hidden content
- Replaces the `<script type="text/template">` technique
