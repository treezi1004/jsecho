# jsecho
Javascript way of PHP echo. jsecho only works within document.

Goal was printing static contents where the function is called without writing bunch of codes within javascript.

## How to use jsecho.js:

Same as other script, uses script tag from html document. Example is index.html file in this repository.

### Example:
```html
<!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8">
      <title>JS Echo</title>
      <script src='./jsecho.js'></script>
    </head>
    <body>
      <script>
        echo("EZ!");
      </script>

      <script>
        var kimchi = "test";
        echo(1);
        echo("<p>Ya! Feel so good!</p>");
        echo("<p>" + kimchi + "</p>");
        echo("<p>It's working!</p>");
        echo(true);
        echo("<p>Unidentified object should be fixed here.</p>");
      </script>
    </body>
  </html>
```
