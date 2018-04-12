## HTML Import

Include HTML documents in other HTML documents

An import can also include CSS, JavaScript, or anything else an .html file can contain

```html
<!-- index.html -->
<head>
  <link rel="import" href="bootstrap.html">
</head>
...

<!-- bootstrap.html -->
<link rel="stylesheet" href="bootstrap.css">
<script src="jquery.js"></script>
<template>
...
```
