## Shadow DOM

Isolated DOM and scoped styles

Removes the brittleness of building web apps

~~`!important` all the things!~~

```javascript
const header = document.createElement('header');
const shadowRoot = header.attachShadow({mode: 'open'});
// Could also use appendChild()
shadowRoot.innerHTML = '<h1>Hello Shadow DOM</h1>';
// header.shadowRoot === shadowRoot
// shadowRoot.host === header
```
