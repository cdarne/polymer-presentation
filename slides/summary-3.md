## Summary

Other frameworks to create Custom Elements:

Vue.js (https://github.com/karol-f/vue-custom-elementcript)
```javascript
Vue.customElement('widget-vue', {
  props: ['name'],
  data: {
    message: 'Hello'
  },
  template: '<p>{{ message }}, {{ name }}!</p>'
});
```
