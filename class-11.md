## [Back to Homepage](https://pengchen11.github.io/reading-notes/readme.md)

## 1. CSS Background Image
The background-image property specifies an image to use as the background of an element.  
By default, the image is repeated so it covers the entire element.
   ### Example
The background image for a page can be set like this: 
```
body {
  background-image: url("paper.gif");
}
```
## 2. CSS background-repeat
By default, the background-image property repeats an image both horizontally and vertically.

Some images should be repeated only horizontally or vertically, or they will look strange, like this:
```
body {
  background-image: url("gradient_bg.png");
}
```

## 3. CSS background-position
The background-position property is used to specify the position of the background image.
### Example
Position the background image in the top-right corner: 
```
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}
```

## 4. CSS background-attachment
The background-attachment property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page):

Example
Specify that the background image should be fixed:
```
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```
