## Custom Elements

Create new HTML tags

Custom elements teach the browser new tricks while preserving the benefits of HTML

Define it:
```javascript
// Define element class/behaviour
class AppDrawer extends HTMLElement {...}

// Register the custom element
window.customElements.define('app-drawer', AppDrawer);
```
