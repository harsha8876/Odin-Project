***

# Paragraph

Directly placing text in the body won't create paragraph it will just display the whole paragraph in one line.

To create paragraph, we use `<p>` tag.

```html
    <p>hello</p>
```

# Heading

There are total 6 level of heading `<h1>` to `<h6>`, with `<h1>` being the biggest and `<h6>` being smallest.

```html
<h1>This is a heading 1</h1>
<h2>This is a heading 2</h2>
<h3>This is a heading 3</h3>
<h4>This is a heading 4</h4>
<h5>This is a heading 5</h5>
<h6>This is a heading 6</h6>
```
# Text Formatting

## Strong
The `<strong>` element makes text bold.

## em
The `<em>` element italicizes text and places emphasis on it.

# Nesting and Indentation

When we nest elements within other elements, we create a parent and child relationship between them. The nested elements are the children and the element they are nested within is the parent.

## Example

```html
<html>
  <head>
  </head>
  <body>
    <p>Lorem ipsum dolor sit amet.</p>
  </body>
 </html>
 ```

in the above example body element is the parent and the paragraph is the child

# Comments

Comments makes the code more readable that helps the other future developers. Comments are not shown in the browser.

```html
<!-- I am an html comment -->
 ```


## List

there are two type of list in HTML 1.ordered and 2.unordered

## unordered

When the order of items doesn't matter we use unordered list.

created using `<ul>` and each item within the list is created using `<li>`.

## Ordered

If list have a define ordered like a step by step instruction we use ordered list.

reated using `<Ol>` and each item within the list is created using `<li>`.

 # Code Example

 ```html
 <html>
    <head>
        <title>Demo</title>
    </head>
    <body>
        <!--Main heading-->
        <h1>welcome</h1>
        <!--Sub heading-->
        <h2>Introduction</h2>
        <p><em>Lorem</em> ipsum dolor sit amet consectetur <strong>adipisicing</strong> elit.</p>
        <p>Maxime necessitatibus sit cupiditate corrupti dolore inventore debitis. Laborum molestias dolor hic quis perferendis voluptas, earum, voluptate quam aut, alias vel. Blanditiis!</p>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
        <ol>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ol>
    </body>
</html>
```

***
