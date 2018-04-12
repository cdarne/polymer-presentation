## Custom Elements

Use it:
```html
<app-drawer></app-drawer>
```
Or
```javascript
// Create with javascript
var newDrawer = document.createElement('app-drawer');

// Add it to the page
document.body.appendChild(newDrawer);

// Attach event listeners
document.querySelector('app-drawer').
  addEventListener('open', function() {...});
```
