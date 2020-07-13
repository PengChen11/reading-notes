# Navs and Navbar

[Table of Content](../README.md)

## Creating Navs

1. Basic Nav Classes:
   1. With/without ULs
   2. `<nav>`
   3. `<nav>` items
   4. `<nav>` links
2. Nav Link Options:
   1. .active class
   2. .disabled class
3. Nav Styles
   1. nav-pills
   2. nav-tabs
4. Nav Alignment
   1. justify-content-center
   2. justify-content-end
   3. nav-fill
   4. nav-justified
   5. flex-column

## Creating Navbars

- Navbar Classes:
  - .navbar
  - .navbar-expand(-BP)
    - BP: you know it
- Navbar Colors:
  - bg-COLOR for backgrounds
    - COLOR: primary etc
  - navbar-light
  - navbar-dark
- navbar-nav options
  - .navbar-nav container
    - .nav-item
    - .nav-link
    - .active
    - .disabled

## Branding and text

- Navbar options
  - .navbar-brand
    - right next to .navbar-nav
  - Link or Headline
  - Using Images
  - .navbar-text

## Add dropdown to Navigation

- Dropdown Setup
  - .dropdown to align
  - .dropdown-toggle on link
  - data-toggle="dropdown" in JS
  - .dropdown-menu
  - .dropdown-item
  - id & aria attributes

## Using Form Elements(search in Nav)

- .form-inline for `<form>`
- .form-control for `<input>`
- spacing as needed

## Positioning

- Placement Opitons
  - .fixed-top
  - .fixed-bottom
  - .sticky-top
  - Spacing as needed

## Collapsable Content

- Collapsable content
  - .collapse
  - .navbar-collapse
  - id
  - we need all of those in one div
- Toggler Classes
  - .navbar-toggler
  - Other properties
  - .navbar-toggler-icon
  - Here's what you need:
  
     ```html
     <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#myTogglerNav" aria-expanded="false" aria-controls="myTogglerNav" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>

    <div class="collapse navbar-collapse" id="myTogglerNav">
        <div class="navbar-nav ml-auto">
          <a class="nav-item nav-link active" href="#">Home</a>
          <a class="nav-item nav-link" href="#">Mission</a>
          <a class="nav-item nav-link" href="#">Services</a>
          <a class="nav-item nav-link" href="#">Staff</a>
          <a class="nav-item nav-link" href="#">Testimonials</a>
        </div><!-- navbar -->

    </div>

     ```
