# HTML
1. [Basic code](#basic-code)
2. [dir="ltr"](#dirltr)
3. [script src="app.js" or "folderName/app.js"](#script-srcappjs-or-foldernameappjs)

### Basic code

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <script src="app.js" charset="utf-8"></script>
    <link rel="stylesheet" href="style.css"></link>
    <title> Title </title>
  </head>
  <body>
  </body>
</html>
```

### dir="ltr"

- [Reference:HTML lang and dir attributes](https://www.w3resource.com/html/attributes/HTML-lang-and-dir-attributes.php)

1. dir attribute of HTML sets the direction of the text within an element in HTML document.
2. The value of the dir attribute is either ltr (i.e. left to right) or rtl (i.e. right to left).

```
abcdefg <= ltr
                                                                                                           rtl => abcdefg
```

### script src="app.js" or "folderName/app.js"

1. app.js and index.html at the same location => `<script src="app.js" carset="utf-8"></script>`
2. folderName/app.js and index.html (different location) => `<script src="folderName/app.js" carset="utf-8"></script>`

