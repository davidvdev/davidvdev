# Setting an Emoji as your Favicon

Here's a simple code snippet you can use to set an emoji as your site's favicon.

Create a file called `favicon.svg` with the following code:
```js
<!-- favicon.svg -->
<svg xmlns="http://www.w3.org/2000/svg">
  <text y="32" font-size="32">🤠</text>
</svg>
```

Replace 🤠 with your prefered emoji and link the file in your HTML as a child of `<head>`. It may look something like this:

```html
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/src/favicon.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Cool App</title>
  </head>
```