# :bulb:CSS Notes

## Programming Case Types

> - ***camelCase***
>
> - ***snake_case***
>
> - ***kebab-case***
>
> - ***PascalCase***
>
> - ***UPPER_CASE_SNAKE_CASE***

:point_right:We use 'kebab-case' when naming identifiers.

---

## :art:CSS Colors

- HEX Colors

- RGB Colors ----> ( red, green, blue )
  - RGBA Colors

- HSL Colors ----> ( hue, saturation, lightness )

  - HSLA Colors

---

>
> ***`visibility: hidden`*** ---->makes the element invisible to the browser, but it still takes up the same space.  
>
>***`display: none`*** ----> removes the element completely from the document.
>

---

## CSS Units

- Lengths

  |   Absolute length units   |        Relative length units            |
  |:--------------------------|:----------------------------------------|
  | cm  (Centimeters)         |  em ( Font size of the parent )         |
  | mm  (Millimeters)         |  rem  ( Font size of the root element ) |
  | Q   (Quarter-millimeters) |  vw ( 1% of the viewport's width )      |
  | in  (Inches)              |  vh  ( 1% of the viewport's height )    |
  | pc  (Picas)               |  lh ( Line height of the element )      |
  | px  (Pixels)              |                                         |
  | pt  (Points)              |                                         |
  
  ---

## Selectors

>- '*'
>- Element => [p, div, h2]
>- Element OtherElement => div p
>- .class-name
>- #id-name
>- .parent .child
>- .class-one.class-two
>- .class-name div, .class-name p
>- Element.class-name => p.class-name
>- .parent > .child => Direct Child
>
>---
>
>- Element + Other Element => [div + p]
>- Element ~ Other Elements => [p ~ div]
>- [Attribute]
>- Element[Attribute]
>- [Attribute=Value]
>- Element[Attribute=Value] => input[type="submit"]
>- [Attribute~=Value] => Contains A Word
>- [Attribute*=Value] => Contains A String
>- [Attribute^=Value] => Start With A String
>
>---
>
>- :first-child
>- :last-child
>- :first-of-type
>- :last-of-type
>- :only-child
>- :only-of-type
>
>---
>
> - :not(Selectors)
> - [:nth-child(n)](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child)
> - :nth-last-child(n)
> - :nth-of-type(n)
> - :nth-last-of-type(n)
>
>---
>
> - :root
> - :checked
> - :empty
> - :disabled
> - :required
> - :focus
> - ::selection
> - ::placeholder
