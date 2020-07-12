# Mastering layout with Bootstrap

 Bootstrap uses a 12 column grid breakpoints system.

   1. Extra small
   2. small
   3. medium
   4. large
   5. extra large

## using containers

1. responsive 12 column container
2. flexbox based
3. `container`, `row`, `column` three classes
    1. `.container(-SIZ)`
        - SIZ: sm, md, lg,xl,fluid
    2. They all have each side of 15px padding
    3. containers have different break point. ![img](../asset/bootstrap_1.png)

## Rows/Coloums

1. Rows:
   1. needs the class of `row`
   2. more details: `row-cols(-BP)(-COL)
      1. BP: sm > 576px, md > 768px and so on
      2. COL: 1-6
   3. Delete space between use `no-gutters`
2. Columns
   1. up to 12 columns
   2. `col(-BP)(-COL)`
      1. BP: sm > 576px, md > 768px, etc
      2. COL: 1-12
3. Aligning columns
   1. **Vertical**
      1. `align-TYP-DIR`
         1. TYP: items, self
         2. DIR: start, center, end
         3. Don't forget to add a `VH-100` first, means view point 100%.
   2. **Horizontal**
      1. `justify-content-DIR`
         1. DIR: start, center, end, around, between

## Offset columns

1. 