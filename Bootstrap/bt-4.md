# Style element

## Basic buttons

- Button Options
  - .btn basic class
  - .btn-SIZ
    - SIZ: sm, lg
  - works on `<a>`,`<button>` or `<input>`. They all look the same

    ```html
      <a class="btn btn-danger" href="#" role="button">Link</a>
      <button class="btn btn-danger" type="submit">Button</button>
      <input class="btn btn-danger" type="button" value="Input">
    ```

- Button Colors
  - .btn-COLOR
    - COLOR: primary, secondary, sucess, danger etc
    - this is solid color button
  - .btn-outline-COLOR
    - same COLOR
    - this is just the colorful border button with same color text
  - Other options
    - .btn-block  full width
    - .active
    - .disabled

- Button Groups
  - .btn-group
  - .btn-group-vertical
  - .btn-toolbar
  - .btn-group-SIZ

## Badges

- Badge classes
  - .badge
  - .badge-pill
  - .badge-COLOR
    - COLOR: primary, you know it

## Progress Bars

- Progress Classes
  - .progress  to containers
  - .progress-bar  to item
  - Style `width`, `height`
  - Label text

- Progress Styles
  - Use .bg-COLOR
  - .progress-bar-striped
  - .progress-bar-animated
  - multiple bars can be used together.

- Accessibility Properties
  - role="progressbar"
  - aria-valuenow
  - aria-valuemin
  - aria-valuemax

```html
<div class="progress">
    <div class="progress-bar" role="progressbar" aria-value-now="73%" aria-value-min="0"  aria-value-max="100%" style="width:73%">73%</div>
</div>
```

## List Groups

- List Group Class
  - .list-group  go to containers
  - .list-group-item  go to items
  - applied to `<li>`, `<button>`, or `<a>`.

- List Group Styles
  - .active
  - .disabled
  - .list-group-item-action  Style
  - use .list-group-item-COLOR for color
  - .list-group-horizontal(-BP) adding break point to it.
  
- Adding badges
  - .badge classes
  - .justify-content-between

```html
<ul class="list-group mb-3">
  <li class="list-group-item active">Grooming</li>
  <li class="list-group-item list-group-item-action">General Health</li>
  <li class="list-group-item list-group-item-action d-flex justify-content-between align-items-center">Nutrition
  <span class="badge badge-primary badge-pill">12</span>
  </li>
  <li class="list-group-item list-group-item-action">Pest Control</li>
  <li class="list-group-item list-group-item-action">Vaccinations</li>
</ul>
```

## Breadcrumb

- Breadcrumb Links
  - .breadcrumb go to containers
  - .breadcrumb-item go to items
  - .active style
  - can be used in `<li>` and `<a>` inside `<nav>`
