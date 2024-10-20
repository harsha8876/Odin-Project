# Link and Images

***

# Link

link allows us to redirect to other HTML Pages on the web.

# Anchor element

To create a link we use anchor element `<a>` and to we must also provide a href field that contains the address of next site.

```html
<a href="https://www.theodinproject.com/about">About The Odin Project</a>
```
To open link in new tab we should add `target` attribute in the field.

```html
<a href="https://www.theodinproject.com/about" target="_blank" rel="noopener noreferrer">About The Odin Project</a>
```

`rel` describe the realtionship  between the current and the linked document.

***

***

# Absolute and relative links

## Absolute links

Links to pageson other websites on the internet are called absolute links.

## Relative links

Links to other pages within our own website are called relative links.

# Images

To display image in HTML document we can use `<img>` element.

image can be sized using `height` and `width` attributes, and `alt` can be used to name the image for code readability.

## syntax

```html
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Cat03.jpg/800px-Cat03.jpg" alt="cat" height="310" width="310">
 ```

# Code

## index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Homepage</title>
  </head>
  <body>
    <h1>Homepage</h1>
    <a href="https://www.google.com/">go to google</a><br>
  
    <a href="about.html">About</a>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Cat03.jpg/800px-Cat03.jpg" alt="cat" height="310" width="310">
  </body>
  
</html>
```

## About.html

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Odin Links and Images</title>
  </head>

  <body>
    <h1>About Page</h1>
  </body>
</html>

```
