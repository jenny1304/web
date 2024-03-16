## Content Tables

<details>
  <summary>I. Basic CSS</summary>

 - [1. CSS Selector](#1-css-selector)
 - [2. Độ ưu tiên trong CSS](#2-độ-ưu-tiên-trong-css)
 - [3. Pseudo classes](#3-pseudo-classes)
 - [4. Pseudo elements](#4-pseudo-elements)
</details>


## I. Basic CSS

## 1. CSS Selector
[:arrow_up:](#content-tables)

Select:
- `class`: Use `.`
- `id`: Use `#`


## 2. Độ ưu tiên trong CSS
  [:arrow_up:](#content-tables)
1. `!important ` = 10000
  2. `inline` = 1000
  3. `#id` = 100
  4. `.class` = 10
  5. `tag` (div, h1) = 1
  6. `*` (for all) = 0


## 3. Pseudo classes
  [:arrow_up:](#content-tables)
  
- `Root`

```css
:root{
    --font-color: red;
}
```

```css
color: var(--font-color);
```

- `hover`

```css
.class:hover{
    background-color: rgba(240,81,35,0.1);
}
```
  
- `active`
- `first-child`
- `ast-child`

## 4. Pseudo elements
  [:arrow_up:](#content-tables)
- `before`
- `after`

```css
.container::after{
    content: "Hello"; /*có thể có content hoặc không*/
    display:block;
  }
```
  
- `first-line`
- `first-word`


