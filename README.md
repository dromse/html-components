# HTML-Components

My list of html components to reuse for landing pages, ecommerce websites etc.  
Every directory must have README.md which contains screenshots, animations, instructions of how to start work with components.

## Defenitions:

### Base stack

- base.html - use only html/css/js stack
- scss.html - use html/scss/js stack
- tailwind.html - use html/tailwind/js stack

```html
<!-- styles, put inside .{css, scss} file -->
<style></style>

<!-- html component, put inside html -->
<div></div>

<!-- js, put inside .{js,ts} file -->
<script></script>
```

### React stack 

Also there can be react-\*.tsx, which contains reusable component for inserting in react application.

- react-base.tsx - use only tsx,css,ts
- react-scss.tsx - use only tsx,scss,ts
- react-tailwind.tsx - use only tsx,tailwind,ts
- react-styled.tsx - use only tsx,styled-components,ts

```js
// styles, put inside .{css, scss} or .module.css file
<style></style>;

// jsx component, put inside jsx
function Component() {
  return <div></div>;
}
```
