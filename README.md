# bottom footer css
By using flexbox

```html
<html lang="en">
  <head>
    <title>Minimal bottom footer css</title>
    <style>
      .app {
        min-height: 100vh;
        display: flex;
        flex-direction: column;
      } 
      .app-content {
        flex: 1;
      }
    </style>
  </head>
  <body class="app">
    <nav>navbar is here</nav>
    <div class="app-content">
      main site content is here
    </div>
    <footer>footer is here</footer>
  </body>
</html>
```
