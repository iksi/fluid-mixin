# Fluid mixin

An SCSS mixin to help scale CSS properties fluidly between breakpoints.

- https://tbrown.org/notes/2012/02/03/molten-leading-or-fluid-line-height/
- https://fvsch.com/css-locks/
- https://css-tricks.com/molten-leading-css/

## Usage

The numbers are assumed to be `rem`.

```scss
@include fluid('.test', (
  "font-size": (min: 2, max: 6),
  "line-height": (min: 2.5, max: 6)
));
```
