<title> Get Started with bootstrap</title>

[Table of Content](../README.md)

## Install

1. Can use CDN or download the JS and CSS to use Bootstrap without network connection.

2. Need jQuery and popper to support it if running bootstrap locally without network.
   html setup example:

   ```html
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <link rel="stylesheet" href="css/bootstrap.min.css">
        <title>Bootstrap</title>
      </head>
      <body>
      <div class="container">
      </div><!-- content container -->

      <script src="js/jquery.slim.min.js"></script> <!-- The sequence of rendering these files really matters -->
      <script src="js/popper.min.js"></script>
      <script src="js/bootstrap.min.js"></script>
      </body>
      </html>
    ```

## basic layout

1. The ```<link rel="stylesheet" href="css/bootstrap.min.css">``` applies basic style to the web page and make it looks great, adaptive to different screen sizes.

2. can use ```class = display-(1-4)``` to make the title larger than regular `<h>`tags.

## Topographic utilities

1. Horizontal alignment

    - `text-justify`

    - `text-(XX)-POS`.
      - XX: sm, md, lg, xl
      - POS: lfet, center, right

2. Line height alignment

    - `align-SID`
      - SID: baseline, top, middle, bottom, text-bottom, text-top, right

3. Text-captialization

    - `text-TYP`
        - TYP: lowercase, uppercase, captialize, nomospace

4. Text-styles
    - `font-STYL`
        - STYL: italic, weight-normal, `weight-light(r)`, `weight-bold(r)`

5. Text-modifier
    - `text-decoration-none`
    - `text-reset` this one removes everything of that link text, leave it matching the parent settings.

6. Flow
    - `test-FLOW`
        FLOW: wrap, nowarp, break, turncate

## lists and blockquote

1. lists
    - `list-unstyled` removes the dots infornt of `<li>`
    - inline lists
        - `list-inline` on UL
        - `list-inline-item` on each LI

2. blockquotes
    - `blockquote` makes the text bigger
    - `blockquote-footer` makes the footer gray and looks good

## Using colors

1. text color
    - `text-COLOR` here this COLOR is color group
        - COLOR: primary, secondary, danger, etc.

2. background color
    - `bg-COLOR` same deal
        - COLOR: primary,, secondary, danger, etc.

## work with img

1. basic responsive images
    - `img-fluid`
        - responsive images
    - `img-thumbnail`
        - rounded 1px border

2. Rounded
    - rounded(-SID)(-SHA)(-SIZ)
        - SID: top, right, bottom, left
        - SHA: circle, pill
        - SIZ: 0, sm, lg
        - they meant to be individual. do NOT use them all together.

3. Aligning img
    - `float-left` or `float-right`
    - `text-center` : center inline
    - `mx-auto` : center block

4. Figures
    - `figure` on the `<figure>` tag
    - `figure-img` on the images

## CSS variables

1. use --(var) to call it and `:root` to defign it.

    ```html
    <style>
        :root {
            --pink: #c4226f

        }
    </style>
    <h1 style="color: var(--pink);">
    ```
